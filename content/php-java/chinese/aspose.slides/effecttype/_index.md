---
title: EffectType
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/effecttype/
---
## EffectType 类

 表示动画效果的类型。

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[Appear](#Appear) | 0 | Appear effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[CurveUpDown](#CurveUpDown) | 1 | CurveUpDown effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Ascend](#Ascend) | 2 | Ascend effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[FloatUp](#FloatUp) | 2 | Float effect with direction Up. This is the alias for Ascend type. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Blast](#Blast) | 3 | Blast effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Blinds](#Blinds) | 4 | Blinds effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.Horizontal EffectSubtype.Vertical |
[Blink](#Blink) | 5 | Blink effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[BoldFlash](#BoldFlash) | 6 | BoldFlash effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[BoldReveal](#BoldReveal) | 7 | BoldReveal effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Boomerang](#Boomerang) | 8 | Boomerang effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Bounce](#Bounce) | 9 | Bounce effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Box](#Box) | 10 | Box effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.In EffectSubtype.Out |
[BrushOnColor](#BrushOnColor) | 11 | BrushOnColor effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[BrushOnUnderline](#BrushOnUnderline) | 12 | BrushOnUnderline effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[CenterRevolve](#CenterRevolve) | 13 | CenterRevolve effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[ChangeFillColor](#ChangeFillColor) | 14 | ChangeFillColor effect. Class Emphasis. Valid subtypes: EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise |
[ChangeFont](#ChangeFont) | 15 | ChangeFont effect. Class Emphasis. Valid subtypes: EffectSubtype.Instant EffectSubtype.Gradual |
[ChangeFontColor](#ChangeFontColor) | 16 | ChangeFontColor effect. Class Emphasis. Valid subtypes: EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise |
[ChangeFontSize](#ChangeFontSize) | 17 | ChangeFontSize effect. Class Emphasis. Valid subtypes: EffectSubtype.Instant EffectSubtype.Gradual |
[ChangeFontStyle](#ChangeFontStyle) | 18 | ChangeFontSize effect. Class Emphasis. Valid subtypes: EffectSubtype.FontBold EffectSubtype.FontItalic EffectSubtype.FontUnderline |
[ChangeLineColor](#ChangeLineColor) | 19 | ChangeLineColor effect. Class Emphasis. Valid subtypes: EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise |
[Checkerboard](#Checkerboard) | 20 | Checkerboard effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.Vertical EffectSubtype.Across |
[Circle](#Circle) | 21 | ColorBlend effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.In EffectSubtype.Out |
[ColorBlend](#ColorBlend) | 22 | BrushOnUnderline effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[ColorTypewriter](#ColorTypewriter) | 23 | Checkerboard effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[ColorWave](#ColorWave) | 24 | ColorWave effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[ComplementaryColor](#ComplementaryColor) | 25 | ComplementaryColor effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[ComplementaryColor2](#ComplementaryColor2) | 26 | ComplementaryColor2 effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Compress](#Compress) | 27 | Compress effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[ContrastingColor](#ContrastingColor) | 28 | ContrastingColor effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Crawl](#Crawl) | 29 | Crawl effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom |
[Credits](#Credits) | 30 | Credits effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Custom](#Custom) | 31 | Custom effect. |
[Darken](#Darken) | 32 | Darken effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Desaturate](#Desaturate) | 33 | Desaturate effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Descend](#Descend) | 34 | Descend effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[FloatDown](#FloatDown) | 34 | Float effect with direction Down. This is the alias for Descend type. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Diamond](#Diamond) | 35 | Diamond effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.In EffectSubtype.Out |
[Dissolve](#Dissolve) | 36 | Dissolve effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[EaseInOut](#EaseInOut) | 37 | Dissolve effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Expand](#Expand) | 38 | Expand effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Fade](#Fade) | 39 | Fade effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[FadedSwivel](#FadedSwivel) | 40 | FadedSwivel effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[FadedZoom](#FadedZoom) | 41 | FadedZoom effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[FlashBulb](#FlashBulb) | 42 | FlashBulb effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[FlashOnce](#FlashOnce) | 43 | FlashOnce effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Flicker](#Flicker) | 44 | Flicker effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Flip](#Flip) | 45 | Flip effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Float](#Float) | 46 | Float effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Fly](#Fly) | 47 | Fly effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom EffectSubtype.TopLeft EffectSubtype.TopRight EffectSubtype.BottomLeft EffectSubtype.BottomRight |
[Fold](#Fold) | 48 | Fold effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[Glide](#Glide) | 49 | Glide effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[GrowAndTurn](#GrowAndTurn) | 50 | GrowAndTurn effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[GrowShrink](#GrowShrink) | 51 | GrowShrink effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[GrowWithColor](#GrowWithColor) | 52 | GrowWithColor effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[Lighten](#Lighten) | 53 | Lighten effect. Class Emphasis. Valid subtypes: EffectSubtype.None |
[LightSpeed](#LightSpeed) | 54 | LightSpeed effect. Class Entrance or Exit. Valid subtypes: EffectSubtype.None |
[MediaPause](#MediaPause) | 55 | MediaPause effect. Class Media. Valid subtypes: EffectSubtype.None |
[MediaPlay](#MediaPlay) | 56 | MediaPlay effect. Class Media. Valid subtypes: EffectSubtype.None |
[MediaStop](#MediaStop) | 57 | MediaStop effect. Class Media. Valid subtypes: EffectSubtype.None |
[Path4PointStar](#Path4PointStar) | 58 | Path4PointStar effect. Class Path. Valid subtypes: EffectSubtype.None |
[Path5PointStar](#Path5PointStar) | 59 | Path5PointStar effect. Class Path. Valid subtypes: EffectSubtype.None |
[Path6PointStar](#Path6PointStar) | 60 | Path6PointStar effect. Class Path. Valid subtypes: EffectSubtype.None |
[Path8PointStar](#Path8PointStar) | 61 | Path8PointStar effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathArcDown](#PathArcDown) | 62 | PathArcDown effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathArcLeft](#PathArcLeft) | 63 | PathArcLeft effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathArcRight](#PathArcRight) | 64 | PathArcRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathArcUp](#PathArcUp) | 65 | PathArcUp effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathBean](#PathBean) | 66 | PathBean effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathBounceLeft](#PathBounceLeft) | 67 | PathBounceLeft effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathBounceRight](#PathBounceRight) | 68 | PathBounceRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathBuzzsaw](#PathBuzzsaw) | 69 | PathBuzzsaw effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathCircle](#PathCircle) | 70 | PathCircle effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathCrescentMoon](#PathCrescentMoon) | 71 | PathCrescentMoon effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathCurvedSquare](#PathCurvedSquare) | 72 | PathCurvedSquare effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathCurvedX](#PathCurvedX) | 73 | PathCurvedX effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathCurvyLeft](#PathCurvyLeft) | 74 | PathCurvyLeft effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathCurvyRight](#PathCurvyRight) | 75 | PathCurvyRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathCurvyStar](#PathCurvyStar) | 76 | PathCurvyStar effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathDecayingWave](#PathDecayingWave) | 77 | PathDecayingWave effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathDiagonalDownRight](#PathDiagonalDownRight) | 78 | PathDiagonalDownRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathDiagonalUpRight](#PathDiagonalUpRight) | 79 | PathDiagonalUpRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathDiamond](#PathDiamond) | 80 | PathDiamond effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathDown](#PathDown) | 81 | PathDown effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathEqualTriangle](#PathEqualTriangle) | 82 | PathEqualTriangle effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathFigure8Four](#PathFigure8Four) | 83 | PathFigure8Four effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathFootball](#PathFootball) | 84 | PathFootball effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathFunnel](#PathFunnel) | 85 | PathFunnel effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathHeart](#PathHeart) | 86 | PathHeart effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathHeartbeat](#PathHeartbeat) | 87 | PathHeartbeat effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathHexagon](#PathHexagon) | 88 | PathHexagon effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathHorizontalFigure8](#PathHorizontalFigure8) | 89 | PathHorizontalFigure8 effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathInvertedSquare](#PathInvertedSquare) | 90 | PathInvertedSquare effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathInvertedTriangle](#PathInvertedTriangle) | 91 | PathInvertedTriangle effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathLeft](#PathLeft) | 92 | PathLeft effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathLoopdeLoop](#PathLoopdeLoop) | 93 | PathLoopdeLoop effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathNeutron](#PathNeutron) | 94 | PathNeutron effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathOctagon](#PathOctagon) | 95 | PathOctagon effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathParallelogram](#PathParallelogram) | 96 | PathParallelogram effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathPeanut](#PathPeanut) | 97 | PathPeanut effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathPentagon](#PathPentagon) | 98 | PathPentagon effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathPlus](#PathPlus) | 99 | PathPlus effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathPointyStar](#PathPointyStar) | 100 | PathPointyStar effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathRight](#PathRight) | 101 | PathRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathRightTriangle](#PathRightTriangle) | 102 | PathRightTriangle effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSCurve1](#PathSCurve1) | 103 | PathSCurve1 effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSCurve2](#PathSCurve2) | 104 | PathSCurve2 effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSineWave](#PathSineWave) | 105 | PathSineWave effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSpiralLeft](#PathSpiralLeft) | 106 | PathSpiralLeft effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSpiralRight](#PathSpiralRight) | 107 | PathSpiralRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSpring](#PathSpring) | 108 | PathSpring effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSquare](#PathSquare) | 109 | PathSquare effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathStairsDown](#PathStairsDown) | 110 | PathStairsDown effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathSwoosh](#PathSwoosh) | 111 | PathSwoosh effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathTeardrop](#PathTeardrop) | 112 | PathTeardrop effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathTrapezoid](#PathTrapezoid) | 113 | PathTrapezoid effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathTurnDown](#PathTurnDown) | 114 | PathTurnDown effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathTurnRight](#PathTurnRight) | 115 | PathTurnRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathTurnUp](#PathTurnUp) | 116 | PathTurnUp effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathTurnUpRight](#PathTurnUpRight) | 117 | PathTurnUpRight effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathUp](#PathUp) | 118 | PathUp effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathUser](#PathUser) | 119 | PathUser effect. Class Path. Valid subtypes: EffectSubtype.None |
[PathVerticalFigure8](#PathVerticalFigure8) | 120 | PathVerticalFigure8 效果。 类 Path。 有效子类型： EffectSubtype.None |
[PathWave](#PathWave) | 121 | PathWave 效果。 类 Path。 有效子类型： EffectSubtype.None |
[PathZigzag](#PathZigzag) | 122 | PathZigzag 效果。 类 Path。 有效子类型： EffectSubtype.None |
[Peek](#Peek) | 123 | Peek 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Pinwheel](#Pinwheel) | 124 | Pinwheel 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Plus](#Plus) | 125 | Plus 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.In EffectSubtype.Out |
[RandomBars](#RandomBars) | 126 | RandomBars 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Horizontal EffectSubtype.Vertical |
[RandomEffects](#RandomEffects) | 127 | RandomEffects 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[RiseUp](#RiseUp) | 128 | RandomEffects 效果。 类 Entrance。 有效子类型： EffectSubtype.None |
[Shimmer](#Shimmer) | 129 | Shimmer 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Sling](#Sling) | 130 | RandomEffects 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Spin](#Spin) | 131 | Spin 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Spinner](#Spinner) | 132 | Spinner 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Spiral](#Spiral) | 133 | Spiral 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Split](#Split) | 134 | Split 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.HorizontalIn EffectSubtype.HorizontalOut EffectSubtype.VerticalIn EffectSubtype.VerticalOut |
[Stretch](#Stretch) | 135 | Stretch 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom EffectSubtype.Across |
[Strips](#Strips) | 136 | Stretch 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.UpLeft EffectSubtype.UpRight EffectSubtype.DownLeft EffectSubtype.DownRight |
[StyleEmphasis](#StyleEmphasis) | 137 | StyleEmphasis 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Swish](#Swish) | 138 | Swish 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Swivel](#Swivel) | 139 | Swivel 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Horizontal EffectSubtype.Vertical |
[Teeter](#Teeter) | 140 | Teeter 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Thread](#Thread) | 141 | Thread 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Transparency](#Transparency) | 142 | Transparency 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Unfold](#Unfold) | 143 | Unfold 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[VerticalGrow](#VerticalGrow) | 144 | VerticalGrow 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Wave](#Wave) | 145 | Wave 效果。 类 Emphasis。 有效子类型： EffectSubtype.None |
[Wedge](#Wedge) | 146 | Wedge 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Wheel](#Wheel) | 147 | Wedge 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Wheel1 EffectSubtype.Wheel2 EffectSubtype.Wheel3 EffectSubtype.Wheel4 EffectSubtype.Wheel8 |
[Whip](#Whip) | 148 | Whip 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Wipe](#Wipe) | 149 | Wedge 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Top EffectSubtype.Right EffectSubtype.Bottom EffectSubtype.Left |
[Magnify](#Magnify) | 150 | Magnify 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None |
[Zoom](#Zoom) | 151 | Zoom 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.In EffectSubtype.Out EffectSubtype.InCenter - only for Entrance class EffectSubtype.OutBottom - only for Entrance class EffectSubtype.OutSlightly EffectSubtype.InSlightly EffectSubtype.OutCenter - only for Exit class EffectSubtype.InBottom - only for Exit class |
[OLEObjectShow](#OLEObjectShow) | 152 | OLEObjectShow 效果。 类 OLEActionVerbs。 有效子类型： EffectSubtype.None |
[OLEObjectEdit](#OLEObjectEdit) | 153 | OLEObjectEdit 效果。 类 OLEActionVerbs。 有效子类型： EffectSubtype.None |
[OLEObjectOpen](#OLEObjectOpen) | 154 | OLEObjectOpen 效果。 类 OLEActionVerbs。 有效子类型： EffectSubtype.None |


---


### Appear {#Appear}
Appear 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### CurveUpDown {#CurveUpDown}
CurveUpDown 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Ascend {#Ascend}
Ascend 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### FloatUp {#FloatUp}
Float 效果（方向 Up）。 这是 Ascend 类型的别名。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Blast {#Blast}
Blast 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Blinds {#Blinds}
Blinds 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Horizontal EffectSubtype.Vertical

---

### Blink {#Blink}
Blink 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### BoldFlash {#BoldFlash}
BoldFlash 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### BoldReveal {#BoldReveal}
BoldReveal 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Boomerang {#Boomerang}
Boomerang 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Bounce {#Bounce}
Bounce 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Box {#Box}
Box 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.In EffectSubtype.Out

---

### BrushOnColor {#BrushOnColor}
BrushOnColor 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### BrushOnUnderline {#BrushOnUnderline}
BrushOnUnderline 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### CenterRevolve {#CenterRevolve}
CenterRevolve 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### ChangeFillColor {#ChangeFillColor}
ChangeFillColor 效果。 类 Emphasis。 有效子类型： EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise

---

### ChangeFont {#ChangeFont}
ChangeFont 效果。 类 Emphasis。 有效子类型： EffectSubtype.Instant EffectSubtype.Gradual

---

### ChangeFontColor {#ChangeFontColor}
ChangeFontColor 效果。 类 Emphasis。 有效子类型： EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise

---

### ChangeFontSize {#ChangeFontSize}
ChangeFontSize 效果。 类 Emphasis。 有效子类型： EffectSubtype.Instant EffectSubtype.Gradual

---

### ChangeFontStyle {#ChangeFontStyle}
ChangeFontSize 效果。 类 Emphasis。 有效子类型： EffectSubtype.FontBold EffectSubtype.FontItalic EffectSubtype.FontUnderline

---

### ChangeLineColor {#ChangeLineColor}
ChangeLineColor 效果。 类 Emphasis。 有效子类型： EffectSubtype.Instant EffectSubtype.Gradual EffectSubtype.GradualAndCycleClockwise EffectSubtype.GradualAndCycleCounterClockwise

---

### Checkerboard {#Checkerboard}
Checkerboard 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Vertical EffectSubtype.Across

---

### Circle {#Circle}
ColorBlend 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.In EffectSubtype.Out

---

### ColorBlend {#ColorBlend}
BrushOnUnderline 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### ColorTypewriter {#ColorTypewriter}
Checkerboard 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### ColorWave {#ColorWave}
ColorWave 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### ComplementaryColor {#ComplementaryColor}
ComplementaryColor 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### ComplementaryColor2 {#ComplementaryColor2}
ComplementaryColor2 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Compress {#Compress}
Compress 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### ContrastingColor {#ContrastingColor}
ContrastingColor 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Crawl {#Crawl}
Crawl 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom

---

### Credits {#Credits}
Credits 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Custom {#Custom}
Custom 效果。

---

### Darken {#Darken}
Darken 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Desaturate {#Desaturate}
Desaturate 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Descend {#Descend}
Descend 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### FloatDown {#FloatDown}
Float 效果（方向 Down）。 这是 Descend 类型的别名。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Diamond {#Diamond}
Diamond 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.In EffectSubtype.Out

---

### Dissolve {#Dissolve}
Dissolve 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### EaseInOut {#EaseInOut}
Dissolve 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Expand {#Expand}
Expand 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Fade {#Fade}
Fade 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### FadedSwivel {#FadedSwivel}
FadedSwivel 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### FadedZoom {#FadedZoom}
FadedZoom 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### FlashBulb {#FlashBulb}
FlashBulb 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### FlashOnce {#FlashOnce}
FlashOnce 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Flicker {#Flicker}
Flicker 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Flip {#Flip}
Flip 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Float {#Float}
Float 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Fly {#Fly}
Fly 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom EffectSubtype.TopLeft EffectSubtype.TopRight EffectSubtype.BottomLeft EffectSubtype.BottomRight

---

### Fold {#Fold}
Fold 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### Glide {#Glide}
Glide 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### GrowAndTurn {#GrowAndTurn}
GrowAndTurn 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### GrowShrink {#GrowShrink}
GrowShrink 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### GrowWithColor {#GrowWithColor}
GrowWithColor 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### Lighten {#Lighten}
Lighten 效果。 类 Emphasis。 有效子类型： EffectSubtype.None

---

### LightSpeed {#LightSpeed}
LightSpeed 效果。 类 Entrance 或 Exit。 有效子类型： EffectSubtype.None

---

### MediaPause {#MediaPause}
MediaPause 效果。 类 Media。 有效子类型： EffectSubtype.None

---

### MediaPlay {#MediaPlay}
MediaPlay 效果。 类 Media。 有效子类型： EffectSubtype.None

---

### MediaStop {#MediaStop}
MediaStop 效果。 类 Media。 有效子类型： EffectSubtype.None

---

### Path4PointStar {#Path4PointStar}
Path4PointStar 效果。 类 Path。 有效子类型： EffectSubtype.None

---

### Path5PointStar {#Path5PointStar}
Path5PointStar 效果。 类 Path。 有效子类型： EffectSubtype.None

---

### Path6PointStar {#Path6PointStar}
Path6PointStar 效果。 类 Path。 有效子类型： EffectSubtype.None

---

### Path8PointStar {#Path8PointStar}
Path8PointStar 效果。 类 Path。 有效子类型： EffectSubtype.None

---

### PathArcDown {#PathArcDown}
PathArcDown 效果。 类 Path。 有效子类型： EffectSubtype.None

---

### PathArcLeft {#PathArcLeft}
PathArcLeft 效果。 类 Path。 有效子类型： EffectSubtype.None

---

### PathArcRight {#PathArcRight}
PathArcRight 效果。 类 Path。 有效子类型： EffectSubtype.None

---

### PathArcUp {#PathArcUp}
PathArcUp 效果。 类 Path。 有效子类型： EffectSubtype.None
PathArcUp effect. Class Path. Valid subtypes: EffectSubtype.None

---

### PathArcUp {#PathArcUp}
PathArcUp 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathBean {#PathBean}
PathBean 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathBounceLeft {#PathBounceLeft}
PathBounceLeft 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathBounceRight {#PathBounceRight}
PathBounceRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathBuzzsaw {#PathBuzzsaw}
PathBuzzsaw 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathCircle {#PathCircle}
PathCircle 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathCrescentMoon {#PathCrescentMoon}
PathCrescentMoon 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathCurvedSquare {#PathCurvedSquare}
PathCurvedSquare 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathCurvedX {#PathCurvedX}
PathCurvedX 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathCurvyLeft {#PathCurvyLeft}
PathCurvyLeft 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathCurvyRight {#PathCurvyRight}
PathCurvyRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathCurvyStar {#PathCurvyStar}
PathCurvyStar 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathDecayingWave {#PathDecayingWave}
PathDecayingWave 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathDiagonalDownRight {#PathDiagonalDownRight}
PathDiagonalDownRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathDiagonalUpRight {#PathDiagonalUpRight}
PathDiagonalUpRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathDiamond {#PathDiamond}
PathDiamond 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathDown {#PathDown}
PathDown 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathEqualTriangle {#PathEqualTriangle}
PathEqualTriangle 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathFigure8Four {#PathFigure8Four}
PathFigure8Four 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathFootball {#PathFootball}
PathFootball 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathFunnel {#PathFunnel}
PathFunnel 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathHeart {#PathHeart}
PathHeart 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathHeartbeat {#PathHeartbeat}
PathHeartbeat 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathHexagon {#PathHexagon}
PathHexagon 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathHorizontalFigure8 {#PathHorizontalFigure8}
PathHorizontalFigure8 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathInvertedSquare {#PathInvertedSquare}
PathInvertedSquare 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathInvertedTriangle {#PathInvertedTriangle}
PathInvertedTriangle 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathLeft {#PathLeft}
PathLeft 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathLoopdeLoop {#PathLoopdeLoop}
PathLoopdeLoop 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathNeutron {#PathNeutron}
PathNeutron 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathOctagon {#PathOctagon}
PathOctagon 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathParallelogram {#PathParallelogram}
PathParallelogram 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathPeanut {#PathPeanut}
PathPeanut 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathPentagon {#PathPentagon}
PathPentagon 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathPlus {#PathPlus}
PathPlus 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathPointyStar {#PathPointyStar}
PathPointyStar 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathRight {#PathRight}
PathRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathRightTriangle {#PathRightTriangle}
PathRightTriangle 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSCurve1 {#PathSCurve1}
PathSCurve1 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSCurve2 {#PathSCurve2}
PathSCurve2 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSineWave {#PathSineWave}
PathSineWave 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSpiralLeft {#PathSpiralLeft}
PathSpiralLeft 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSpiralRight {#PathSpiralRight}
PathSpiralRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSpring {#PathSpring}
PathSpring 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSquare {#PathSquare}
PathSquare 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathStairsDown {#PathStairsDown}
PathStairsDown 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathSwoosh {#PathSwoosh}
PathSwoosh 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathTeardrop {#PathTeardrop}
PathTeardrop 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathTrapezoid {#PathTrapezoid}
PathTrapezoid 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathTurnDown {#PathTurnDown}
PathTurnDown 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathTurnRight {#PathTurnRight}
PathTurnRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathTurnUp {#PathTurnUp}
PathTurnUp 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathTurnUpRight {#PathTurnUpRight}
PathTurnUpRight 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathUp {#PathUp}
PathUp 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathUser {#PathUser}
PathUser 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathVerticalFigure8 {#PathVerticalFigure8}
PathVerticalFigure8 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathWave {#PathWave}
PathWave 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### PathZigzag {#PathZigzag}
PathZigzag 效果. 类 Path. 有效子类型: EffectSubtype.None

---

### Peek {#Peek}
Peek 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Pinwheel {#Pinwheel}
Pinwheel 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Plus {#Plus}
Plus 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.In EffectSubtype.Out

---

### RandomBars {#RandomBars}
RandomBars 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.Horizontal EffectSubtype.Vertical

---

### RandomEffects {#RandomEffects}
RandomEffects 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### RiseUp {#RiseUp}
RandomEffects 效果. 类 Entrance. 有效子类型: EffectSubtype.None

---

### Shimmer {#Shimmer}
Shimmer 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Sling {#Sling}
RandomEffects 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Spin {#Spin}
Spin 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Spinner {#Spinner}
Spinner 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Spiral {#Spiral}
Spiral 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Split {#Split}
Split 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.HorizontalIn EffectSubtype.HorizontalOut EffectSubtype.VerticalIn EffectSubtype.VerticalOut

---

### Stretch {#Stretch}
Stretch 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.Right EffectSubtype.Left EffectSubtype.Top EffectSubtype.Bottom EffectSubtype.Across

---

### Strips {#Strips}
Stretch 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.UpLeft EffectSubtype.UpRight EffectSubtype.DownLeft EffectSubtype.DownRight

---

### StyleEmphasis {#StyleEmphasis}
StyleEmphasis 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Swish {#Swish}
Swish 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Swivel {#Swivel}
Swivel 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.Horizontal EffectSubtype.Vertical

---

### Teeter {#Teeter}
Teeter 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Thread {#Thread}
Thread 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Transparency {#Transparency}
Transparency 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Unfold {#Unfold}
Unfold 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### VerticalGrow {#VerticalGrow}
VerticalGrow 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Wave {#Wave}
Wave 效果. 类 Emphasis. 有效子类型: EffectSubtype.None

---

### Wedge {#Wedge}
Wedge 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Wheel {#Wheel}
Wedge 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.Wheel1 EffectSubtype.Wheel2 EffectSubtype.Wheel3 EffectSubtype.Wheel4 EffectSubtype.Wheel8

---

### Whip {#Whip}
Whip 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Wipe {#Wipe}
Wedge 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.Top EffectSubtype.Right EffectSubtype.Bottom EffectSubtype.Left

---

### Magnify {#Magnify}
Magnify 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.None

---

### Zoom {#Zoom}
Zoom 效果. 类 Entrance 或 Exit. 有效子类型: EffectSubtype.In EffectSubtype.Out EffectSubtype.InCenter - only for Entrance class EffectSubtype.OutBottom - only for Entrance class EffectSubtype.OutSlightly EffectSubtype.InSlightly EffectSubtype.OutCenter - only for Exit class EffectSubtype.InBottom - only for Exit class

---

### OLEObjectShow {#OLEObjectShow}
OLEObjectShow 效果. 类 OLEActionVerbs. 有效子类型: EffectSubtype.None

---

### OLEObjectEdit {#OLEObjectEdit}
OLEObjectEdit 效果. 类 OLEActionVerbs. 有效子类型: EffectSubtype.None

---

### OLEObjectOpen {#OLEObjectOpen}
OLEObjectOpen 效果. 类 OLEActionVerbs. 有效子类型: EffectSubtype.None

---