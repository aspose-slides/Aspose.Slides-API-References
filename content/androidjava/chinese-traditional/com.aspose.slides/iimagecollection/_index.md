---
title: IImageCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 PPImage 的集合。
type: docs
url: /zh-hant/com.aspose.slides/iimagecollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

表示 PPImage 的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 依索引傳回影像。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 將影像加入簡報。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 從串流將影像加入簡報。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 從串流建立並將影像加入簡報。 |
| [addImage(byte[] buffer)](#addImage-byte---) | 從指定的緩衝區將影像加入簡報。 |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 從另一個簡報加入影像的副本。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | 從 SVG 物件將影像加入簡報。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


依索引傳回影像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 索引。 |

**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


將影像加入簡報。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 要加入的影像。

--------------------

此方法會將 WMF/EMF 中繪圖檔轉換為光柵 PNG 影像，然後插入至簡報。 |

**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的影像。
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


從串流將影像加入簡報。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 從串流加入影像。

--------------------

此方法可將 WMF/EMF 中繪圖檔加入簡報，無需轉換為光柵 PNG 影像。 |

**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的影像。
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


從串流建立並將影像加入簡報。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 從串流加入影像檔。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入 [IPPImage](../../com.aspose.slides/ippimage)。
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


從指定的緩衝區將影像加入簡報。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | byte[] | 緩衝區。 |

**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的影像。
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


從另一個簡報加入影像的副本。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 來源影像。 |

**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的影像。
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


從 SVG 物件將影像加入簡報。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG 影像物件 [ISvgImage](../../com.aspose.slides/isvgimage) |

**傳回值:**
[IPPImage](../../com.aspose.slides/ippimage) - 已加入的影像。