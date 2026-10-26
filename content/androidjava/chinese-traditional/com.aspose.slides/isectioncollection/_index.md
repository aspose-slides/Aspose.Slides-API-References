---
title: ISectionCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示區段的集合。
type: docs
url: /zh-hant/com.aspose.slides/isectioncollection/
---
**已實作的所有介面：**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

表示區段的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 新增以特定投影片開始的區段。 |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | 在集合的指定位置新增空的區段。 |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | 移除區段以及區段中包含的投影片。 |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | 移除區段。 |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | 將區段及其投影片從集合中移動到指定位置。 |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | 在集合的末尾新增空的區段。 |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | 傳回集合中指定區段的索引。 |
| [clear()](#clear--) | 移除集合中的所有區段。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


取得指定索引處的元素。唯讀 [ISection](../../com.aspose.slides/isection)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**回傳：**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


新增以特定投影片開始的區段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 區段的名稱 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | 區段的第一張投影片 |

**回傳：**
[ISection](../../com.aspose.slides/isection) - 已新增的區段。
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


在集合的指定位置新增空的區段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 區段的名稱 |
| index | int | 新區段的索引。 |

**回傳：**
[ISection](../../com.aspose.slides/isection) - 已新增的區段。
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


移除區段以及區段中包含的投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要從集合中移除的區段。 |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


移除區段。區段中包含的投影片將合併到前一個區段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要從集合中移除的區段。 |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


將區段及其投影片從集合中移動到指定位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要移動的區段。 |
| index | int | 目標索引。 |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


在集合的末尾新增空的區段。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 區段的名稱 |

**回傳：**
[ISection](../../com.aspose.slides/isection) - 已新增的區段。
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


傳回集合中指定區段的索引。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要尋找的區段。 |

**回傳：**
int - 區段的索引；如果區段不屬於此集合，則為 -1。
### clear() {#clear--}
```
public abstract void clear()
```


移除集合中的所有區段。