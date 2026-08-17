---
title: MasterSlideCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一个主幻灯片集合。
type: docs
url: /zh/com.aspose.slides/masterslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

表示一个主幻灯片集合。
## 方法

| Method | Description |
| --- | --- |
| [size()](#size--) | 获取集合实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 从集合中移除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 移除未使用的主幻灯片。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 将指定主幻灯片的副本添加到集合末尾。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 将指定主幻灯片的副本插入到集合的指定位置。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个指示对集合的访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 为整个集合返回一个 java 迭代器。 |
### size() {#size--}
```
public final int size()
```


获取集合实际包含的元素数量。只读 int。

**返回:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


获取指定索引处的元素。只读 [MasterSlide](../../com.aspose.slides/masterslide)。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**返回:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


从集合中移除特定对象的第一次出现。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要从集合中移除的主幻灯片。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除集合中指定索引处的元素。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。

--------------------

为避免抛出 PptxEditException，请在此之前检查主幻灯片的 HasDependingSlides 属性。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


移除未使用的主幻灯片。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | 确定即使其 [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) 属性设置为 true，此方法是否仍应移除未使用的主幻灯片。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


将指定主幻灯片的副本添加到集合末尾。链接的布局幻灯片也会被复制。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的幻灯片。 |

**返回:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已添加的幻灯片。
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


在集合的指定位置插入指定主幻灯片的副本。链接的布局幻灯片也会被复制。

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // 实例化 Presentation 类以加载源演示文稿文件
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // 实例化 Presentation 类用于目标演示文稿（要克隆幻灯片的地方）
>      Presentation destPres = new Presentation();
>      try {
>          // 从源演示文稿的幻灯片集合中实例化 ISlide，并包括
>          // 主幻灯片
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // 获取目标演示文稿的主幻灯片
>          IMasterSlideCollection masters = destPres.getMasters();
>          // 将所需的主幻灯片从源演示文稿克隆到目标演示文稿的主幻灯片集合中
>          // 目标演示文稿
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // 目标演示文稿中的幻灯片集合
>          ISlideCollection slds = destPres.getSlides();
>          // 将源幻灯片克隆到目标幻灯片集合中。
>          slds.addClone(SourceSlide, iSlide, true);
>          // 将目标演示文稿保存到磁盘
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 新幻灯片的索引。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的幻灯片。 |

**返回:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已插入的主幻灯片。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


将集合中的所有元素复制到指定数组。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


返回一个指示对集合的访问是否同步（线程安全）的值。只读 boolean。

**返回:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


返回同步根。只读 Object。

**返回:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


返回一个遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 整个集合的 java.util.Iterator。