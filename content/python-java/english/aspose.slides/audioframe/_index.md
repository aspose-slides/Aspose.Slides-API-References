---
title: AudioFrame
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/audioframe/
---

## AudioFrame class

  Represents an audio clip on a slide.
 
### addPlaceholder {#addPlaceholder}

| Name | Description |
| --- | --- |
| addPlaceholder ([Placeholder](../placeholder)) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [Placeholder](../placeholder) | Placeholder to copy content from. |

 **Result:**
[Placeholder](../placeholder)


---


### createShapeElements {#createShapeElements}

| Name | Description |
| --- | --- |
| createShapeElements () | Creates and returns array of shape's elements. |

 **Result:**
[ShapeElement](../shapeelement)


---


### getAdjustments {#getAdjustments}

| Name | Description |
| --- | --- |
| getAdjustments () | Returns a collection of shape's adjustment values. Read-only IAdjustValueCollection. |

 **Result:**
[AdjustValueCollection](../adjustvaluecollection)


---


### getAlternativeText {#getAlternativeText}

| Name | Description |
| --- | --- |
| getAlternativeText () | Returns or sets the alternative text associated with a shape. Read/write String. |

 **Result:**
String


---


### getAlternativeTextTitle {#getAlternativeTextTitle}

| Name | Description |
| --- | --- |
| getAlternativeTextTitle () | Returns or sets the title of alternative text associated with a shape. Read/write String. |

 **Result:**
String


---


### getAudioCdEndTrack {#getAudioCdEndTrack}

| Name | Description |
| --- | --- |
| getAudioCdEndTrack () | Returns or sets a last track index Read/write int. |

 **Result:**
int


---


### getAudioCdEndTrackTime {#getAudioCdEndTrackTime}

| Name | Description |
| --- | --- |
| getAudioCdEndTrackTime () | Returns or sets a last track time. Read/write int. |

 **Result:**
int


---


### getAudioCdStartTrack {#getAudioCdStartTrack}

| Name | Description |
| --- | --- |
| getAudioCdStartTrack () | Returns or sets a start track index. Read/write int. |

 **Result:**
int


---


### getAudioCdStartTrackTime {#getAudioCdStartTrackTime}

| Name | Description |
| --- | --- |
| getAudioCdStartTrackTime () | Returns or sets a start track time. Read/write int. |

 **Result:**
int


---


### getBasePlaceholder {#getBasePlaceholder}

| Name | Description |
| --- | --- |
| getBasePlaceholder () | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |

 **Result:**
[SummaryZoomSection](../summaryzoomsection), [AutoShape](../autoshape), [AudioFrame](../audioframe), [OleObjectFrame](../oleobjectframe), [SummaryZoomFrame](../summaryzoomframe), [ZoomFrame](../zoomframe), [GraphicalObject](../graphicalobject), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [GeometryShape](../geometryshape), [SmartArtShape](../smartartshape), [SmartArt](../smartart), [Ink](../ink), [Chart](../chart), [GroupShape](../groupshape), [Table](../table), [SectionZoomFrame](../sectionzoomframe), [Shape](../shape), [LegacyDiagram](../legacydiagram), [Connector](../connector)


---


### getBlackWhiteMode {#getBlackWhiteMode}

| Name | Description |
| --- | --- |
| getBlackWhiteMode () | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |

 **Result:**
byte


---


### getConnectionSiteCount {#getConnectionSiteCount}

| Name | Description |
| --- | --- |
| getConnectionSiteCount () | Returns the number of connection sites on the shape. Read-only int. |

 **Result:**
int


---


### getCustomData {#getCustomData}

| Name | Description |
| --- | --- |
| getCustomData () | Returns the shape's custom data. Read-only ICustomData. |

 **Result:**
[CustomData](../customdata)


---


### getEffectFormat {#getEffectFormat}

| Name | Description |
| --- | --- |
| getEffectFormat () | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only IEffectFormat. |

 **Result:**
[EffectFormat](../effectformat)


---


### getEmbedded {#getEmbedded}

