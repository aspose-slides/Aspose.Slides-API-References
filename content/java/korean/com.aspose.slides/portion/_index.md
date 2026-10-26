---
title: Portion
second_title: Aspose.Slides for Java API 레퍼런스
description: 텍스트 단락 안의 텍스트 구간을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/portion/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

텍스트 단락 안의 텍스트 구간을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Portion()](#Portion--) | Portion 클래스를 새 인스턴스로 초기화합니다. |
| [Portion(String str)](#Portion-java.lang.String-) | Portion 클래스를 새 인스턴스로 초기화합니다. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Portion 클래스를 새 인스턴스로 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 상속이 적용되지 않은 텍스트 구간에 대해 명시적으로 설정된 서식 속성을 포함하는 서식 객체를 반환합니다. |
| [getText()](#getText--) | 구간의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 구간의 일반 텍스트를 가져오거나 설정합니다. |
| [getField()](#getField--) | 이 구간의 필드를 반환합니다. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | 이 구간을 자동으로 업데이트되는 필드로 변환합니다. |
| [addField(String internalString)](#addField-java.lang.String-) | 이 구간을 자동으로 업데이트되는 필드로 변환합니다. |
| [removeField()](#removeField--) | 이 필드 구간을 단순 구간으로 변환합니다. |
| [getRect()](#getRect--) | 구간을 둘러싸는 사각형의 좌표를 가져옵니다. |
| [getCoordinates()](#getCoordinates--) | 구간 시작점의 좌표를 가져옵니다. |
| [getSlide()](#getSlide--) | 텍스트가 포함된 슬라이드의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 텍스트가 포함된 프레젠테이션의 상위 프레젠테이션을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```


Portion 클래스를 새 인스턴스로 초기화합니다.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```


Portion 클래스를 새 인스턴스로 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```


Portion 클래스를 새 인스턴스로 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```


상속이 적용되지 않은 텍스트 구간에 대해 명시적으로 설정된 서식 속성을 포함하는 서식 객체를 반환합니다. 읽기 전용 [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

서식 객체는 현재 구간에만 정의된 서식 매개변수를 포함하며, 상속된 데이터는 적용되지 않습니다.

상속된 값을 포함한 실제 값을 얻으려면 [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) 메서드를 사용하십시오.

**반환:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```


구간의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**반환:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


구간의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```


이 구간의 필드를 반환합니다. 읽기 전용 [IField](../../com.aspose.slides/ifield).

**반환:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```


이 구간을 자동으로 업데이트되는 필드로 변환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```


이 구간을 자동으로 업데이트되는 필드로 변환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| internalString | java.lang.String | FieldType의 내부 이름. |

### removeField() {#removeField--}
```
public final void removeField()
```


이 필드 구간을 단순 구간으로 변환합니다.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


구간을 둘러싸는 사각형의 좌표를 가져옵니다. 사각형은 빈 라인을 포함한 구간의 모든 텍스트 라인을 포함합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**반환:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```


구간 시작점의 좌표를 가져옵니다. X 좌표는 왼쪽 여백을 포함한 첫 번째 문자부터 시작하는 구간 시작점을 나타내며, Y 좌표는 위쪽 여백을 포함합니다.

**반환:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


텍스트가 포함된 슬라이드의 상위 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


텍스트가 포함된 프레젠테이션의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject