---
title: ParagraphFormat
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraphformat/
---

## ParagraphFormat class

 This class contains the paragraph formatting properties. Unlike  IParagraphFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  ParagraphFormat#getEffective method 
 which returns a  IParagraphFormatEffectiveData instance.
### ParagraphFormat {#ParagraphFormat}

| Name | Description |
| --- | --- |
| ParagraphFormat() | Initializes a new instance of ParagraphFormat class. |

 **Result:**
ParagraphFormat


---


### getAlignment {#getAlignment}

| Name | Description |
| --- | --- |
| getAlignment () | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |

 **Result:**
int


---


### getBullet {#getBullet}

| Name | Description |
| --- | --- |
| getBullet () | Returns bullet format of the paragraph. Read-only IBulletFormat. |

 **Result:**
[BulletFormat](../bulletformat)


---


### getDefaultPortionFormat {#getDefaultPortionFormat}

| Name | Description |
| --- | --- |
| getDefaultPortionFormat () | Returns default portion format of a paragraph. No inheritance applied. Read-only IPortionFormat. |

 **Result:**
[PortionFormat](../portionformat)


---


### getDefaultTabSize {#getDefaultTabSize}

| Name | Description |
| --- | --- |
| getDefaultTabSize () | Returns or sets default tabulation size with no inheritance. Read/write float. |

 **Result:**
float


---


### getDepth {#getDepth}

| Name | Description |
| --- | --- |
| getDepth () | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |

 **Result:**
short


---


### getEastAsianLineBreak {#getEastAsianLineBreak}

| Name | Description |
| --- | --- |
| getEastAsianLineBreak () | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Gets effective paragraph formatting data with the inheritance applied. |

 **Result:**
ParagraphFormatEffectiveData


---


### getFontAlignment {#getFontAlignment}

| Name | Description |
| --- | --- |
| getFontAlignment () | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |

 **Result:**
int


---


### getHangingPunctuation {#getHangingPunctuation}

| Name | Description |
| --- | --- |
| getHangingPunctuation () | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


---


### getIndent {#getIndent}

| Name | Description |
| --- | --- |
| getIndent () | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |

 **Result:**
float


---


### getLatinLineBreak {#getLatinLineBreak}

| Name | Description |
| --- | --- |
| getLatinLineBreak () | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


---


### getMarginLeft {#getMarginLeft}

| Name | Description |
| --- | --- |
| getMarginLeft () | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |

 **Result:**
float


---


### getMarginRight {#getMarginRight}

| Name | Description |
| --- | --- |
| getMarginRight () | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |

 **Result:**
float


---


### getParent_IPresentationComponent {#getParent_IPresentationComponent}

| Name | Description |
| --- | --- |
| getParent_IPresentationComponent () |  |

 **Result:**
