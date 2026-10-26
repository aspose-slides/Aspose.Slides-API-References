---
title: EffectType
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーション効果の種類を表します。
type: docs
weight: 833
url: /ja/aspose.slides.animation/effecttype/
---
## EffectType 列挙体

アニメーション効果のタイプを表します。

```cpp
enum class EffectType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Appear | 0 | Appear 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CurveUpDown | 1 | CurveUpDown 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Ascend | 2 | Ascend 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatUp | 2 | Float 効果（方向 Up）。これは Ascend タイプのエイリアスです。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blast | 3 | Blast 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Blinds | 4 | Blinds 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Blink | 5 | Blink 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldFlash | 6 | BoldFlash 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BoldReveal | 7 | BoldReveal 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Boomerang | 8 | Boomerang 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Bounce | 9 | Bounce 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Box | 10 | Box 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| BrushOnColor | 11 | BrushOnColor 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| BrushOnUnderline | 12 | BrushOnUnderline 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| CenterRevolve | 13 | CenterRevolve 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ChangeFillColor | 14 | ChangeFillColor 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFont | 15 | ChangeFont 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontColor | 16 | ChangeFontColor 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| ChangeFontSize | 17 | ChangeFontSize 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li></ul> |
| ChangeFontStyle | 18 | ChangeFontSize 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::FontBold](../effectsubtype/)</li><li>[EffectSubtype::FontItalic](../effectsubtype/)</li><li>[EffectSubtype::FontUnderline](../effectsubtype/)</li></ul> |
| ChangeLineColor | 19 | ChangeLineColor 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Instant](../effectsubtype/)</li><li>[EffectSubtype::Gradual](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleClockwise](../effectsubtype/)</li><li>[EffectSubtype::GradualAndCycleCounterClockwise](../effectsubtype/)</li></ul> |
| Checkerboard | 20 | Checkerboard 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Vertical](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Circle | 21 | ColorBlend 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| ColorBlend | 22 | BrushOnUnderline 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorTypewriter | 23 | Checkerboard 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ColorWave | 24 | ColorWave 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor | 25 | ComplementaryColor 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ComplementaryColor2 | 26 | ComplementaryColor2 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Compress | 27 | Compress 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| ContrastingColor | 28 | ContrastingColor 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Crawl | 29 | Crawl 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li></ul> |
| Credits | 30 | Credits 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Custom | 31 | Custom 効果です。 |
| Darken | 32 | Darken 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Desaturate | 33 | Desaturate 効果です।クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Descend | 34 | Descend 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FloatDown | 34 | Float 効果（方向 Down）。これは Descend タイプのエイリアスです。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Diamond | 35 | Diamond 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| Dissolve | 36 | Dissolve 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| EaseInOut | 37 | Dissolve 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Expand | 38 | Expand 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fade | 39 | Fade 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedSwivel | 40 | FadedSwivel 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FadedZoom | 41 | FadedZoom 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashBulb | 42 | FlashBulb 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| FlashOnce | 43 | FlashOnce 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flicker | 44 | Flicker 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Flip | 45 | Flip 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Float | 46 | Float 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Fly | 47 | Fly 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::TopLeft](../effectsubtype/)</li><li>[EffectSubtype::TopRight](../effectsubtype/)</li><li>[EffectSubtype::BottomLeft](../effectsubtype/)</li><li>[EffectSubtype::BottomRight](../effectsubtype/)</li></ul> |
| Fold | 48 | Fold 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Glide | 49 | Glide 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowAndTurn | 50 | GrowAndTurn 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowShrink | 51 | GrowShrink 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| GrowWithColor | 52 | GrowWithColor 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Lighten | 53 | Lighten 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| LightSpeed | 54 | LightSpeed 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPause | 55 | MediaPause 効果です。クラス **Media**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaPlay | 56 | MediaPlay 効果です。クラス **Media**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| MediaStop | 57 | MediaStop 効果です。クラス **Media**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path4PointStar | 58 | Path4PointStar 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path5PointStar | 59 | Path5PointStar 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path6PointStar | 60 | Path6PointStar 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Path8PointStar | 61 | Path8PointStar 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcDown | 62 | PathArcDown 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcLeft | 63 | PathArcLeft 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcRight | 64 | PathArcRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathArcUp | 65 | PathArcUp 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBean | 66 | PathBean 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceLeft | 67 | PathBounceLeft 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBounceRight | 68 | PathBounceRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathBuzzsaw | 69 | PathBuzzsaw 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCircle | 70 | PathCircle 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCrescentMoon | 71 | PathCrescentMoon 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedSquare | 72 | PathCurvedSquare 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvedX | 73 | PathCurvedX 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyLeft | 74 | PathCurvyLeft 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyRight | 75 | PathCurvyRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathCurvyStar | 76 | PathCurvyStar 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDecayingWave | 77 | PathDecayingWave 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalDownRight | 78 | PathDiagonalDownRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiagonalUpRight | 79 | PathDiagonalUpRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDiamond | 80 | PathDiamond 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathDown | 81 | PathDown 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathEqualTriangle | 82 | PathEqualTriangle 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFigure8Four | 83 | PathFigure8Four 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFootball | 84 | PathFootball 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathFunnel | 85 | PathFunnel 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeart | 86 | PathHeart 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHeartbeat | 87 | PathHeartbeat 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHexagon | 88 | PathHexagon 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathHorizontalFigure8 | 89 | PathHorizontalFigure8 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedSquare | 90 | PathInvertedSquare 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathInvertedTriangle | 91 | PathInvertedTriangle 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLeft | 92 | PathLeft 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathLoopdeLoop | 93 | PathLoopdeLoop 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathNeutron | 94 | PathNeutron 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathOctagon | 95 | PathOctagon 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathParallelogram | 96 | PathParallelogram 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPeanut | 97 | PathPeanut 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPentagon | 98 | PathPentagon 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPlus | 99 | PathPlus 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathPointyStar | 100 | PathPointyStar 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRight | 101 | PathRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathRightTriangle | 102 | PathRightTriangle 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve1 | 103 | PathSCurve1 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSCurve2 | 104 | PathSCurve2 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSineWave | 105 | PathSineWave 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralLeft | 106 | PathSpiralLeft 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpiralRight | 107 | PathSpiralRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSpring | 108 | PathSpring 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSquare | 109 | PathSquare 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathStairsDown | 110 | PathStairsDown 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathSwoosh | 111 | PathSwoosh 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTeardrop | 112 | PathTeardrop 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTrapezoid | 113 | PathTrapezoid 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnDown | 114 | PathTurnDown 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnRight | 115 | PathTurnRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUp | 116 | PathTurnUp 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathTurnUpRight | 117 | PathTurnUpRight 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUp | 118 | PathUp 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathUser | 119 | PathUser 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathVerticalFigure8 | 120 | PathVerticalFigure8 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathWave | 121 | PathWave 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| PathZigzag | 122 | PathZigzag 効果です。クラス **Path**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Peek | 123 | Peek 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Pinwheel | 124 | Pinwheel 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Plus | 125 | Plus 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li></ul> |
| RandomBars | 126 | RandomBars 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| RandomEffects | 127 | RandomEffects 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| RiseUp | 128 | RandomEffects 効果です。クラス **Entrance**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Shimmer | 129 | Shimmer 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Sling | 130 | RandomEffects 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spin | 131 | Spin 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spinner | 132 | Spinner 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Spiral | 133 | Spiral 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Split | 134 | Split 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::HorizontalIn](../effectsubtype/)</li><li>[EffectSubtype::HorizontalOut](../effectsubtype/)</li><li>[EffectSubtype::VerticalIn](../effectsubtype/)</li><li>[EffectSubtype::VerticalOut](../effectsubtype/)</li></ul> |
| Stretch | 135 | Stretch 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Across](../effectsubtype/)</li></ul> |
| Strips | 136 | Stretch 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::UpLeft](../effectsubtype/)</li><li>[EffectSubtype::UpRight](../effectsubtype/)</li><li>[EffectSubtype::DownLeft](../effectsubtype/)</li><li>[EffectSubtype::DownRight](../effectsubtype/)</li></ul> |
| StyleEmphasis | 137 | StyleEmphasis 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swish | 138 | Swish 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Swivel | 139 | Swivel 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Horizontal](../effectsubtype/)</li><li>[EffectSubtype::Vertical](../effectsubtype/)</li></ul> |
| Teeter | 140 | Teeter 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Thread | 141 | Thread 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Transparency | 142 | Transparency 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Unfold | 143 | Unfold 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| VerticalGrow | 144 | VerticalGrow 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wave | 145 | Wave 効果です。クラス **Emphasis**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wedge | 146 | Wedge 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wheel | 147 | Wedge 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Wheel1](../effectsubtype/)</li><li>[EffectSubtype::Wheel2](../effectsubtype/)</li><li>[EffectSubtype::Wheel3](../effectsubtype/)</li><li>[EffectSubtype::Wheel4](../effectsubtype/)</li><li>[EffectSubtype::Wheel8](../effectsubtype/)</li></ul> |
| Whip | 148 | Whip 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Wipe | 149 | Wedge 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::Top](../effectsubtype/)</li><li>[EffectSubtype::Right](../effectsubtype/)</li><li>[EffectSubtype::Bottom](../effectsubtype/)</li><li>[EffectSubtype::Left](../effectsubtype/)</li></ul> |
| Magnify | 150 | Magnify 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| Zoom | 151 | Zoom 効果です。クラス **Entrance** または **Exit**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::In](../effectsubtype/)</li><li>[EffectSubtype::Out](../effectsubtype/)</li><li>[EffectSubtype::InCenter](../effectsubtype/) - Entrance クラスのみ</li><li>[EffectSubtype::OutBottom](../effectsubtype/) - Entrance クラスのみ</li><li>[EffectSubtype::OutSlightly](../effectsubtype/)</li><li>[EffectSubtype::InSlightly](../effectsubtype/)</li><li>[EffectSubtype::OutCenter](../effectsubtype/) - Exit クラスのみ</li><li>[EffectSubtype::InBottom](../effectsubtype/) - Exit クラスのみ</li></ul> |
| OLEObjectShow | 152 | OLEObjectShow 効果です。クラス **OLEActionVerbs**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectEdit | 153 | OLEObjectEdit 効果です。クラス **OLEActionVerbs**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |
| OLEObjectOpen | 154 | OLEObjectOpen 効果です。クラス **OLEActionVerbs**。<br>有効なサブタイプ:<br><ul><li>[EffectSubtype::None](../effectsubtype/)</li></ul> |

## 参照

* 名前空間 [Aspose::Slides::Animation](../)
* ライブラリ [Aspose.Slides](../../)