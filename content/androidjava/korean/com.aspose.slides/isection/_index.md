---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: 슬라이드 섹션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isection/
---```
public interface ISection
```

슬라이드 섹션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | 섹션 이름. |
| [setName(String value)](#setName-java.lang.String-) | 섹션 이름. |
| [getSectionId()](#getSectionId--) | 섹션 ID. |
| [getStartedFromSlide()](#getStartedFromSlide--) | 섹션의 첫 번째 슬라이드를 반환합니다. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | 섹션에 있는 슬라이드 목록을 반환합니다. |
### getName() {#getName--}
```
public abstract String getName()
```

섹션 이름.

**반환:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

섹션 이름.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

섹션 ID.

**반환:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

섹션의 첫 번째 슬라이드를 반환합니다.

**반환:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

섹션에 있는 슬라이드 목록을 반환합니다.

**반환:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - 슬라이드 목록 [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)