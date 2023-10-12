---
title: ShapeType
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapetype/
---

## ShapeType class

 Represents preset geometry of geometry shapes.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| [NotDefined](#NotDefined) | -1 | Not defined. |
| [Custom](#Custom) | 0 | Custom shape. This is return-only value. |
| [Line](#Line) | 1 | Line Shape. |
| [LineInverse](#LineInverse) | 2 | Line Inverse Shape. |
| [Triangle](#Triangle) | 3 | Triangle Shape. |
| [RightTriangle](#RightTriangle) | 4 | Right Triangle Shape. |
| [Rectangle](#Rectangle) | 5 | Rectangle Shape. |
| [Diamond](#Diamond) | 6 | Diamond Shape. |
| [Parallelogram](#Parallelogram) | 7 | Parallelogram Shape. |
| [Trapezoid](#Trapezoid) | 8 | Trapezoid Shape. |
| [NonIsoscelesTrapezoid](#NonIsoscelesTrapezoid) | 9 | Non-Isosceles Trapezoid Shape. |
| [Pentagon](#Pentagon) | 10 | Pentagon Shape. |
| [Hexagon](#Hexagon) | 11 | Hexagon Shape. |
| [Heptagon](#Heptagon) | 12 | Heptagon Shape. |
| [Octagon](#Octagon) | 13 | Octagon Shape. |
| [Decagon](#Decagon) | 14 | Decagon Shape. |
| [Dodecagon](#Dodecagon) | 15 | Dodecagon Shape. |
| [FourPointedStar](#FourPointedStar) | 16 | Four Pointed Star Shape. |
| [FivePointedStar](#FivePointedStar) | 17 | Five Pointed Star Shape. |
| [SixPointedStar](#SixPointedStar) | 18 | Six Pointed Star Shape. |
| [SevenPointedStar](#SevenPointedStar) | 19 | Seven Pointed Star Shape. |
| [EightPointedStar](#EightPointedStar) | 20 | Eight Pointed Star Shape. |
| [TenPointedStar](#TenPointedStar) | 21 | Ten Pointed Star Shape. |
| [TwelvePointedStar](#TwelvePointedStar) | 22 | Twelve Pointed Star Shape. |
| [SixteenPointedStar](#SixteenPointedStar) | 23 | Sixteen Pointed Star Shape. |
| [TwentyFourPointedStar](#TwentyFourPointedStar) | 24 | Twenty Four Pointed Star Shape. |
| [ThirtyTwoPointedStar](#ThirtyTwoPointedStar) | 25 | Thirty Two Pointed Star Shape. |
| [RoundCornerRectangle](#RoundCornerRectangle) | 26 | Round Corner Rectangle Shape. |
| [OneRoundCornerRectangle](#OneRoundCornerRectangle) | 27 | One Round Corner Rectangle Shape. |
| [TwoSamesideRoundCornerRectangle](#TwoSamesideRoundCornerRectangle) | 28 | Two Same-side Round Corner Rectangle Shape. |
| [TwoDiagonalRoundCornerRectangle](#TwoDiagonalRoundCornerRectangle) | 29 | Two Diagonal Round Corner Rectangle Shape. |
| [OneSnipOneRoundCornerRectangle](#OneSnipOneRoundCornerRectangle) | 30 | One Snip One Round Corner Rectangle Shape. |
| [OneSnipCornerRectangle](#OneSnipCornerRectangle) | 31 | One Snip Corner Rectangle Shape. |
| [TwoSamesideSnipCornerRectangle](#TwoSamesideSnipCornerRectangle) | 32 | Two Same-side Snip Corner Rectangle Shape. |
| [TwoDiagonalSnipCornerRectangle](#TwoDiagonalSnipCornerRectangle) | 33 | Two Diagonal Snip Corner Rectangle Shape. |
| [Plaque](#Plaque) | 34 | Plaque Shape. |
| [Ellipse](#Ellipse) | 35 | Ellipse Shape. |
| [Teardrop](#Teardrop) | 36 | Teardrop Shape. |
| [HomePlate](#HomePlate) | 37 | Home Plate Shape. |
| [Chevron](#Chevron) | 38 | Chevron Shape. |
| [PieWedge](#PieWedge) | 39 | Pie Wedge Shape. |
| [Pie](#Pie) | 40 | Pie Shape. |
| [BlockArc](#BlockArc) | 41 | Block Arc Shape. |
| [Donut](#Donut) | 42 | Donut Shape. |
| [NoSmoking](#NoSmoking) | 43 | No Smoking Shape. |
| [RightArrow](#RightArrow) | 44 | Right Arrow Shape. |
| [LeftArrow](#LeftArrow) | 45 | Left Arrow Shape. |
| [UpArrow](#UpArrow) | 46 | Up Arrow Shape. |
| [DownArrow](#DownArrow) | 47 | Down Arrow Shape. |
| [StripedRightArrow](#StripedRightArrow) | 48 | Striped Right Arrow Shape. |
| [NotchedRightArrow](#NotchedRightArrow) | 49 | Notched Right Arrow Shape. |
| [BentUpArrow](#BentUpArrow) | 50 | Bent Up Arrow Shape. |
| [LeftRightArrow](#LeftRightArrow) | 51 | Left Right Arrow Shape. |
| [UpDownArrow](#UpDownArrow) | 52 | Up Down Arrow Shape. |
| [LeftUpArrow](#LeftUpArrow) | 53 | Left Up Arrow Shape. |
| [LeftRightUpArrow](#LeftRightUpArrow) | 54 | Left Right Up Arrow Shape. |
| [QuadArrow](#QuadArrow) | 55 | Quad-Arrow Shape. |
| [CalloutLeftArrow](#CalloutLeftArrow) | 56 | Callout Left Arrow Shape. |
| [CalloutRightArrow](#CalloutRightArrow) | 57 | Callout Right Arrow Shape. |
| [CalloutUpArrow](#CalloutUpArrow) | 58 | Callout Up Arrow Shape. |
| [CalloutDownArrow](#CalloutDownArrow) | 59 | Callout Down Arrow Shape. |
| [CalloutLeftRightArrow](#CalloutLeftRightArrow) | 60 | Callout Left Right Arrow Shape. |
| [CalloutUpDownArrow](#CalloutUpDownArrow) | 61 | Callout Up Down Arrow Shape. |
| [CalloutQuadArrow](#CalloutQuadArrow) | 62 | Callout Quad-Arrow Shape. |
| [BentArrow](#BentArrow) | 63 | Bent Arrow Shape. |
| [UTurnArrow](#UTurnArrow) | 64 | U-Turn Arrow Shape. |
| [CircularArrow](#CircularArrow) | 65 | Circular Arrow Shape. |
| [LeftCircularArrow](#LeftCircularArrow) | 66 | Left Circular Arrow Shape. |
| [LeftRightCircularArrow](#LeftRightCircularArrow) | 67 | Left Right Circular Arrow Shape. |
| [CurvedRightArrow](#CurvedRightArrow) | 68 | Curved Right Arrow Shape. |
| [CurvedLeftArrow](#CurvedLeftArrow) | 69 | Curved Left Arrow Shape. |
| [CurvedUpArrow](#CurvedUpArrow) | 70 | Curved Up Arrow Shape. |
| [CurvedDownArrow](#CurvedDownArrow) | 71 | Curved Down Arrow Shape. |
| [SwooshArrow](#SwooshArrow) | 72 | Swoosh Arrow Shape. |
| [Cube](#Cube) | 73 | Cube Shape. |
| [Can](#Can) | 74 | Can Shape. |
| [LightningBolt](#LightningBolt) | 75 | Lightning Bolt Shape. |
| [Heart](#Heart) | 76 | Heart Shape. |
| [Sun](#Sun) | 77 | Sun Shape. |
| [Moon](#Moon) | 78 | Moon Shape. |
| [SmileyFace](#SmileyFace) | 79 | Smiley Face Shape. |
| [IrregularSeal1](#IrregularSeal1) | 80 | Irregular Seal 1 Shape. |
| [IrregularSeal2](#IrregularSeal2) | 81 | Irregular Seal 2 Shape. |
| [FoldedCorner](#FoldedCorner) | 82 | Folded Corner Shape. |
| [Bevel](#Bevel) | 83 | Bevel Shape. |
| [Frame](#Frame) | 84 | Frame Shape. |
| [HalfFrame](#HalfFrame) | 85 | Half Frame Shape. |
| [Corner](#Corner) | 86 | Corner Shape. |
| [DiagonalStripe](#DiagonalStripe) | 87 | Diagonal Stripe Shape. |
| [Chord](#Chord) | 88 | Chord Shape. |
| [CurvedArc](#CurvedArc) | 89 | Curved Arc Shape. |
| [LeftBracket](#LeftBracket) | 90 | Left Bracket Shape. |
| [RightBracket](#RightBracket) | 91 | Right Bracket Shape. |
| [LeftBrace](#LeftBrace) | 92 | Left Brace Shape. |
| [RightBrace](#RightBrace) | 93 | Right Brace Shape. |
| [BracketPair](#BracketPair) | 94 | Bracket Pair Shape. |
| [BracePair](#BracePair) | 95 | Brace Pair Shape. |
| [StraightConnector1](#StraightConnector1) | 96 | Straight Connector 1 Shape. |
| [BentConnector2](#BentConnector2) | 97 | Bent Connector 2 Shape. |
| [BentConnector3](#BentConnector3) | 98 | Bent Connector 3 Shape. |
| [BentConnector4](#BentConnector4) | 99 | Bent Connector 4 Shape. |
| [BentConnector5](#BentConnector5) | 100 | Bent Connector 5 Shape. |
| [CurvedConnector2](#CurvedConnector2) | 101 | Curved Connector 2 Shape. |
| [CurvedConnector3](#CurvedConnector3) | 102 | Curved Connector 3 Shape. |
| [CurvedConnector4](#CurvedConnector4) | 103 | Curved Connector 4 Shape. |
| [CurvedConnector5](#CurvedConnector5) | 104 | Curved Connector 5 Shape. |
| [Callout1](#Callout1) | 105 | Callout 1 Shape. |
| [Callout2](#Callout2) | 106 | Callout 2 Shape. |
| [Callout3](#Callout3) | 107 | Callout 3 Shape. |
| [Callout1WithAccent](#Callout1WithAccent) | 108 | Callout 1 with Accent Shape. |
| [Callout2WithAccent](#Callout2WithAccent) | 109 | Callout 2 with Accent Shape. |
| [Callout3WithAccent](#Callout3WithAccent) | 110 | Callout 3 with Accent Shape. |
| [Callout1WithBorder](#Callout1WithBorder) | 111 | Callout 1 with Border Shape. |
| [Callout2WithBorder](#Callout2WithBorder) | 112 | Callout 2 with Border Shape. |
| [Callout3WithBorder](#Callout3WithBorder) | 113 | Callout 3 with Border Shape. |
| [Callout1WithBorderAndAccent](#Callout1WithBorderAndAccent) | 114 | Callout 1 with Border and Accent Shape. |
| [Callout2WithBorderAndAccent](#Callout2WithBorderAndAccent) | 115 | Callout 2 with Border and Accent Shape. |
| [Callout3WithBorderAndAccent](#Callout3WithBorderAndAccent) | 116 | Callout 3 with Border and Accent Shape. |
| [CalloutWedgeRectangle](#CalloutWedgeRectangle) | 117 | Callout Wedge Rectangle Shape. |
| [CalloutWedgeRoundRectangle](#CalloutWedgeRoundRectangle) | 118 | Callout Wedge Round Rectangle Shape. |
| [CalloutWedgeEllipse](#CalloutWedgeEllipse) | 119 | Callout Wedge Ellipse Shape. |
| [CalloutCloud](#CalloutCloud) | 120 | Callout Cloud Shape. |
| [Cloud](#Cloud) | 121 | Cloud Shape. |
| [Ribbon](#Ribbon) | 122 | Ribbon Shape. |
| [Ribbon2](#Ribbon2) | 123 | Ribbon 2 Shape. |
| [EllipseRibbon](#EllipseRibbon) | 124 | Ellipse Ribbon Shape. |
| [EllipseRibbon2](#EllipseRibbon2) | 125 | Ellipse Ribbon 2 Shape. |
| [LeftRightRibbon](#LeftRightRibbon) | 126 | Left Right Ribbon Shape. |
| [VerticalScroll](#VerticalScroll) | 127 | Vertical Scroll Shape. |
| [HorizontalScroll](#HorizontalScroll) | 128 | Horizontal Scroll Shape. |
| [Wave](#Wave) | 129 | Wave Shape. |
| [DoubleWave](#DoubleWave) | 130 | Double Wave Shape. |
| [Plus](#Plus) | 131 | Plus Shape. |
| [ProcessFlow](#ProcessFlow) | 132 | Process Flow Shape. |
| [DecisionFlow](#DecisionFlow) | 133 | Decision Flow Shape. |
| [InputOutputFlow](#InputOutputFlow) | 134 | Input Output Flow Shape. |
| [PredefinedProcessFlow](#PredefinedProcessFlow) | 135 | Predefined Process Flow Shape. |
| [InternalStorageFlow](#InternalStorageFlow) | 136 | Internal Storage Flow Shape. |
| [DocumentFlow](#DocumentFlow) | 137 | Document Flow Shape. |
| [MultiDocumentFlow](#MultiDocumentFlow) | 138 | Multi-Document Flow Shape. |
| [TerminatorFlow](#TerminatorFlow) | 139 | Terminator Flow Shape. |
| [PreparationFlow](#PreparationFlow) | 140 | Preparation Flow Shape. |
| [ManualInputFlow](#ManualInputFlow) | 141 | Manual Input Flow Shape. |
| [ManualOperationFlow](#ManualOperationFlow) | 142 | Manual Operation Flow Shape. |
| [ConnectorFlow](#ConnectorFlow) | 143 | Connector Flow Shape. |
| [PunchedCardFlow](#PunchedCardFlow) | 144 | Punched Card Flow Shape. |
| [PunchedTapeFlow](#PunchedTapeFlow) | 145 | Punched Tape Flow Shape. |
| [SummingJunctionFlow](#SummingJunctionFlow) | 146 | Summing Junction Flow Shape. |
| [OrFlow](#OrFlow) | 147 | Or Flow Shape. |
| [CollateFlow](#CollateFlow) | 148 | Collate Flow Shape. |
| [SortFlow](#SortFlow) | 149 | Sort Flow Shape. |
| [ExtractFlow](#ExtractFlow) | 150 | Extract Flow Shape. |
| [MergeFlow](#MergeFlow) | 151 | Merge Flow Shape. |
| [OfflineStorageFlow](#OfflineStorageFlow) | 152 | Offline Storage Flow Shape. |
| [OnlineStorageFlow](#OnlineStorageFlow) | 153 | Online Storage Flow Shape. |
| [MagneticTapeFlow](#MagneticTapeFlow) | 154 | Magnetic Tape Flow Shape. |
| [MagneticDiskFlow](#MagneticDiskFlow) | 155 | Magnetic Disk Flow Shape. |
| [MagneticDrumFlow](#MagneticDrumFlow) | 156 | Magnetic Drum Flow Shape. |
| [DisplayFlow](#DisplayFlow) | 157 | Display Flow Shape. |
| [DelayFlow](#DelayFlow) | 158 | Delay Flow Shape. |
| [AlternateProcessFlow](#AlternateProcessFlow) | 159 | Alternate Process Flow Shape. |
| [OffPageConnectorFlow](#OffPageConnectorFlow) | 160 | Off-Page Connector Flow Shape. |
| [BlankButton](#BlankButton) | 161 | Blank Button Shape. |
| [HomeButton](#HomeButton) | 162 | Home Button Shape. |
| [HelpButton](#HelpButton) | 163 | Help Button Shape. |
| [InformationButton](#InformationButton) | 164 | Information Button Shape. |
| [ForwardOrNextButton](#ForwardOrNextButton) | 165 | Forward or Next Button Shape. |
| [BackOrPreviousButton](#BackOrPreviousButton) | 166 | Back or Previous Button Shape. |
| [EndButton](#EndButton) | 167 | End Button Shape. |
| [BeginningButton](#BeginningButton) | 168 | Beginning Button Shape. |
| [ReturnButton](#ReturnButton) | 169 | Return Button Shape. |
| [DocumentButton](#DocumentButton) | 170 | Document Button Shape. |
| [SoundButton](#SoundButton) | 171 | Sound Button Shape. |
| [MovieButton](#MovieButton) | 172 | Movie Button Shape. |
| [Gear6](#Gear6) | 173 | Gear 6 Shape. |
| [Gear9](#Gear9) | 174 | Gear 9 Shape. |
| [Funnel](#Funnel) | 175 | Funnel Shape. |
| [PlusMath](#PlusMath) | 176 | Plus Math Shape. |
| [MinusMath](#MinusMath) | 177 | Minus Math Shape. |
| [MultiplyMath](#MultiplyMath) | 178 | Multiply Math Shape. |
| [DivideMath](#DivideMath) | 179 | Divide Math Shape. |
| [EqualMath](#EqualMath) | 180 | Equal Math Shape. |
| [NotEqualMath](#NotEqualMath) | 181 | Not Equal Math Shape. |
| [CornerTabs](#CornerTabs) | 182 | Corner Tabs Shape. |
| [SquareTabs](#SquareTabs) | 183 | Square Tabs Shape. |
| [PlaqueTabs](#PlaqueTabs) | 184 | Plaque Tabs Shape. |
| [ChartX](#ChartX) | 185 | Chart X Shape. |
| [ChartStar](#ChartStar) | 186 | Chart Star Shape. |
| [ChartPlus](#ChartPlus) | 187 | Chart Plus Shape. |


---


### NotDefined {#NotDefined}
| NotDefined| -1 | Not defined. |


---

### Custom {#Custom}
| Custom| 0 | Custom shape. This is return-only value. |


---

### Line {#Line}
| Line| 1 | Line Shape. |


---

### LineInverse {#LineInverse}
| LineInverse| 2 | Line Inverse Shape. |


---

### Triangle {#Triangle}
| Triangle| 3 | Triangle Shape. |


---

### RightTriangle {#RightTriangle}
| RightTriangle| 4 | Right Triangle Shape. |


---

### Rectangle {#Rectangle}
| Rectangle| 5 | Rectangle Shape. |


---

### Diamond {#Diamond}
| Diamond| 6 | Diamond Shape. |


---

### Parallelogram {#Parallelogram}
| Parallelogram| 7 | Parallelogram Shape. |


---

### Trapezoid {#Trapezoid}
| Trapezoid| 8 | Trapezoid Shape. |


---

### NonIsoscelesTrapezoid {#NonIsoscelesTrapezoid}
| NonIsoscelesTrapezoid| 9 | Non-Isosceles Trapezoid Shape. |


---

### Pentagon {#Pentagon}
| Pentagon| 10 | Pentagon Shape. |


---

### Hexagon {#Hexagon}
| Hexagon| 11 | Hexagon Shape. |


---

### Heptagon {#Heptagon}
| Heptagon| 12 | Heptagon Shape. |


---

### Octagon {#Octagon}
| Octagon| 13 | Octagon Shape. |


---

### Decagon {#Decagon}
| Decagon| 14 | Decagon Shape. |


---

### Dodecagon {#Dodecagon}
| Dodecagon| 15 | Dodecagon Shape. |


---

### FourPointedStar {#FourPointedStar}
| FourPointedStar| 16 | Four Pointed Star Shape. |


---

### FivePointedStar {#FivePointedStar}
| FivePointedStar| 17 | Five Pointed Star Shape. |


---

### SixPointedStar {#SixPointedStar}
| SixPointedStar| 18 | Six Pointed Star Shape. |


---

### SevenPointedStar {#SevenPointedStar}
| SevenPointedStar| 19 | Seven Pointed Star Shape. |


---

### EightPointedStar {#EightPointedStar}
| EightPointedStar| 20 | Eight Pointed Star Shape. |


---

### TenPointedStar {#TenPointedStar}
| TenPointedStar| 21 | Ten Pointed Star Shape. |


---

### TwelvePointedStar {#TwelvePointedStar}
| TwelvePointedStar| 22 | Twelve Pointed Star Shape. |


---

### SixteenPointedStar {#SixteenPointedStar}
| SixteenPointedStar| 23 | Sixteen Pointed Star Shape. |


---

### TwentyFourPointedStar {#TwentyFourPointedStar}
| TwentyFourPointedStar| 24 | Twenty Four Pointed Star Shape. |


---

### ThirtyTwoPointedStar {#ThirtyTwoPointedStar}
| ThirtyTwoPointedStar| 25 | Thirty Two Pointed Star Shape. |


---

### RoundCornerRectangle {#RoundCornerRectangle}
| RoundCornerRectangle| 26 | Round Corner Rectangle Shape. |


---

### OneRoundCornerRectangle {#OneRoundCornerRectangle}
| OneRoundCornerRectangle| 27 | One Round Corner Rectangle Shape. |


---

### TwoSamesideRoundCornerRectangle {#TwoSamesideRoundCornerRectangle}
| TwoSamesideRoundCornerRectangle| 28 | Two Same-side Round Corner Rectangle Shape. |


---

### TwoDiagonalRoundCornerRectangle {#TwoDiagonalRoundCornerRectangle}
| TwoDiagonalRoundCornerRectangle| 29 | Two Diagonal Round Corner Rectangle Shape. |


---

### OneSnipOneRoundCornerRectangle {#OneSnipOneRoundCornerRectangle}
| OneSnipOneRoundCornerRectangle| 30 | One Snip One Round Corner Rectangle Shape. |


---

### OneSnipCornerRectangle {#OneSnipCornerRectangle}
| OneSnipCornerRectangle| 31 | One Snip Corner Rectangle Shape. |


---

### TwoSamesideSnipCornerRectangle {#TwoSamesideSnipCornerRectangle}
| TwoSamesideSnipCornerRectangle| 32 | Two Same-side Snip Corner Rectangle Shape. |


---

### TwoDiagonalSnipCornerRectangle {#TwoDiagonalSnipCornerRectangle}
| TwoDiagonalSnipCornerRectangle| 33 | Two Diagonal Snip Corner Rectangle Shape. |


---

### Plaque {#Plaque}
| Plaque| 34 | Plaque Shape. |


---

### Ellipse {#Ellipse}
| Ellipse| 35 | Ellipse Shape. |


---

### Teardrop {#Teardrop}
| Teardrop| 36 | Teardrop Shape. |


---

### HomePlate {#HomePlate}
| HomePlate| 37 | Home Plate Shape. |


---

### Chevron {#Chevron}
| Chevron| 38 | Chevron Shape. |


---

### PieWedge {#PieWedge}
| PieWedge| 39 | Pie Wedge Shape. |


---

### Pie {#Pie}
| Pie| 40 | Pie Shape. |


---

### BlockArc {#BlockArc}
| BlockArc| 41 | Block Arc Shape. |


---

### Donut {#Donut}
| Donut| 42 | Donut Shape. |


---

### NoSmoking {#NoSmoking}
| NoSmoking| 43 | No Smoking Shape. |


---

### RightArrow {#RightArrow}
| RightArrow| 44 | Right Arrow Shape. |


---

### LeftArrow {#LeftArrow}
| LeftArrow| 45 | Left Arrow Shape. |


---

### UpArrow {#UpArrow}
| UpArrow| 46 | Up Arrow Shape. |


---

### DownArrow {#DownArrow}
| DownArrow| 47 | Down Arrow Shape. |


---

### StripedRightArrow {#StripedRightArrow}
| StripedRightArrow| 48 | Striped Right Arrow Shape. |


---

### NotchedRightArrow {#NotchedRightArrow}
| NotchedRightArrow| 49 | Notched Right Arrow Shape. |


---

### BentUpArrow {#BentUpArrow}
| BentUpArrow| 50 | Bent Up Arrow Shape. |


---

### LeftRightArrow {#LeftRightArrow}
| LeftRightArrow| 51 | Left Right Arrow Shape. |


---

### UpDownArrow {#UpDownArrow}
| UpDownArrow| 52 | Up Down Arrow Shape. |


---

### LeftUpArrow {#LeftUpArrow}
| LeftUpArrow| 53 | Left Up Arrow Shape. |


---

### LeftRightUpArrow {#LeftRightUpArrow}
| LeftRightUpArrow| 54 | Left Right Up Arrow Shape. |


---

### QuadArrow {#QuadArrow}
| QuadArrow| 55 | Quad-Arrow Shape. |


---

### CalloutLeftArrow {#CalloutLeftArrow}
| CalloutLeftArrow| 56 | Callout Left Arrow Shape. |


---

### CalloutRightArrow {#CalloutRightArrow}
| CalloutRightArrow| 57 | Callout Right Arrow Shape. |


---

### CalloutUpArrow {#CalloutUpArrow}
| CalloutUpArrow| 58 | Callout Up Arrow Shape. |


---

### CalloutDownArrow {#CalloutDownArrow}
| CalloutDownArrow| 59 | Callout Down Arrow Shape. |


---

### CalloutLeftRightArrow {#CalloutLeftRightArrow}
| CalloutLeftRightArrow| 60 | Callout Left Right Arrow Shape. |


---

### CalloutUpDownArrow {#CalloutUpDownArrow}
| CalloutUpDownArrow| 61 | Callout Up Down Arrow Shape. |


---

### CalloutQuadArrow {#CalloutQuadArrow}
| CalloutQuadArrow| 62 | Callout Quad-Arrow Shape. |


---

### BentArrow {#BentArrow}
| BentArrow| 63 | Bent Arrow Shape. |


---

### UTurnArrow {#UTurnArrow}
| UTurnArrow| 64 | U-Turn Arrow Shape. |


---

### CircularArrow {#CircularArrow}
| CircularArrow| 65 | Circular Arrow Shape. |


---

### LeftCircularArrow {#LeftCircularArrow}
| LeftCircularArrow| 66 | Left Circular Arrow Shape. |


---

### LeftRightCircularArrow {#LeftRightCircularArrow}
| LeftRightCircularArrow| 67 | Left Right Circular Arrow Shape. |


---

### CurvedRightArrow {#CurvedRightArrow}
| CurvedRightArrow| 68 | Curved Right Arrow Shape. |


---

### CurvedLeftArrow {#CurvedLeftArrow}
| CurvedLeftArrow| 69 | Curved Left Arrow Shape. |


---

### CurvedUpArrow {#CurvedUpArrow}
| CurvedUpArrow| 70 | Curved Up Arrow Shape. |


---

### CurvedDownArrow {#CurvedDownArrow}
| CurvedDownArrow| 71 | Curved Down Arrow Shape. |


---

### SwooshArrow {#SwooshArrow}
| SwooshArrow| 72 | Swoosh Arrow Shape. |


---

### Cube {#Cube}
| Cube| 73 | Cube Shape. |


---

### Can {#Can}
| Can| 74 | Can Shape. |


---

### LightningBolt {#LightningBolt}
| LightningBolt| 75 | Lightning Bolt Shape. |


---

### Heart {#Heart}
| Heart| 76 | Heart Shape. |


---

### Sun {#Sun}
| Sun| 77 | Sun Shape. |


---

### Moon {#Moon}
| Moon| 78 | Moon Shape. |


---

### SmileyFace {#SmileyFace}
| SmileyFace| 79 | Smiley Face Shape. |


---

### IrregularSeal1 {#IrregularSeal1}
| IrregularSeal1| 80 | Irregular Seal 1 Shape. |


---

### IrregularSeal2 {#IrregularSeal2}
| IrregularSeal2| 81 | Irregular Seal 2 Shape. |


---

### FoldedCorner {#FoldedCorner}
| FoldedCorner| 82 | Folded Corner Shape. |


---

### Bevel {#Bevel}
| Bevel| 83 | Bevel Shape. |


---

### Frame {#Frame}
| Frame| 84 | Frame Shape. |


---

### HalfFrame {#HalfFrame}
| HalfFrame| 85 | Half Frame Shape. |


---

### Corner {#Corner}
| Corner| 86 | Corner Shape. |


---

### DiagonalStripe {#DiagonalStripe}
| DiagonalStripe| 87 | Diagonal Stripe Shape. |


---

### Chord {#Chord}
| Chord| 88 | Chord Shape. |


---

### CurvedArc {#CurvedArc}
| CurvedArc| 89 | Curved Arc Shape. |


---

### LeftBracket {#LeftBracket}
| LeftBracket| 90 | Left Bracket Shape. |


---

### RightBracket {#RightBracket}
| RightBracket| 91 | Right Bracket Shape. |


---

### LeftBrace {#LeftBrace}
| LeftBrace| 92 | Left Brace Shape. |


---

### RightBrace {#RightBrace}
| RightBrace| 93 | Right Brace Shape. |


---

### BracketPair {#BracketPair}
| BracketPair| 94 | Bracket Pair Shape. |


---

### BracePair {#BracePair}
| BracePair| 95 | Brace Pair Shape. |


---

### StraightConnector1 {#StraightConnector1}
| StraightConnector1| 96 | Straight Connector 1 Shape. |


---

### BentConnector2 {#BentConnector2}
| BentConnector2| 97 | Bent Connector 2 Shape. |


---

### BentConnector3 {#BentConnector3}
| BentConnector3| 98 | Bent Connector 3 Shape. |


---

### BentConnector4 {#BentConnector4}
| BentConnector4| 99 | Bent Connector 4 Shape. |


---

### BentConnector5 {#BentConnector5}
| BentConnector5| 100 | Bent Connector 5 Shape. |


---

### CurvedConnector2 {#CurvedConnector2}
| CurvedConnector2| 101 | Curved Connector 2 Shape. |


---

### CurvedConnector3 {#CurvedConnector3}
| CurvedConnector3| 102 | Curved Connector 3 Shape. |


---

### CurvedConnector4 {#CurvedConnector4}
| CurvedConnector4| 103 | Curved Connector 4 Shape. |


---

### CurvedConnector5 {#CurvedConnector5}
| CurvedConnector5| 104 | Curved Connector 5 Shape. |


---

### Callout1 {#Callout1}
| Callout1| 105 | Callout 1 Shape. |


---

### Callout2 {#Callout2}
| Callout2| 106 | Callout 2 Shape. |


---

### Callout3 {#Callout3}
| Callout3| 107 | Callout 3 Shape. |


---

### Callout1WithAccent {#Callout1WithAccent}
| Callout1WithAccent| 108 | Callout 1 with Accent Shape. |


---

### Callout2WithAccent {#Callout2WithAccent}
| Callout2WithAccent| 109 | Callout 2 with Accent Shape. |


---

### Callout3WithAccent {#Callout3WithAccent}
| Callout3WithAccent| 110 | Callout 3 with Accent Shape. |


---

### Callout1WithBorder {#Callout1WithBorder}
| Callout1WithBorder| 111 | Callout 1 with Border Shape. |


---

### Callout2WithBorder {#Callout2WithBorder}
| Callout2WithBorder| 112 | Callout 2 with Border Shape. |


---

### Callout3WithBorder {#Callout3WithBorder}
| Callout3WithBorder| 113 | Callout 3 with Border Shape. |


---

### Callout1WithBorderAndAccent {#Callout1WithBorderAndAccent}
| Callout1WithBorderAndAccent| 114 | Callout 1 with Border and Accent Shape. |


---

### Callout2WithBorderAndAccent {#Callout2WithBorderAndAccent}
| Callout2WithBorderAndAccent| 115 | Callout 2 with Border and Accent Shape. |


---

### Callout3WithBorderAndAccent {#Callout3WithBorderAndAccent}
| Callout3WithBorderAndAccent| 116 | Callout 3 with Border and Accent Shape. |


---

### CalloutWedgeRectangle {#CalloutWedgeRectangle}
| CalloutWedgeRectangle| 117 | Callout Wedge Rectangle Shape. |


---

### CalloutWedgeRoundRectangle {#CalloutWedgeRoundRectangle}
| CalloutWedgeRoundRectangle| 118 | Callout Wedge Round Rectangle Shape. |


---

### CalloutWedgeEllipse {#CalloutWedgeEllipse}
| CalloutWedgeEllipse| 119 | Callout Wedge Ellipse Shape. |


---

### CalloutCloud {#CalloutCloud}
| CalloutCloud| 120 | Callout Cloud Shape. |


---

### Cloud {#Cloud}
| Cloud| 121 | Cloud Shape. |


---

### Ribbon {#Ribbon}
| Ribbon| 122 | Ribbon Shape. |


---

### Ribbon2 {#Ribbon2}
| Ribbon2| 123 | Ribbon 2 Shape. |


---

### EllipseRibbon {#EllipseRibbon}
| EllipseRibbon| 124 | Ellipse Ribbon Shape. |


---

### EllipseRibbon2 {#EllipseRibbon2}
| EllipseRibbon2| 125 | Ellipse Ribbon 2 Shape. |


---

### LeftRightRibbon {#LeftRightRibbon}
| LeftRightRibbon| 126 | Left Right Ribbon Shape. |


---

### VerticalScroll {#VerticalScroll}
| VerticalScroll| 127 | Vertical Scroll Shape. |


---

### HorizontalScroll {#HorizontalScroll}
| HorizontalScroll| 128 | Horizontal Scroll Shape. |


---

### Wave {#Wave}
| Wave| 129 | Wave Shape. |


---

### DoubleWave {#DoubleWave}
| DoubleWave| 130 | Double Wave Shape. |


---

### Plus {#Plus}
| Plus| 131 | Plus Shape. |


---

### ProcessFlow {#ProcessFlow}
| ProcessFlow| 132 | Process Flow Shape. |


---

### DecisionFlow {#DecisionFlow}
| DecisionFlow| 133 | Decision Flow Shape. |


---

### InputOutputFlow {#InputOutputFlow}
| InputOutputFlow| 134 | Input Output Flow Shape. |


---

### PredefinedProcessFlow {#PredefinedProcessFlow}
| PredefinedProcessFlow| 135 | Predefined Process Flow Shape. |


---

### InternalStorageFlow {#InternalStorageFlow}
| InternalStorageFlow| 136 | Internal Storage Flow Shape. |


---

### DocumentFlow {#DocumentFlow}
| DocumentFlow| 137 | Document Flow Shape. |


---

### MultiDocumentFlow {#MultiDocumentFlow}
| MultiDocumentFlow| 138 | Multi-Document Flow Shape. |


---

### TerminatorFlow {#TerminatorFlow}
| TerminatorFlow| 139 | Terminator Flow Shape. |


---

### PreparationFlow {#PreparationFlow}
| PreparationFlow| 140 | Preparation Flow Shape. |


---

### ManualInputFlow {#ManualInputFlow}
| ManualInputFlow| 141 | Manual Input Flow Shape. |


---

### ManualOperationFlow {#ManualOperationFlow}
| ManualOperationFlow| 142 | Manual Operation Flow Shape. |


---

### ConnectorFlow {#ConnectorFlow}
| ConnectorFlow| 143 | Connector Flow Shape. |


---

### PunchedCardFlow {#PunchedCardFlow}
| PunchedCardFlow| 144 | Punched Card Flow Shape. |


---

### PunchedTapeFlow {#PunchedTapeFlow}
| PunchedTapeFlow| 145 | Punched Tape Flow Shape. |


---

### SummingJunctionFlow {#SummingJunctionFlow}
| SummingJunctionFlow| 146 | Summing Junction Flow Shape. |


---

### OrFlow {#OrFlow}
| OrFlow| 147 | Or Flow Shape. |


---

### CollateFlow {#CollateFlow}
| CollateFlow| 148 | Collate Flow Shape. |


---

### SortFlow {#SortFlow}
| SortFlow| 149 | Sort Flow Shape. |


---

### ExtractFlow {#ExtractFlow}
| ExtractFlow| 150 | Extract Flow Shape. |


---

### MergeFlow {#MergeFlow}
| MergeFlow| 151 | Merge Flow Shape. |


---

### OfflineStorageFlow {#OfflineStorageFlow}
| OfflineStorageFlow| 152 | Offline Storage Flow Shape. |


---

### OnlineStorageFlow {#OnlineStorageFlow}
| OnlineStorageFlow| 153 | Online Storage Flow Shape. |


---

### MagneticTapeFlow {#MagneticTapeFlow}
| MagneticTapeFlow| 154 | Magnetic Tape Flow Shape. |


---

### MagneticDiskFlow {#MagneticDiskFlow}
| MagneticDiskFlow| 155 | Magnetic Disk Flow Shape. |


---

### MagneticDrumFlow {#MagneticDrumFlow}
| MagneticDrumFlow| 156 | Magnetic Drum Flow Shape. |


---

### DisplayFlow {#DisplayFlow}
| DisplayFlow| 157 | Display Flow Shape. |


---

### DelayFlow {#DelayFlow}
| DelayFlow| 158 | Delay Flow Shape. |


---

### AlternateProcessFlow {#AlternateProcessFlow}
| AlternateProcessFlow| 159 | Alternate Process Flow Shape. |


---

### OffPageConnectorFlow {#OffPageConnectorFlow}
| OffPageConnectorFlow| 160 | Off-Page Connector Flow Shape. |


---

### BlankButton {#BlankButton}
| BlankButton| 161 | Blank Button Shape. |


---

### HomeButton {#HomeButton}
| HomeButton| 162 | Home Button Shape. |


---

### HelpButton {#HelpButton}
| HelpButton| 163 | Help Button Shape. |


---

### InformationButton {#InformationButton}
| InformationButton| 164 | Information Button Shape. |


---

### ForwardOrNextButton {#ForwardOrNextButton}
| ForwardOrNextButton| 165 | Forward or Next Button Shape. |


---

### BackOrPreviousButton {#BackOrPreviousButton}
| BackOrPreviousButton| 166 | Back or Previous Button Shape. |


---

### EndButton {#EndButton}
| EndButton| 167 | End Button Shape. |


---

### BeginningButton {#BeginningButton}
| BeginningButton| 168 | Beginning Button Shape. |


---

### ReturnButton {#ReturnButton}
| ReturnButton| 169 | Return Button Shape. |


---

### DocumentButton {#DocumentButton}
| DocumentButton| 170 | Document Button Shape. |


---

### SoundButton {#SoundButton}
| SoundButton| 171 | Sound Button Shape. |


---

### MovieButton {#MovieButton}
| MovieButton| 172 | Movie Button Shape. |


---

### Gear6 {#Gear6}
| Gear6| 173 | Gear 6 Shape. |


---

### Gear9 {#Gear9}
| Gear9| 174 | Gear 9 Shape. |


---

### Funnel {#Funnel}
| Funnel| 175 | Funnel Shape. |


---

### PlusMath {#PlusMath}
| PlusMath| 176 | Plus Math Shape. |


---

### MinusMath {#MinusMath}
| MinusMath| 177 | Minus Math Shape. |


---

### MultiplyMath {#MultiplyMath}
| MultiplyMath| 178 | Multiply Math Shape. |


---

### DivideMath {#DivideMath}
| DivideMath| 179 | Divide Math Shape. |


---

### EqualMath {#EqualMath}
| EqualMath| 180 | Equal Math Shape. |


---

### NotEqualMath {#NotEqualMath}
| NotEqualMath| 181 | Not Equal Math Shape. |


---

### CornerTabs {#CornerTabs}
| CornerTabs| 182 | Corner Tabs Shape. |


---

### SquareTabs {#SquareTabs}
| SquareTabs| 183 | Square Tabs Shape. |


---

### PlaqueTabs {#PlaqueTabs}
| PlaqueTabs| 184 | Plaque Tabs Shape. |


---

### ChartX {#ChartX}
| ChartX| 185 | Chart X Shape. |


---

### ChartStar {#ChartStar}
| ChartStar| 186 | Chart Star Shape. |


---

### ChartPlus {#ChartPlus}
| ChartPlus| 187 | Chart Plus Shape. |


---