[ColorFormat](../colorformat), [Background](../background), [Blur](../blur), [MasterTheme](../mastertheme), [TextFrameFormat](../textframeformat), [FillFormat](../fillformat), [GroupShape](../groupshape), [LayoutSlide](../layoutslide), [Legend](../legend), [Axis](../axis), [GraphicalObject](../graphicalobject), [TextStyle](../textstyle), [TextFrame](../textframe), [ImageTransformOperation](../imagetransformoperation), [Luminance](../luminance), [ParagraphFormat](../paragraphformat), [SketchFormat](../sketchformat), [Duotone](../duotone), [LineFormat](../lineformat), [BulletFormat](../bulletformat), [AutoShape](../autoshape), [BiLevel](../bilevel), [AudioFrame](../audioframe), [Backdrop3DScene](../backdrop3dscene), [Picture](../picture), [Hyperlink](../hyperlink), [SummaryZoomFrame](../summaryzoomframe), [MasterNotesSlide](../masternotesslide), [ZoomObject](../zoomobject), [AlphaBiLevel](../alphabilevel), [AlphaInverse](../alphainverse), [Tab](../tab), [AlphaReplace](../alphareplace), [PatternFormat](../patternformat), [SectionZoomFrame](../sectionzoomframe), [FormatScheme](../formatscheme), [MathPortion](../mathportion), [Paragraph](../paragraph), [BaseSlide](../baseslide), [ErrorBarsFormat](../errorbarsformat), [DataLabel](../datalabel), [FillOverlay](../filloverlay), [OleObjectFrame](../oleobjectframe), [Column](../column), [Format](../format), [Control](../control), [ColorChange](../colorchange), [OverrideTheme](../overridetheme), [ChartSeriesGroup](../chartseriesgroup), [LegendEntryProperties](../legendentryproperties), [BasePortionFormat](../baseportionformat), [AlphaCeiling](../alphaceiling), [ShapeBevel](../shapebevel), [LegacyDiagram](../legacydiagram), [ColorReplace](../colorreplace), [Tint](../tint), [Presentation](../presentation), [ZoomFrame](../zoomframe), [Field](../field), [ParagraphCollection](../paragraphcollection), [PVIObject](../pviobject), [ChartPortionFormat](../chartportionformat), [Chart](../chart), [Portion](../portion), [DataLabelCollection](../datalabelcollection), [Camera](../camera), [Connector](../connector), [CellCollection](../cellcollection), [VideoFrame](../videoframe), [MasterSlide](../masterslide), [GeometryShape](../geometryshape), [AlphaModulate](../alphamodulate), [NotesSlide](../notesslide), [SmartArt](../smartart), [Cell](../cell), [ImageTransformOperationCollection](../imagetransformoperationcollection), [Trendline](../trendline), [Ink](../ink), [ChartPlotArea](../chartplotarea), [EffectFormat](../effectformat), [AlphaModulateFixed](../alphamodulatefixed), [Shape](../shape), [ThreeDFormat](../threedformat), [Row](../row), [HSL](../hsl), [SummaryZoomSection](../summaryzoomsection), [GradientStopCollection](../gradientstopcollection), [LineFillFormat](../linefillformat), [GradientStop](../gradientstop), [GradientFormat](../gradientformat), [SmartArtShape](../smartartshape), [GrayScale](../grayscale), [Slide](../slide), [LightRig](../lightrig), [CellFormat](../cellformat), [Table](../table), [Theme](../theme), [ChartSeries](../chartseries), [ChartTitle](../charttitle), [DataTable](../datatable), [PictureFillFormat](../picturefillformat), [PictureFrame](../pictureframe), [ColorScheme](../colorscheme), [DataLabelFormat](../datalabelformat), [AlphaFloor](../alphafloor), [MasterHandoutSlide](../masterhandoutslide), [PortionFormat](../portionformat)


---


### getParent_ISlideComponent {#getParent_ISlideComponent}

| Name | Description |
| --- | --- |
| getParent_ISlideComponent () |  |

 **Result:**
[ColorFormat](../colorformat), [Background](../background), [Blur](../blur), [TextFrameFormat](../textframeformat), [FillFormat](../fillformat), [GroupShape](../groupshape), [LayoutSlide](../layoutslide), [Legend](../legend), [Axis](../axis), [GraphicalObject](../graphicalobject), [TextStyle](../textstyle), [TextFrame](../textframe), [ImageTransformOperation](../imagetransformoperation), [Luminance](../luminance), [ParagraphFormat](../paragraphformat), [SketchFormat](../sketchformat), [Duotone](../duotone), [LineFormat](../lineformat), [BulletFormat](../bulletformat), [AutoShape](../autoshape), [BiLevel](../bilevel), [AudioFrame](../audioframe), [Backdrop3DScene](../backdrop3dscene), [Picture](../picture), [Hyperlink](../hyperlink), [SummaryZoomFrame](../summaryzoomframe), [MasterNotesSlide](../masternotesslide), [ZoomObject](../zoomobject), [AlphaBiLevel](../alphabilevel), [AlphaInverse](../alphainverse), [Tab](../tab), [AlphaReplace](../alphareplace), [PatternFormat](../patternformat), [SectionZoomFrame](../sectionzoomframe), [FormatScheme](../formatscheme), [MathPortion](../mathportion), [Paragraph](../paragraph), [BaseSlide](../baseslide), [ErrorBarsFormat](../errorbarsformat), [DataLabel](../datalabel), [FillOverlay](../filloverlay), [OleObjectFrame](../oleobjectframe), [Column](../column), [Format](../format), [Control](../control), [ColorChange](../colorchange), [ChartSeriesGroup](../chartseriesgroup), [LegendEntryProperties](../legendentryproperties), [BasePortionFormat](../baseportionformat), [AlphaCeiling](../alphaceiling), [ShapeBevel](../shapebevel), [LegacyDiagram](../legacydiagram), [ColorReplace](../colorreplace), [Tint](../tint), [ZoomFrame](../zoomframe), [Field](../field), [ParagraphCollection](../paragraphcollection), [PVIObject](../pviobject), [ChartPortionFormat](../chartportionformat), [Chart](../chart), [Portion](../portion), [DataLabelCollection](../datalabelcollection), [Camera](../camera), [Connector](../connector), [CellCollection](../cellcollection), [VideoFrame](../videoframe), [MasterSlide](../masterslide), [GeometryShape](../geometryshape), [AlphaModulate](../alphamodulate), [NotesSlide](../notesslide), [SmartArt](../smartart), [Cell](../cell), [ImageTransformOperationCollection](../imagetransformoperationcollection), [Trendline](../trendline), [Ink](../ink), [ChartPlotArea](../chartplotarea), [EffectFormat](../effectformat), [AlphaModulateFixed](../alphamodulatefixed), [Shape](../shape), [ThreeDFormat](../threedformat), [Row](../row), [HSL](../hsl), [SummaryZoomSection](../summaryzoomsection), [GradientStopCollection](../gradientstopcollection), [LineFillFormat](../linefillformat), [GradientStop](../gradientstop), [GradientFormat](../gradientformat), [SmartArtShape](../smartartshape), [GrayScale](../grayscale), [Slide](../slide), [LightRig](../lightrig), [CellFormat](../cellformat), [Table](../table), [ChartSeries](../chartseries), [ChartTitle](../charttitle), [DataTable](../datatable), [PictureFillFormat](../picturefillformat), [PictureFrame](../pictureframe), [ColorScheme](../colorscheme), [DataLabelFormat](../datalabelformat), [AlphaFloor](../alphafloor), [MasterHandoutSlide](../masterhandoutslide), [PortionFormat](../portionformat)


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate () |  |

 **Result:**
