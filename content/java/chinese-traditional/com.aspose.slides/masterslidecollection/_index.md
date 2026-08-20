---
title: MasterSlideCollection
second_title: Aspose.Slides for Java API 參考
description: 表示一組母版投影片的集合。
type: docs
url: /zh-hant/com.aspose.slides/masterslidecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

表示一組母版投影片的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | 從集合中移除第一個出現的特定物件。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除指定索引處的元素。 |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | 移除未使用的母版投影片。 |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | 將指定母版投影片的複本加入集合的末端。 |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | 將指定母版投影片的複本插入集合的指定位置。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否已同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
### size() {#size--}
```
public final int size()
```

取得集合實際包含的元素數量。唯讀 int。

**傳回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

取得指定索引處的元素。唯讀 [MasterSlide](../../com.aspose.slides/masterslide)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

從集合中移除第一個出現的特定物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要從集合中移除的母版投影片。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從集合中移除指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素之零基索引。 |

--------------------

為避免拋出 PptxEditException，請先檢查母版的 HasDependingSlides 屬性。 |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

移除未使用的母版投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ignorePreserveField | boolean | 決定即使其 [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) 屬性被設定為 true，此方法是否仍應移除未使用的母版。 |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

將指定母版投影片的複本加入集合的末端。會同時複製相關的版面配置投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的投影片。 |

**傳回值：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已新增的投影片。
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

將指定母版投影片的複本插入集合的指定位置。會同時複製相關的版面配置投影片。

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>      // 實例化 Presentation 類別以載入來源簡報檔案
>      Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>      try {
>          // 為目標簡報（要克隆投影片的地方）實例化 Presentation 類別
>          Presentation destPres = new Presentation();
>          try {
>              // 從來源簡報的投影片集合中實例化 ISlide，並帶有
>              // 母版投影片
>              ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>              IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>              // 取得目標簡報的母版投影片
>              IMasterSlideCollection masters = destPres.getMasters();
>              // 將所需的母版投影片從來源簡報克隆到目標簡報的母版集合中
>              // 目標簡報
>              IMasterSlide iSlide = masters.addClone(SourceMaster);
>              // 目標簡報中的投影片集合
>              ISlideCollection slds = destPres.getSlides();
>              // 將來源投影片克隆到目標投影片集合。
>              slds.addClone(SourceSlide, iSlide, true);
>              // 將目標簡報儲存至磁碟
>              destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>          } finally {
>              if (destPres != null) destPres.dispose();
>          }
>      } finally {
>          if (srcPres != null) srcPres.dispose();
>      }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 新投影片的索引。 |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 要克隆的投影片。 |

**傳回值：**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 已插入的母版投影片。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將所有元素從集合複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否已同步（執行緒安全）的值。唯讀 boolean。

**傳回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值：**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

傳回用於遍歷集合的列舉器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - 整個集合的 java.util.Iterator。