---
title: FormatScheme
second_title: Aspose.Slides for Java API 레퍼런스
description: 도형에 대한 테마 정의 형식을 저장합니다.
type: docs
url: /ko/com.aspose.slides/formatscheme/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IFormatScheme](../../com.aspose.slides/iformatscheme), com.aspose.slides.IDOMObject  
```
public class FormatScheme implements IFormatScheme, IDOMObject
```

테마에서 정의된 형식들을 도형에 저장합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillStyles()](#getFillStyles--) | 테마에서 정의된 채우기 스타일 컬렉션을 반환합니다. |
| [getLineStyles()](#getLineStyles--) | 테마에서 정의된 선 스타일 컬렉션을 반환합니다. |
| [getEffectStyles()](#getEffectStyles--) | 테마에서 정의된 효과 스타일 컬렉션을 반환합니다. |
| [getBackgroundFillStyles()](#getBackgroundFillStyles--) | 테마에서 정의된 배경 채우기 스타일 컬렉션을 반환합니다. |
| [getSlide()](#getSlide--) | 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 부모 프레젠테이션을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getFillStyles() {#getFillStyles--}
```
public final IFillFormatCollection getFillStyles()
```

테마에서 정의된 채우기 스타일 컬렉션을 반환합니다. 읽기 전용 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**반환:**  
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)

### getLineStyles() {#getLineStyles--}
```
public final ILineFormatCollection getLineStyles()
```

테마에서 정의된 선 스타일 컬렉션을 반환합니다. 읽기 전용 [ILineFormatCollection](../../com.aspose.slides/ilineformatcollection).

**반환:**  
[ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)

### getEffectStyles() {#getEffectStyles--}
```
public final IEffectStyleCollection getEffectStyles()
```

테마에서 정의된 효과 스타일 컬렉션을 반환합니다. 읽기 전용 [IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection).

**반환:**  
[IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)

### getBackgroundFillStyles() {#getBackgroundFillStyles--}
```
public final IFillFormatCollection getBackgroundFillStyles()
```

테마에서 정의된 배경 채우기 스타일 컬렉션을 반환합니다. 읽기 전용 [IFillFormatCollection](../../com.aspose.slides/ifillformatcollection).

**반환:**  
[IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

부모 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject