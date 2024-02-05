---
title: ChartPortionFormat
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/chartportionformat/
---

## ChartPortionFormat class

 This class contains the chart portion formatting properties used in charts.
 Unlike  IPortionFormatEffectiveData, all properties of this class are writeable.
 
 This class is used to return and manipulate text portion formatting
 properties defined for the particular portion. This means that
 no inheritance is applied when getting values so for the majority of cases
 you will get values meaning "undefined".
 In order to get the effective formatting parameter values including
 inherited you need to use  PortionFormat#getEffective method
 which returns a  IPortionFormatEffectiveData instance.
### getAlternativeLanguageId {#getAlternativeLanguageId}

| Name | Description |
| --- | --- |
| getAlternativeLanguageId () | Returns or sets the Id of an alternative language. Read/write String. |

 **Result:**
String


---


### getComplexScriptFont {#getComplexScriptFont}

| Name | Description |
| --- | --- |
| getComplexScriptFont () | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Result:**
[FontData](../fontdata)


---


### getEastAsianFont {#getEastAsianFont}

| Name | Description |
| --- | --- |
| getEastAsianFont () | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Result:**
[FontData](../fontdata)


---


### getEffectFormat {#getEffectFormat}

| Name | Description |
| --- | --- |
| getEffectFormat () | Returns the text EffectFormat properties. No inheritance applied. Read-only IEffectFormat. |

 **Result:**
[EffectFormat](../effectformat)


---


### getEscapement {#getEscapement}

| Name | Description |
| --- | --- |
| getEscapement () | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |

 **Result:**
float


---


### getFillFormat {#getFillFormat}

| Name | Description |
| --- | --- |
| getFillFormat () | Returns the text FillFormat properties. No inheritance applied. Read-only IFillFormat. |

 **Result:**
[FillFormat](../fillformat)


---


### getFontBold {#getFontBold}

| Name | Description |
| --- | --- |
| getFontBold () | Determines whether the font is bold. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


---


### getFontHeight {#getFontHeight}

| Name | Description |
| --- | --- |
| getFontHeight () | Returns or sets the font height of a portion. Float.NaN means height is undefined and should be inherited from the Master. Read/write float. |

 **Result:**
float


---


### getFontItalic {#getFontItalic}

| Name | Description |
| --- | --- |
| getFontItalic () | Determines whether the font is itallic. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


---


### getFontUnderline {#getFontUnderline}

| Name | Description |
| --- | --- |
| getFontUnderline () | Returns or sets the text underline type. No inheritance applied. Read/write TextUnderlineType. |

 **Result:**
byte


---


### getHighlightColor {#getHighlightColor}

| Name | Description |
| --- | --- |
| getHighlightColor () | Returns the color used to highlight a text. No inheritance applied. Read-only IColorFormat. |

 **Result:**
[ColorFormat](../colorformat)


---


### getKerningMinimalSize {#getKerningMinimalSize}

| Name | Description |
| --- | --- |
| getKerningMinimalSize () | Returns or sets the minimal font size, for which kerning should be switched on. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |

 **Result:**
float


---


### getKumimoji {#getKumimoji}

| Name | Description |
| --- | --- |
| getKumimoji () | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


---


### getLanguageId {#getLanguageId}

| Name | Description |
| --- | --- |
| getLanguageId () | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |

 **Result:**
String


---


### getLatinFont {#getLatinFont}

| Name | Description |
| --- | --- |
| getLatinFont () | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Result:**
[FontData](../fontdata)


---


### getLineFormat {#getLineFormat}

| Name | Description |
| --- | --- |
| getLineFormat () | Returns the LineFormat properties for text outlining. No inheritance applied. Read-only ILineFormat. |

 **Result:**
[LineFormat](../lineformat)


---


### getNormaliseHeight {#getNormaliseHeight}

| Name | Description |
| --- | --- |
| getNormaliseHeight () | Determines whether the height of a text should be normalized. No inheritance applied. Read/write NullableBool. |

 **Result:**
byte


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


### getProofDisabled {#getProofDisabled}

| Name | Description |
| --- | --- |
| getProofDisabled () | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write NullableBool. |

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


### getSpacing {#getSpacing}

| Name | Description |
| --- | --- |
| getSpacing () | Returns or sets the intercharacter spacing increment. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |

 **Result:**
float


---


### getStrikethroughType {#getStrikethroughType}

| Name | Description |
| --- | --- |
| getStrikethroughType () | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write TextStrikethroughType. |

 **Result:**
byte


---


### getSymbolFont {#getSymbolFont}

| Name | Description |
| --- | --- |
| getSymbolFont () | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |

 **Result:**
[FontData](../fontdata)


---


### getTextCapType {#getTextCapType}

| Name | Description |
| --- | --- |
| getTextCapType () | Returns or sets the type of text capitalization. No inheritance applied. Read/write TextCapType. |

 **Result:**
byte


---


### getUnderlineFillFormat {#getUnderlineFillFormat}

