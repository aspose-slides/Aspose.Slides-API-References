---
title: EffectType
second_title: Aspose.Slides C++ API referencia
description: Ábrázolja egy animációs hatás típusát.
type: docs
weight: 833
url: /hu/aspose.slides.animation/effecttype/
---
## EffectType enum

Ábrázolja egy animációs hatás típusát.

```cpp
enum class EffectType
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| Appear | 0 | Appear hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CurveUpDown | 1 | CurveUpDown hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Ascend | 2 | Ascend hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatUp | 2 | Lebegő hatás felfelé irányú. Ez az Ascend típus álnéve. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blast | 3 | Blast hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blinds | 4 | Blinds hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Blink | 5 | Blink hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldFlash | 6 | BoldFlash hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldReveal | 7 | BoldReveal hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Boomerang | 8 | Boomerang hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Bounce | 9 | Bounce hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Box | 10 | Box hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| BrushOnColor | 11 | BrushOnColor hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BrushOnUnderline | 12 | BrushOnUnderline hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CenterRevolve | 13 | CenterRevolve hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ChangeFillColor | 14 | ChangeFillColor hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFont | 15 | ChangeFont hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontColor | 16 | ChangeFontColor hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFontSize | 17 | ChangeFontSize hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontStyle | 18 | ChangeFontSize hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::FontBold](../effectsubtype/)</li><li>[EffectSubtype::FontItalic](../effectsubtype/)</li><li>[EffectSubtype::FontUnderline](../effectsubtype/)</li></ul> |
| ChangeLineColor | 19 | ChangeLineColor hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| Checkerboard | 20 | Checkerboard hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Vertical](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Circle | 21 | ColorBlend hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| ColorBlend | 22 | BrushOnUnderline hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorTypewriter | 23 | Checkerboard hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorWave | 24 | ColorWave hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor | 25 | ComplementaryColor hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor2 | 26 | ComplementaryColor2 hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Compress | 27 | Compress hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ContrastingColor | 28 | ContrastingColor hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Crawl | 29 | Crawl hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li></ul> |
| Credits | 30 | Credits hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Custom | 31 | Custom hatás. |
| Darken | 32 | Darken hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Desaturate | 33 | Desaturate hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Descend | 34 | Descend hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatDown | 34 | Lebegő hatás lefelé irányú. Ez a Descend típus álnéve. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Diamond | 35 | Diamond hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| Dissolve | 36 | Dissolve hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| EaseInOut | 37 | Dissolve hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Expand | 38 | Expand hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fade | 39 | Fade hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedSwivel | 40 | FadedSwivel hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedZoom | 41 | FadedZoom hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashBulb | 42 | FlashBulb hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashOnce | 43 | FlashOnce hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flicker | 44 | Flicker hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flip | 45 | Flip hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Float | 46 | Float hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fly | 47 | Fly hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::TopLeft](../effectsubtype/)</li><li>[EffectSubtype::TopRight](../effectsubtype/)</li><li>[EffectSubtype::BottomLeft](../effectsubtype/)</li><li>[EffectSubtype::BottomRight](../effectsubtype/)</li></ul> |
| Fold | 48 | Fold hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Glide | 49 | Glide hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowAndTurn | 50 | GrowAndTurn hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowShrink | 51 | GrowShrink hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowWithColor | 52 | GrowWithColor hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Lighten | 53 | Lighten hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| LightSpeed | 54 | LightSpeed hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPause | 55 | MediaPause hatás. Osztály **Media**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPlay | 56 | MediaPlay hatás. Osztály **Media**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaStop | 57 | MediaStop hatás. Osztály **Media**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path4PointStar | 58 | Path4PointStar hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path5PointStar | 59 | Path5PointStar hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path6PointStar | 60 | Path6PointStar hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path8PointStar | 61 | Path8PointStar hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcDown | 62 | PathArcDown hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcLeft | 63 | PathArcLeft hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcRight | 64 | PathArcRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcUp | 65 | PathArcUp hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBean | 66 | PathBean hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceLeft | 67 | PathBounceLeft hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceRight | 68 | PathBounceRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBuzzsaw | 69 | PathBuzzsaw hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCircle | 70 | PathCircle hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCrescentMoon | 71 | PathCrescentMoon hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedSquare | 72 | PathCurvedSquare hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedX | 73 | PathCurvedX hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyLeft | 74 | PathCurvyLeft hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyRight | 75 | PathCurvyRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyStar | 76 | PathCurvyStar hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDecayingWave | 77 | PathDecayingWave hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalDownRight | 78 | PathDiagonalDownRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalUpRight | 79 | PathDiagonalUpRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiamond | 80 | PathDiamond hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDown | 81 | PathDown hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathEqualTriangle | 82 | PathEqualTriangle hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFigure8Four | 83 | PathFigure8Four hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFootball | 84 | PathFootball hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFunnel | 85 | PathFunnel hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeart | 86 | PathHeart hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeartbeat | 87 | PathHeartbeat hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHexagon | 88 | PathHexagon hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHorizontalFigure8 | 89 | PathHorizontalFigure8 hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedSquare | 90 | PathInvertedSquare hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedTriangle | 91 | PathInvertedTriangle hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLeft | 92 | PathLeft hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLoopdeLoop | 93 | PathLoopdeLoop hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathNeutron | 94 | PathNeutron hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathOctagon | 95 | PathOctagon hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathParallelogram | 96 | PathParallelogram hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPeanut | 97 | PathPeanut hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPentagon | 98 | PathPentagon hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPlus | 99 | PathPlus hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPointyStar | 100 | PathPointyStar hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRight | 101 | PathRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRightTriangle | 102 | PathRightTriangle hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve1 | 103 | PathSCurve1 hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve2 | 104 | PathSCurve2 hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSineWave | 105 | PathSineWave hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralLeft | 106 | PathSpiralLeft hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralRight | 107 | PathSpiralRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpring | 108 | PathSpring hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSquare | 109 | PathSquare hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathStairsDown | 110 | PathStairsDown hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSwoosh | 111 | PathSwoosh hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTeardrop | 112 | PathTeardrop hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTrapezoid | 113 | PathTrapezoid hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnDown | 114 | PathTurnDown hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnRight | 115 | PathTurnRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUp | 116 | PathTurnUp hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUpRight | 117 | PathTurnUpRight hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUp | 118 | PathUp hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUser | 119 | PathUser hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathVerticalFigure8 | 120 | PathVerticalFigure8 hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathWave | 121 | PathWave hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathZigzag | 122 | PathZigzag hatás. Osztály **Path**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Peek | 123 | Peek hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Pinwheel | 124 | Pinwheel hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Plus | 125 | Plus hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| RandomBars | 126 | RandomBars hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| RandomEffects | 127 | RandomEffects hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| RiseUp | 128 | RandomEffects hatás. Osztály **Entrance**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Shimmer | 129 | Shimmer hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Sling | 130 | RandomEffects hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spin | 131 | Spin hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spinner | 132 | Spinner hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spiral | 133 | Spiral hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Split | 134 | Split hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::HorizontalIn](../effectsubtype/)</li><li>[EffectSubtype::HorizontalOut](../effectsubtype/)</li><li>[EffectSubtype::VerticalIn](../effectsubtype/)</li><li>[EffectSubtype::VerticalOut](../effectsubtype/)</li></ul> |
| Stretch | 135 | Stretch hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Strips | 136 | Stretch hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::UpLeft](../effectsubtype/)</li><li>[EffectSubtype::UpRight](../effectsubtype/)</li><li>[EffectSubtype::DownLeft](../effectsubtype/)</li><li>[EffectSubtype::DownRight](../effectsubtype/)</li></ul> |
| StyleEmphasis | 137 | StyleEmphasis hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swish | 138 | Swish hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swivel | 139 | Swivel hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Teeter | 140 | Teeter hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Thread | 141 | Thread hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Transparency | 142 | Transparency hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Unfold | 143 | Unfold hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| VerticalGrow | 144 | VerticalGrow hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wave | 145 | Wave hatás. Osztály **Emphasis**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wedge | 146 | Wedge hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wheel | 147 | Wedge hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Wheel1](../effectsubtype/)</li><li>[EffectSubtype::Wheel2](../effectsubtype/)</li><li>[EffectSubtype::Wheel3](../effectsubtype/)</li><li>[EffectSubtype::Wheel4](../effectsubtype/)</li><li>[EffectSubtype::Wheel8](../effectsubtype/)</li></ul> |
| Whip | 148 | Whip hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wipe | 149 | Wedge hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li></ul> |
| Magnify | 150 | Magnify hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Zoom | 151 | Zoom hatás. Osztály **Entrance** vagy **Exit**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li><li>[EffectSubtype::InCenter](../effectsubtype/) - csak az Entrance osztályra</li><li>[EffectSubtype::OutBottom](../effectsubtype/) - csak az Entrance osztályra</li><li>[EffectSubtype::OutSlightly](../effectsubtype/)</li><li>[EffectSubtype::InSlightly](../effectsubtype/)</li><li>[EffectSubtype::OutCenter](../effectsubtype/) - csak az Exit osztályra</li><li>[EffectSubtype::InBottom](../effectsubtype/) - csak az Exit osztályra</li></ul> |
| OLEObjectShow | 152 | OLEObjectShow hatás. Osztály **OLEActionVerbs**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectEdit | 153 | OLEObjectEdit hatás. Osztály **OLEActionVerbs**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectOpen | 154 | OLEObjectOpen hatás. Osztály **OLEActionVerbs**.<br>Érvényes altípusok:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |

## Lásd még

* Névterület [Aspose::Slides::Animation](../)
* Könyvtár [Aspose.Slides](../../)