---
title: EffectType
second_title: Aspose.Slides for C++ API Referansı
description: Bir animasyon etkisinin tipini temsil eder.
type: docs
weight: 833
url: /tr/aspose.slides.animation/effecttype/
---
## EffectType enum

Bir animasyon etkisinin tipini temsil eder.

```cpp
enum class EffectType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Appear | 0 | Appear etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CurveUpDown | 1 | CurveUpDown etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Ascend | 2 | Ascend etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatUp | 2 | Yönü Up olan Float etkisi. Bu, Ascend tipi için bir takma addır. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blast | 3 | Blast etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blinds | 4 | Blinds etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Blink | 5 | Blink etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldFlash | 6 | BoldFlash etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldReveal | 7 | BoldReveal etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Boomerang | 8 | Boomerang etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Bounce | 9 | Bounce etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Box | 10 | Box etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| BrushOnColor | 11 | BrushOnColor etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BrushOnUnderline | 12 | BrushOnUnderline etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CenterRevolve | 13 | CenterRevolve etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ChangeFillColor | 14 | ChangeFillColor etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFont | 15 | ChangeFont etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontColor | 16 | ChangeFontColor etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFontSize | 17 | ChangeFontSize etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontStyle | 18 | ChangeFontSize etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::FontBold](../effectsubtype/)</li><li>[EffectSubtype::FontItalic](../effectsubtype/)</li><li>[EffectSubtype::FontUnderline](../effectsubtype/)</li></ul> |
| ChangeLineColor | 19 | ChangeLineColor etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| Checkerboard | 20 | Checkerboard etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Vertical](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Circle | 21 | ColorBlend etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| ColorBlend | 22 | BrushOnUnderline etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorTypewriter | 23 | Checkerboard etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorWave | 24 | ColorWave etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor | 25 | ComplementaryColor etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor2 | 26 | ComplementaryColor2 etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Compress | 27 | Compress etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ContrastingColor | 28 | ContrastingColor etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Crawl | 29 | Crawl etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li></ul> |
| Credits | 30 | Credits etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Custom | 31 | Custom etkisi. |
| Darken | 32 | Darken etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Desaturate | 33 | Desaturate etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Descend | 34 | Descend etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatDown | 34 | Yönü Down olan Float etkisi. Bu, Descend tipi için bir takma addır. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Diamond | 35 | Diamond etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| Dissolve | 36 | Dissolve etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| EaseInOut | 37 | Dissolve etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Expand | 38 | Expand etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fade | 39 | Fade etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedSwivel | 40 | FadedSwivel etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedZoom | 41 | FadedZoom etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashBulb | 42 | FlashBulb etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashOnce | 43 | FlashOnce etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flicker | 44 | Flicker etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flip | 45 | Flip etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Float | 46 | Float etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fly | 47 | Fly etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::TopLeft](../effectsubtype/)</li><li>[EffectSubtype::TopRight](../effectsubtype/)</li><li>[EffectSubtype::BottomLeft](../effectsubtype/)</li><li>[EffectSubtype::BottomRight](../effectsubtype/)</li></ul> |
| Fold | 48 | Fold etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Glide | 49 | Glide etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowAndTurn | 50 | GrowAndTurn etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowShrink | 51 | GrowShrink etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowWithColor | 52 | GrowWithColor etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Lighten | 53 | Lighten etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| LightSpeed | 54 | LightSpeed etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPause | 55 | MediaPause etkisi. Sınıf **Media**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPlay | 56 | MediaPlay etkisi. Sınıf **Media**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaStop | 57 | MediaStop etkisi. Sınıf **Media**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path4PointStar | 58 | Path4PointStar etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path5PointStar | 59 | Path5PointStar etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path6PointStar | 60 | Path6PointStar etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path8PointStar | 61 | Path8PointStar etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcDown | 62 | PathArcDown etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcLeft | 63 | PathArcLeft etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcRight | 64 | PathArcRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcUp | 65 | PathArcUp etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBean | 66 | PathBean etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceLeft | 67 | PathBounceLeft etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceRight | 68 | PathBounceRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBuzzsaw | 69 | PathBuzzsaw etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCircle | 70 | PathCircle etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCrescentMoon | 71 | PathCrescentMoon etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedSquare | 72 | PathCurvedSquare etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedX | 73 | PathCurvedX etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyLeft | 74 | PathCurvyLeft etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyRight | 75 | PathCurvyRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyStar | 76 | PathCurvyStar etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDecayingWave | 77 | PathDecayingWave etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalDownRight | 78 | PathDiagonalDownRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalUpRight | 79 | PathDiagonalUpRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiamond | 80 | PathDiamond etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDown | 81 | PathDown etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathEqualTriangle | 82 | PathEqualTriangle etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFigure8Four | 83 | PathFigure8Four etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFootball | 84 | PathFootball etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFunnel | 85 | PathFunnel etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeart | 86 | PathHeart etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeartbeat | 87 | PathHeartbeat etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHexagon | 88 | PathHexagon etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHorizontalFigure8 | 89 | PathHorizontalFigure8 etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedSquare | 90 | PathInvertedSquare etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedTriangle | 91 | PathInvertedTriangle etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLeft | 92 | PathLeft etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLoopdeLoop | 93 | PathLoopdeLoop etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathNeutron | 94 | PathNeutron etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathOctagon | 95 | PathOctagon etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathParallelogram | 96 | PathParallelogram etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPeanut | 97 | PathPeanut etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPentagon | 98 | PathPentagon etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPlus | 99 | PathPlus etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPointyStar | 100 | PathPointyStar etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRight | 101 | PathRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRightTriangle | 102 | PathRightTriangle etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve1 | 103 | PathSCurve1 etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve2 | 104 | PathSCurve2 etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSineWave | 105 | PathSineWave etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralLeft | 106 | PathSpiralLeft etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralRight | 107 | PathSpiralRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpring | 108 | PathSpring etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSquare | 109 | PathSquare etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathStairsDown | 110 | PathStairsDown etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSwoosh | 111 | PathSwoosh etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTeardrop | 112 | PathTeardrop etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTrapezoid | 113 | PathTrapezoid etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnDown | 114 | PathTurnDown etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnRight | 115 | PathTurnRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUp | 116 | PathTurnUp etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUpRight | 117 | PathTurnUpRight etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUp | 118 | PathUp etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUser | 119 | PathUser etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathVerticalFigure8 | 120 | PathVerticalFigure8 etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathWave | 121 | PathWave etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathZigzag | 122 | PathZigzag etkisi. Sınıf **Path**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Peek | 123 | Peek etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Pinwheel | 124 | Pinwheel etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Plus | 125 | Plus etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| RandomBars | 126 | RandomBars etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| RandomEffects | 127 | RandomEffects etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| RiseUp | 128 | RandomEffects etkisi. Sınıf **Entrance**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Shimmer | 129 | Shimmer etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Sling | 130 | RandomEffects etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spin | 131 | Spin etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spinner | 132 | Spinner etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spiral | 133 | Spiral etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Split | 134 | Split etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::HorizontalIn](../effectsubtype/)</li><li>[EffectSubtype::HorizontalOut](../effectsubtype/)</li><li>[EffectSubtype::VerticalIn](../effectsubtype/)</li><li>[EffectSubtype::VerticalOut](../effectsubtype/)</li></ul> |
| Stretch | 135 | Stretch etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Strips | 136 | Stretch etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::UpLeft](../effectsubtype/)</li><li>[EffectSubtype::UpRight](../effectsubtype/)</li><li>[EffectSubtype::DownLeft](../effectsubtype/)</li><li>[EffectSubtype::DownRight](../effectsubtype/)</li></ul> |
| StyleEmphasis | 137 | StyleEmphasis etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swish | 138 | Swish etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swivel | 139 | Swivel etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Teeter | 140 | Teeter etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Thread | 141 | Thread etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Transparency | 142 | Transparency etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Unfold | 143 | Unfold etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| VerticalGrow | 144 | VerticalGrow etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wave | 145 | Wave etkisi. Sınıf **Emphasis**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wedge | 146 | Wedge etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wheel | 147 | Wedge etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Wheel1](../effectsubtype/)</li><li>[EffectSubtype::Wheel2](../effectsubtype/)</li><li>[EffectSubtype::Wheel3](../effectsubtype/)</li><li>[EffectSubtype::Wheel4](../effectsubtype/)</li><li>[EffectSubtype::Wheel8](../effectsubtype/)</li></ul> |
| Whip | 148 | Whip etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wipe | 149 | Wedge etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li></ul> |
| Magnify | 150 | Magnify etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Zoom | 151 | Zoom etkisi. Sınıf **Entrance** veya **Exit**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li><li>[EffectSubtype::InCenter](../effectsubtype/) - yalnızca Entrance sınıfı için</li><li>[EffectSubtype::OutBottom](../effectsubtype/) - yalnızca Entrance sınıfı için</li><li>[EffectSubtype::OutSlightly](../effectsubtype/)</li><li>[EffectSubtype::InSlightly](../effectsubtype/)</li><li>[EffectSubtype::OutCenter](../effectsubtype/) - yalnızca Exit sınıfı için</li><li>[EffectSubtype::InBottom](../effectsubtype/) - yalnızca Exit sınıfı için</li></ul> |
| OLEObjectShow | 152 | OLEObjectShow etkisi. Sınıf **OLEActionVerbs**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectEdit | 153 | OLEObjectEdit etkisi. Sınıf **OLEActionVerbs**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectOpen | 154 | OLEObjectOpen etkisi. Sınıf **OLEActionVerbs**.<br>Geçerli alt tipler:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |

## Ayrıca Bakınız

* Ad alanı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)