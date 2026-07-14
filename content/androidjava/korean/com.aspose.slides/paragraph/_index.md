---
title: Paragraph
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 텍스트 단락을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/paragraph/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

텍스트 단락을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Paragraph()](#Paragraph--) | Paragraph 클래스를 기본 속성으로 새 인스턴스로 초기화합니다. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Paragraph 클래스의 새 인스턴스를 초기화하는 복사 생성자입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPortions()](#getPortions--) | 텍스트 부분의 컬렉션을 반환합니다. |
| [getParagraphFormat()](#getParagraphFormat--) | 이 단락에 대한 서식 개체를 반환합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 동일한 서식을 가진 실행을 결합합니다. |
| [getText()](#getText--) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [getRect()](#getRect--) | 단락을 둘러싸는 사각형의 좌표를 가져옵니다. |
| [getLinesCount()](#getLinesCount--) | 단락의 줄 수를 가져옵니다. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 다른 부분이 마지막 뒤에 삽입될 경우 사용할 부분 속성을 지정합니다. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 다른 부분이 마지막 뒤에 삽입될 경우 사용할 부분 속성을 지정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 단락의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 단락의 상위 프레젠테이션을 반환합니다. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Paragraph 클래스를 기본 속성으로 새 인스턴스로 초기화합니다.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

복사 생성자 that initializes a new instance of a Paragraph class.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

텍스트 부분의 컬렉션을 반환합니다. 읽기 전용 [IPortionCollection](../../com.aspose.slides/iportioncollection).

**반환값:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

이 단락에 대한 서식 개체를 반환합니다. 읽기 전용 [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

서식 개체는 현재 단락에만 정의된 서식 매개변수를 포함하며, 상속된 데이터는 적용되지 않습니다.

상속된 값을 포함한 실제 값을 얻으려면 [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 메서드를 사용하십시오.

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

동일한 서식을 가진 실행을 결합합니다.

### getText() {#getText--}
```
public final String getText()
```

단락의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 문자열.

값: 텍스트.

**반환값:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

단락의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 문자열.

값: 텍스트.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

단락을 둘러싸는 사각형의 좌표를 가져옵니다. 이 사각형은 단락의 모든 텍스트 줄을 포함하며 빈 줄도 포함합니다.

**반환값:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

단락의 줄 수를 가져옵니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
int - 단락의 줄 수
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

다른 부분이 마지막 뒤에 삽입될 경우 사용할 부분 속성을 지정합니다.

**반환값:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

다른 부분이 마지막 뒤에 삽입될 경우 사용할 부분 속성을 지정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 개체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

단락의 상위 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환값:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

단락의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**
[IPresentation](../../com.aspose.slides/ipresentation)