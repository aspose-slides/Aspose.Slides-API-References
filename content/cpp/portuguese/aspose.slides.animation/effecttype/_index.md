---
title: EffectType
second_title: Referência da API Aspose.Slides para C++
description: Representa o tipo de um efeito de animação.
type: docs
weight: 833
url: /pt/aspose.slides.animation/effecttype/
---
## EffectType enum

Representa o tipo de um efeito de animação.

```cpp
enum class EffectType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Appear | 0 | Efeito Appear. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CurveUpDown | 1 | Efeito CurveUpDown. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Ascend | 2 | Efeito Ascend. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatUp | 2 | Efeito Float com direção Up. Este é o alias para o tipo Ascend. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blast | 3 | Efeito Blast. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blinds | 4 | Efeito Blinds. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Blink | 5 | Efeito Blink. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldFlash | 6 | Efeito BoldFlash. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldReveal | 7 | Efeito BoldReveal. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Boomerang | 8 | Efeito Boomerang. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Bounce | 9 | Efeito Bounce. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Box | 10 | Efeito Box. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| BrushOnColor | 11 | Efeito BrushOnColor. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BrushOnUnderline | 12 | Efeito BrushOnUnderline. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CenterRevolve | 13 | Efeito CenterRevolve. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ChangeFillColor | 14 | Efeito ChangeFillColor. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFont | 15 | Efeito ChangeFont. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontColor | 16 | Efeito ChangeFontColor. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFontSize | 17 | Efeito ChangeFontSize. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontStyle | 18 | Efeito ChangeFontSize. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::FontBold](../effectsubtype/)</li><li>[EffectSubtype::FontItalic](../effectsubtype/)</li><li>[EffectSubtype::FontUnderline](../effectsubtype/)</li></ul> |
| ChangeLineColor | 19 | Efeito ChangeLineColor. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| Checkerboard | 20 | Efeito Checkerboard. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Vertical](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Circle | 21 | Efeito ColorBlend. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| ColorBlend | 22 | Efeito BrushOnUnderline. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorTypewriter | 23 | Efeito Checkerboard. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorWave | 24 | Efeito ColorWave. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor | 25 | Efeito ComplementaryColor. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor2 | 26 | Efeito ComplementaryColor2. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Compress | 27 | Efeito Compress. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ContrastingColor | 28 | Efeito ContrastingColor. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Crawl | 29 | Efeito Crawl. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li></ul> |
| Credits | 30 | Efeito Credits. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Custom | 31 | Efeito Custom. |
| Darken | 32 | Efeito Darken. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Desaturate | 33 | Efeito Desaturate. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Descend | 34 | Efeito Descend. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatDown | 34 | Efeito Float com direção Down. Este é o alias para o tipo Descend. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Diamond | 35 | Efeito Diamond. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| Dissolve | 36 | Efeito Dissolve. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| EaseInOut | 37 | Efeito Dissolve. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Expand | 38 | Efeito Expand. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fade | 39 | Efeito Fade. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedSwivel | 40 | Efeito FadedSwivel. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedZoom | 41 | Efeito FadedZoom. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashBulb | 42 | Efeito FlashBulb. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashOnce | 43 | Efeito FlashOnce. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flicker | 44 | Efeito Flicker. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flip | 45 | Efeito Flip. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Float | 46 | Efeito Float. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fly | 47 | Efeito Fly. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::TopLeft](../effectsubtype/)</li><li>[EffectSubtype::TopRight](../effectsubtype/)</li><li>[EffectSubtype::BottomLeft](../effectsubtype/)</li><li>[EffectSubtype::BottomRight](../effectsubtype/)</li></ul> |
| Fold | 48 | Efeito Fold. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Glide | 49 | Efeito Glide. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowAndTurn | 50 | Efeito GrowAndTurn. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowShrink | 51 | Efeito GrowShrink. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowWithColor | 52 | Efeito GrowWithColor. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Lighten | 53 | Efeito Lighten. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| LightSpeed | 54 | Efeito LightSpeed. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPause | 55 | Efeito MediaPause. Classe **Media**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPlay | 56 | Efeito MediaPlay. Classe **Media**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaStop | 57 | Efeito MediaStop. Classe **Media**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path4PointStar | 58 | Efeito Path4PointStar. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path5PointStar | 59 | Efeito Path5PointStar. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path6PointStar | 60 | Efeito Path6PointStar. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path8PointStar | 61 | Efeito Path8PointStar. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcDown | 62 | Efeito PathArcDown. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcLeft | 63 | Efeito PathArcLeft. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcRight | 64 | Efeito PathArcRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcUp | 65 | Efeito PathArcUp. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBean | 66 | Efeito PathBean. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceLeft | 67 | Efeito PathBounceLeft. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceRight | 68 | Efeito PathBounceRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBuzzsaw | 69 | Efeito PathBuzzsaw. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCircle | 70 | Efeito PathCircle. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCrescentMoon | 71 | Efeito PathCrescentMoon. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedSquare | 72 | Efeito PathCurvedSquare. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedX | 73 | Efeito PathCurvedX. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyLeft | 74 | Efeito PathCurvyLeft. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyRight | 75 | Efeito PathCurvyRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyStar | 76 | Efeito PathCurvyStar. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDecayingWave | 77 | Efeito PathDecayingWave. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalDownRight | 78 | Efeito PathDiagonalDownRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalUpRight | 79 | Efeito PathDiagonalUpRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiamond | 80 | Efeito PathDiamond. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDown | 81 | Efeito PathDown. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathEqualTriangle | 82 | Efeito PathEqualTriangle. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFigure8Four | 83 | Efeito PathFigure8Four. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFootball | 84 | Efeito PathFootball. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFunnel | 85 | Efeito PathFunnel. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeart | 86 | Efeito PathHeart. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeartbeat | 87 | Efeito PathHeartbeat. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHexagon | 88 | Efeito PathHexagon. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHorizontalFigure8 | 89 | Efeito PathHorizontalFigure8. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedSquare | 90 | Efeito PathInvertedSquare. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedTriangle | 91 | Efeito PathInvertedTriangle. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLeft | 92 | Efeito PathLeft. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLoopdeLoop | 93 | Efeito PathLoopdeLoop. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathNeutron | 94 | Efeito PathNeutron. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathOctagon | 95 | Efeito PathOctagon. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathParallelogram | 96 | Efeito PathParallelogram. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPeanut | 97 | Efeito PathPeanut. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPentagon | 98 | Efeito PathPentagon. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPlus | 99 | Efeito PathPlus. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPointyStar | 100 | Efeito PathPointyStar. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRight | 101 | Efeito PathRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRightTriangle | 102 | Efeito PathRightTriangle. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve1 | 103 | Efeito PathSCurve1. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve2 | 104 | Efeito PathSCurve2. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSineWave | 105 | Efeito PathSineWave. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralLeft | 106 | Efeito PathSpiralLeft. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralRight | 107 | Efeito PathSpiralRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpring | 108 | Efeito PathSpring. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSquare | 109 | Efeito PathSquare. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathStairsDown | 110 | Efeito PathStairsDown. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSwoosh | 111 | Efeito PathSwoosh. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTeardrop | 112 | Efeito PathTeardrop. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTrapezoid | 113 | Efeito PathTrapezoid. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnDown | 114 | Efeito PathTurnDown. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnRight | 115 | Efeito PathTurnRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUp | 116 | Efeito PathTurnUp. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUpRight | 117 | Efeito PathTurnUpRight. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUp | 118 | Efeito PathUp. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUser | 119 | Efeito PathUser. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathVerticalFigure8 | 120 | Efeito PathVerticalFigure8. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathWave | 121 | Efeito PathWave. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathZigzag | 122 | Efeito PathZigzag. Classe **Path**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Peek | 123 | Efeito Peek. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Pinwheel | 124 | Efeito Pinwheel. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Plus | 125 | Efeito Plus. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| RandomBars | 126 | Efeito RandomBars. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| RandomEffects | 127 | Efeito RandomEffects. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| RiseUp | 128 | Efeito RandomEffects. Classe **Entrance**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Shimmer | 129 | Efeito Shimmer. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Sling | 130 | Efeito RandomEffects. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spin | 131 | Efeito Spin. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spinner | 132 | Efeito Spinner. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spiral | 133 | Efeito Spiral. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Split | 134 | Efeito Split. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::HorizontalIn](../effectsubtype/)</li><li>[EffectSubtype::HorizontalOut](../effectsubtype/)</li><li>[EffectSubtype::VerticalIn](../effectsubtype/)</li><li>[EffectSubtype::VerticalOut](../effectsubtype/)</li></ul> |
| Stretch | 135 | Efeito Stretch. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Strips | 136 | Efeito Stretch. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::UpLeft](../effectsubtype/)</li><li>[EffectSubtype::UpRight](../effectsubtype/)</li><li>[EffectSubtype::DownLeft](../effectsubtype/)</li><li>[EffectSubtype::DownRight](../effectsubtype/)</li></ul> |
| StyleEmphasis | 137 | Efeito StyleEmphasis. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swish | 138 | Efeito Swish. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swivel | 139 | Efeito Swivel. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Teeter | 140 | Efeito Teeter. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Thread | 141 | Efeito Thread. Classe **Emphasis**.<br>Subtipos válitos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Transparency | 142 | Efeito Transparency. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Unfold | 143 | Efeito Unfold. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| VerticalGrow | 144 | Efeito VerticalGrow. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wave | 145 | Efeito Wave. Classe **Emphasis**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wedge | 146 | Efeito Wedge. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wheel | 147 | Efeito Wedge. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Wheel1](../effectsubtype/)</li><li>[EffectSubtype::Wheel2](../effectsubtype/)</li><li>[EffectSubtype::Wheel3](../effectsubtype/)</li><li>[EffectSubtype::Wheel4](../effectsubtype/)</li><li>[EffectSubtype::Wheel8](../effectsubtype/)</li></ul> |
| Whip | 148 | Efeito Whip. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wipe | 149 | Efeito Wedge. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li></ul> |
| Magnify | 150 | Efeito Magnify. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Zoom | 151 | Efeito Zoom. Classe **Entrance** ou **Exit**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li><li>[EffectSubtype::InCenter](../effectsubtype/) - only for Entrance class</li><li>[EffectSubtype::OutBottom](../effectsubtype/) - only for Entrance class</li><li>[EffectSubtype::OutSlightly](../effectsubtype/)</li><li>[EffectSubtype::InSlightly](../effectsubtype/)</li><li>[EffectSubtype::OutCenter](../effectsubtype/) - only for Exit class</li><li>[EffectSubtype::InBottom](../effectsubtype/) - only for Exit class</li></ul> |
| OLEObjectShow | 152 | Efeito OLEObjectShow. Classe **OLEActionVerbs**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectEdit | 153 | Efeito OLEObjectEdit. Classe **OLEActionVerbs**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectOpen | 154 | Efeito OLEObjectOpen. Classe **OLEActionVerbs**.<br>Subtipos válidos:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |

## Veja também

* Namespace [Aspose::Slides::Animation](../)
* Biblioteca [Aspose.Slides](../../)