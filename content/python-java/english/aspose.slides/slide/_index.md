---
title: Slide
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/slide/
---

## Slide class

  Represents a slide in a presentation.
 
### createThemeEffective {#createThemeEffective}

| Name | Description |
| --- | --- |
| createThemeEffective () | Returns an effective theme for this slide. |

 **Result:**
ThemeEffectiveData


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([Slide](../slide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([MasterNotesSlide](../masternotesslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterNotesSlide](../masternotesslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([MasterSlide](../masterslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterSlide](../masterslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([LayoutSlide](../layoutslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [LayoutSlide](../layoutslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([MasterHandoutSlide](../masterhandoutslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [MasterHandoutSlide](../masterhandoutslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### equals {#equals}

| Name | Description |
| --- | --- |
| equals ([NotesSlide](../notesslide)) | Determines whether the two IBaseSlide instances are equal. Returning value is calculated based on slide's structure and static content. Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [NotesSlide](../notesslide) | The IBaseSlide to compare with the current IBaseSlide. |

 **Result:**
boolean


---


### findShapeByAltText {#findShapeByAltText}

| Name | Description |
| --- | --- |
| findShapeByAltText (String) | Finds first occurrence of a shape with the specified alternative text. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| altText | String | Alternative text. |

 **Result:**
[SummaryZoomSection](../summaryzoomsection), [AutoShape](../autoshape), [AudioFrame](../audioframe), [OleObjectFrame](../oleobjectframe), [SummaryZoomFrame](../summaryzoomframe), [ZoomFrame](../zoomframe), [GraphicalObject](../graphicalobject), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [GeometryShape](../geometryshape), [SmartArtShape](../smartartshape), [SmartArt](../smartart), [Ink](../ink), [Chart](../chart), [GroupShape](../groupshape), [Table](../table), [SectionZoomFrame](../sectionzoomframe), [Shape](../shape), [LegacyDiagram](../legacydiagram), [Connector](../connector)


---


### getBackground {#getBackground}

| Name | Description |
| --- | --- |
| getBackground () | Returns slide's background. Read-only IBackground. |

 **Result:**
[Background](../background)


---


### getControls {#getControls}

| Name | Description |
| --- | --- |
| getControls () | Returns the collection of ActiveX controls on a slide. Read-only IControlCollection. |

 **Result:**
[ControlCollection](../controlcollection)


---


### getCustomData {#getCustomData}

| Name | Description |
| --- | --- |
| getCustomData () | Returns the slide's custom data. Read-only ICustomData. |

 **Result:**
[CustomData](../customdata)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| Name | Description |
| --- | --- |
| getHeaderFooterManager () | Returns HeaderFooter manager of the slide. Read-only ISlideHeaderFooterManager. |

 **Result:**
[SlideHeaderFooterManager](../slideheaderfootermanager)


---


### getHidden {#getHidden}

| Name | Description |
| --- | --- |
| getHidden () | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |

 **Result:**
boolean


---


### getHyperlinkQueries {#getHyperlinkQueries}

| Name | Description |
| --- | --- |
| getHyperlinkQueries () | Provides easy access to contained hyperlinks. Read-only IHyperlinkQueries. |

 **Result:**
[HyperlinkQueries](../hyperlinkqueries)


---


### getLayoutSlide {#getLayoutSlide}

| Name | Description |
| --- | --- |
| getLayoutSlide () | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |

 **Result:**
[LayoutSlide](../layoutslide)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName () | Returns or sets the name of a slide. Read/write String. |

 **Result:**
String


---


### getNotesSlideManager {#getNotesSlideManager}

| Name | Description |
| --- | --- |
| getNotesSlideManager () | Allow to access notes slide, add and remove it. Read-only INotesSlideManager. |

 **Result:**
[NotesSlideManager](../notesslidemanager)


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
| getPresentation () | Returns IPresentation interface. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getShapes {#getShapes}

| Name | Description |
| --- | --- |
| getShapes () | Returns the shapes of a slide. Read-only IShapeCollection. |

 **Result:**
[ShapeCollection](../shapecollection)


---


### getShowMasterShapes {#getShowMasterShapes}

| Name | Description |
| --- | --- |
| getShowMasterShapes () | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |

 **Result:**
boolean


---


### getShowMasterShapes {#getShowMasterShapes}

| Name | Description |
| --- | --- |
| getShowMasterShapes () | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Result:**
boolean

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set true for master slide. |


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () |  |

 **Result:**
[Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide)


---


### getSlideComments {#getSlideComments}

| Name | Description |
| --- | --- |
| getSlideComments ([CommentAuthor](../commentauthor)) | Returns all slide comments added by specific author. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | Author of comments to find or null to return all comments. |

 **Result:**
[Comment](../comment), [ModernComment](../moderncomment)


---


### getSlideId {#getSlideId}

| Name | Description |
| --- | --- |
| getSlideId () | Returns the ID of a slide. Read-only long. |

 **Result:**
long


---


### getSlideNumber {#getSlideNumber}

| Name | Description |
| --- | --- |
| getSlideNumber () | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |

 **Result:**
int


---


### getSlideShowTransition {#getSlideShowTransition}

| Name | Description |
| --- | --- |
| getSlideShowTransition () | Returns the Transition object which contains information about how the specified slide advances during a slide show. Read-only ISlideShowTransition. |

 **Result:**
[SlideShowTransition](../slideshowtransition)


---


### getThemeManager {#getThemeManager}

| Name | Description |
| --- | --- |
| getThemeManager () | Returns the overriding theme manager. Read-only IOverrideThemeManager. |

 **Result:**
[LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager), [SlideThemeManager](../slidethememanager)


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail (float, float) | Returns a Thumbnail Bitmap object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Result:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail () | Returns a Thumbnail Image object (20% of real size). |

 **Result:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail (Dimension) | Returns a Thumbnail Bitmap object with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| imageSize | Dimension | Size of the image to create. |

 **Result:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail ([TiffOptions](../tiffoptions)) | Returns a Thumbnail tiff BufferedImage object with specified parameters. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../tiffoptions) | Tiff options. |

 **Result:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull. |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | Returns a Thumbnail BufferedImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |

 **Result:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), float, float) | Returns a Thumbnail BufferedImage object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Result:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Dimension) | Returns a Thumbnail BufferedImage object with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | Dimension | Size of the image to create. |

 **Result:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail ([RenderingOptions](../renderingoptions)) | Returns a Thumbnail BufferedImage object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |

 **Result:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail ([RenderingOptions](../renderingoptions), float, float) | Returns a Thumbnail BufferedImage object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

 **Result:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail ([RenderingOptions](../renderingoptions), Dimension) | Returns a Thumbnail BufferedImage object with specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| imageSize | Dimension | Size of the image to create. |

 **Result:**
BufferedImage

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when options.NotesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### getTimeline {#getTimeline}

| Name | Description |
| --- | --- |
| getTimeline () | Returns animation timeline object. Read-only IAnimationTimeLine. |

 **Result:**
[AnimationTimeLine](../animationtimeline)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting in all paragraphs in all acceptable shapes. |


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting in all paragraphs all acceptable shapes. |


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting ([ShapeCollection](../shapecollection)) | Joins runs with same formatting in all paragraphs in all acceptable shapes. |


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Removes slide from presentation. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if slide is already removed from presentation. |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Graphics2D, int, int) | Renders certain slide to a Graphics object using specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | Graphics2D | The object where to render to. |
| width | int | The maximum width (in pixels) that can be occupied by the rendered slide. |
| height | int | The maximum height (in pixels) that can be occupied by the rendered slide. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Graphics2D, float) | Renders certain slide to a Graphics object using specified scale. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | Graphics2D | The object where to render to. |
| scale | float | The scale for rendering the slide (1.0 is 100%). |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), Graphics2D) | Renders certain slide to a Graphics object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [NotesCommentsLayoutingOptions](../notescommentslayoutingoptions) | Options for notes and comments layouting. |
| graphics | Graphics2D | The object where to render to. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics ([RenderingOptions](../renderingoptions), Graphics2D) | Renders certain slide to a Graphics object. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics ([RenderingOptions](../renderingoptions), Graphics2D, float, float) | Renders certain slide to a Graphics object with custom scaling. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |
| scaleX | float | The scale for rendering the slide (1.0 is 100%) in the x-axis direction. |
| scaleY | float | The scale for rendering the slide (1.0 is 100%) in the y-axis direction. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### renderToGraphics {#renderToGraphics}

| Name | Description |
| --- | --- |
| renderToGraphics ([RenderingOptions](../renderingoptions), Graphics2D, Dimension) | Renders certain slide to a Graphics object using specified size. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Rendering options. |
| graphics | Graphics2D | The object where to render to. |
| renderingSize | Dimension | The maximum dimensions (in pixels) that can be occupied by the rendered slide. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Thrown when notesCommentsLayouting.NotesPosition takes the value NotesPositions.BottomFull |


---


### reset {#reset}

| Name | Description |
| --- | --- |
| reset () | Resets position, size and formatting of every shape that has a prototype on LayoutSlide. |


---


### setHidden {#setHidden}

| Name | Description |
| --- | --- |
| setHidden (boolean) | Determines whether the specified slide is hidden during a slide show. Read/write boolean. |


---


### setLayoutSlide {#setLayoutSlide}

| Name | Description |
| --- | --- |
| setLayoutSlide ([LayoutSlide](../layoutslide)) | Returns or sets the layout slide for the current slide. Read/write ILayoutSlide. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName (String) | Returns or sets the name of a slide. Read/write String. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Specifies if shapes on the master slide should be shown on slides or not. Read/write boolean. |


---


### setShowMasterShapes {#setShowMasterShapes}

| Name | Description |
| --- | --- |
| setShowMasterShapes (boolean) | Specifies if shapes on the master slide should be shown on slides or not. For master slide itself this property always returns false. Read/write boolean. |

 **Error**

| Error | Condition |
| --- | --- |
 | NotSupportedException | Thrown if set true for master slide. |


---


### setSlideNumber {#setSlideNumber}

| Name | Description |
| --- | --- |
| setSlideNumber (int) | Returns a number of slide. Index of slide in ( Presentation#getSlides) collection is always equal to SlideNumber - Presentation.FirstSlideNumber. Read/write int. |


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes  () | Saves content of slide as SVG file. |


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes  ([SVGOptions](../svgoptions)) | Saves content of slide as SVG file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgOptions | [SVGOptions](../svgoptions) | SVG generation options |


---


