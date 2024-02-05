---
title: SlideCollection
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/slidecollection/
---

## SlideCollection class

 Represents a collection of a slides.
 
### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide)) | Adds a copy of a specified slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #addClone(ISlide,ILayoutSlide) or #addClone(ISlide,IMasterSlide,boolean) for cloning slides, IGlobalLayoutSlideCollection#addClone(ILayoutSlide) or IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) for cloning layouts and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

 **Result:**
[Slide](../slide)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide), [Section](../section)) | Adds a copy of a specified slide to the end of the specified section. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| section | [Section](../section) | Section for a new slide. |

 **Result:**
[Slide](../slide)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | When section parameter contains wrong or invalid value. |


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide), [LayoutSlide](../layoutslide)) | Adds a copy of a specified slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destLayout | [LayoutSlide](../layoutslide) | Layout slide for a new slide. |

 **Result:**
[Slide](../slide)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide), [MasterSlide](../masterslide), boolean) | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destMaster | [MasterSlide](../masterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Result:**
[Slide](../slide)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


### addEmptySlide {#addEmptySlide}

| Name | Description |
| --- | --- |
| addEmptySlide ([LayoutSlide](../layoutslide)) | Adds a new empty slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| layout | [LayoutSlide](../layoutslide) | Layout for a slide. |

 **Result:**
[Slide](../slide)


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |

 **Result:**
[Slide](../slide)


---


### addFromHtmlFromBytes  {#addFromHtmlFromBytes }

| Name | Description |
| --- | --- |
| addFromHtmlFromBytes  (Bytes[], [ExternalResourceResolver](../externalresourceresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlStream | Bytes[] | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### addFromHtmlFromBytes  {#addFromHtmlFromBytes }

| Name | Description |
| --- | --- |
| addFromHtmlFromBytes  (Bytes[], [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlStream | Bytes[] | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### addFromHtmlFromBytes  {#addFromHtmlFromBytes }

| Name | Description |
| --- | --- |
| addFromHtmlFromBytes  (Bytes[]) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlStream | Bytes[] | A Stream object which will be used as a source of a HTML file. |

 **Result:**
[Slide](../slide)


---


### addFromPdf {#addFromPdf}

| Name | Description |
| --- | --- |
| addFromPdf (String) | Creates slides from the PDF document and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | A path to the PDF document |

 **Result:**
[Slide](../slide)


---


### addFromPdfFromBytes  {#addFromPdfFromBytes }

| Name | Description |
| --- | --- |
| addFromPdfFromBytes  (Bytes[]) | Creates slides from the PDF document and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pdfStream | Bytes[] | A stream which will be used as a source of the PDF document |

 **Result:**
[Slide](../slide)


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
| get_Item (int) | Gets the element at the specified index. Read-only Slide. |

 **Result:**
[Slide](../slide)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Slide](../slide)) | Returns an index of the specified slide in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | Slide to find. |

 **Result:**
int


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Slide](../slide)) | Inserts a copy of a specified slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #insertClone(int,ISlide,ILayoutSlide) or #insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

 **Result:**
[Slide](../slide)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Slide](../slide), [LayoutSlide](../layoutslide)) | Inserts a copy of a specified slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destLayout | [LayoutSlide](../layoutslide) | Layout slide for a new slide. |

 **Result:**
[Slide](../slide)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Slide](../slide), [MasterSlide](../masterslide), boolean) | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destMaster | [MasterSlide](../masterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Result:**
[Slide](../slide)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


### insertEmptySlide {#insertEmptySlide}

| Name | Description |
| --- | --- |
| insertEmptySlide (int, [LayoutSlide](../layoutslide)) | Inserts a copy of a specified slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a new slide. |
| layout | [LayoutSlide](../layoutslide) | Layout for a slide. |

 **Result:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |

 **Result:**
[Slide](../slide)


---


### insertFromHtmlFromBytes  {#insertFromHtmlFromBytes }

| Name | Description |
| --- | --- |
| insertFromHtmlFromBytes  (int, Bytes[], [ExternalResourceResolver](../externalresourceresolver),  String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | Bytes[] | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### insertFromHtmlFromBytes  {#insertFromHtmlFromBytes }

| Name | Description |
| --- | --- |
| insertFromHtmlFromBytes  (int, Bytes[], [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | Bytes[] | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### insertFromHtmlFromBytes  {#insertFromHtmlFromBytes }

| Name | Description |
| --- | --- |
| insertFromHtmlFromBytes  (int, Bytes[]) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | Bytes[] | A Stream object which will be used as a source of a HTML file. |

 **Result:**
[Slide](../slide)


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
| remove ([Slide](../slide)) | Removes the first occurrence of a specific object from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [Slide](../slide) | The slide to remove from the collection. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the element at the specified index of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | When index parameter contains wrong section number. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Slide](../slide)) | Moves slide from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| slide | [Slide](../slide) | Slide to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, com.aspose.slides.ISlide[]) | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| slides | com.aspose.slides.ISlide[] | Slides to move. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Result:**
int


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray () | Creates and returns an array with all slides in it. |

 **Result:**
[Slide](../slide)


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray (int, int) | Creates and returns an array with all slides from the specified range in it. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first slide to add. |
| count | int | A number of slides to add. |

 **Result:**
[Slide](../slide)


---


