---
title: ShapeCollection
type: docs
weight: 0
url: /php-java/shapecollection/
---

# ShapeCollection class

 Represents a collection of a shapes.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addAudioFrameCD](/slides/php-java/shapecollection/addaudioframecd/)(float, float, float, float) | IAudioFrame | Adds an AudioFrame with CD to the end of collection. |
| [addAudioFrameEmbedded](/slides/php-java/shapecollection/addaudioframeembedded/)(float, float, float, float, InputStream) | IAudioFrame | Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list. |
| [addAudioFrameEmbedded](/slides/php-java/shapecollection/addaudioframeembedded/)(float, float, float, float, IAudio) | IAudioFrame | Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list. |
| [addAudioFrameLinked](/slides/php-java/shapecollection/addaudioframelinked/)(float, float, float, float, String) | IAudioFrame | Adds a new audio frame with linked audio file to the end of a collection. |
| [addAutoShape](/slides/php-java/shapecollection/addautoshape/)(int, float, float, float, float) | IAutoShape | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |
| [addAutoShape](/slides/php-java/shapecollection/addautoshape/)(int, float, float, float, float, boolean) | IAutoShape | Creates a new AutoShape and adds it to the end of the collection. |
| [addChart](/slides/php-java/shapecollection/addchart/)(int, float, float, float, float) | IChart | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |
| [addChart](/slides/php-java/shapecollection/addchart/)(int, float, float, float, float, boolean) | IChart | Creates a new Chart and adds it to the end of the collection. |
| [addClone](/slides/php-java/shapecollection/addclone/)(IShape, float, float, float, float) | IShape | Adds a copy of a specified shape to the end of the collection. |
| [addClone](/slides/php-java/shapecollection/addclone/)(IShape, float, float) | IShape | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |
| [addClone](/slides/php-java/shapecollection/addclone/)(IShape) | IShape | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |
| [addConnector](/slides/php-java/shapecollection/addconnector/)(int, float, float, float, float) | IConnector | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |
| [addConnector](/slides/php-java/shapecollection/addconnector/)(int, float, float, float, float, boolean) | IConnector | Creates a new Connector and adds it to the end of the collection. |
| [addGroupShape](/slides/php-java/shapecollection/addgroupshape/)() | IGroupShape | Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [addGroupShape](/slides/php-java/shapecollection/addgroupshape/)(ISvgImage, float, float, float, float) | IGroupShape | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |
| [addMathShape](/slides/php-java/shapecollection/addmathshape/)(float, float, float, float) | IAutoShape | Creates a new Autoshape tuned from default template to math content and adds it to the end of the collection. |
| [addOleObjectFrame](/slides/php-java/shapecollection/addoleobjectframe/)(float, float, float, float, IOleEmbeddedDataInfo) | IOleObjectFrame | Adds a new OLE object to the end of a collection. |
| [addOleObjectFrame](/slides/php-java/shapecollection/addoleobjectframe/)(float, float, float, float, String, String) | IOleObjectFrame | Adds a new OLE object to the end of a collection. |
| [addPictureFrame](/slides/php-java/shapecollection/addpictureframe/)(int, float, float, float, float, IPPImage) | IPictureFrame | Creates a new PictureFrame and adds it to the end of the collection. |
| [addSectionZoomFrame](/slides/php-java/shapecollection/addsectionzoomframe/)(float, float, float, float, ISection) | ISectionZoomFrame | Adds a new Section Zoom object to the end of a collection. |
| [addSectionZoomFrame](/slides/php-java/shapecollection/addsectionzoomframe/)(float, float, float, float, ISection, IPPImage) | ISectionZoomFrame | Adds a new Section Zoom object to the end of a collection with a predefined image. |
| [addSmartArt](/slides/php-java/shapecollection/addsmartart/)(float, float, float, float, int) | ISmartArt | Add SmartArt diagram. |
| [addSummaryZoomFrame](/slides/php-java/shapecollection/addsummaryzoomframe/)(float, float, float, float) | ISummaryZoomFrame | Adds a new Summary Zoom object to the end of a collection. |
| [addTable](/slides/php-java/shapecollection/addtable/)(float, float, double[], double[]) | ITable | Creates a new Table and adds it to the end of the collection. |
| [addVideoFrame](/slides/php-java/shapecollection/addvideoframe/)(float, float, float, float, String) | IVideoFrame | Adds a new video frame to the end of a collection. |
| [addVideoFrame](/slides/php-java/shapecollection/addvideoframe/)(float, float, float, float, IVideo) | IVideoFrame | Adds a new video frame to the end of a collection. |
| [addZoomFrame](/slides/php-java/shapecollection/addzoomframe/)(float, float, float, float, ISlide) | IZoomFrame | Adds a new Zoom object to the end of a collection. |
| [addZoomFrame](/slides/php-java/shapecollection/addzoomframe/)(float, float, float, float, ISlide, IPPImage) | IZoomFrame | Adds a new Zoom object to the end of a collection. |
| [clear](/slides/php-java/shapecollection/clear/)() | void | Removes all shapes from the collection. |
| [getParentGroup](/slides/php-java/shapecollection/getparentgroup/)() | IGroupShape | Returns parent GroupShape object for a shapes collection. Read-only IGroupShape. |
| [getSyncRoot](/slides/php-java/shapecollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/shapecollection/get_item/)(int) | IShape | Gets the element at the specified index. Read-only IShape. |
| [indexOf](/slides/php-java/shapecollection/indexof/)(IShape) | int | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [insertAudioFrameCD](/slides/php-java/shapecollection/insertaudioframecd/)(int, float, float, float, float) | IAudioFrame | Insert an AudioFrame with CD. |
| [insertAudioFrameEmbedded](/slides/php-java/shapecollection/insertaudioframeembedded/)(int, float, float, float, float, InputStream) | IAudioFrame | Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. |
| [insertAudioFrameEmbedded](/slides/php-java/shapecollection/insertaudioframeembedded/)(int, float, float, float, float, IAudio) | IAudioFrame | Insert an AudioFrame with embedded audio file. It uses audio file from Presentation.Audios list. |
| [insertAudioFrameLinked](/slides/php-java/shapecollection/insertaudioframelinked/)(int, float, float, float, float, String) | IAudioFrame | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [insertAutoShape](/slides/php-java/shapecollection/insertautoshape/)(int, int, float, float, float, float) | IAutoShape | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [insertAutoShape](/slides/php-java/shapecollection/insertautoshape/)(int, int, float, float, float, float, boolean) | IAutoShape | Creates a new AutoShape and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [insertChart](/slides/php-java/shapecollection/insertchart/)(int, float, float, float, float, int) | IChart | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |
| [insertChart](/slides/php-java/shapecollection/insertchart/)(int, float, float, float, float, int, boolean) | IChart | Creates a new Chart and inserts it to the specified position in the collection. |
| [insertClone](/slides/php-java/shapecollection/insertclone/)(int, IShape, float, float, float, float) | IShape | Inserts a copy of a specified shape to specified position of the collection. |
| [insertClone](/slides/php-java/shapecollection/insertclone/)(int, IShape, float, float) | IShape | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |
| [insertClone](/slides/php-java/shapecollection/insertclone/)(int, IShape) | IShape | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |
| [insertConnector](/slides/php-java/shapecollection/insertconnector/)(int, int, float, float, float, float) | IConnector | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. |
| [insertConnector](/slides/php-java/shapecollection/insertconnector/)(int, int, float, float, float, float, boolean) | IConnector | Creates a new Connector and inserts it to the collection at the specified index. |
| [insertGroupShape](/slides/php-java/shapecollection/insertgroupshape/)(int) | IGroupShape | Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [insertOleObjectFrame](/slides/php-java/shapecollection/insertoleobjectframe/)(int, float, float, float, float, IOleEmbeddedDataInfo) | IOleObjectFrame | Creates a new OLE object and inserts it to a collection at the specified index. |
| [insertOleObjectFrame](/slides/php-java/shapecollection/insertoleobjectframe/)(int, float, float, float, float, String, String) | IOleObjectFrame | Creates a new OLE object and inserts it to a collection at the specified index. |
| [insertPictureFrame](/slides/php-java/shapecollection/insertpictureframe/)(int, int, float, float, float, float, IPPImage) | IPictureFrame | Creates a new PictureFrame and inserts it to the collection at the specified index. |
| [insertSectionZoomFrame](/slides/php-java/shapecollection/insertsectionzoomframe/)(int, float, float, float, float, ISection) | ISectionZoomFrame | Creates a new Section Zoom object and inserts into to a collection at the specified index. |
| [insertSectionZoomFrame](/slides/php-java/shapecollection/insertsectionzoomframe/)(int, float, float, float, float, ISection, IPPImage) | ISectionZoomFrame | Creates a new Section Zoom object and inserts it to a collection at the specified index. |
| [insertSummaryZoomFrame](/slides/php-java/shapecollection/insertsummaryzoomframe/)(int, float, float, float, float) | ISummaryZoomFrame | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |
| [insertTable](/slides/php-java/shapecollection/inserttable/)(int, float, float, double[], double[]) | ITable | Creates a new Table and inserts it to the collection at the specified index. |
| [insertVideoFrame](/slides/php-java/shapecollection/insertvideoframe/)(int, float, float, float, float, String) | IVideoFrame | Creates a new video frame and inserts it to a collection at the specified index. |
| [insertZoomFrame](/slides/php-java/shapecollection/insertzoomframe/)(int, float, float, float, float, ISlide) | IZoomFrame | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [insertZoomFrame](/slides/php-java/shapecollection/insertzoomframe/)(int, float, float, float, float, ISlide, IPPImage) | IZoomFrame | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [isSynchronized](/slides/php-java/shapecollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/shapecollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/shapecollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/slides/php-java/shapecollection/remove/)(IShape) | void | Removes the first occurrence of a specific shape from the collection. |
| [removeAt](/slides/php-java/shapecollection/removeat/)(int) | void | Removes the element at the specified index of the collection. |
| [reorder](/slides/php-java/shapecollection/reorder/)(int, IShape) | void | Moves a shape from the collection to the specified position. |
| [reorder](/slides/php-java/shapecollection/reorder/)(int, com.aspose.slides.IShape[]) | void | Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list. |
| [size](/slides/php-java/shapecollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
| [toArray](/slides/php-java/shapecollection/toarray/)() | IShape | Creates and returns an array with all shapse in it. |
| [toArray](/slides/php-java/shapecollection/toarray/)(int, int) | IShape | Creates and returns an array with all shapes from the specified range in it. |
