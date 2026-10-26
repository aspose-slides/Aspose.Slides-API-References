---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: 表示幻灯片的章节。
type: docs
url: /zh/com.aspose.slides/isection/
---```
public interface ISection
```

表示幻灯片的章节。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 章节的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 章节的名称。 |
| [getSectionId()](#getSectionId--) | 章节 ID。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | 返回章节的第一张幻灯片。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | 返回章节中的幻灯片列表。 |
### getName() {#getName--}
```
public abstract String getName()
```

章节的名称。

**返回:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

章节的名称。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

章节 ID。

**返回:**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

返回章节的第一张幻灯片。

**返回:**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

返回章节中的幻灯片列表。

**返回:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 幻灯片列表 [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)