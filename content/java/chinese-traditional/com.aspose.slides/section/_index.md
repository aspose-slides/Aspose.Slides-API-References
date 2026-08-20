---
title: Section
second_title: Aspose.Slides for Java API 參考文件
description: 表示投影片的區段。
type: docs
url: /zh-hant/com.aspose.slides/section/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面：**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

表示投影片的區段。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 區段的名稱。 |
| [setName(String value)](#setName-java.lang.String-) | 區段的名稱。 |
| [getSectionId()](#getSectionId--) | 區段 Id。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | 傳回區段的第一張投影片。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | 傳回區段中投影片的列表。 |
### getName() {#getName--}
```
public final String getName()
```

區段的名稱。

**傳回值：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

區段的名稱。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

區段 Id。

**傳回值：**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

傳回區段的第一張投影片。

**傳回值：**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

傳回區段中投影片的列表。

**傳回值：**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 投影片列表。