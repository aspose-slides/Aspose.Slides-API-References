---
title: ImageCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/imagecollection/
---
## ImageCollection 类

 表示 PPImage 的集合。
 
### addImage {#addImage}

| 名称 | 描述 |
| --- | --- |
| addImage ([PPImage](../ppimage)) | 从另一个演示文稿中添加图像的副本。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| imageSource | [PPImage](../ppimage) | Source image. |

 **返回：**
[PPImage](../ppimage)

---

### addImage {#addImage}

| 名称 | 描述 |
| --- | --- |
| addImage ([IImage](../iimage)) | 向演示文稿添加图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| image | [IImage](../iimage) | 要添加的图像。此方法在插入演示文稿之前将 WMF/EMF 元文件转换为栅格 PNG 图像。 |

 **返回：**
[PPImage](../ppimage)

---

### addImage {#addImage}

| 名称 | 描述 |
| --- | --- |
| addImage (InputStream) | 从流中向演示文稿添加图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 用于添加图像的流。此方法可以在不将 WMF/EMF 元文件转换为栅格 PNG 图像的情况下将其添加到演示文稿。 |

 **返回：**
[PPImage](../ppimage)

---

### addImage {#addImage}

| 名称 | 描述 |
| --- | --- |
| addImage (InputStream, int) | 从流创建并添加图像到演示文稿。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 用于添加图像文件的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

 **返回：**
[PPImage](../ppimage)

---

### addImage {#addImage}

| 名称 | 描述 |
| --- | --- |
| addImage (byte[]) | 从指定缓冲区向演示文稿添加图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 缓冲区。 |

 **返回：**
[PPImage](../ppimage)

---

### addImage {#addImage}

| 名称 | 描述 |
| --- | --- |
| addImage ([SvgImage](../svgimage)) | 从 Svg 对象向演示文稿添加图像。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | Svg 图像对象 ISvgImage |

 **返回：**
[PPImage](../ppimage)

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentNullException | 当 svgImage 参数为 null 时。 |

---

### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回：**
Object

---

### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 IPPImage。 |

 **返回：**
[PPImage](../ppimage)

---

### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回指示集合访问是否同步（线程安全）的值。只读 boolean。 |

 **返回：**
boolean

---

### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

 **返回：**



---

### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回：**



---

### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 返回集合中图像的数量。只读 int。 |

 **返回：**
int

---