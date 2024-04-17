---
title: Output
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of output elements for IWebDocument.
type: docs
url: /com.aspose.slides/output/
---
**Inheritance:**
java.lang.Object
```
public final class Output
```

Represents a collection of output elements for IWebDocument.
## Methods

| Method | Description |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, Bitmap image)](#add-java.lang.String-android.graphics.Bitmap-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Adds an output element for the font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Adds an output element for the context object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| templateKey | java.lang.String | The key of the template used for context object transformation before output. |
| contextObject | TContextObject | Context object. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the context object.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Adds an output element for the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Image to output. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, Bitmap image) {#add-java.lang.String-android.graphics.Bitmap-}
```
public final IOutputFile add(String path, Bitmap image)
```


Adds an output element for the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| image | android.graphics.Bitmap | Image to output. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Adds an output element for the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| image | [IImage](../../com.aspose.slides/iimage) | Image to output. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Adds an output element for the video.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video to output. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the video.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Adds an output element for the font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font to output. |
| fontStyle | int | Font style. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the font.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Adds an output element for the text content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| textContent | java.lang.String | Content to output. |

**Returns:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the text content.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Binds resource to output file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Output file. |
| obj | java.lang.Object | Resource object. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Returns the path for a given resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Resource object. |

**Returns:**
java.lang.String - Resource path.
