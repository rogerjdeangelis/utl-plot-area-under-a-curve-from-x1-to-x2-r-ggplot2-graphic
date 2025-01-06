# utl-plot-area-under-a-curve-from-x1-to-x2-r-ggplot2-graphic
Plot area under a curve from x1 to x2 r ggplot2 graphic 
    %let pgm=utl-plot-area-under-a-curve-from-x1-to-x2-r-ggplot2-graphic;

    %stop_submission;

    Plot area under a curve from x1 to x2 r ggplot2 graphic


    Hi Res graphical output
    https://tinyurl.com/2vnmw8t2
    https://github.com/rogerjdeangelis/utl-plot-area-under-a-curve-from-x1-to-x2-r-ggplot2-graphic/blob/main/auc.png


    github
    https://tinyurl.com/2hfu2y7d
    https://github.com/rogerjdeangelis/utl-plot-area-under-a-curve-from-x1-to-x2-r-ggplot2-graphic

    stackoverflow
    https://tinyurl.com/2hfu2y7d
    https://stackoverflow.com/questions/79326771/geom-area-in-ggplot2-giving-off-auc-shadings

    Related Repos

    https://github.com/rogerjdeangelis/utl-area-of-intersection-of-arbitrary-polygons-R-AI
    https://github.com/rogerjdeangelis/utl-area-under-y-equal-x-squared-from-0-to-1-trapezoid-auc-clinical
    https://github.com/rogerjdeangelis/utl-calculate-the-area-within-a-latittude-longitude-polygon
    https://github.com/rogerjdeangelis/utl-find-area-under-curve-and-compute-regression-slope-and-intercept-using-sqllite-r-python
    https://github.com/rogerjdeangelis/utl-r-compute-the-area--of-an-image-which-is-under-a-curve-AI-image-processing-AI
    https://github.com/rogerjdeangelis/utl-r-python-compute-the-area-between-two-curves-AI-sympy-trapezoid
    https://github.com/rogerjdeangelis/utl_calculating_the_area_between_a_curve_and_a_straight_line
    https://github.com/rogerjdeangelis/utl_monte_carlo_simulation_to_determine_the_area_under_a_non_integrable_function

    /*                   _
    (_)_ __  _ __  _   _| |_
    | | `_ \| `_ \| | | | __|
    | | | | | |_) | |_| | |_
    |_|_| |_| .__/ \__,_|\__|
            |_|
    */

    /**************************************************************************************************************************/
    /*                       |                                              |                                                 */
    /*      INPUT            |      PROCESS (GGPLOT LANGUAGE)               |                        OUTPUT                   */
    /*      =====            |      =========================               |                        ======                   */
    /*                       |                                              |                                                 */
    /*                       |                                              |   Hi Res Grapg    https://tinyurl.com/2vnmw8t2  */
    /*   X   Y   X   Y       | R GGPLOT                                     |                             X                   */
    /*                       | =========                                    |          500        600        700       800    */
    /*  419 021 608 416      |                                              |    Y------+----------+----------+--------+--Y   */
    /*  429 028 618 438      | png("d:/png/auc.png")                        |  62+                   ***                  +62 */
    /*  439 038 628 453      | ggplot(data=have,mapping=aes(x=X,y=Y)) +     |    |                  *   *                 |   */
    /*                       |  geom_line()+                                |    |        ****     *    |*                |   */
    /*  ,,,,                 |  geom_area(fill = "red",                     |  96+       *     ****     |||*              +96 */
    /*                       |  data=function(dd) subset(dd,X>650 & X<700)) |    |                      ||||              |   */
    /*  569 395 758 055      | png()                                        |    |      *               ||||              |   */
    /*  589 385 768 034      |                                              |  30+                      ||||*             +30 */
    /*  599 395 778 020      |                                              |    |        AREA UNDER    |||||             |   */
    /*                       |                                              |    |     *  A CURVE       |||||*            |   */
    /*                       |                                              |  64+      FRAM 650 to 700 ||||||            +64 */
    /* options               |                                              |    |    *                 ||||||            |   */
    /*  validvarname=upcase; |                                              |    |                      ||||||*           |   */
    /* libname sd1 "d:/sd1"; |                                              |  98+                      ||||||            +98 */
    /* data sd1.have;        |                                              |    |   *                  |||||| *          |   */
    /*  input x y @@ ;       |                                              |    |                      ||||||            |   */
    /* cards4;               |                                              |  32+  *                   ||||||  *         +32 */
    /* 419 021 608 416       |                                              |    |                      ||||||   *        |   */
    /* 429 028 618 438       |                                              |    |*                     ||||||    *       |   */
    /* 439 038 628 453       |                                              |  66+                      ||||||     *      +66 */
    /* 449 055 638 459       |                                              |    |                      ||||||      *     |   */
    /* 459 082 648 457       |                                              |    |                      ||||||        **  |   */
    /* 469 122 658 448       |                                              |   0+                      ||||||          **+ 0 */
    /* 479 175 668 425       |                                              |    ------+----------+----------+----------+--   */
    /* 489 234 678 386       |                                              |         500        600        700        800    */
    /* 499 294 688 334       |                                              |                            X                    */
    /* 509 348 698 278       |                                              |                                                 */
    /* 519 390 708 225       |                                              |                                                 */
    /* 529 415 718 180       |                                              |                                                 */
    /* 539 423 728 142       |                                              |                                                 */
    /* 549 418 738 109       |                                              |                                                 */
    /* 559 407 748 080       |                                              |                                                 */
    /* 569 395 758 055       |                                              |                                                 */
    /* 589 385 768 034       |                                              |                                                 */
    /* 599 395 778 020       |                                              |                                                 */
    /* ;;;;                  |                                              |                                                 */
    /* run;quit;             |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /*                       |                                              |                                                 */
    /**************************************************************************************************************************/

    /*                   _
    (_)_ __  _ __  _   _| |_
    | | `_ \| `_ \| | | | __|
    | | | | | |_) | |_| | |_
    |_|_| |_| .__/ \__,_|\__|
            |_|
    */

    options
     validvarname=upcase;
    libname sd1 "d:/sd1";
    data sd1.have;
     input x y @@ ;
    cards4;
    419 021 608 416
    429 028 618 438
    439 038 628 453
    449 055 638 459
    459 082 648 457
    469 122 658 448
    479 175 668 425
    489 234 678 386
    499 294 688 334
    509 348 698 278
    519 390 708 225
    529 415 718 180
    539 423 728 142
    549 418 738 109
    559 407 748 080
    569 395 758 055
    589 385 768 034
    599 395 778 020
    ;;;;
    run;quit;

    options ls=64 ps=32;
    proc plot data=sd1.have ;
     plot y*x='*' /
        haxis=400 to 900 by 100
        href=650 to 700 by 10;
    run;quit;


    /**************************************************************************************************************************/
    /*                                                                                                                        */
    /*   X   Y   X   Y                                                                                                        */
    /*                                                                                                                        */
    /*  419 021 608 416                                                                                                       */
    /*  429 028 618 438                                                                                                       */
    /*  439 038 628 453                                                                                                       */
    /*                                                                                                                        */
    /*  ,,,,                                                                                                                  */
    /*                                                                                                                        */
    /*  569 395 758 055                                                                                                       */
    /*  589 385 768 034                                                                                                       */
    /*  599 395 778 020                                                                                                       */
    /*                                                                                                                        */
    /**************************************************************************************************************************/

    /*                        _       _   ____
     _ __    __ _  __ _ _ __ | | ___ | |_|___ \
    | `__|  / _` |/ _` | `_ \| |/ _ \| __| __) |
    | |    | (_| | (_| | |_) | | (_) | |_ / __/
    |_|     \__, |\__, | .__/|_|\___/ \__|_____|
            |___/ |___/|_|
    */

    %utlfkil(d:/png/auc.png)

    %utl_rbeginx;
    parmcards4;
    library(haven)
    library(ggplot2)
    source("c:/oto/fn_tosas9x.R")
    have<-read_sas("d:/sd1/have.sas7bdat")
    have
    png("d:/png/auc.png")
    ggplot(data=have,mapping=aes(x=X,y=Y)) +
      geom_line()+
      geom_area(fill = "red",
       data=function(dd) subset(dd,X>650 & X< 700))
    png()
    ;;;;
    %utl_rendx;


    /**************************************************************************************************************************/
    /*                                                                                                                        */
    /*                                                                                                                        */
    /*  HiRes image at  https://tinyurl.com/2vnmw8t2                                                                          */
    /*                                                                                                                        */
    /*           500        600        700       800                                                                          */
    /*     Y------+----------+----------+--------+--Y                                                                         */
    /*   62+                   ***                  +62                                                                       */
    /*     |                  *   *                 |                                                                         */
    /*     |        ****     *    |*                |                                                                         */
    /*   96+       *     ****     |||*              +96                                                                       */
    /*     |                      ||||              |                                                                         */
    /*     |      *               ||||              |                                                                         */
    /*   30+                      ||||*             +30                                                                       */
    /*     |        AREA UNDER    |||||             |                                                                         */
    /*     |     *  A CURVE       |||||*            |                                                                         */
    /*   64+      FRAM 650 to 700 ||||||            +64                                                                       */
    /*     |    *                 ||||||            |                                                                         */
    /*     |                      ||||||*           |                                                                         */
    /*   98+                      ||||||            +98                                                                       */
    /*     |   *                  |||||| *          |                                                                         */
    /*     |                      ||||||            |                                                                         */
    /*   32+  *                   ||||||  *         +32                                                                       */
    /*     |                      ||||||   *        |                                                                         */
    /*     |*                     ||||||    *       |                                                                         */
    /*   66+                      ||||||     *      +66                                                                       */
    /*     |                      ||||||      *     |                                                                         */
    /*     |                      ||||||        **  |                                                                         */
    /*    0+                      ||||||          **+ 0                                                                       */
    /*     ------+----------+----------+----------+--                                                                         */
    /*          500        600        700        800                                                                          */
    /*                      X                                                                                                 */
    /*                                                                                                                        */
    /**************************************************************************************************************************/

    /*              _
      ___ _ __   __| |
     / _ \ `_ \ / _` |
    |  __/ | | | (_| |
     \___|_| |_|\__,_|

    */
