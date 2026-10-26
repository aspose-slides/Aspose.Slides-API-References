---
title: IImage
second_title: Aspose.Slides for Java API 參考
description: 表示光柵或向量圖像。
type: docs
url: /zh-hant/com.aspose.slides/iimage/
---
**所有已實作的介面:**  
com.aspose.ms.System.IDisposable  
```
public interface IImage extends System.IDisposable
```

表示光柵或向量圖像。

--------------------

此介面提供了一個用於處理光柵與向量圖像的通用抽象。實作可能會因底層圖像類型而異。

## 方法

| 方法 | 說明 |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | 將圖像儲存至檔案。 |
| [save(String filename, int format)](#save-java.lang.String-int-) | 以指定格式將圖像儲存至檔案。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 以指定格式將圖像儲存至資料流。 |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | 以指定格式及品質將圖像儲存至檔案。 |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | 以指定格式及品質將圖像儲存至資料流。 |
| [getSize()](#getSize--) | 取得圖像的大小。 |
| [getWidth()](#getWidth--) | 取得圖像的寬度（以像素為單位）。 |
| [getHeight()](#getHeight--) | 取得圖像的高度（以像素為單位）。 |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

將圖像儲存至檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | java.lang.String | 要儲存圖像的檔案路徑。 |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

以指定格式將圖像儲存至檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | java.lang.String | 要儲存圖像的檔案路徑。 |
| format | int | 圖像格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

以指定格式將圖像儲存至資料流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 要儲存圖像的資料流。 |
| format | int | 圖像格式。 |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

以指定格式及品質將圖像儲存至檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | java.lang.String | 要儲存圖像的檔案路徑。 |
| format | int | 圖像格式。 |
| quality | int | 已儲存圖像的品質（0 至 100）。此參數僅影響 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 的儲存；對其他所有格式則會被忽略。 |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

以指定格式及品質將圖像儲存至資料流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 要儲存圖像的資料流。 |
| format | int | 圖像格式。 |
| quality | int | 已儲存圖像的品質（0 至 100）。此參數僅影響 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 的儲存；對其他所有格式則會被忽略。 |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

取得圖像的大小。

**回傳:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

取得圖像的寬度（以像素為單位）。

**回傳:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

取得圖像的高度（以像素為單位）。

**回傳:**
int