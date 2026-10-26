---
title: IImage
second_title: Aspose.Slides for Android via Java API 參考
description: 表示光柵或向量圖像。
type: docs
url: /zh-hant/com.aspose.slides/iimage/
---
**所有已實作的介面：**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

表示光柵或向量圖像。

--------------------

此介面提供用於處理光柵與向量圖像的共同抽象。實作可能因底層圖像類型而異。
## 方法

| 方法 | 說明 |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Saves the image to a file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Saves the image to a file in the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves the image to a stream in the specified format. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Saves the image to a file in the specified format and quality. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Saves the image to a stream in the specified format and quality. |
| [getSize()](#getSize--) | Gets the size of the image. |
| [getWidth()](#getWidth--) | Gets the width of the image in pixels. |
| [getHeight()](#getHeight--) | Gets the height of the image in pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

將圖像儲存至檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | java.lang.String | 圖像要儲存的檔案路徑。 |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

將圖像儲存至指定格式的檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | java.lang.String | 圖像要儲存的檔案路徑。 |
| format | int | 圖像格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

將圖像儲存至指定格式的串流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 圖像要儲存的串流。 |
| format | int | 圖像格式。 |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

將圖像儲存至指定格式及品質的檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | java.lang.String | 圖像要儲存的檔案路徑。 |
| format | int | 圖像格式。 |
| quality | int | 儲存圖像的品質 (0 到 100)。此參數僅影響儲存在 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 時；對其他所有格式皆會被忽略。 |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

將圖像儲存至指定格式及品質的串流。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 圖像要儲存的串流。 |
| format | int | 圖像格式。 |
| quality | int | 儲存圖像的品質 (0 到 100)。此參數僅影響儲存在 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 時；對其他所有格式皆會被忽略。 |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

取得圖像的大小。

**傳回值:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

取得圖像的寬度（像素）。

**傳回值:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

取得圖像的高度（像素）。

**傳回值:**
int