| Name | Description |
| --- | --- |
| getEmbedded () | Determines whether a sound is embedded to a presentation. Read-only boolean. |

 **Result:**
boolean


---


### getEmbeddedAudio {#getEmbeddedAudio}

| Name | Description |
| --- | --- |
| getEmbeddedAudio () | Returns or sets embedded audio object. Read/write IAudio. |

 **Result:**
[Audio](../audio)


---


### getFillFormat {#getFillFormat}

| Name | Description |
| --- | --- |
| getFillFormat () | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |

 **Result:**
[FillFormat](../fillformat)


---


### getFrame {#getFrame}

| Name | Description |
| --- | --- |
| getFrame () | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |

 **Result:**
[ShapeFrame](../shapeframe)


---


### getGeometryPaths {#getGeometryPaths}

| Name | Description |
| --- | --- |
| getGeometryPaths () | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |

 **Result:**
[GeometryPath](../geometrypath)


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getHidden {#getHidden}

| Name | Description |
| --- | --- |
| getHidden () | Determines whether the shape is hidden. Read/write boolean. |

 **Result:**
boolean


---


### getHideAtShowing {#getHideAtShowing}

| Name | Description |
| --- | --- |
| getHideAtShowing () | Determines whether an AudioFrame is hidden. Read/write boolean. |

 **Result:**
boolean


---


### getHyperlinkClick {#getHyperlinkClick}

| Name | Description |
| --- | --- |
| getHyperlinkClick () | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |

 **Result:**
[Hyperlink](../hyperlink)


---


### getHyperlinkManager {#getHyperlinkManager}

| Name | Description |
| --- | --- |
| getHyperlinkManager () | Returns the hyperlink manager. Read-only IHyperlinkManager. |

 **Result:**
[HyperlinkManager](../hyperlinkmanager)


---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| getHyperlinkMouseOver () | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |

 **Result:**
[Hyperlink](../hyperlink)


---


### getLineFormat {#getLineFormat}

| Name | Description |
| --- | --- |
| getLineFormat () | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only ILineFormat. |

 **Result:**
[LineFormat](../lineformat)


---


### getLinkPathLong {#getLinkPathLong}

| Name | Description |
| --- | --- |
| getLinkPathLong () | Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String. |

 **Result:**
String


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName () | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |

 **Result:**
String


---


### getOfficeInteropShapeId {#getOfficeInteropShapeId}

| Name | Description |
| --- | --- |
| getOfficeInteropShapeId () | Gets unique shape identifier in slide scope. Read-only long. See also ( #getUniqueId) for getting unique shape identifier in presentation scope. |

 **Result:**
long


---


### getParentGroup {#getParentGroup}

| Name | Description |
| --- | --- |
| getParentGroup () | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only IGroupShape. Property ( #isGrouped) determines whether the shape is grouped. |

 **Result:**
[GroupShape](../groupshape)


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate () |  |

 **Result:**
DisplayUnitLabel, [ChartThemeManager](../chartthememanager), [RotationEffect](../rotationeffect), [ChartTitle](../charttitle), [MathBar](../mathbar), [GlobalLayoutSlideCollection](../globallayoutslidecollection), [ChartDataWorksheet](../chartdataworksheet), [SoftEdge](../softedge), [Audio](../audio), [ChartWall](../chartwall), [BaseOverrideThemeManager](../baseoverridethememanager), [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager), ThemeableLineFormat, [UpDownBarsManager](../updownbarsmanager), [MathMatrix](../mathmatrix), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement), [Format](../format), [GradientFormat](../gradientformat), [ThreeDFormat](../threedformat), [Slide](../slide), [TabCollection](../tabcollection), [ColorScheme](../colorscheme), [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [SlideHeaderFooterManager](../slideheaderfootermanager), [CommentAuthor](../commentauthor), [CellFormat](../cellformat), [SlideShowTransition](../slideshowtransition), [CustomXmlPartCollection](../customxmlpartcollection), [SlideCollection](../slidecollection), [ViewProperties](../viewproperties), [Shape](../shape), [ExtraColorScheme](../extracolorscheme), [Luminance](../luminance), [MasterThemeManager](../masterthememanager), [DataLabel](../datalabel), [GradientStop](../gradientstop), [CellCollection](../cellcollection), [MathematicalText](../mathematicaltext), [Row](../row), MasterNotesSlideManager, [MathNaryOperator](../mathnaryoperator), [BaseThemeManager](../basethememanager), ThemeableFillFormat, [RowCollection](../rowcollection), [GeometryShape](../geometryshape), TableStyle, [LightRig](../lightrig), [ChartPlotArea](../chartplotarea), [BulletFormat](../bulletformat), [MathSuperscriptElement](../mathsuperscriptelement), [VideoCollection](../videocollection), [Table](../table), [ChartDataPointLevel](../chartdatapointlevel), PresetTextShape, [MasterTheme](../mastertheme), [SectionSlideCollection](../sectionslidecollection), [OleObjectFrame](../oleobjectframe), [ChartData](../chartdata), [ChartDataPointCollection](../chartdatapointcollection), [ChartDataWorkbook](../chartdataworkbook), [NotesSlideHeaderFooterManager](../notesslideheaderfootermanager), [PresetShadow](../presetshadow), AggregatedDataPoint, [SketchFormat](../sketchformat), [MathParagraph](../mathparagraph), [SmartArt](../smartart), [AudioCollection](../audiocollection), [AxisFormat](../axisformat), [CommentCollection](../commentcollection), [ParagraphFormat](../paragraphformat), [ChartDataWorksheetCollection](../chartdataworksheetcollection), FormatOverrides, [TextStyle](../textstyle), [FillFormatCollection](../fillformatcollection), [NotesSlideManager](../notesslidemanager), [ColumnFormat](../columnformat), [Section](../section), [MathBlock](../mathblock), [TableFormat](../tableformat), [StringChartValue](../stringchartvalue), [Reflection](../reflection), [Ink](../ink), [Trendline](../trendline), [LayoutSlideCollection](../layoutslidecollection), [LineFormat](../lineformat), [BasePortionFormat](../baseportionformat), [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager), [MasterHandoutSlide](../masterhandoutslide), [DataLabelFormat](../datalabelformat), [Timing](../timing), [MathAccent](../mathaccent), [LegacyDiagram](../legacydiagram), FormatOverride, [ChartSeriesGroup](../chartseriesgroup), [Blur](../blur), [MathSubscriptElement](../mathsubscriptelement), [NotesSlideThemeManager](../notesslidethememanager), [Axis](../axis), [AlphaBiLevel](../alphabilevel), [Paragraph](../paragraph), [MathGroupingCharacter](../mathgroupingcharacter), [MathLimit](../mathlimit), TableBackgroundStyle, [SetEffect](../seteffect), [StringOrDoubleChartValue](../stringordoublechartvalue), [Chart](../chart), [PictureFillFormat](../picturefillformat), [HyperlinkQueries](../hyperlinkqueries), [ZoomFrame](../zoomframe), [BaseScript](../basescript), [MasterNotesSlideHeaderFooterManager](../masternotesslideheaderfootermanager), [Rotation3D](../rotation3d), [FontScheme](../fontscheme), [PictureFrame](../pictureframe), [Effect](../effect), [OverrideTheme](../overridetheme), [ColorChange](../colorchange), [ColumnCollection](../columncollection), [TrendlineCollection](../trendlinecollection), [EffectStyleCollection](../effectstylecollection), [AlphaInverse](../alphainverse), [ErrorBarsCustomValues](../errorbarscustomvalues), PlaceholderCollection, [FillFormat](../fillformat), [ModernComment](../moderncomment), [ColorFormat](../colorformat), [AdjustValueCollection](../adjustvaluecollection), [MasterNotesSlide](../masternotesslide), [CommentAuthorCollection](../commentauthorcollection), [ImageTransformOperation](../imagetransformoperation), AggregatedDataPointCollection, [LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager), [Background](../background), [Control](../control), [GrayScale](../grayscale), [LineFillFormat](../linefillformat), [AnimationTimeLine](../animationtimeline), [SmartArtShape](../smartartshape), [Tab](../tab), [MotionEffect](../motioneffect), [GradientStopCollection](../gradientstopcollection), [ChartCellCollection](../chartcellcollection), [ColorEffect](../coloreffect), [ChartPortionFormat](../chartportionformat), [MathBox](../mathbox), [DigitalSignatureCollection](../digitalsignaturecollection), [AutoShape](../autoshape), [NotesSlide](../notesslide), [SectionCollection](../sectioncollection), [ScaleEffect](../scaleeffect), [MathFunction](../mathfunction), [ChartSeries](../chartseries), [Connector](../connector), [Picture](../picture), [CommandEffect](../commandeffect), [SlideThemeManager](../slidethememanager), [DoubleChartValue](../doublechartvalue), [Column](../column), [EffectStyle](../effectstyle), [SlideSize](../slidesize), [CustomData](../customdata), [SummaryZoomSection](../summaryzoomsection), [HSL](../hsl), [Tint](../tint), [DataLabelCollection](../datalabelcollection), [ImageTransformOperationCollection](../imagetransformoperationcollection), LayoutTree, [GraphicalObject](../graphicalobject), [Field](../field), [FormatScheme](../formatscheme), [Legend](../legend), [AlphaCeiling](../alphaceiling), [Hyperlink](../hyperlink), [Cell](../cell), [Portion](../portion), [BiLevel](../bilevel), [MathElementBase](../mathelementbase), [MasterHandoutSlideHeaderFooterManager](../masterhandoutslideheaderfootermanager), [MathFraction](../mathfraction), [DataTable](../datatable), [HyperlinkManager](../hyperlinkmanager), [BaseHeaderFooterManager](../baseheaderfootermanager), [ChartSeriesCollection](../chartseriescollection), [ChartTextFormat](../charttextformat), [LayoutSlide](../layoutslide), [ShapeBevel](../shapebevel), [ShapeStyle](../shapestyle), [Camera](../camera), ThemeableTableFormat, [RowFormat](../rowformat), [ChartCategoryCollection](../chartcategorycollection), ChartSeriesGroupCollection, [LayoutSlideThemeManager](../layoutslidethememanager), [ControlCollection](../controlcollection), [InnerShadow](../innershadow), [PortionFormat](../portionformat), [AlphaReplace](../alphareplace), [MasterLayoutSlideCollection](../masterlayoutslidecollection), [MathPortion](../mathportion), [Duotone](../duotone), [Backdrop3DScene](../backdrop3dscene), MasterHandoutSlideManager, [Video](../video), [AlphaModulate](../alphamodulate), [Behavior](../behavior), [ImageCollection](../imagecollection), BaseStyles, [ChartDataPointLevelsManager](../chartdatapointlevelsmanager), [PVIObject](../pviobject), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [Comment](../comment), [PatternFormat](../patternformat), [ChartCategory](../chartcategory), [PortionCollection](../portioncollection), [ErrorBarsFormat](../errorbarsformat), [ColorReplace](../colorreplace), ThemeableCellFormat, [GroupShape](../groupshape), [PresentationHeaderFooterManager](../presentationheaderfootermanager), MathRunElement, [MasterSlideCollection](../masterslidecollection), [TextFrameFormat](../textframeformat), [SectionZoomFrame](../sectionzoomframe), [DomObject](../domobject), [AlphaFloor](../alphafloor), [SummaryZoomSectionCollection](../summaryzoomsectioncollection), [AudioFrame](../audioframe), [EffectFormat](../effectformat), [ShapeCollection](../shapecollection), [VideoFrame](../videoframe), [Theme](../theme), [ChartDataPoint](../chartdatapoint), [AxesManager](../axesmanager), [MathRadical](../mathradical), [FillOverlay](../filloverlay), [FilterEffect](../filtereffect), [TextFrame](../textframe), [Marker](../marker), [ParagraphCollection](../paragraphcollection), [Presentation](../presentation), [MathArray](../matharray), [ZoomObject](../zoomobject), [LineFormatCollection](../lineformatcollection), [MathDelimiter](../mathdelimiter), TableCellTextStyle, [OuterShadow](../outershadow), [ExtraColorSchemeCollection](../extracolorschemecollection), [MathBorderBox](../mathborderbox), [Glow](../glow), [BaseChartValue](../basechartvalue), [SummaryZoomFrame](../summaryzoomframe), [LegendEntryProperties](../legendentryproperties), TableStyleCollection, TablePartStyle, [AlphaModulateFixed](../alphamodulatefixed), ThemeableEffectFormat, [MasterSlideHeaderFooterManager](../masterslideheaderfootermanager), [ChartLinesFormat](../chartlinesformat)


---


### getPictureFormat {#getPictureFormat}

| Name | Description |
| --- | --- |
| getPictureFormat () | Returns the PictureFillFormat object for a picture frame. Read-only IPictureFillFormat. |

 **Result:**
[PictureFillFormat](../picturefillformat)


---


### getPictureFrameLock {#getPictureFrameLock}

| Name | Description |
| --- | --- |
| getPictureFrameLock () | Returns shape's locks. Read-only IPictureFrameLock. |

 **Result:**
[PictureFrameLock](../pictureframelock)


---


### getPlaceholder {#getPlaceholder}

| Name | Description |
| --- | --- |
| getPlaceholder () | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only IPlaceholder. |

 **Result:**
[Placeholder](../placeholder)


---


### getPlayAcrossSlides {#getPlayAcrossSlides}

| Name | Description |
| --- | --- |
| getPlayAcrossSlides () | Determines whether audio is playing across the slides. Read/write boolean. |

 **Result:**
boolean


---


### getPlayLoopMode {#getPlayLoopMode}

| Name | Description |
| --- | --- |
| getPlayLoopMode () | Determines whether an audio is looped. Read/write boolean. |

 **Result:**
boolean


---


### getPlayMode {#getPlayMode}

| Name | Description |
| --- | --- |
| getPlayMode () | Returns or sets the audio play mode. Read/write AudioPlayModePreset. |

 **Result:**
int


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a slide. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getRawFrame {#getRawFrame}

| Name | Description |
| --- | --- |
| getRawFrame () | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |

 **Result:**
[ShapeFrame](../shapeframe)


---


### getRelativeScaleHeight {#getRelativeScaleHeight}

| Name | Description |
| --- | --- |
| getRelativeScaleHeight () | Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write float. |

 **Result:**
float


---


### getRelativeScaleWidth {#getRelativeScaleWidth}

| Name | Description |
| --- | --- |
| getRelativeScaleWidth () | Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write float. |

 **Result:**
float


---


### getRewindAudio {#getRewindAudio}

| Name | Description |
| --- | --- |
| getRewindAudio () | Determines whether audio is automatically rewinded to start after playing. Read/write boolean. |

 **Result:**
boolean


---


### getRotation {#getRotation}

| Name | Description |
| --- | --- |
| getRotation () | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getShapeLock {#getShapeLock}

| Name | Description |
| --- | --- |
| getShapeLock () | Returns shape's locks. Read-only IBaseShapeLock. |

 **Result:**
[BaseShapeLock](../baseshapelock), [PictureFrameLock](../pictureframelock), [AutoShapeLock](../autoshapelock), [GraphicalObjectLock](../graphicalobjectlock), [GroupShapeLock](../groupshapelock), [ConnectorLock](../connectorlock)


---


### getShapeStyle {#getShapeStyle}

| Name | Description |
| --- | --- |
| getShapeStyle () | Returns shape's style object. Read-only IShapeStyle. |

 **Result:**
[ShapeStyle](../shapestyle)


---


### getShapeType {#getShapeType}

| Name | Description |
| --- | --- |
| getShapeType () | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write ShapeType. |

 **Result:**
int


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a shape. Read-only IBaseSlide. |

 **Result:**
[Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide)


---


### getThreeDFormat {#getThreeDFormat}

| Name | Description |
| --- | --- |
| getThreeDFormat () | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only IThreeDFormat. |

 **Result:**
[ThreeDFormat](../threedformat)


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail () | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |

 **Result:**
BufferedImage


---


### getThumbnail {#getThumbnail}

| Name | Description |
| --- | --- |
| getThumbnail (int, float, float) | Returns shape thumbnail. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

 **Result:**
BufferedImage


---


### getUniqueId {#getUniqueId}

| Name | Description |
| --- | --- |
| getUniqueId () | Gets unique shape identifier in presentation scope. Read-only long. See also ( #getOfficeInteropShapeId) for getting unique shape identifier in slide scope. |

 **Result:**
long


---


### getVolume {#getVolume}

| Name | Description |
| --- | --- |
| getVolume () | Returns or sets the audio volume. Read/write AudioVolumeMode. |

 **Result:**
int


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getX {#getX}

| Name | Description |
| --- | --- |
| getX () | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getY {#getY}

| Name | Description |
| --- | --- |
| getY () | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |

 **Result:**
float


---


### getZOrderPosition {#getZOrderPosition}

| Name | Description |
| --- | --- |
| getZOrderPosition () | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int. |

 **Result:**
int


---


### isGrouped {#isGrouped}

| Name | Description |
| --- | --- |
| isGrouped () | Determines whether the shape is grouped. Read-only boolean. Property ( #getParentGroup) returns parent GroupShape object if shape is grouped. |

 **Result:**
boolean


---


### isTextHolder {#isTextHolder}

| Name | Description |
| --- | --- |
| isTextHolder () | Determines whether the shape is TextHolder_PPT. Read-only boolean. |

 **Result:**
boolean


---


### removePlaceholder {#removePlaceholder}

| Name | Description |
| --- | --- |
| removePlaceholder () | Defines that this shape isn't a placeholder. |


---


### setAlternativeText {#setAlternativeText}

| Name | Description |
| --- | --- |
| setAlternativeText (String) | Returns or sets the alternative text associated with a shape. Read/write String. |


---


### setAlternativeTextTitle {#setAlternativeTextTitle}

| Name | Description |
| --- | --- |
| setAlternativeTextTitle (String) | Returns or sets the title of alternative text associated with a shape. Read/write String. |


---


### setAudioCdEndTrack {#setAudioCdEndTrack}

| Name | Description |
| --- | --- |
| setAudioCdEndTrack (int) | Returns or sets a last track index Read/write int. |


---


### setAudioCdEndTrackTime {#setAudioCdEndTrackTime}

| Name | Description |
| --- | --- |
| setAudioCdEndTrackTime (int) | Returns or sets a last track time. Read/write int. |


---


### setAudioCdStartTrack {#setAudioCdStartTrack}

| Name | Description |
| --- | --- |
| setAudioCdStartTrack (int) | Returns or sets a start track index. Read/write int. |


---


### setAudioCdStartTrackTime {#setAudioCdStartTrackTime}

| Name | Description |
| --- | --- |
| setAudioCdStartTrackTime (int) | Returns or sets a start track time. Read/write int. |


---


### setBlackWhiteMode {#setBlackWhiteMode}

| Name | Description |
| --- | --- |
| setBlackWhiteMode (byte) | Property specifies how a shape will render in black-and-white display mode.. Read/write BlackWhiteMode. |


---


### setEmbeddedAudio {#setEmbeddedAudio}

| Name | Description |
| --- | --- |
| setEmbeddedAudio ([Audio](../audio)) | Returns or sets embedded audio object. Read/write IAudio. |


---


### setFrame {#setFrame}

| Name | Description |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | Returns or sets the shape frame's properties. Read/write IShapeFrame. Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties. |


---


### setGeometryPath {#setGeometryPath}

| Name | Description |
| --- | --- |
| setGeometryPath ([GeometryPath](../geometrypath)) | Updates shape geometry from IGeometryPath object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType( #getShapeType/ #setShapeType(int))) to ShapeType#Custom. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) | Geometry path |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Empty path found |


---


### setGeometryPaths {#setGeometryPaths}

| Name | Description |
| --- | --- |
| setGeometryPaths (com.aspose.slides.IGeometryPath[]) | Updates shape geometry from array of IGeometryPath. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType( #getShapeType/ #setShapeType(int))) to ShapeType#Custom. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| geometryPaths | com.aspose.slides.IGeometryPath[] | Array geometry paths |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Empty path |


---


### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight (float) | Returns or sets the height of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setHidden {#setHidden}

| Name | Description |
| --- | --- |
| setHidden (boolean) | Determines whether the shape is hidden. Read/write boolean. |


---


### setHideAtShowing {#setHideAtShowing}

| Name | Description |
| --- | --- |
| setHideAtShowing (boolean) | Determines whether an AudioFrame is hidden. Read/write boolean. |


---


### setHyperlinkClick {#setHyperlinkClick}

| Name | Description |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |


---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| Name | Description |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |


---


### setLinkPathLong {#setLinkPathLong}

| Name | Description |
| --- | --- |
| setLinkPathLong (String) | Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String. |


---


### setName {#setName}

| Name | Description |
| --- | --- |
| setName (String) | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |


---


### setPlayAcrossSlides {#setPlayAcrossSlides}

| Name | Description |
| --- | --- |
| setPlayAcrossSlides (boolean) | Determines whether audio is playing across the slides. Read/write boolean. |


---


### setPlayLoopMode {#setPlayLoopMode}

| Name | Description |
| --- | --- |
| setPlayLoopMode (boolean) | Determines whether an audio is looped. Read/write boolean. |


---


### setPlayMode {#setPlayMode}

| Name | Description |
| --- | --- |
| setPlayMode (int) | Returns or sets the audio play mode. Read/write AudioPlayModePreset. |


---


### setRawFrame {#setRawFrame}

| Name | Description |
| --- | --- |
| setRawFrame ([ShapeFrame](../shapeframe)) | Returns or sets the raw shape frame's properties. Read/write IShapeFrame. |


---


### setRelativeScaleHeight {#setRelativeScaleHeight}

| Name | Description |
| --- | --- |
| setRelativeScaleHeight (float) | Returns or sets the scale of height(relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write float. |


---


### setRelativeScaleWidth {#setRelativeScaleWidth}

| Name | Description |
| --- | --- |
| setRelativeScaleWidth (float) | Returns or sets the scale of width (relative to original picture size) of the picture frame. Value 1.0 corresponds to 100%. Read/write float. |


---


### setRewindAudio {#setRewindAudio}

| Name | Description |
| --- | --- |
| setRewindAudio (boolean) | Determines whether audio is automatically rewinded to start after playing. Read/write boolean. |


---


### setRotation {#setRotation}

| Name | Description |
| --- | --- |
| setRotation (float) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setShapeType {#setShapeType}

| Name | Description |
| --- | --- |
| setShapeType (int) | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write ShapeType. |


---


### setVolume {#setVolume}

| Name | Description |
| --- | --- |
| setVolume (int) | Returns or sets the audio volume. Read/write AudioVolumeMode. |


---


### setWidth {#setWidth}

| Name | Description |
| --- | --- |
| setWidth (float) | Returns or sets the width of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setX {#setX}

| Name | Description |
| --- | --- |
| setX (float) | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### setY {#setY}

| Name | Description |
| --- | --- |
| setY (float) | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write float. Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties. |


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes  () | Saves content of Shape as SVG file. |


---


### writeAsSvgToBytes  {#writeAsSvgToBytes }

| Name | Description |
| --- | --- |
| writeAsSvgToBytes  ([SVGOptions](../svgoptions)) | Saves content of Shape as SVG file. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| svgOptions | [SVGOptions](../svgoptions) | SVG generation options |


---


