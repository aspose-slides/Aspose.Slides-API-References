---
title: IImageCollection
second_title: Aspose.Slides for Java API 參考
description: 表示 PPImage 的集合。
type: docs
url: /zh-hant/com.aspose.slides/iimagecollection/
---
**所有實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

表示 PPImage 的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據其索引返回 Image。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 將 Image 新增至簡報。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 從串流將 Image 新增至簡報。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 從串流建立並將 Image 新增至簡報。 |
| [addImage(byte[] buffer)](#addImage-byte---) | Adds an image to a presentation from specified buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 從另一個簡報新增 Image 的副本。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | 從 SVG 物件將 Image 新增至簡報。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

根據其索引返回 Image。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

將 Image 新增至簡報。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 要新增的 Image。 |

--------------------

此方法會在插入簡報之前，將 WMF/EMF 中繪圖檔轉換為光柵 PNG 圖像。

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的 Image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

從串流將 Image 新增至簡報。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用於新增 Image 的串流。 |

--------------------

此方法可以將 WMF/EMF 中繪圖檔直接新增至簡報，而不轉換為光柵 PNG 圖像。

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的 Image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

從串流建立並將 Image 新增至簡報。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用於新增 Image 檔案的串流。 |
| loadingStreamBehavior | int | 將套用於串流的行為。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的 [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

從指定緩衝區將 Image 新增至簡報。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 緩衝區。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的 Image.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

從另一個簡報新增 Image 的副本。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 來源 Image。 |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的 Image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

從 SVG 物件將 Image 新增至簡報。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG 圖像物件 [ISvgImage](../../com.aspose.slides/isvgimage) |

**傳回值：**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的 Image.