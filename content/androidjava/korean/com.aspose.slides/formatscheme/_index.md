---
title: FormatScheme
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 도형에 대한 테마 정의 형식을 저장합니다.
type: docs
url: /ko/com.aspose.slides/formatscheme/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFormatScheme](../../com.aspose.slides/iformatscheme), com.aspose.slides.IDOMObject
```
public class FormatScheme implements IFormatScheme, IDOMObject
```

도형에 대한 테마 정의 형식을 저장합니다.
## 메서드

| Method | Description |
| --- | --- |
| [getFillStyles()](#getFillStyles--) | 테마에서 정의된 채우기 스타일 컬렉션을 반환합니다. |
| [getLineStyles()](#getLineStyles--) | 테마에서 정의된 선 스타일 컬렉션을 반환합니다. |
| [getEffectStyles()](#getEffectStyles--) | 테마에서 정의된 효과 스타일 컬렉션을 반환합니다. |
| [getBackgroundFillStyles()](#getBackgroundFillStyles--) | 테마에서 정의된 배경 채우기 스타일 컬렉션을 반환합니다. |
| [getSlide()](#getSlide--) | 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 상위 프레젠테이션을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getFillStyles() {#getFillStyles--}
```
public final IFillFormatCollection getFillStyles()
```


테마에서 정의된 채우기 스타일 컬렉션을 반환합니다. 읽기 전용 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**Returns:**
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
### getLineStyles() {#getLineStyles--}
```
public final ILineFormatCollection getLineStyles()
```


테마에서 정의된 선 스타일 컬렉션을 반환합니다. 읽기 전용 [ILineFormatCollection](../../com.aspose.slides/ilineformatcollection).

**Returns:**
[ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
### getEffectStyles() {#getEffectStyles--}
```
public final IEffectStyleCollection getEffectStyles()
```


테마에서 정의된 효과 스타일 컬렉션을 반환합니다. 읽기 전용 [IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection).

**Returns:**
[IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
### getBackgroundFillStyles() {#getBackgroundFillStyles--}
```
public final IFillFormatCollection getBackgroundFillStyles()
```


테마에서 정의된 배경 채우기 스타일 컬렉션을 반환합니다. 읽기 전용 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**Returns:**
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject