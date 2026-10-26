---
title: IParagraph
second_title: Aspose.Slides for Java API 레퍼런스
description: 텍스트의 단락을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iparagraph/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

텍스트의 단락을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPortions()](#getPortions--) | 텍스트 구문의 컬렉션을 반환합니다. |
| [getParagraphFormat()](#getParagraphFormat--) | 이 단락에 대한 형식 지정 객체를 반환합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 동일한 형식의 실행을 병합합니다. |
| [getText()](#getText--) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [getRect()](#getRect--) | 단락을 둘러싼 사각형의 좌표를 가져옵니다. |
| [getLinesCount()](#getLinesCount--) | 단락의 줄 수를 가져옵니다. |
| [getImage()](#getImage--) | 단락의 이미지를 반환합니다. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 지정된 배율로 단락의 이미지를 반환합니다. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 마지막 구문 뒤에 다른 구문이 삽입될 경우 사용될 구문 속성을 지정합니다. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 마지막 구문 뒤에 다른 구문이 삽입될 경우 사용될 구문 속성을 지정합니다. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

텍스트 구문의 컬렉션을 반환합니다. 읽기 전용 [IPortionCollection](../../com.aspose.slides/iportioncollection).

**반환값:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

이 단락에 대한 형식 지정 객체를 반환합니다. 읽기 전용 [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

동일한 형식의 실행을 병합합니다.

### getText() {#getText--}
```
public abstract String getText()
```

단락의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**반환값:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

단락의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

단락을 둘러싼 사각형의 좌표를 가져옵니다. 사각형은 빈 줄을 포함한 단락의 모든 텍스트 줄을 포함합니다.

**반환값:**
java.awt.geom.Rectangle2D.Float - 단락을 둘러싼 사각형 java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
### getImage() {#getImage--}
```
public abstract IImage getImage()
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
[IImage](../../com.aspose.slides/iimage) - 렌더링된 단락을 포함하는 이미지, 또는 단락을 상위 컬렉션에서 찾을 수 없거나 유효한 렌더링 경계가 없거나 이미지를 렌더링하는 동안 오류가 발생한 경우 null.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | float | 단락 이미지에 적용되는 수평 배율 계수. |
| scaleY | float | 단락 이미지에 적용되는 수직 배율 계수. |

**반환값:**
[IImage](../../com.aspose.slides/iimage) - 렌더링된 단락을 포함하는 이미지, 또는 단락을 상위 컬렉션에서 찾을 수 없거나 유효한 렌더링 경계가 없거나 이미지를 렌더링하는 동안 오류가 발생한 경우 null.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

마지막 구문 뒤에 다른 구문이 삽입될 경우 사용될 구문 속성을 지정합니다.

**반환값:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

마지막 구문 뒤에 다른 구문이 삽입될 경우 사용될 구문 속성을 지정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |