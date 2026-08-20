---
title: IPortion
second_title: Aspose.Slides for Java API 레퍼런스
description: 텍스트 단락 안의 텍스트 부분을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iportion/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

텍스트 단락 안의 텍스트 부분을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | 상속이 적용되지 않은 텍스트 부분에 대해 명시적으로 설정된 서식 속성을 포함하는 서식 객체를 반환합니다. |
| [getText()](#getText--) | 부분의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 부분의 일반 텍스트를 가져오거나 설정합니다. |
| [getField()](#getField--) | 이 부분의 필드를 반환합니다. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | 이 부분을 자동 업데이트되는 필드로 변환합니다. |
| [addField(String internalString)](#addField-java.lang.String-) | 이 부분을 자동 업데이트되는 필드로 변환합니다. |
| [removeField()](#removeField--) | 이 필드 부분을 단순 부분으로 변환합니다. |
| [getRect()](#getRect--) | 부분을 둘러싼 사각형의 좌표를 가져옵니다. |
| [getCoordinates()](#getCoordinates--) | 부분 시작점의 좌표를 가져옵니다. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

상속이 적용되지 않은 텍스트 부분에 대해 명시적으로 설정된 서식 속성을 포함하는 서식 객체를 반환합니다. 읽기 전용 [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

서식 객체는 현재 부분에만 정의된 서식 매개변수를 포함하며, 상속된 데이터는 적용되지 않습니다.

상속된 값을 포함한 실제 값을 얻으려면 [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) 메서드를 사용하십시오.

**반환값:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

부분의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**반환값:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

부분의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

이 부분의 필드를 반환합니다. 읽기 전용 [IField](../../com.aspose.slides/ifield).

**반환값:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

이 부분을 자동 업데이트되는 필드로 변환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | 필드 유형 [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

이 부분을 자동 업데이트되는 필드로 변환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| internalString | java.lang.String | FieldTypeEx String의 내부 이름 |
### removeField() {#removeField--}
```
public abstract void removeField()
```

이 필드 부분을 단순 부분으로 변환합니다.
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

부분을 둘러싼 사각형의 좌표를 가져옵니다. 이 사각형은 빈 줄을 포함한 모든 텍스트 라인을 포함합니다.

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


**반환값:**
java.awt.geom.Rectangle2D.Float - 부분을 둘러싼 사각형 java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

부분 시작점의 좌표를 가져옵니다. 점의 X 좌표는 왼쪽 측면 베어링을 포함하여 첫 번째 문자를 시작점으로 나타냅니다. Y 좌표는 상단 측면 베어링을 포함합니다.

**반환값:**
java.awt.geom.Point2D.Float - 부분 시작점의 좌표 java.awt.geom.Point2D.Float