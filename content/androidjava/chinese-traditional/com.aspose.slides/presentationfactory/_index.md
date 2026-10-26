---
title: PresentationFactory
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 允許透過 COM 介面建立簡報
type: docs
url: /zh-hant/com.aspose.slides/presentationfactory/
---
**繼承：**
java.lang.Object

**全部已實作介面：**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

允許透過 COM 介面建立簡報

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation factory 靜態實例。 |
| [createPresentation()](#createPresentation--) | 建立新的簡報。 |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | 建立新的簡報並附加載入選項 |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | 從檔案建立新的 PresentationInfo 物件並將簡報與之繫結。 |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | 從串流建立新的 PresentationInfo 物件並將簡報與之繫結。 |
| [readPresentation(byte[] data)](#readPresentation-byte---) | 從陣列讀取現有的簡報 |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | 從陣列讀取現有的簡報，並附加載入選項 |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | 從串流讀取現有的簡報 |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | 從串流讀取現有的簡報，並附加載入選項 |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | 從檔案讀取現有的簡報 |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | 從串流讀取現有的簡報，並附加載入選項 |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | 取得投影片的原始文字 |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | 取得投影片的原始文字 |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | 取得投影片的原始文字 |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Presentation factory 靜態實例。唯讀 [PresentationFactory](../../com.aspose.slides/presentationfactory)。

**返回值：**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


建立新的簡報。

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 新簡報
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


建立新的簡報，並附加載入選項

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 新簡報
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


從檔案建立新的 PresentationInfo 物件並將簡報與之繫結。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 簡報檔案。 |

**返回值：**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 與簡報繫結的 PresentationInfo。
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


從串流建立新的 PresentationInfo 物件並將簡報與之繫結。取得指定串流中簡報的資訊。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 簡報串流。 |

**返回值：**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - 與簡報繫結的 PresentationInfo。
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


從陣列讀取現有的簡報

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | 要讀取的陣列 |

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 讀取的簡報
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


從陣列讀取現有的簡報，並附加載入選項

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| data | byte[] | 要讀取的陣列 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 讀取的簡報
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


從串流讀取現有的簡報

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要讀取的輸入串流 |

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 讀取的簡報
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


從串流讀取現有的簡報，並附加載入選項

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要讀取的輸入串流 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 讀取的簡報
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


從檔案讀取現有的簡報

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 檔案名稱 |

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 讀取的簡報
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


從檔案讀取現有的簡報，並附加載入選項

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 檔案名稱 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation) - 讀取的簡報
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


取得投影片的原始文字

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 輸入檔案 |
| mode | int | 抽取模式 |

**返回值：**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含投影片文字陣列的 PresentationText 實例，代表原始投影片文字
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


取得投影片的原始文字

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 輸入串流 |
| mode | int | 抽取模式 |

**返回值：**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含投影片文字陣列的 PresentationText 實例，代表原始投影片文字
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


取得投影片的原始文字

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 輸入串流 |
| mode | int | 抽取模式 |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | 載入選項 |

**返回值：**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - 包含投影片文字陣列的 PresentationText 實例，代表原始投影片文字