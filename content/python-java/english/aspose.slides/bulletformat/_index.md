---
title: BulletFormat
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/bulletformat/
---

## BulletFormat class

 Represents paragraph bullet formatting properties.
 
### applyDefaultParagraphIndentsShifts {#applyDefaultParagraphIndentsShifts}

| Name | Description |
| --- | --- |
| applyDefaultParagraphIndentsShifts () | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Calling this method doesn't matter and throw InvalidOperationException in following cases: if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception); or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |


---


### getChar {#getChar}

| Name | Description |
| --- | --- |
| getChar () | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |

 **Result:**
char


---


### getColor {#getColor}

| Name | Description |
| --- | --- |
| getColor () | Returns the color format of a bullet of a paragraph with no inheritance. Read-only IColorFormat. |

 **Result:**
[ColorFormat](../colorformat)


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Gets effective bullet formatting data with the inheritance applied. |

 **Result:**
BulletFormatEffectiveData


---


### getFont {#getFont}

| Name | Description |
| --- | --- |
| getFont () | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |

 **Result:**
[FontData](../fontdata)


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |

 **Result:**
float


---


### getNumberedBulletStartWith {#getNumberedBulletStartWith}

| Name | Description |
| --- | --- |
| getNumberedBulletStartWith () | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |

 **Result:**
short


---


### getNumberedBulletStyle {#getNumberedBulletStyle}

| Name | Description |
| --- | --- |
| getNumberedBulletStyle () | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |

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


### getPicture {#getPicture}

| Name | Description |
| --- | --- |
| getPicture () | Returns the picture used as a bullet in a paragraph with no inheritance. Read-only ISlidesPicture. |

 **Result:**
[Picture](../picture)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () |  |

 **Result:**
Presentation


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () |  |

 **Result:**
BaseSlide


---


### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |

 **Result:**
byte


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


### isBulletHardColor {#isBulletHardColor}

| Name | Description |
| --- | --- |
| isBulletHardColor () | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |

 **Result:**
byte


---


### isBulletHardFont {#isBulletHardFont}

| Name | Description |
| --- | --- |
| isBulletHardFont () | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |

 **Result:**
byte


---


### setBulletHardColor {#setBulletHardColor}

| Name | Description |
| --- | --- |
| setBulletHardColor (byte) | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write NullableBool. |


---


### setBulletHardFont {#setBulletHardFont}

| Name | Description |
| --- | --- |
| setBulletHardFont (byte) | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write NullableBool. |


---


### setChar {#setChar}

| Name | Description |
| --- | --- |
| setChar (char) | Returns or sets the bullet char of a paragraph with no inheritance. Read/write char. |


---


### setFont {#setFont}

| Name | Description |
| --- | --- |
| setFont ([FontData](../fontdata)) | Returns or sets the bullet font of a paragraph with no inheritance. Read/write IFontData. |


---


### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight (float) | Returns or sets the bullet height of a paragraph with no inheritance. Value Float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write float. |


---


### setNumberedBulletStartWith {#setNumberedBulletStartWith}

| Name | Description |
| --- | --- |
| setNumberedBulletStartWith (short) | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write short. |


---


### setNumberedBulletStyle {#setNumberedBulletStyle}

| Name | Description |
| --- | --- |
| setNumberedBulletStyle (byte) | Returns or sets the style of a numbered bullet with no inheritance. Read/write NumberedBulletStyle. |


---


### setType {#setType}

| Name | Description |
| --- | --- |
| setType (byte) | Returns or sets the bullet type of a paragraph with no inheritance. Read/write BulletType. |


---


