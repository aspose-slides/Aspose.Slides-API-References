---
title: IImage
second_title: Aspose.Slides 的 Java API 参考
description: 表示栅格图像或矢量图像。
type: docs
url: /zh/com.aspose.slides/iimage/
---
**所有实现的接口：**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

表示栅格图像或矢量图像。

--------------------

此接口提供了处理栅格图像和矢量图像的通用抽象。实现可能因底层图像类型而异。
## 方法

| 方法 | 描述 |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | 将图像保存到文件。 |
| [save(String filename, int format)](#save-java.lang.String-int-) | 将图像保存到指定格式的文件。 |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 将图像以指定格式保存到流中。 |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | 将图像以指定格式和质量保存到文件。 |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | 将图像以指定格式和质量保存到流中。 |
| [getSize()](#getSize--) | 获取图像的大小。 |
| [getWidth()](#getWidth--) | 获取图像的宽度（像素）。 |
| [getHeight()](#getHeight--) | 获取图像的高度（像素）。 |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

将图像保存到文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 图像将被保存的文件路径。 |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

将图像保存到指定格式的文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 图像将被保存的文件路径。 |
| format | int | 图像格式。 |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

将图像以指定格式保存到流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 图像将被保存的流。 |
| format | int | 图像格式。 |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

将图像以指定格式和质量保存到文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String | 图像将被保存的文件路径。 |
| format | int | 图像格式。 |
| quality | int | 已保存图像的质量（0 到 100）。此参数仅影响在 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 中的保存；对所有其他格式将被忽略。 |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

将图像以指定格式和质量保存到流中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 图像将被保存的流。 |
| format | int | 图像格式。 |
| quality | int | 已保存图像的质量（0 到 100）。此参数仅影响在 [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) 中的保存；对所有其他格式将被忽略。 |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

获取图像的大小。

**返回值：**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

获取图像的宽度（像素）。

**返回值：**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

获取图像的高度（像素）。

**返回值：**
int