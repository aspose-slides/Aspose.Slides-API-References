---
title: Output
second_title: Aspose.Slides for Java API 參考
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

| 方法 | 描述 |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | 為上下文物件新增輸出元素。 |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | 為圖像新增輸出元素。 |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | 為圖像新增輸出元素。 |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | 為影片新增輸出元素。 |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | 為音訊新增輸出元素。 |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | 為指定的字型建立並新增輸出檔案元素。 |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | 為文字內容新增輸出元素。 |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | 將資源繫結至輸出檔案。 |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | 傳回給定資源的路徑。 |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

為上下文物件新增輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 輸出路徑。 |
| templateKey | java.lang.String | 用於在輸出前對上下文物件轉換的模板鍵。 |
| contextObject | TContextObject | 上下文物件。 |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 物件，用於上下文物件。

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

為圖像新增輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 輸出路徑。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要輸出的圖像。 |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 物件，用於圖像。

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

為圖像新增輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 輸出路徑。 |
| image | [IImage](../../com.aspose.slides/iimage) | 要輸出的圖像。 |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 物件，用於圖像。

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

為影片新增輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 輸出路徑。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 要輸出的影片。 |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 物件，用於影片。

### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

為音訊新增輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 輸出路徑。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 要輸出的音訊。 |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 物件，用於音訊。

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

建立並為指定的字型新增輸出檔案元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 字型輸出將被儲存的檔案路徑。 |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 要寫入輸出的字型資料。 |
| fontStyle | int | 字型樣式（例如 Regular、Bold、Italic）。 |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - 產生的字型的 [IOutputFile](../../com.aspose.slides/ioutputfile) 實例。

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

為文字內容新增輸出元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | java.lang.String | 輸出路徑。 |
| textContent | java.lang.String | 要輸出的內容。 |

**傳回值：**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 物件，用於文字內容。

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

將資源繫結至輸出檔案。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 輸出檔案。 |
| obj | java.lang.Object | 資源物件。

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

傳回給定資源的路徑。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 資源物件。 |

**傳回值：**
java.lang.String - 資源路徑。