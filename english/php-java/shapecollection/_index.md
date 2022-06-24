---
title: ShapeCollection
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/shapecollection/
---

## ShapeCollection class

 Represents a collection of a shapes.
 

## Methods

| Name | Description |
| --- | --- |
| [addAudioFrameCD](addaudioframecd)(float, float, float, float) | Adds an AudioFrame with CD to the end of collection. |
| [addAudioFrameEmbedded](addaudioframeembedded)(float, float, float, float, InputStream) | Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list. |
| [addAudioFrameEmbedded](addaudioframeembedded)(float, float, float, float, IAudio) | Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list. |
| [addAudioFrameLinked](addaudioframelinked)(float, float, float, float, String) | Adds a new audio frame with linked audio file to the end of a collection. |
| [addAutoShape](addautoshape)(int, float, float, float, float) | Creates a new AutoShape, tunes it from default template and adds it to the end of the collection. |
| [addAutoShape](addautoshape)(int, float, float, float, float, boolean) | Creates a new AutoShape and adds it to the end of the collection. |
| [addChart](addchart)(int, float, float, float, float) | Creates a new Chart, initialize it with sample series data and settings and adds it to the end of the collection. |
| [addChart](addchart)(int, float, float, float, float, boolean) | Creates a new Chart and adds it to the end of the collection. |
| [addClone](addclone)(IShape, float, float, float, float) | Adds a copy of a specified shape to the end of the collection. |
| [addClone](addclone)(IShape, float, float) | Adds a copy of a specified shape to the end of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |
| [addClone](addclone)(IShape) | Adds a copy of a specified shape to the end of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |
| [addConnector](addconnector)(int, float, float, float, float) | Creates a new Connector, tunes it from default template and adds it to the end of the collection. |
| [addConnector](addconnector)(int, float, float, float, float, boolean) | Creates a new Connector and adds it to the end of the collection. |
| [addGroupShape](addgroupshape)() | Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [addGroupShape](addgroupshape)(ISvgImage, float, float, float, float) | Creates a new GroupShape, fills it with converted shapes from SVG and adds it to the end of the collection. |
| [addMathShape](addmathshape)(float, float, float, float) | Creates a new Autoshape tuned from default template to math content and adds it to the end of the collection. |
| [addOleObjectFrame](addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Adds a new OLE object to the end of a collection. |
| [addOleObjectFrame](addoleobjectframe)(float, float, float, float, String, String) | Adds a new OLE object to the end of a collection. |
| [addPictureFrame](addpictureframe)(int, float, float, float, float, IPPImage) | Creates a new PictureFrame and adds it to the end of the collection. |
| [addSectionZoomFrame](addsectionzoomframe)(float, float, float, float, ISection) | Adds a new Section Zoom object to the end of a collection. |
| [addSectionZoomFrame](addsectionzoomframe)(float, float, float, float, ISection, IPPImage) | Adds a new Section Zoom object to the end of a collection with a predefined image. |
| [addSmartArt](addsmartart)(float, float, float, float, int) | Add SmartArt diagram. |
| [addSummaryZoomFrame](addsummaryzoomframe)(float, float, float, float) | Adds a new Summary Zoom object to the end of a collection. |
| [addTable](addtable)(float, float, double[], double[]) | Creates a new Table and adds it to the end of the collection. |
| [addVideoFrame](addvideoframe)(float, float, float, float, String) | Adds a new video frame to the end of a collection. |
| [addVideoFrame](addvideoframe)(float, float, float, float, IVideo) | Adds a new video frame to the end of a collection. |
| [addZoomFrame](addzoomframe)(float, float, float, float, ISlide) | Adds a new Zoom object to the end of a collection. |
| [addZoomFrame](addzoomframe)(float, float, float, float, ISlide, IPPImage) | Adds a new Zoom object to the end of a collection. |
| [clear](clear)() | Removes all shapes from the collection. |
| [getParentGroup](getparentgroup)() | Returns parent GroupShape object for a shapes collection. Read-only IGroupShape. |
| [getSyncRoot](getsyncroot)() | Returns a synchronization root. Read-only Object. |
| [get_Item](get_item)(int) | Gets the element at the specified index. Read-only IShape. |
| [indexOf](indexof)(IShape) | Returns the zero-based index of the first occurrence of a shape in the collection. |
| [insertAudioFrameCD](insertaudioframecd)(int, float, float, float, float) | Insert an AudioFrame with CD. |
| [insertAudioFrameEmbedded](insertaudioframeembedded)(int, float, float, float, float, InputStream) | Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. |
| [insertAudioFrameEmbedded](insertaudioframeembedded)(int, float, float, float, float, IAudio) | Insert an AudioFrame with embedded audio file. It uses audio file from Presentation.Audios list. |
| [insertAudioFrameLinked](insertaudioframelinked)(int, float, float, float, float, String) | Creates a new audio frame with linked audio file and inserts it to a collection at the specified index. |
| [insertAutoShape](insertautoshape)(int, int, float, float, float, float) | Creates a new AutoShape, tunes it from default template and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [insertAutoShape](insertautoshape)(int, int, float, float, float, float, boolean) | Creates a new AutoShape and inserts it to the collection at the specified index. Note: the type of the shape will be determined by the shapeType parameter. |
| [insertChart](insertchart)(int, float, float, float, float, int) | Creates a new Chart, initialize it with sample series data and settings and inserts it to the specified position in the collection. |
| [insertChart](insertchart)(int, float, float, float, float, int, boolean) | Creates a new Chart and inserts it to the specified position in the collection. |
| [insertClone](insertclone)(int, IShape, float, float, float, float) | Inserts a copy of a specified shape to specified position of the collection. |
| [insertClone](insertclone)(int, IShape, float, float) | Inserts a copy of a specified shape to specified position of the collection. Width and Height of the new shape are equal to Width and Height of the source Shape. |
| [insertClone](insertclone)(int, IShape) | Inserts a copy of a specified shape to specified position of the collection. X, Y, Width and Height of the new shape are equal to X, Y, Width and Height of the source Shape. |
| [insertConnector](insertconnector)(int, int, float, float, float, float) | Creates a new Connector, tunes it from default template and inserts it to the collection at the specified index. |
| [insertConnector](insertconnector)(int, int, float, float, float, float, boolean) | Creates a new Connector and inserts it to the collection at the specified index. |
| [insertGroupShape](insertgroupshape)(int) | Creates a new GroupShape and inserts it to the collection at the specified index. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape. |
| [insertOleObjectFrame](insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [insertOleObjectFrame](insertoleobjectframe)(int, float, float, float, float, String, String) | Creates a new OLE object and inserts it to a collection at the specified index. |
| [insertPictureFrame](insertpictureframe)(int, int, float, float, float, float, IPPImage) | Creates a new PictureFrame and inserts it to the collection at the specified index. |
| [insertSectionZoomFrame](insertsectionzoomframe)(int, float, float, float, float, ISection) | Creates a new Section Zoom object and inserts into to a collection at the specified index. |
| [insertSectionZoomFrame](insertsectionzoomframe)(int, float, float, float, float, ISection, IPPImage) | Creates a new Section Zoom object and inserts it to a collection at the specified index. |
| [insertSummaryZoomFrame](insertsummaryzoomframe)(int, float, float, float, float) | Creates a new Summary Zoom object and inserts it to a collection at the specified index. |
| [insertTable](inserttable)(int, float, float, double[], double[]) | Creates a new Table and inserts it to the collection at the specified index. |
| [insertVideoFrame](insertvideoframe)(int, float, float, float, float, String) | Creates a new video frame and inserts it to a collection at the specified index. |
| [insertZoomFrame](insertzoomframe)(int, float, float, float, float, ISlide) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [insertZoomFrame](insertzoomframe)(int, float, float, float, float, ISlide, IPPImage) | Creates a new Zoom object and inserts it to a collection at the specified index. |
| [isSynchronized](issynchronized)() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
| [remove](remove)(IShape) | Removes the first occurrence of a specific shape from the collection. |
| [removeAt](removeat)(int) | Removes the element at the specified index of the collection. |
| [reorder](reorder)(int, IShape) | Moves a shape from the collection to the specified position. |
| [reorder](reorder)(int, com.aspose.slides.IShape[]) | Moves shapes from the collection to the specified position. Shapes will be placed starting from index in order they appear in list. |
| [size](size)() | Gets the number of elements actually contained in the collection. Read-only int. |
| [toArray](toarray)() | Creates and returns an array with all shapse in it. |
| [toArray](toarray)(int, int) | Creates and returns an array with all shapes from the specified range in it. |
