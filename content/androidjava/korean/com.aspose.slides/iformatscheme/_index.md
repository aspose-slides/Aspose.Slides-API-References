---
title: IFormatScheme
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 도형에 대한 테마 정의 형식을 저장합니다.
type: docs
url: /ko/com.aspose.slides/iformatscheme/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IFormatScheme extends ISlideComponent
```

도형에 대한 테마 정의 형식을 저장합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillStyles()](#getFillStyles--) | 테마 정의 채우기 스타일 컬렉션을 반환합니다. |
| [getLineStyles()](#getLineStyles--) | 테마 정의 선 스타일 컬렉션을 반환합니다. |
| [getEffectStyles()](#getEffectStyles--) | 테마 정의 효과 스타일 컬렉션을 반환합니다. |
| [getBackgroundFillStyles()](#getBackgroundFillStyles--) | 테마 정의 배경 채우기 스타일 컬렉션을 반환합니다. |
### getFillStyles() {#getFillStyles--}
```
public abstract IFillFormatCollection getFillStyles()
```


테마 정의 채우기 스타일 컬렉션을 반환합니다. 읽기 전용 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**반환:**
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
### getLineStyles() {#getLineStyles--}
```
public abstract ILineFormatCollection getLineStyles()
```


테마 정의 선 스타일 컬렉션을 반환합니다. 읽기 전용 [ILineFormatCollection](../../com.aspose.slides/ilineformatcollection).

**반환:**
[ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
### getEffectStyles() {#getEffectStyles--}
```
public abstract IEffectStyleCollection getEffectStyles()
```


테마 정의 효과 스타일 컬렉션을 반환합니다. 읽기 전용 [IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection).

**반환:**
[IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
### getBackgroundFillStyles() {#getBackgroundFillStyles--}
```
public abstract IFillFormatCollection getBackgroundFillStyles()
```


테마 정의 배경 채우기 스타일 컬렉션을 반환합니다. 읽기 전용 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**반환:**
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)