DisplayUnitLabel, [ChartThemeManager](../chartthememanager), [RotationEffect](../rotationeffect), [ChartTitle](../charttitle), [MathBar](../mathbar), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ChartDataWorksheet](../chartdataworksheet), [SoftEdge](../softedge), [Audio](../audio), [ChartWall](../chartwall), [BaseOverrideThemeManager](../baseoverridethememanager), [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager), ThemeableLineFormat, [UpDownBarsManager](../updownbarsmanager), [MathMatrix](../mathmatrix), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement), [Format](../format), [GradientFormat](../gradientformat), [ThreeDFormat](../threedformat), [Slide](../slide), [TabCollection](../tabcollection), [ColorScheme](../colorscheme), [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [SlideHeaderFooterManager](../slideheaderfootermanager), [CommentAuthor](../commentauthor), [CellFormat](../cellformat), [SlideShowTransition](../slideshowtransition), [CustomXmlPartCollection](../customxmlpartcollection), [SlideCollection](../slidecollection), [ViewProperties](../viewproperties), [Shape](../shape), [ExtraColorScheme](../extracolorscheme), [Luminance](../luminance), [MasterThemeManager](../masterthememanager), [DataLabel](../datalabel), [GradientStop](../gradientstop), [CellCollection](../cellcollection), [MathematicalText](../mathematicaltext), [Row](../row), MasterNotesSlideManager, [MathNaryOperator](../mathnaryoperator), [BaseThemeManager](../basethememanager), ThemeableFillFormat, [RowCollection](../rowcollection), [GeometryShape](../geometryshape), TableStyle, [LightRig](../lightrig), [ChartPlotArea](../chartplotarea), [BulletFormat](../bulletformat), [MathSuperscriptElement](../mathsuperscriptelement), [VideoCollection](../videocollection), [Table](../table), [ChartDataPointLevel](../chartdatapointlevel), PresetTextShape, [MasterTheme](../mastertheme), [SectionSlideCollection](../sectionslidecollection), [OleObjectFrame](../oleobjectframe), [ChartData](../chartdata), [ChartDataPointCollection](../chartdatapointcollection), [ChartDataWorkbook](../chartdataworkbook), [NotesSlideHeaderFooterManager](../notesslideheaderfootermanager), [PresetShadow](../presetshadow), AggregatedDataPoint, [SketchFormat](../sketchformat), [MathParagraph](../mathparagraph), [SmartArt](../smartart), [AudioCollection](../audiocollection), [AxisFormat](../axisformat), [CommentCollection](../commentcollection), [ParagraphFormat](../paragraphformat), [ChartDataWorksheetCollection](../chartdataworksheetcollection), FormatOverrides, [TextStyle](../textstyle), [FillFormatCollection](../fillformatcollection), [NotesSlideManager](../notesslidemanager), [ColumnFormat](../columnformat), [Section](../section), [MathBlock](../mathblock), [TableFormat](../tableformat), [StringChartValue](../stringchartvalue), [Reflection](../reflection), [Ink](../ink), [Trendline](../trendline), [LayoutSlideCollection](../layoutslidecollection), [LineFormat](../lineformat), [BasePortionFormat](../baseportionformat), [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager), [MasterHandoutSlide](../masterhandoutslide), [DataLabelFormat](../datalabelformat), [Timing](../timing), [MathAccent](../mathaccent), [LegacyDiagram](../legacydiagram), FormatOverride, [ChartSeriesGroup](../chartseriesgroup), [Blur](../blur), [MathSubscriptElement](../mathsubscriptelement), [NotesSlideThemeManager](../notesslidethememanager), [Axis](../axis), [AlphaBiLevel](../alphabilevel), [Paragraph](../paragraph), [MathGroupingCharacter](../mathgroupingcharacter), [MathLimit](../mathlimit), TableBackgroundStyle, [SetEffect](../seteffect), [StringOrDoubleChartValue](../stringordoublechartvalue), [Chart](../chart), [PictureFillFormat](../picturefillformat), [HyperlinkQueries](../hyperlinkqueries), [ZoomFrame](../zoomframe), [BaseScript](../basescript), [MasterNotesSlideHeaderFooterManager](../masternotesslideheaderfootermanager), [Rotation3D](../rotation3d), [FontScheme](../fontscheme), [PictureFrame](../pictureframe), [Effect](../effect), [OverrideTheme](../overridetheme), [ColorChange](../colorchange), [ColumnCollection](../columncollection), [TrendlineCollection](../trendlinecollection), [EffectStyleCollection](../effectstylecollection), [AlphaInverse](../alphainverse), [ErrorBarsCustomValues](../errorbarscustomvalues), PlaceholderCollection, [FillFormat](../fillformat), [ModernComment](../moderncomment), [ColorFormat](../colorformat), [AdjustValueCollection](../adjustvaluecollection), [MasterNotesSlide](../masternotesslide), [CommentAuthorCollection](../commentauthorcollection), [ImageTransformOperation](../imagetransformoperation), AggregatedDataPointCollection, [LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager), [Background](../background), [Control](../control), [GrayScale](../grayscale), [LineFillFormat](../linefillformat), [AnimationTimeLine](../animationtimeline), [SmartArtShape](../smartartshape), [Tab](../tab), [MotionEffect](../motioneffect), [GradientStopCollection](../gradientstopcollection), [ChartCellCollection](../chartcellcollection), [ColorEffect](../coloreffect), [ChartPortionFormat](../chartportionformat), [MathBox](../mathbox), [DigitalSignatureCollection](../digitalsignaturecollection), [AutoShape](../autoshape), [NotesSlide](../notesslide), [SectionCollection](../sectioncollection), [ScaleEffect](../scaleeffect), [MathFunction](../mathfunction), [ChartSeries](../chartseries), [Connector](../connector), [Picture](../picture), [CommandEffect](../commandeffect), [SlideThemeManager](../slidethememanager), [DoubleChartValue](../doublechartvalue), [Column](../column), [EffectStyle](../effectstyle), [SlideSize](../slidesize), [CustomData](../customdata), [SummaryZoomSection](../summaryzoomsection), [HSL](../hsl), [Tint](../tint), [DataLabelCollection](../datalabelcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), LayoutTree, [GraphicalObject](../graphicalobject), [Field](../field), [FormatScheme](../formatscheme), [Legend](../legend), [AlphaCeiling](../alphaceiling), [Hyperlink](../hyperlink), [Cell](../cell), [Portion](../portion), [BiLevel](../bilevel), [MathElementBase](../mathelementbase), [MasterHandoutSlideHeaderFooterManager](../masterhandoutslideheaderfootermanager), [MathFraction](../mathfraction), [DataTable](../datatable), [HyperlinkManager](../hyperlinkmanager), [BaseHeaderFooterManager](../baseheaderfootermanager), [ChartSeriesCollection](../chartseriescollection), [ChartTextFormat](../charttextformat), [LayoutSlide](../layoutslide), [ShapeBevel](../shapebevel), [ShapeStyle](../shapestyle), [Camera](../camera), ThemeableTableFormat, [RowFormat](../rowformat), [ChartCategoryCollection](../chartcategorycollection), ChartSeriesGroupCollection, [LayoutSlideThemeManager](../layoutslidethememanager), [ControlCollection](../controlcollection), [InnerShadow](../innershadow), [PortionFormat](../portionformat), [AlphaReplace](../alphareplace), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [MathPortion](../mathportion), [Duotone](../duotone), [Backdrop3DScene](../backdrop3dscene), MasterHandoutSlideManager, [Video](../video), [AlphaModulate](../alphamodulate), [Behavior](../behavior), [ImageCollection](../imagecollection), BaseStyles, [ChartDataPointLevelsManager](../chartdatapointlevelsmanager), [PVIObject](../pviobject), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [Comment](../comment), [PatternFormat](../patternformat), [ChartCategory](../chartcategory), [PortionCollection](../portioncollection), [ErrorBarsFormat](../errorbarsformat), [ColorReplace](../colorreplace), ThemeableCellFormat, [GroupShape](../groupshape), [PresentationHeaderFooterManager](../presentationheaderfootermanager), MathRunElement, [MasterSlideCollection](../masterslidecollection), [TextFrameFormat](../textframeformat), [SectionZoomFrame](../sectionzoomframe), [DomObject](../domobject), [AlphaFloor](../alphafloor), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [AudioFrame](../audioframe), [EffectFormat](../effectformat), [ShapeCollection](../shapecollection), [VideoFrame](../videoframe), [Theme](../theme), [ChartDataPoint](../chartdatapoint), [AxesManager](../axesmanager), [MathRadical](../mathradical), [FillOverlay](../filloverlay), [FilterEffect](../filtereffect), [TextFrame](../textframe), [Marker](../marker), [ParagraphCollection](../paragraphcollection), [Presentation](../presentation), [MathArray](../matharray), [ZoomObject](../zoomobject), [LineFormatCollection](../lineformatcollection), [MathDelimiter](../mathdelimiter), TableCellTextStyle, [OuterShadow](../outershadow), [ExtraColorSchemeCollection](../extracolorschemecollection), [MathBorderBox](../mathborderbox), [Glow](../glow), [BaseChartValue](../basechartvalue), [SummaryZoomFrame](../summaryzoomframe), [LegendEntryProperties](../legendentryproperties), TableStyleCollection, TablePartStyle, [AlphaModulateFixed](../alphamodulatefixed), ThemeableEffectFormat, [MasterSlideHeaderFooterManager](../masterslideheaderfootermanager), [ChartLinesFormat](../chartlinesformat)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () |  |

 **Result:**
Presentation


---


### getRightToLeft {#getRightToLeft}

| Name | Description |
| --- | --- |
| getRightToLeft () | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () |  |

 **Result:**
BaseSlide


---


### getSpaceAfter {#getSpaceAfter}

| Name | Description |
| --- | --- |
| getSpaceAfter () | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Result:**
float


---


### getSpaceBefore {#getSpaceBefore}

| Name | Description |
| --- | --- |
| getSpaceBefore () | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Result:**
float


---


### getSpaceWithin {#getSpaceWithin}

| Name | Description |
| --- | --- |
| getSpaceWithin () | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |

 **Result:**
float


---


### getTabs {#getTabs}

| Name | Description |
| --- | --- |
| getTabs () | Returns tabulations of a paragraph. No inheritance applied. Read-only ITabCollection. |

 **Result:**
[TabCollection](../tabcollection)


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Result:**
long


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Result:**
long


---


### setAlignment {#setAlignment}

| Name | Description |
| --- | --- |
| setAlignment (int) | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |


---


### setDefaultTabSize {#setDefaultTabSize}

| Name | Description |
| --- | --- |
| setDefaultTabSize (float) | Returns or sets default tabulation size with no inheritance. Read/write float. |


---


### setDepth {#setDepth}

| Name | Description |
| --- | --- |
| setDepth (short) | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |


---


### setEastAsianLineBreak {#setEastAsianLineBreak}

| Name | Description |
| --- | --- |
| setEastAsianLineBreak (byte) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setFontAlignment {#setFontAlignment}

| Name | Description |
| --- | --- |
| setFontAlignment (int) | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |


---


### setHangingPunctuation {#setHangingPunctuation}

| Name | Description |
| --- | --- |
| setHangingPunctuation (byte) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setIndent {#setIndent}

| Name | Description |
| --- | --- |
| setIndent (float) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |


---


### setLatinLineBreak {#setLatinLineBreak}

| Name | Description |
| --- | --- |
| setLatinLineBreak (byte) | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setMarginLeft {#setMarginLeft}

| Name | Description |
| --- | --- |
| setMarginLeft (float) | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |


---


### setMarginRight {#setMarginRight}

| Name | Description |
| --- | --- |
| setMarginRight (float) | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |


---


### setRightToLeft {#setRightToLeft}

| Name | Description |
| --- | --- |
| setRightToLeft (byte) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setSpaceAfter {#setSpaceAfter}

| Name | Description |
| --- | --- |
| setSpaceAfter (float) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


### setSpaceBefore {#setSpaceBefore}

| Name | Description |
| --- | --- |
| setSpaceBefore (float) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


### setSpaceWithin {#setSpaceWithin}

| Name | Description |
| --- | --- |
| setSpaceWithin (float) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |


---


