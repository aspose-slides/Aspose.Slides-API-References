---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: 代表投影片的章節。
type: docs
url: /zh-hant/com.aspose.slides/isection/
---```
public interface ISection
```

代表投影片的章節。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getName()](#getName--) | Name of the section. |
| [setName(String value)](#setName-java.lang.String-) | Name of the section. |
| [getSectionId()](#getSectionId--) | Section Id. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Returns first slide of the section. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Returns list of slides in the section. |

### getName() {#getName--}
```
public abstract String getName()
```

章節的名稱。

**傳回：**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

章節的名稱。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

章節 ID。

**傳回：**
java.util.UUID

### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

傳回章節的第一張投影片。

**傳回：**
[ISlide](../../com.aspose.slides/islide)

### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

傳回章節中投影片的清單。

**傳回：**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 投影片清單 [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)