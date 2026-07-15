---
title: Section
second_title: 透過 Java API 參考的 Aspose.Slides for Android
description: 表示投影片的區段。
type: docs
url: /zh-hant/com.aspose.slides/section/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

表示投影片的區段。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getName()](#getName--) | 區段名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 區段名稱。 |
| [getSectionId()](#getSectionId--) | 區段 ID。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | 傳回區段的第一張投影片。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | 傳回區段中的投影片清單。 |
### getName() {#getName--}
```
public final String getName()
```


區段名稱。

**傳回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


區段名稱。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


區段 ID。

**傳回：**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


傳回區段的第一張投影片。

**傳回：**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


傳回區段中的投影片清單。

**傳回：**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 投影片清單。