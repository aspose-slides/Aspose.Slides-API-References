---
title: EffectType
type: docs
weight: 0
url: /php-java/effecttype/
---

# EffectType class

 Represents the type of an animation effect.
 

## Constants

| name | description |
| --- | --- |
| Appear | Appear effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Ascend | Ascend effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Blast | Blast effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Blinds | Blinds effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Horizontal EffectSubtype.Vertical} |
| Blink | Blink effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| BoldFlash | BoldFlash effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| BoldReveal | BoldReveal effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Boomerang | Boomerang effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Bounce | Bounce effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Box | Box effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.In EffectSubtype.Out} |
| BrushOnColor | BrushOnColor effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| BrushOnUnderline | BrushOnUnderline effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| CenterRevolve | CenterRevolve effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| ChangeFillColor | ChangeFillColor effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise} |
| ChangeFont | ChangeFont effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.Instant EffectSubtype.Gradual} |
| ChangeFontColor | ChangeFontColor effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise} |
| ChangeFontSize | ChangeFontSize effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.Instant EffectSubtype.Gradual} |
| ChangeFontStyle | ChangeFontSize effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.FontBold EffectSubtype.FontItalic EffectSubtype.FontUnderline} |
| ChangeLineColor | ChangeLineColor effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise} |
| Checkerboard | Checkerboard effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Vertical EffectSubtype.Across} |
| Circle | ColorBlend effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.In EffectSubtype.Out} |
| ColorBlend | BrushOnUnderline effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| ColorTypewriter | Checkerboard effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| ColorWave | ColorWave effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| ComplementaryColor | ComplementaryColor effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| ComplementaryColor2 | ComplementaryColor2 effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Compress | Compress effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| ContrastingColor | ContrastingColor effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Crawl | Crawl effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom} |
| Credits | Credits effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| CurveUpDown | CurveUpDown effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Custom | Custom effect. |
| Darken | Darken effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Desaturate | Desaturate effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Descend | Descend effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Diamond | Diamond effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.In EffectSubtype.Out} |
| Dissolve | Dissolve effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| EaseInOut | Dissolve effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Expand | Expand effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Fade | Fade effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| FadedSwivel | FadedSwivel effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| FadedZoom | FadedZoom effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| FlashBulb | FlashBulb effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| FlashOnce | FlashOnce effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Flicker | Flicker effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Flip | Flip effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Float | Float effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Fly | Fly effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom EffectSubtype.TopLeft EffectSubtype.TopRight EffectSubtype.BottomLeft EffectSubtype.BottomRight} |
| Fold | Fold effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Glide | Glide effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| GrowAndTurn | GrowAndTurn effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| GrowShrink | GrowShrink effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| GrowWithColor | GrowWithColor effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| LightSpeed | LightSpeed effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Lighten | Lighten effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Magnify | Magnify effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| MediaPause | MediaPause effect. Class Media. Valid subtypes: {@code EffectSubtype.None} |
| MediaPlay | MediaPlay effect. Class Media. Valid subtypes: {@code EffectSubtype.None} |
| MediaStop | MediaStop effect. Class Media. Valid subtypes: {@code EffectSubtype.None} |
| OLEObjectEdit | OLEObjectEdit effect. Class OLEActionVerbs. Valid subtypes: {@code EffectSubtype.None} |
| OLEObjectOpen | OLEObjectOpen effect. Class OLEActionVerbs. Valid subtypes: {@code EffectSubtype.None} |
| OLEObjectShow | OLEObjectShow effect. Class OLEActionVerbs. Valid subtypes: {@code EffectSubtype.None} |
| Path4PointStar | Path4PointStar effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| Path5PointStar | Path5PointStar effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| Path6PointStar | Path6PointStar effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| Path8PointStar | Path8PointStar effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathArcDown | PathArcDown effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathArcLeft | PathArcLeft effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathArcRight | PathArcRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathArcUp | PathArcUp effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathBean | PathBean effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathBounceLeft | PathBounceLeft effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathBounceRight | PathBounceRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathBuzzsaw | PathBuzzsaw effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathCircle | PathCircle effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathCrescentMoon | PathCrescentMoon effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathCurvedSquare | PathCurvedSquare effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathCurvedX | PathCurvedX effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathCurvyLeft | PathCurvyLeft effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathCurvyRight | PathCurvyRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathCurvyStar | PathCurvyStar effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathDecayingWave | PathDecayingWave effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathDiagonalDownRight | PathDiagonalDownRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathDiagonalUpRight | PathDiagonalUpRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathDiamond | PathDiamond effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathDown | PathDown effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathEqualTriangle | PathEqualTriangle effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathFigure8Four | PathFigure8Four effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathFootball | PathFootball effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathFunnel | PathFunnel effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathHeart | PathHeart effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathHeartbeat | PathHeartbeat effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathHexagon | PathHexagon effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathHorizontalFigure8 | PathHorizontalFigure8 effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathInvertedSquare | PathInvertedSquare effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathInvertedTriangle | PathInvertedTriangle effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathLeft | PathLeft effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathLoopdeLoop | PathLoopdeLoop effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathNeutron | PathNeutron effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathOctagon | PathOctagon effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathParallelogram | PathParallelogram effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathPeanut | PathPeanut effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathPentagon | PathPentagon effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathPlus | PathPlus effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathPointyStar | PathPointyStar effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathRight | PathRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathRightTriangle | PathRightTriangle effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSCurve1 | PathSCurve1 effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSCurve2 | PathSCurve2 effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSineWave | PathSineWave effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSpiralLeft | PathSpiralLeft effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSpiralRight | PathSpiralRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSpring | PathSpring effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSquare | PathSquare effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathStairsDown | PathStairsDown effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathSwoosh | PathSwoosh effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathTeardrop | PathTeardrop effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathTrapezoid | PathTrapezoid effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathTurnDown | PathTurnDown effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathTurnRight | PathTurnRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathTurnUp | PathTurnUp effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathTurnUpRight | PathTurnUpRight effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathUp | PathUp effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathUser | PathUser effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathVerticalFigure8 | PathVerticalFigure8 effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathWave | PathWave effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| PathZigzag | PathZigzag effect. Class Path. Valid subtypes: {@code EffectSubtype.None} |
| Peek | Peek effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Pinwheel | Pinwheel effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Plus | Plus effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.In EffectSubtype.Out} |
| RandomBars | RandomBars effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Horizontal EffectSubtype.Vertical} |
| RandomEffects | RandomEffects effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| RiseUp | RandomEffects effect. Class Entrance. Valid subtypes: {@code EffectSubtype.None} |
| Shimmer | Shimmer effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Sling | RandomEffects effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Spin | Spin effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Spinner | Spinner effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Spiral | Spiral effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Split | Split effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.HorizontalIn EffectSubtype.HorizontalOut EffectSubtype.VerticalIn EffectSubtype.VerticalOut} |
| Stretch | Stretch effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom EffectSubtype.Across} |
| Strips | Stretch effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.UpLeft EffectSubtype.UpRight EffectSubtype.DownLeft EffectSubtype.DownRight} |
| StyleEmphasis | StyleEmphasis effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Swish | Swish effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Swivel | Swivel effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Horizontal EffectSubtype.Vertical} |
| Teeter | Teeter effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Thread | Thread effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Transparency | Transparency effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Unfold | Unfold effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| VerticalGrow | VerticalGrow effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Wave | Wave effect. Class Emphasis. Valid subtypes: {@code EffectSubtype.None} |
| Wedge | Wedge effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Wheel | Wedge effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Wheel1 EffectSubtype.Wheel2 EffectSubtype.Wheel3 EffectSubtype.Wheel4 EffectSubtype.Wheel8} |
| Whip | Whip effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.None} |
| Wipe | Wedge effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.Top EffectSubtype.Right EffectSubtype.Bottom EffectSubtype.Left} |
| Zoom | Zoom effect. Class Entrance or Exit. Valid subtypes: {@code EffectSubtype.In EffectSubtype.Out EffectSubtype.InCenter - only for Entrance class EffectSubtype.OutBottom - only for Entrance class EffectSubtype.OutSlightly EffectSubtype.InSlightly EffectSubtype.OutCenter - only for Exit class EffectSubtype.InBottom - only for Exit class} |

