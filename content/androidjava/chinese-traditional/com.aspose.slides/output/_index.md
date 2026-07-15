---
title: Output
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示 IWebDocument 的輸出元素集合。
type: docs
url: /zh-hant/com.aspose.slides/output/
---
**繼承：**
java.lang.Object
```
public final class Output
```

表示 IWebDocument 的輸出元素集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creates and adds an output file element for the specified font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

新增用於 context object 的輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| templateKey | java.lang.String | The key of the template used for context object transformation before output. |
| contextObject | TContextObject | Context object. |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用於 context object 的物件。

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

新增用於 image 的輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Image to output. |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用於 image 的物件。

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

新增用於 image 的輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| image | [IImage](../../com.aspose.slides/iimage) | Image to output. |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用於 image 的物件。

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

新增用於 video 的輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video to output. |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用於 video 的物件。

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

建立並新增指定字型的輸出檔案元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | The file path where the font output will be saved. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | The font data to be written to the output. |
| fontStyle | int | The style of the font (e.g., Regular, Bold, Italic). |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - An [IOutputFile](../../com.aspose.slides/ioutputfile) instance for the generated font.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

新增文字內容的輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| textContent | java.lang.String | Content to output. |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用於 text content 的物件。

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

將資源繫結至輸出檔案。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Output file. |
| obj | java.lang.Object | Resource object. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

傳回指定資源的路徑。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | Resource object. |

**傳回值：**
java.lang.String - Resource path。