| Name | Description |
| --- | --- |
| getUnderlineFillFormat () | Returns the underline line FillFormat properties. No inheritance applied. Read-only IFillFormat. |

 **Result:**
[FillFormat](../fillformat)


---


### getUnderlineLineFormat {#getUnderlineLineFormat}

| Name | Description |
| --- | --- |
| getUnderlineLineFormat () | Returns the LineFormat properties used to outline underline line. No inheritance applied. Read-only ILineFormat. |

 **Result:**
[LineFormat](../lineformat)


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


### isHardUnderlineFill {#isHardUnderlineFill}

| Name | Description |
| --- | --- |
| isHardUnderlineFill () | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write NullableBool. |

 **Result:**
byte


---


### isHardUnderlineLine {#isHardUnderlineLine}

| Name | Description |
| --- | --- |
| isHardUnderlineLine () | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write NullableBool. |

 **Result:**
byte


---


### setAlternativeLanguageId {#setAlternativeLanguageId}

| Name | Description |
| --- | --- |
| setAlternativeLanguageId (String) | Returns or sets the Id of an alternative language. Read/write String. |


---


### setComplexScriptFont {#setComplexScriptFont}

| Name | Description |
| --- | --- |
| setComplexScriptFont ([FontData](../fontdata)) | Returns or sets the complex script font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setEastAsianFont {#setEastAsianFont}

| Name | Description |
| --- | --- |
| setEastAsianFont ([FontData](../fontdata)) | Returns or sets the East Asian font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setEscapement {#setEscapement}

| Name | Description |
| --- | --- |
| setEscapement (float) | Returns or sets the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |


---


### setFontBold {#setFontBold}

| Name | Description |
| --- | --- |
| setFontBold (byte) | Determines whether the font is bold. No inheritance applied. Read/write NullableBool. |


---


### setFontHeight {#setFontHeight}

| Name | Description |
| --- | --- |
| setFontHeight (float) | Returns or sets the font height of a portion. Float.NaN means height is undefined and should be inherited from the Master. Read/write float. |


---


### setFontItalic {#setFontItalic}

| Name | Description |
| --- | --- |
| setFontItalic (byte) | Determines whether the font is itallic. No inheritance applied. Read/write NullableBool. |


---


### setFontUnderline {#setFontUnderline}

| Name | Description |
| --- | --- |
| setFontUnderline (byte) | Returns or sets the text underline type. No inheritance applied. Read/write TextUnderlineType. |


---


### setHardUnderlineFill {#setHardUnderlineFill}

| Name | Description |
| --- | --- |
| setHardUnderlineFill (byte) | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read/write NullableBool. |


---


### setHardUnderlineLine {#setHardUnderlineLine}

| Name | Description |
| --- | --- |
| setHardUnderlineLine (byte) | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read/write NullableBool. |


---


### setKerningMinimalSize {#setKerningMinimalSize}

| Name | Description |
| --- | --- |
| setKerningMinimalSize (float) | Returns or sets the minimal font size, for which kerning should be switched on. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |


---


### setKumimoji {#setKumimoji}

| Name | Description |
| --- | --- |
| setKumimoji (byte) | Determines whether the numbers should ignore text eastern language-specific vertical text layout. No inheritance applied. Read/write NullableBool. |


---


### setLanguageId {#setLanguageId}

| Name | Description |
| --- | --- |
| setLanguageId (String) | Returns or sets the Id of a proofing language. Used for checking spelling and grammar. Read/write String. |


---


### setLatinFont {#setLatinFont}

| Name | Description |
| --- | --- |
| setLatinFont ([FontData](../fontdata)) | Returns or sets the Latin font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setNormaliseHeight {#setNormaliseHeight}

| Name | Description |
| --- | --- |
| setNormaliseHeight (byte) | Determines whether the height of a text should be normalized. No inheritance applied. Read/write NullableBool. |


---


### setProofDisabled {#setProofDisabled}

| Name | Description |
| --- | --- |
| setProofDisabled (byte) | Determines whether the text shouldn't be proofed. No inheritance applied. Read/write NullableBool. |


---


### setSpacing {#setSpacing}

| Name | Description |
| --- | --- |
| setSpacing (float) | Returns or sets the intercharacter spacing increment. Float.NaN means value is undefined and should be inherited from the Master. Read/write float. |


---


### setStrikethroughType {#setStrikethroughType}

| Name | Description |
| --- | --- |
| setStrikethroughType (byte) | Returns or sets the strikethrough type of a text. No inheritance applied. Read/write TextStrikethroughType. |


---


### setSymbolFont {#setSymbolFont}

| Name | Description |
| --- | --- |
| setSymbolFont ([FontData](../fontdata)) | Returns or sets the symbolic font info. Null means font is undefined and should be inherited from the Master. Read/write IFontData. |


---


### setTextCapType {#setTextCapType}

| Name | Description |
| --- | --- |
| setTextCapType (byte) | Returns or sets the type of text capitalization. No inheritance applied. Read/write TextCapType. |


---


