---
title: ChartData
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdata/
---

## ChartData class

 Represents data used for a chart plotting.
 
### getCategories {#getCategories}

| Name | Description |
| --- | --- |
| getCategories () | Gets the primary categories (or both primary and secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false). Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then ( #getSecondaryCategories) property return null and data in this #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in ( #getSecondaryCategories) property is used for secondary series and data in this #getCategories property is used for primary series. |

 **Result:**
[ChartCategoryCollection](../chartcategorycollection)


---


### getChartDataWorkbook {#getChartDataWorkbook}

| Name | Description |
| --- | --- |
| getChartDataWorkbook () | Gets the cells factory to create cells used for chart series or categories. Read-only IChartDataWorkbook. |

 **Result:**
[ChartDataWorkbook](../chartdataworkbook)


---


### getDataSourceType {#getDataSourceType}

| Name | Description |
| --- | --- |
| getDataSourceType () | Represents external workbook path if external data source, null otherwise |

 **Result:**
int


---


### getExternalWorkbookPath {#getExternalWorkbookPath}

| Name | Description |
| --- | --- |
| getExternalWorkbookPath () | Represents data source of the chart |

 **Result:**
String


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate () |  |

 **Result:**
DisplayUnitLabel, [ChartThemeManager](../chartthememanager), [RotationEffect](../rotationeffect), [ChartTitle](../charttitle), [MathBar](../mathbar), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ChartDataWorksheet](../chartdataworksheet), [SoftEdge](../softedge), [Audio](../audio), [ChartWall](../chartwall), [BaseOverrideThemeManager](../baseoverridethememanager), [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager), ThemeableLineFormat, [UpDownBarsManager](../updownbarsmanager), [MathMatrix](../mathmatrix), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement), [Format](../format), [GradientFormat](../gradientformat), [ThreeDFormat](../threedformat), [Slide](../slide), [TabCollection](../tabcollection), [ColorScheme](../colorscheme), [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [SlideHeaderFooterManager](../slideheaderfootermanager), [CommentAuthor](../commentauthor), [CellFormat](../cellformat), [SlideShowTransition](../slideshowtransition), [CustomXmlPartCollection](../customxmlpartcollection), [SlideCollection](../slidecollection), [ViewProperties](../viewproperties), [Shape](../shape), [ExtraColorScheme](../extracolorscheme), [Luminance](../luminance), [MasterThemeManager](../masterthememanager), [DataLabel](../datalabel), [GradientStop](../gradientstop), [CellCollection](../cellcollection), [MathematicalText](../mathematicaltext), [Row](../row), MasterNotesSlideManager, [MathNaryOperator](../mathnaryoperator), [BaseThemeManager](../basethememanager), ThemeableFillFormat, [RowCollection](../rowcollection), [GeometryShape](../geometryshape), TableStyle, [LightRig](../lightrig), [ChartPlotArea](../chartplotarea), [BulletFormat](../bulletformat), [MathSuperscriptElement](../mathsuperscriptelement), [VideoCollection](../videocollection), [Table](../table), [ChartDataPointLevel](../chartdatapointlevel), PresetTextShape, [MasterTheme](../mastertheme), [SectionSlideCollection](../sectionslidecollection), [OleObjectFrame](../oleobjectframe), [ChartData](../chartdata), [ChartDataPointCollection](../chartdatapointcollection), [ChartDataWorkbook](../chartdataworkbook), [NotesSlideHeaderFooterManager](../notesslideheaderfootermanager), [PresetShadow](../presetshadow), AggregatedDataPoint, [SketchFormat](../sketchformat), [MathParagraph](../mathparagraph), [SmartArt](../smartart), [AudioCollection](../audiocollection), [AxisFormat](../axisformat), [CommentCollection](../commentcollection), [ParagraphFormat](../paragraphformat), [ChartDataWorksheetCollection](../chartdataworksheetcollection), FormatOverrides, [TextStyle](../textstyle), [FillFormatCollection](../fillformatcollection), [NotesSlideManager](../notesslidemanager), [ColumnFormat](../columnformat), [Section](../section), [MathBlock](../mathblock), [TableFormat](../tableformat), [StringChartValue](../stringchartvalue), [Reflection](../reflection), [Ink](../ink), [Trendline](../trendline), [LayoutSlideCollection](../layoutslidecollection), [LineFormat](../lineformat), [BasePortionFormat](../baseportionformat), [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager), [MasterHandoutSlide](../masterhandoutslide), [DataLabelFormat](../datalabelformat), [Timing](../timing), [MathAccent](../mathaccent), [LegacyDiagram](../legacydiagram), FormatOverride, [ChartSeriesGroup](../chartseriesgroup), [Blur](../blur), [MathSubscriptElement](../mathsubscriptelement), [NotesSlideThemeManager](../notesslidethememanager), [Axis](../axis), [AlphaBiLevel](../alphabilevel), [Paragraph](../paragraph), [MathGroupingCharacter](../mathgroupingcharacter), [MathLimit](../mathlimit), TableBackgroundStyle, [SetEffect](../seteffect), [StringOrDoubleChartValue](../stringordoublechartvalue), [Chart](../chart), [PictureFillFormat](../picturefillformat), [HyperlinkQueries](../hyperlinkqueries), [ZoomFrame](../zoomframe), [BaseScript](../basescript), [MasterNotesSlideHeaderFooterManager](../masternotesslideheaderfootermanager), [Rotation3D](../rotation3d), [FontScheme](../fontscheme), [PictureFrame](../pictureframe), [Effect](../effect), [OverrideTheme](../overridetheme), [ColorChange](../colorchange), [ColumnCollection](../columncollection), [TrendlineCollection](../trendlinecollection), [EffectStyleCollection](../effectstylecollection), [AlphaInverse](../alphainverse), [ErrorBarsCustomValues](../errorbarscustomvalues), PlaceholderCollection, [FillFormat](../fillformat), [ModernComment](../moderncomment), [ColorFormat](../colorformat), [AdjustValueCollection](../adjustvaluecollection), [MasterNotesSlide](../masternotesslide), [CommentAuthorCollection](../commentauthorcollection), [ImageTransformOperation](../imagetransformoperation), AggregatedDataPointCollection, [LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager), [Background](../background), [Control](../control), [GrayScale](../grayscale), [LineFillFormat](../linefillformat), [AnimationTimeLine](../animationtimeline), [SmartArtShape](../smartartshape), [Tab](../tab), [MotionEffect](../motioneffect), [GradientStopCollection](../gradientstopcollection), [ChartCellCollection](../chartcellcollection), [ColorEffect](../coloreffect), [ChartPortionFormat](../chartportionformat), [MathBox](../mathbox), [DigitalSignatureCollection](../digitalsignaturecollection), [AutoShape](../autoshape), [NotesSlide](../notesslide), [SectionCollection](../sectioncollection), [ScaleEffect](../scaleeffect), [MathFunction](../mathfunction), [ChartSeries](../chartseries), [Connector](../connector), [Picture](../picture), [CommandEffect](../commandeffect), [SlideThemeManager](../slidethememanager), [DoubleChartValue](../doublechartvalue), [Column](../column), [EffectStyle](../effectstyle), [SlideSize](../slidesize), [CustomData](../customdata), [SummaryZoomSection](../summaryzoomsection), [HSL](../hsl), [Tint](../tint), [DataLabelCollection](../datalabelcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), LayoutTree, [GraphicalObject](../graphicalobject), [Field](../field), [FormatScheme](../formatscheme), [Legend](../legend), [AlphaCeiling](../alphaceiling), [Hyperlink](../hyperlink), [Cell](../cell), [Portion](../portion), [BiLevel](../bilevel), [MathElementBase](../mathelementbase), [MasterHandoutSlideHeaderFooterManager](../masterhandoutslideheaderfootermanager), [MathFraction](../mathfraction), [DataTable](../datatable), [HyperlinkManager](../hyperlinkmanager), [BaseHeaderFooterManager](../baseheaderfootermanager), [ChartSeriesCollection](../chartseriescollection), [ChartTextFormat](../charttextformat), [LayoutSlide](../layoutslide), [ShapeBevel](../shapebevel), [ShapeStyle](../shapestyle), [Camera](../camera), ThemeableTableFormat, [RowFormat](../rowformat), [ChartCategoryCollection](../chartcategorycollection), ChartSeriesGroupCollection, [LayoutSlideThemeManager](../layoutslidethememanager), [ControlCollection](../controlcollection), [InnerShadow](../innershadow), [PortionFormat](../portionformat), [AlphaReplace](../alphareplace), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [MathPortion](../mathportion), [Duotone](../duotone), [Backdrop3DScene](../backdrop3dscene), MasterHandoutSlideManager, [Video](../video), [AlphaModulate](../alphamodulate), [Behavior](../behavior), [ImageCollection](../imagecollection), BaseStyles, [ChartDataPointLevelsManager](../chartdatapointlevelsmanager), [PVIObject](../pviobject), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [Comment](../comment), [PatternFormat](../patternformat), [ChartCategory](../chartcategory), [PortionCollection](../portioncollection), [ErrorBarsFormat](../errorbarsformat), [ColorReplace](../colorreplace), ThemeableCellFormat, [GroupShape](../groupshape), [PresentationHeaderFooterManager](../presentationheaderfootermanager), MathRunElement, [MasterSlideCollection](../masterslidecollection), [TextFrameFormat](../textframeformat), [SectionZoomFrame](../sectionzoomframe), [DomObject](../domobject), [AlphaFloor](../alphafloor), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [AudioFrame](../audioframe), [EffectFormat](../effectformat), [ShapeCollection](../shapecollection), [VideoFrame](../videoframe), [Theme](../theme), [ChartDataPoint](../chartdatapoint), [AxesManager](../axesmanager), [MathRadical](../mathradical), [FillOverlay](../filloverlay), [FilterEffect](../filtereffect), [TextFrame](../textframe), [Marker](../marker), [ParagraphCollection](../paragraphcollection), [Presentation](../presentation), [MathArray](../matharray), [ZoomObject](../zoomobject), [LineFormatCollection](../lineformatcollection), [MathDelimiter](../mathdelimiter), TableCellTextStyle, [OuterShadow](../outershadow), [ExtraColorSchemeCollection](../extracolorschemecollection), [MathBorderBox](../mathborderbox), [Glow](../glow), [BaseChartValue](../basechartvalue), [SummaryZoomFrame](../summaryzoomframe), [LegendEntryProperties](../legendentryproperties), TableStyleCollection, TablePartStyle, [AlphaModulateFixed](../alphamodulatefixed), ThemeableEffectFormat, [MasterSlideHeaderFooterManager](../masterslideheaderfootermanager), [ChartLinesFormat](../chartlinesformat)


---


### getRange {#getRange}

| Name | Description |
| --- | --- |
| getRange () | Gets chart data range. |

 **Result:**
String

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Chart doesn't use workbook as a data source |


---


### getSecondaryCategories {#getSecondaryCategories}

| Name | Description |
| --- | --- |
| getSecondaryCategories () | Gets the secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true. Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then this ( #getSecondaryCategories) property return null and data in #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in this #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. |

 **Result:**
[ChartCategoryCollection](../chartcategorycollection)


---


### getSeries {#getSeries}

| Name | Description |
| --- | --- |
| getSeries () | Gets the series. Read-only IChartSeriesCollection. |

 **Result:**
[ChartSeriesCollection](../chartseriescollection)


---


### getSeriesGroups {#getSeriesGroups}

| Name | Description |
| --- | --- |
| getSeriesGroups () | Gets the groups of series. Read-only IChartSeriesGroupCollection. 1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class. |

 **Result:**
ChartSeriesGroupCollection


---


### getUseSecondaryCategories {#getUseSecondaryCategories}

| Name | Description |
| --- | --- |
| getUseSecondaryCategories () | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |

 **Result:**
boolean


---


### readWorkbookStream {#readWorkbookStream}

| Name | Description |
| --- | --- |
| readWorkbookStream () | Writes the internally contained Excel workbook it into an in-memory stream. |

 **Result:**
byte


---


### setExternalWorkbook {#setExternalWorkbook}

| Name | Description |
| --- | --- |
| setExternalWorkbook (String) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


### setExternalWorkbook {#setExternalWorkbook}

| Name | Description |
| --- | --- |
| setExternalWorkbook (String, boolean) | Sets external workbook as a data source for the chart. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


### setRange {#setRange}

| Name | Description |
| --- | --- |
| setRange (String) | Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| formula | String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | formula has incorrect format. |


---


### setUseSecondaryCategories {#setUseSecondaryCategories}

| Name | Description |
| --- | --- |
| setUseSecondaryCategories (boolean) | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |


---


### switchRowColumn {#switchRowColumn}

| Name | Description |
| --- | --- |
| switchRowColumn () | Swap the data over the axis. Data being charted on the X axis will move to the Y axis and vice versa. |


---


### writeWorkbookStream {#writeWorkbookStream}

| Name | Description |
| --- | --- |
| writeWorkbookStream (byte[]) | Initializes the internally contained Excel workbook with user-specified value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| ms | byte[] | The user-supplied stream containing the entire Excel workbook. |


---


