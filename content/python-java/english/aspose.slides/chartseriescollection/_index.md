---
title: ChartSeriesCollection
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/chartseriescollection/
---

## ChartSeriesCollection class

 Represents collection of   ChartSeries
 
### add {#add}

| Name | Description |
| --- | --- |
| add (int) | Creates new chart series and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Type of series |

 **Result:**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartDataCell](../chartdatacell), int) | Creates new chart series from ChartDataCell and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| cellWithSeriesName | [ChartDataCell](../chartdatacell) | Cell which contain series name. |
| type | int | Type set type of series If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

 **Result:**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([ChartCellCollection](../chartcellcollection), int) | Creates new chart series from ChartCellCollection and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| cellsWithSeriesName | [ChartCellCollection](../chartcellcollection) | Cells which contain series name. |
| type | int | Type set type of series If chart series careted from same cell already in collection then method adds nothing and returns it's index. |

 **Result:**
[ChartSeries](../chartseries)


---


### add {#add}

| Name | Description |
| --- | --- |
| add (String, int) | Creates new chart series from value and adds it to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Series name. |
| type | int | Type set type of series |

 **Result:**
[ChartSeries](../chartseries)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all controls from the collection. |


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate () |  |

 **Result:**
DisplayUnitLabel, [ChartThemeManager](../chartthememanager), [RotationEffect](../rotationeffect), [ChartTitle](../charttitle), [MathBar](../mathbar), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ChartDataWorksheet](../chartdataworksheet), [SoftEdge](../softedge), [Audio](../audio), [ChartWall](../chartwall), [BaseOverrideThemeManager](../baseoverridethememanager), [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager), ThemeableLineFormat, [UpDownBarsManager](../updownbarsmanager), [MathMatrix](../mathmatrix), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement), [Format](../format), [GradientFormat](../gradientformat), [ThreeDFormat](../threedformat), [Slide](../slide), [TabCollection](../tabcollection), [ColorScheme](../colorscheme), [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [SlideHeaderFooterManager](../slideheaderfootermanager), [CommentAuthor](../commentauthor), [CellFormat](../cellformat), [SlideShowTransition](../slideshowtransition), [CustomXmlPartCollection](../customxmlpartcollection), [SlideCollection](../slidecollection), [ViewProperties](../viewproperties), [Shape](../shape), [ExtraColorScheme](../extracolorscheme), [Luminance](../luminance), [MasterThemeManager](../masterthememanager), [DataLabel](../datalabel), [GradientStop](../gradientstop), [CellCollection](../cellcollection), [MathematicalText](../mathematicaltext), [Row](../row), MasterNotesSlideManager, [MathNaryOperator](../mathnaryoperator), [BaseThemeManager](../basethememanager), ThemeableFillFormat, [RowCollection](../rowcollection), [GeometryShape](../geometryshape), TableStyle, [LightRig](../lightrig), [ChartPlotArea](../chartplotarea), [BulletFormat](../bulletformat), [MathSuperscriptElement](../mathsuperscriptelement), [VideoCollection](../videocollection), [Table](../table), [ChartDataPointLevel](../chartdatapointlevel), PresetTextShape, [MasterTheme](../mastertheme), [SectionSlideCollection](../sectionslidecollection), [OleObjectFrame](../oleobjectframe), [ChartData](../chartdata), [ChartDataPointCollection](../chartdatapointcollection), [ChartDataWorkbook](../chartdataworkbook), [NotesSlideHeaderFooterManager](../notesslideheaderfootermanager), [PresetShadow](../presetshadow), AggregatedDataPoint, [SketchFormat](../sketchformat), [MathParagraph](../mathparagraph), [SmartArt](../smartart), [AudioCollection](../audiocollection), [AxisFormat](../axisformat), [CommentCollection](../commentcollection), [ParagraphFormat](../paragraphformat), [ChartDataWorksheetCollection](../chartdataworksheetcollection), FormatOverrides, [TextStyle](../textstyle), [FillFormatCollection](../fillformatcollection), [NotesSlideManager](../notesslidemanager), [ColumnFormat](../columnformat), [Section](../section), [MathBlock](../mathblock), [TableFormat](../tableformat), [StringChartValue](../stringchartvalue), [Reflection](../reflection), [Ink](../ink), [Trendline](../trendline), [LayoutSlideCollection](../layoutslidecollection), [LineFormat](../lineformat), [BasePortionFormat](../baseportionformat), [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager), [MasterHandoutSlide](../masterhandoutslide), [DataLabelFormat](../datalabelformat), [Timing](../timing), [MathAccent](../mathaccent), [LegacyDiagram](../legacydiagram), FormatOverride, [ChartSeriesGroup](../chartseriesgroup), [Blur](../blur), [MathSubscriptElement](../mathsubscriptelement), [NotesSlideThemeManager](../notesslidethememanager), [Axis](../axis), [AlphaBiLevel](../alphabilevel), [Paragraph](../paragraph), [MathGroupingCharacter](../mathgroupingcharacter), [MathLimit](../mathlimit), TableBackgroundStyle, [SetEffect](../seteffect), [StringOrDoubleChartValue](../stringordoublechartvalue), [Chart](../chart), [PictureFillFormat](../picturefillformat), [HyperlinkQueries](../hyperlinkqueries), [ZoomFrame](../zoomframe), [BaseScript](../basescript), [MasterNotesSlideHeaderFooterManager](../masternotesslideheaderfootermanager), [Rotation3D](../rotation3d), [FontScheme](../fontscheme), [PictureFrame](../pictureframe), [Effect](../effect), [OverrideTheme](../overridetheme), [ColorChange](../colorchange), [ColumnCollection](../columncollection), [TrendlineCollection](../trendlinecollection), [EffectStyleCollection](../effectstylecollection), [AlphaInverse](../alphainverse), [ErrorBarsCustomValues](../errorbarscustomvalues), PlaceholderCollection, [FillFormat](../fillformat), [ModernComment](../moderncomment), [ColorFormat](../colorformat), [AdjustValueCollection](../adjustvaluecollection), [MasterNotesSlide](../masternotesslide), [CommentAuthorCollection](../commentauthorcollection), [ImageTransformOperation](../imagetransformoperation), AggregatedDataPointCollection, [LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager), [Background](../background), [Control](../control), [GrayScale](../grayscale), [LineFillFormat](../linefillformat), [AnimationTimeLine](../animationtimeline), [SmartArtShape](../smartartshape), [Tab](../tab), [MotionEffect](../motioneffect), [GradientStopCollection](../gradientstopcollection), [ChartCellCollection](../chartcellcollection), [ColorEffect](../coloreffect), [ChartPortionFormat](../chartportionformat), [MathBox](../mathbox), [DigitalSignatureCollection](../digitalsignaturecollection), [AutoShape](../autoshape), [NotesSlide](../notesslide), [SectionCollection](../sectioncollection), [ScaleEffect](../scaleeffect), [MathFunction](../mathfunction), [ChartSeries](../chartseries), [Connector](../connector), [Picture](../picture), [CommandEffect](../commandeffect), [SlideThemeManager](../slidethememanager), [DoubleChartValue](../doublechartvalue), [Column](../column), [EffectStyle](../effectstyle), [SlideSize](../slidesize), [CustomData](../customdata), [SummaryZoomSection](../summaryzoomsection), [HSL](../hsl), [Tint](../tint), [DataLabelCollection](../datalabelcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), LayoutTree, [GraphicalObject](../graphicalobject), [Field](../field), [FormatScheme](../formatscheme), [Legend](../legend), [AlphaCeiling](../alphaceiling), [Hyperlink](../hyperlink), [Cell](../cell), [Portion](../portion), [BiLevel](../bilevel), [MathElementBase](../mathelementbase), [MasterHandoutSlideHeaderFooterManager](../masterhandoutslideheaderfootermanager), [MathFraction](../mathfraction), [DataTable](../datatable), [HyperlinkManager](../hyperlinkmanager), [BaseHeaderFooterManager](../baseheaderfootermanager), [ChartSeriesCollection](../chartseriescollection), [ChartTextFormat](../charttextformat), [LayoutSlide](../layoutslide), [ShapeBevel](../shapebevel), [ShapeStyle](../shapestyle), [Camera](../camera), ThemeableTableFormat, [RowFormat](../rowformat), [ChartCategoryCollection](../chartcategorycollection), ChartSeriesGroupCollection, [LayoutSlideThemeManager](../layoutslidethememanager), [ControlCollection](../controlcollection), [InnerShadow](../innershadow), [PortionFormat](../portionformat), [AlphaReplace](../alphareplace), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [MathPortion](../mathportion), [Duotone](../duotone), [Backdrop3DScene](../backdrop3dscene), MasterHandoutSlideManager, [Video](../video), [AlphaModulate](../alphamodulate), [Behavior](../behavior), [ImageCollection](../imagecollection), BaseStyles, [ChartDataPointLevelsManager](../chartdatapointlevelsmanager), [PVIObject](../pviobject), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [Comment](../comment), [PatternFormat](../patternformat), [ChartCategory](../chartcategory), [PortionCollection](../portioncollection), [ErrorBarsFormat](../errorbarsformat), [ColorReplace](../colorreplace), ThemeableCellFormat, [GroupShape](../groupshape), [PresentationHeaderFooterManager](../presentationheaderfootermanager), MathRunElement, [MasterSlideCollection](../masterslidecollection), [TextFrameFormat](../textframeformat), [SectionZoomFrame](../sectionzoomframe), [DomObject](../domobject), [AlphaFloor](../alphafloor), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [AudioFrame](../audioframe), [EffectFormat](../effectformat), [ShapeCollection](../shapecollection), [VideoFrame](../videoframe), [Theme](../theme), [ChartDataPoint](../chartdatapoint), [AxesManager](../axesmanager), [MathRadical](../mathradical), [FillOverlay](../filloverlay), [FilterEffect](../filtereffect), [TextFrame](../textframe), [Marker](../marker), [ParagraphCollection](../paragraphcollection), [Presentation](../presentation), [MathArray](../matharray), [ZoomObject](../zoomobject), [LineFormatCollection](../lineformatcollection), [MathDelimiter](../mathdelimiter), TableCellTextStyle, [OuterShadow](../outershadow), [ExtraColorSchemeCollection](../extracolorschemecollection), [MathBorderBox](../mathborderbox), [Glow](../glow), [BaseChartValue](../basechartvalue), [SummaryZoomFrame](../summaryzoomframe), [LegendEntryProperties](../legendentryproperties), TableStyleCollection, TablePartStyle, [AlphaModulateFixed](../alphamodulatefixed), ThemeableEffectFormat, [MasterSlideHeaderFooterManager](../masterslideheaderfootermanager), [ChartLinesFormat](../chartlinesformat)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Result:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. |

 **Result:**
[ChartSeries](../chartseries)

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index is not a valid index in the IList. |


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ChartSeries](../chartseries)) | Searches for the specified ChartSeries and returns the zero-based index of the first occurrence within the entire Collection |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | Chart series value. |

 **Result:**
int


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert (int, int) | Creates new chart series and inserts it into the collection. |

 **Result:**
[ChartSeries](../chartseries)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Result:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Result:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([ChartSeries](../chartseries)) | Removes the specified value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [ChartSeries](../chartseries) | The value. |

 **Error**

| Error | Condition |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | The value parameter was not found in the collection. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes an ActiveX control stored at specified position from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a control to remove. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns a number of objects in the collection. Read-only int. |

 **Result:**
int


---


