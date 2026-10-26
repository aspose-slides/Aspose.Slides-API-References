---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: 表示幻灯片的部分。
type: docs
url: /zh/com.aspose.slides/isection/
---```
public interface ISection
```

表示幻灯片的部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 部分的名称。 |
| [setName(String value)](#setName-java.lang.String-) | 部分的名称。 |
| [getSectionId()](#getSectionId--) | Section Id。 |
| [getStartedFromSlide()](#getStartedFromSlide--) | 返回该部分的第一张幻灯片。 |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | 返回该部分的幻灯片列表。 |
### getName() {#getName--}
```
public abstract String getName()
```

部分的名称。

**返回：**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

部分的名称。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Section Id。

**返回：**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

返回该部分的第一张幻灯片。

**返回：**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

返回该部分的幻灯片列表。

**返回：**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 幻灯片列表 [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)