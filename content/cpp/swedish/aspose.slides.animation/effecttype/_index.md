---
title: EffectType
second_title: Aspose.Slides för C++ API-referens
description: Representerar typen av en animationseffekt.
type: docs
weight: 833
url: /sv/aspose.slides.animation/effecttype/
---
## EffectType enum


Representerar typen av en animationseffekt.

```cpp
enum class EffectType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Appear | 0 | Appear-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CurveUpDown | 1 | CurveUpDown-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Ascend | 2 | Ascend-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatUp | 2 | Float-effekt med riktning Upp. Detta är alias för Ascend-typ. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blast | 3 | Blast-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blinds | 4 | Blinds-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Blink | 5 | Blink-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldFlash | 6 | BoldFlash-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldReveal | 7 | BoldReveal-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Boomerang | 8 | Boomerang-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Bounce | 9 | Bounce-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Box | 10 | Box-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| BrushOnColor | 11 | BrushOnColor-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BrushOnUnderline | 12 | BrushOnUnderline-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CenterRevolve | 13 | CenterRevolve-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ChangeFillColor | 14 | ChangeFillColor-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFont | 15 | ChangeFont-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontColor | 16 | ChangeFontColor-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFontSize | 17 | ChangeFontSize-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontStyle | 18 | ChangeFontSize-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::FontBold](../effectsubtype/)</li><li>[EffectSubtype::FontItalic](../effectsubtype/)</li><li>[EffectSubtype::FontUnderline](../effectsubtype/)</li></ul> |
| ChangeLineColor | 19 | ChangeLineColor-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| Checkerboard | 20 | Checkerboard-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Vertical](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Circle | 21 | ColorBlend-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| ColorBlend | 22 | BrushOnUnderline-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorTypewriter | 23 | Checkerboard-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorWave | 24 | ColorWave-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor | 25 | ComplementaryColor-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor2 | 26 | ComplementaryColor2-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Compress | 27 | Compress-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ContrastingColor | 28 | ContrastingColor-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Crawl | 29 | Crawl-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li></ul> |
| Credits | 30 | Credits-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Custom | 31 | Custom-effekt. |
| Darken | 32 | Darken-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Desaturate | 33 | Desaturate-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Descend | 34 | Descend-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatDown | 34 | Float-effekt med riktning Ner. Detta är alias för Descend-typ. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Diamond | 35 | Diamond-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| Dissolve | 36 | Dissolve-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| EaseInOut | 37 | Dissolve-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Expand | 38 | Expand-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fade | 39 | Fade-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedSwivel | 40 | FadedSwivel-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedZoom | 41 | FadedZoom-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashBulb | 42 | FlashBulb-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashOnce | 43 | FlashOnce-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flicker | 44 | Flicker-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flip | 45 | Flip-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Float | 46 | Float-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fly | 47 | Fly-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::TopLeft](../effectsubtype/)</li><li>[EffectSubtype::TopRight](../effectsubtype/)</li><li>[EffectSubtype::BottomLeft](../effectsubtype/)</li><li>[EffectSubtype::BottomRight](../effectsubtype/)</li></ul> |
| Fold | 48 | Fold-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Glide | 49 | Glide-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowAndTurn | 50 | GrowAndTurn-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowShrink | 51 | GrowShrink-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowWithColor | 52 | GrowWithColor-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Lighten | 53 | Lighten-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| LightSpeed | 54 | LightSpeed-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPause | 55 | MediaPause-effekt. Klass **Media**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPlay | 56 | MediaPlay-effekt. Klass **Media**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaStop | 57 | MediaStop-effekt. Klass **Media**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path4PointStar | 58 | Path4PointStar-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path5PointStar | 59 | Path5PointStar-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path6PointStar | 60 | Path6PointStar-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path8PointStar | 61 | Path8PointStar-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcDown | 62 | PathArcDown-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcLeft | 63 | PathArcLeft-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcRight | 64 | PathArcRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcUp | 65 | PathArcUp-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBean | 66 | PathBean-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceLeft | 67 | PathBounceLeft-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceRight | 68 | PathBounceRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBuzzsaw | 69 | PathBuzzsaw-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCircle | 70 | PathCircle-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCrescentMoon | 71 | PathCrescentMoon-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedSquare | 72 | PathCurvedSquare-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedX | 73 | PathCurvedX-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyLeft | 74 | PathCurvyLeft-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyRight | 75 | PathCurvyRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyStar | 76 | PathCurvyStar-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDecayingWave | 77 | PathDecayingWave-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalDownRight | 78 | PathDiagonalDownRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalUpRight | 79 | PathDiagonalUpRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiamond | 80 | PathDiamond-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDown | 81 | PathDown-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathEqualTriangle | 82 | PathEqualTriangle-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFigure8Four | 83 | PathFigure8Four-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFootball | 84 | PathFootball-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFunnel | 85 | PathFunnel-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeart | 86 | PathHeart-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeartbeat | 87 | PathHeartbeat-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHexagon | 88 | PathHexagon-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHorizontalFigure8 | 89 | PathHorizontalFigure8-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedSquare | 90 | PathInvertedSquare-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedTriangle | 91 | PathInvertedTriangle-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLeft | 92 | PathLeft-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLoopdeLoop | 93 | PathLoopdeLoop-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathNeutron | 94 | PathNeutron-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathOctagon | 95 | PathOctagon-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathParallelogram | 96 | PathParallelogram-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPeanut | 97 | PathPeanut-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPentagon | 98 | PathPentagon-effekt. Klass **Path**.<br>Giltiga undersökningsmärken:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPlus | 99 | PathPlus-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPointyStar | 100 | PathPointyStar-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRight | 101 | PathRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRightTriangle | 102 | PathRightTriangle-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve1 | 103 | PathSCurve1-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve2 | 104 | PathSCurve2-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSineWave | 105 | PathSineWave-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralLeft | 106 | PathSpiralLeft-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralRight | 107 | PathSpiralRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpring | 108 | PathSpring-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSquare | 109 | PathSquare-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathStairsDown | 110 | PathStairsDown-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSwoosh | 111 | PathSwoosh-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTeardrop | 112 | PathTeardrop-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTrapezoid | 113 | PathTrapezoid-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnDown | 114 | PathTurnDown-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnRight | 115 | PathTurnRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUp | 116 | PathTurnUp-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUpRight | 117 | PathTurnUpRight-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUp | 118 | PathUp-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUser | 119 | PathUser-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathVerticalFigure8 | 120 | PathVerticalFigure8-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathWave | 121 | PathWave-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathZigzag | 122 | PathZigzag-effekt. Klass **Path**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Peek | 123 | Peek-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Pinwheel | 124 | Pinwheel-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Plus | 125 | Plus-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| RandomBars | 126 | RandomBars-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| RandomEffects | 127 | RandomEffects-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| RiseUp | 128 | RandomEffects-effekt. Klass **Entrance**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Shimmer | 129 | Shimmer-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Sling | 130 | RandomEffects-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spin | 131 | Spin-effekt. Klass **Emphasis**.<br>Giltiga undersökningsmärken:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spinner | 132 | Spinner-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spiral | 133 | Spiral-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Split | 134 | Split-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::HorizontalIn](../effectsubtype/)</li><li>[EffectSubtype::HorizontalOut](../effectsubtype/)</li><li>[EffectSubtype::VerticalIn](../effectsubtype/)</li><li>[EffectSubtype::VerticalOut](../effectsubtype/)</li></ul> |
| Stretch | 135 | Stretch-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Strips | 136 | Stretch-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::UpLeft](../effectsubtype/)</li><li>[EffectSubtype::UpRight](../effectsubtype/)</li><li>[EffectSubtype::DownLeft](../effectsubtype/)</li><li>[EffectSubtype::DownRight](../effectsubtype/)</li></ul> |
| StyleEmphasis | 137 | StyleEmphasis-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swish | 138 | Swish-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swivel | 139 | Swivel-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Teeter | 140 | Teeter-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Thread | 141 | Thread-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Transparency | 142 | Transparency-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Unfold | 143 | Unfold-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| VerticalGrow | 144 | VerticalGrow-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wave | 145 | Wave-effekt. Klass **Emphasis**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wedge | 146 | Wedge-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wheel | 147 | Wedge-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Wheel1](../effectsubtype/)</li><li>[EffectSubtype::Wheel2](../effectsubtype/)</li><li>[EffectSubtype::Wheel3](../effectsubtype/)</li><li>[EffectSubtype::Wheel4](../effectsubtype/)</li><li>[EffectSubtype::Wheel8](../effectsubtype/)</li></ul> |
| Whip | 148 | Whip-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wipe | 149 | Wedge-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li></ul> |
| Magnify | 150 | Magnify-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Zoom | 151 | Zoom-effekt. Klass **Entrance** eller **Exit**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li><li>[EffectSubtype::InCenter](../effectsubtype/) - endast för klass **Entrance**</li><li>[EffectSubtype::OutBottom](../effectsubtype/) - endast för klass **Entrance**</li><li>[EffectSubtype::OutSlightly](../effectsubtype/)</li><li>[EffectSubtype::InSlightly](../effectsubtype/)</li><li>[EffectSubtype::OutCenter](../effectsubtype/) - endast för klass **Exit**</li><li>[EffectSubtype::InBottom](../effectsubtype/) - endast för klass **Exit**</li></ul> |
| OLEObjectShow | 152 | OLEObjectShow-effekt. Klass **OLEActionVerbs**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectEdit | 153 | OLEObjectEdit-effekt. Klass **OLEActionVerbs**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectOpen | 154 | OLEObjectOpen-effekt. Klass **OLEActionVerbs**.<br>Giltiga undertyper:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |

## Se även

* Namnrymd [Aspose::Slides::Animation](../)
* Bibliotek [Aspose.Slides](../../)