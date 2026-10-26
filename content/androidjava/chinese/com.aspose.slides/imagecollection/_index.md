---
title: ImageCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 PPImage 的集合。
type: docs
url: /zh/com.aspose.slides/imagecollection/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

表示 PPImage 的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 返回集合中图像的数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 从另一个演示文稿中添加图像的副本。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 将图像添加到演示文稿。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 从流中将图像添加到演示文稿。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 从流中创建并将图像添加到演示文稿。 |
| [addImage(byte[] buffer)](#addImage-byte---) | 从指定缓冲区将图像添加到演示文稿。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | 从 Svg 对象将图像添加到演示文稿。 |
| [iterator()](#iterator--) | 返回迭代集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示对集合的访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

返回集合中图像的数量。只读 int .

**返回:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

获取指定索引处的元素。只读 [IPPImage](../../com.aspose.slides/ippimage)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

从另一个演示文稿中添加图像的副本。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 源图像。 |

**返回:**  
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

将图像添加到演示文稿。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 要添加的图像。 |

--------------------

此方法在将 WMF/EMF 元文件插入演示文稿之前，将其转换为光栅 PNG 图像。  

**返回:**  
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

从流中将图像添加到演示文稿。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于添加图像的流。 |

--------------------

此方法可以在不将 WMF/EMF 元文件转换为光栅 PNG 图像的情况下，将其添加到演示文稿。  

**返回:**  
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

从流中创建并将图像添加到演示文稿。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于添加图像文件的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

**返回:**  
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的 [IPPImage](../../com.aspose.slides/ippimage)。
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

从指定缓冲区将图像添加到演示文稿。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 缓冲区。 |

**返回:**  
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

从 Svg 对象将图像添加到演示文稿。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg 图像对象 [ISvgImage](../../com.aspose.slides/isvgimage) |

**返回:**  
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

返回迭代集合的枚举器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - 用于遍历整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回指示对集合的访问是否同步（线程安全）的值。只读 boolean .

**返回:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object .

**返回:**  
java.lang.Object