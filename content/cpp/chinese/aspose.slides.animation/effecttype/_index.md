---
title: EffectType
second_title: Aspose.Slides for C++ API 参考
description: 表示动画效果的类型。
type: docs
weight: 833
url: /zh/aspose.slides.animation/effecttype/
---
## EffectType 枚举

表示动画效果的类型。

```cpp
enum class EffectType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Appear | 0 | Appear 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CurveUpDown | 1 | CurveUpDown 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Ascend | 2 | Ascend 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatUp | 2 | 向上方向的 Float 效果。此为 Ascend 类型的别名。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blast | 3 | Blast 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blinds | 4 | Blinds 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Blink | 5 | Blink 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldFlash | 6 | BoldFlash 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldReveal | 7 | BoldReveal 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Boomerang | 8 | Boomerang 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Bounce | 9 | Bounce 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Box | 10 | Box 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| BrushOnColor | 11 | BrushOnColor 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BrushOnUnderline | 12 | BrushOnUnderline 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CenterRevolve | 13 | CenterRevolve 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ChangeFillColor | 14 | ChangeFillColor 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFont | 15 | ChangeFont 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontColor | 16 | ChangeFontColor 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFontSize | 17 | ChangeFontSize 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontStyle | 18 | ChangeFontSize 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::FontBold](../effectsubtype/)</li><li>[EffectSubtype::FontItalic](../effectsubtype/)</li><li>[EffectSubtype::FontUnderline](../effectsubtype/)</li></ul> |
| ChangeLineColor | 19 | ChangeLineColor 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| Checkerboard | 20 | Checkerboard 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Vertical](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Circle | 21 | ColorBlend 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| ColorBlend | 22 | BrushOnUnderline 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorTypewriter | 23 | Checkerboard 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorWave | 24 | ColorWave 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor | 25 | ComplementaryColor 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor2 | 26 | ComplementaryColor2 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Compress | 27 | Compress 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ContrastingColor | 28 | ContrastingColor 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Crawl | 29 | Crawl 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li></ul> |
| Credits | 30 | Credits 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Custom | 31 | Custom 效果。 |
| Darken | 32 | Darken 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Desaturate | 33 | Desaturate 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Descend | 34 | Descend 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatDown | 34 | 向下方向的 Float 效果。此为 Descend 类型的别名。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Diamond | 35 | Diamond 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| Dissolve | 36 | Dissolve 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| EaseInOut | 37 | Dissolve 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Expand | 38 | Expand 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fade | 39 | Fade 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedSwivel | 40 | FadedSwivel 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedZoom | 41 | FadedZoom 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashBulb | 42 | FlashBulb 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashOnce | 43 | FlashOnce 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flicker | 44 | Flicker 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flip | 45 | Flip 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Float | 46 | Float 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fly | 47 | Fly 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::TopLeft](../effectsubtype/)</li><li>[EffectSubtype::TopRight](../effectsubtype/)</li><li>[EffectSubtype::BottomLeft](../effectsubtype/)</li><li>[EffectSubtype::BottomRight](../effectsubtype/)</li></ul> |
| Fold | 48 | Fold 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Glide | 49 | Glide 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowAndTurn | 50 | GrowAndTurn 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowShrink | 51 | GrowShrink 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowWithColor | 52 | GrowWithColor 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Lighten | 53 | Lighten 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| LightSpeed | 54 | LightSpeed 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPause | 55 | MediaPause 效果。类 **Media**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPlay | 56 | MediaPlay 效果。类 **Media**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaStop | 57 | MediaStop 效果。类 **Media**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path4PointStar | 58 | Path4PointStar 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path5PointStar | 59 | Path5PointStar 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path6PointStar | 60 | Path6PointStar 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path8PointStar | 61 | Path8PointStar 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcDown | 62 | PathArcDown 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcLeft | 63 | PathArcLeft 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcRight | 64 | PathArcRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcUp | 65 | PathArcUp 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBean | 66 | PathBean 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceLeft | 67 | PathBounceLeft 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceRight | 68 | PathBounceRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBuzzsaw | 69 | PathBuzzsaw 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCircle | 70 | PathCircle 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCrescentMoon | 71 | PathCrescentMoon 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedSquare | 72 | PathCurvedSquare 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedX | 73 | PathCurvedX 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyLeft | 74 | PathCurvyLeft 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyRight | 75 | PathCurvyRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyStar | 76 | PathCurvyStar 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDecayingWave | 77 | PathDecayingWave 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalDownRight | 78 | PathDiagonalDownRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalUpRight | 79 | PathDiagonalUpRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiamond | 80 | PathDiamond 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDown | 81 | PathDown 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathEqualTriangle | 82 | PathEqualTriangle 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFigure8Four | 83 | PathFigure8Four 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFootball | 84 | PathFootball 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFunnel | 85 | PathFunnel 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeart | 86 | PathHeart 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeartbeat | 87 | PathHeartbeat 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHexagon | 88 | PathHexagon 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHorizontalFigure8 | 89 | PathHorizontalFigure8 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedSquare | 90 | PathInvertedSquare 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedTriangle | 91 | PathInvertedTriangle 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLeft | 92 | PathLeft 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLoopdeLoop | 93 | PathLoopdeLoop 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathNeutron | 94 | PathNeutron 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathOctagon | 95 | PathOctagon 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathParallelogram | 96 | PathParallelogram 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPeanut | 97 | PathPeanut 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPentagon | 98 | PathPentagon 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPlus | 99 | PathPlus 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPointyStar | 100 | PathPointyStar 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRight | 101 | PathRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRightTriangle | 102 | PathRightTriangle 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve1 | 103 | PathSCurve1 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve2 | 104 | PathSCurve2 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSineWave | 105 | PathSineWave 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralLeft | 106 | PathSpiralLeft 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralRight | 107 | PathSpiralRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpring | 108 | PathSpring 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSquare | 109 | PathSquare 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathStairsDown | 110 | PathStairsDown 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSwoosh | 111 | PathSwoosh 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTeardrop | 112 | PathTeardrop 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTrapezoid | 113 | PathTrapezoid 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnDown | 114 | PathTurnDown 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnRight | 115 | PathTurnRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUp | 116 | PathTurnUp 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUpRight | 117 | PathTurnUpRight 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUp | 118 | PathUp 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUser | 119 | PathUser 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathVerticalFigure8 | 120 | PathVerticalFigure8 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathWave | 121 | PathWave 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathZigzag | 122 | PathZigzag 效果。类 **Path**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Peek | 123 | Peek 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Pinwheel | 124 | Pinwheel 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Plus | 125 | Plus 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| RandomBars | 126 | RandomBars 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| RandomEffects | 127 | RandomEffects 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| RiseUp | 128 | RandomEffects 效果。类 **Entrance**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Shimmer | 129 | Shimmer 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Sling | 130 | RandomEffects 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spin | 131 | Spin 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spinner | 132 | Spinner 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spiral | 133 | Spiral 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Split | 134 | Split 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::HorizontalIn](../effectsubtype/)</li><li>[EffectSubtype::HorizontalOut](../effectsubtype/)</li><li>[EffectSubtype::VerticalIn](../effectsubtype/)</li><li>[EffectSubtype::VerticalOut](../effectsubtype/)</li></ul> |
| Stretch | 135 | Stretch 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Strips | 136 | Stretch 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::UpLeft](../effectsubtype/)</li><li>[EffectSubtype::UpRight](../effectsubtype/)</li><li>[EffectSubtype::DownLeft](../effectsubtype/)</li><li>[EffectSubtype::DownRight](../effectsubtype/)</li></ul> |
| StyleEmphasis | 137 | StyleEmphasis 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swish | 138 | Swish 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swivel | 139 | Swivel 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Teeter | 140 | Teeter 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Thread | 141 | Thread 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Transparency | 142 | Transparency 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Unfold | 143 | Unfold 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| VerticalGrow | 144 | VerticalGrow 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wave | 145 | Wave 效果。类 **Emphasis**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wedge | 146 | Wedge 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wheel | 147 | Wedge 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Wheel1](../effectsubtype/)</li><li>[EffectSubtype::Wheel2](../effectsubtype/)</li><li>[EffectSubtype::Wheel3](../effectsubtype/)</li><li>[EffectSubtype::Wheel4](../effectsubtype/)</li><li>[EffectSubtype::Wheel8](../effectsubtype/)</li></ul> |
| Whip | 148 | Whip 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wipe | 149 | Wedge 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li></ul> |
| Magnify | 150 | Magnify 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Zoom | 151 | Zoom 效果。类 **Entrance** 或 **Exit**。<br>有效子类型：<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li><li>[EffectSubtype::InCenter](../effectsubtype/) - 仅适用于 Entrance 类</li><li>[EffectSubtype::OutBottom](../effectsubtype/) - 仅适用于 Entrance 类</li><li>[EffectSubtype::OutSlightly](../effectsubtype/)</li><li>[EffectSubtype::InSlightly](../effectsubtype/)</li><li>[EffectSubtype::OutCenter](../effectsubtype/) - 仅适用于 Exit 类</li><li>[EffectSubtype::InBottom](../effectsubtype/) - 仅适用于 Exit 类</li></ul> |
| OLEObjectShow | 152 | OLEObjectShow 效果。类 **OLEActionVerbs**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectEdit | 153 | OLEObjectEdit 效果。类 **OLEActionVerbs**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectOpen | 154 | OLEObjectOpen 效果。类 **OLEActionVerbs**。<br>有效子类型：<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |

## 另请参见

* 命名空间 [Aspose::Slides::Animation](../)
* 库 [Aspose.Slides](../../)