---
title: Section
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片的章节。
type: docs
url: /zh/com.aspose.slides/section/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

表示幻灯片的章节。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 章节的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 章节的名称。 |
| [getSectionId()](#getSectionId--) | 章节 ID。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | 返回章节的第一张幻灯片。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | 返回该章节中的幻灯片列表。 |
### getName() {#getName--}
```
public final String getName()
```

章节的名称。

**返回：**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

章节的名称。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

章节 ID。

**返回：**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

返回章节的第一张幻灯片。

**返回：**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

返回该章节中的幻灯片列表。

**返回：**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 幻灯片列表。