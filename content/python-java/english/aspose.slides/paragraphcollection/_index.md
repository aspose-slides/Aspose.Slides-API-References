---
title: ParagraphCollection
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraphcollection/
---

## ParagraphCollection class

 Represents a collection of a paragraphs.
 
### add {#add}

| Name | Description |
| --- | --- |
| add ([Paragraph](../paragraph)) | Adds a Paragraph to the end of collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [Paragraph](../paragraph) | The Paragraph to be added to the end of the collection. |


---


### add {#add}

| Name | Description |
| --- | --- |
| add ([ParagraphCollection](../paragraphcollection)) | Adds a content of ParagraphCollection to the end of collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [ParagraphCollection](../paragraphcollection) | The ParagraphCollection to be added to the end of the collection. |

 **Result:**
int


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String) | Adds text from specified html string to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | HTML text. |


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | Adds text from specified html string to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | HTML text. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | String | URI for adding HTML document. Used for resolving relative links. Specifying resolver can potentially introduce a vulnurability. Use with caution. |


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | Adds text from specified html string to the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | HTML text. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | String | URI for adding HTML document. Used for resolving relative links. Specifying resolver can potentially introduce a vulnurability. Use with caution. |


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all elements from the collection. |


---


### contains {#contains}

| Name | Description |
| --- | --- |
| contains ([Paragraph](../paragraph)) | Determines whether the IGenericCollection contains a specific value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | The object to locate in the IGenericCollection. |

 **Result:**
boolean


---


### copyTo {#copyTo}

| Name | Description |
| --- | --- |
| copyTo (com.aspose.slides.IParagraph[], int) | Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IParagraph[] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


### exportToHtml {#exportToHtml}

| Name | Description |
| --- | --- |
| exportToHtml (int, int, [TextToHtmlConversionOptions](../texttohtmlconversionoptions)) | Converts specifying paragraphs to the HTML and returns it as String object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | First paragraph index int |
| paragraphsCount | int | Paragraph count int |
| options | [TextToHtmlConversionOptions](../texttohtmlconversionoptions) | Convert options ITextToHtmlConversionOptions |

 **Result:**
String


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Result:**
int


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
| getPresentation () | Returns the parent presentation of a paragraphs collection. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a paragraphs collection. Read-only BaseSlide. |

 **Result:**
[Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide)


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. |

 **Result:**
[Paragraph](../paragraph)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Paragraph](../paragraph)) | Determines the index of a specific item in the List. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | The object to locate in the List. |

 **Result:**
int


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert (int, [Paragraph](../paragraph)) | Inserts a Paragraph into the collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Paragraph should be inserted. |
| value | [Paragraph](../paragraph) | The Paragraph to insert. |


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert (int, [ParagraphCollection](../paragraphcollection)) | Inserts a content of ParagraphCollection into the collection at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which paragraphs should be inserted. |
| value | [ParagraphCollection](../paragraphcollection) | The paragraphs to insert. |


---


### isReadOnly {#isReadOnly}

| Name | Description |
| --- | --- |
| isReadOnly () | Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

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
| remove ([Paragraph](../paragraph)) | Removes the first occurrence of a specific object from the IGenericCollection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Paragraph](../paragraph) | The object to remove from the IGenericCollection. |

 **Result:**
boolean

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the element at the specified index of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |


---


