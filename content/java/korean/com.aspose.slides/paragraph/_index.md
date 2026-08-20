---
title: Paragraph
second_title: Aspose.Slides for Java API 레퍼런스
description: 텍스트 단락을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/paragraph/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
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
| [getPortions()](#getPortions--) | 텍스트 부분 컬렉션을 반환합니다. |
| [getParagraphFormat()](#getParagraphFormat--) | 이 단락에 대한 서식 객체를 반환합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 같은 서식을 가진 실행을 결합합니다. |
| [getText()](#getText--) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [getRect()](#getRect--) | 단락을 둘러싸는 사각형의 좌표를 가져옵니다. |
| [getLinesCount()](#getLinesCount--) | 단락의 행 수를 가져옵니다. |
| [getImage()](#getImage--) | 단락의 이미지를 반환합니다. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 지정된 배율로 단락의 이미지를 반환합니다. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 단락의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 단락의 부모 프레젠테이션을 반환합니다. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Paragraph 클래스를 기본 속성으로 새 인스턴스로 초기화합니다.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

복사 생성자이며, Paragraph 클래스의 새 인스턴스를 초기화합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |
### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

텍스트 부분 컬렉션을 반환합니다. 읽기 전용 [IPortionCollection](../../com.aspose.slides/iportioncollection).

**반환값:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

이 단락에 대한 서식 객체를 반환합니다. 읽기 전용 [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

서식 객체는 현재 단락에만 정의된 서식 매개변수를 포함하며, 상속된 데이터는 적용되지 않습니다.

상속된 값을 포함한 실제 값을 얻으려면 [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 메서드를 사용하십시오.

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

같은 서식을 가진 실행을 결합합니다.

### getText() {#getText--}
```
public final String getText()
```

단락의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**반환값:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

단락의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

단락을 둘러싸는 사각형의 좌표를 가져옵니다. 이 사각형은 빈 줄을 포함하여 단락의 모든 텍스트 줄을 포함합니다.

**반환값:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

단락의 행 수를 가져옵니다.

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
int - 단락의 행 수
### getImage() {#getImage--}
```
public final IImage getImage()
```

단락의 이미지를 반환합니다.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[IImage](../../com.aspose.slides/iimage) - 렌더링된 단락을 포함하는 이미지이며, 단락을 부모 컬렉션에서 찾을 수 없거나 유효한 렌더링 경계가 없거나 이미지를 렌더링하는 중 오류가 발생하면 null을 반환합니다.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

지정된 배율로 단락의 이미지를 반환합니다.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | float | 단락 이미지에 적용되는 수평 배율 인자입니다. |
| scaleY | float | 단락 이미지에 적용되는 수직 배율 인자입니다. |

**반환값:**
[IImage](../../com.aspose.slides/iimage) - 렌더링된 단락을 포함하는 이미지이며, 단락을 부모 컬렉션에서 찾을 수 없거나 유효한 렌더링 경계가 없거나 이미지를 렌더링하는 중 오류가 발생하면 null을 반환합니다.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다.

**반환값:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

단락의 부모 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환값:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

단락의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**
[IPresentation](../../com.aspose.slides/ipresentation)