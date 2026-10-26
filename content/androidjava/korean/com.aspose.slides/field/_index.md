---
title: Field
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 필드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/field/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IField](../../com.aspose.slides/ifield)  
```
public final class Field extends DomObject<Portion> implements IField
```

필드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 필드의 유형을 반환하거나 설정합니다. |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | 필드의 유형을 반환하거나 설정합니다. |
| [getSlide()](#getSlide--) | 단락의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 단락의 상위 프레젠테이션을 반환합니다. |
### getType() {#getType--}
```
public final IFieldType getType()
```

필드의 유형을 반환하거나 설정합니다. 읽기/쓰기 [IFieldType](../../com.aspose.slides/ifieldtype).

**반환:**  
[IFieldType](../../com.aspose.slides/ifieldtype)
### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```

필드의 유형을 반환하거나 설정합니다. 읽기/쓰기 [IFieldType](../../com.aspose.slides/ifieldtype).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

단락의 상위 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

단락의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**  
[IPresentation](../../com.aspose.slides/ipresentation)