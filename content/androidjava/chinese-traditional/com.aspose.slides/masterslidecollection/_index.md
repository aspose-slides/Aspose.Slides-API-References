---
title: MasterSlideCollection
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示 master slide 的集合。
type: docs
url: /zh-hant/com.aspose.slides/masterslidecollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面:**  
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)  
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

表示 master slide 的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 移除集合中特定物件的第一次出現。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 移除未使用的 master slide。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 將指定 master slide 的副本新增至集合的末端。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 在集合的指定位置插入指定 master slide 的副本。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將所有元素從集合複製至指定陣列。 |
| [isSynchronized()](#isSynchronized--) | 回傳一個值，指示對集合的存取是否同步 (執行緒安全)。 |
| [getSyncRoot()](#getSyncRoot--) | 回傳同步根。 |
| [iterator()](#iterator--) | 回傳可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 回傳整個集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數量。 Read-only int.

**傳回值:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

取得指定索引處的元素。 Read-only [MasterSlide](../../com.aspose.slides/masterslide)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

移除集合中特定物件的第一次出現。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要從集合中移除的 master slide。 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的元素。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

--------------------

為避免拋出 PptxEditException，請先檢查 master 的 HasDependingSlides 屬性。 |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

移除未使用的 master slide。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ignorePreserveField | boolean | 決定即使其 [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) 屬性設為 true，此方法是否仍應移除未使用的 master。 |
### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

將指定 master slide 的副本新增至集合的末端。連結的版面配置投影片也會被複製。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的投影片。 |

**傳回值:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已新增的投影片。
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

在集合的指定位置插入指定 master slide 的副本。連結的版面配置投影片也會被複製。

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instantiate Presentation class for destination presentation (where slide is to be cloned)
>      Presentation destPres = new Presentation();
>      try {
>          // Instantiate ISlide from the collection of slides in source presentation along with
>          // Master slide
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Get Master Slides of destination presentation
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clone the desired master slide from the source presentation to the collection of masters in the
>          // Destination presentation
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Collection of slides in the destination presentation
>          ISlideCollection slds = destPres.getSlides();
>          // Clone source slide to destination slides collection.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Save the destination presentation to disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的投影片。 |

**傳回值:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已插入的 master slide。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將所有元素從集合複製到指定的陣列。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

回傳一個值，指示對集合的存取是否同步 (執行緒安全)。 Read-only boolean。

**傳回值:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

回傳同步根。 Read-only Object。

**傳回值:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

回傳可遍歷集合的列舉器。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

回傳整個集合的 java 迭代器。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 整個集合的 java.util.Iterator。