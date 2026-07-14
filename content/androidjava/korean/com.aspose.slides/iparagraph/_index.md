---
title: IParagraph
second_title: Java API 레퍼런스를 통해 Android용 Aspose.Slides
description: 텍스트의 단락을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iparagraph/
---
**전체 구현된 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

텍스트의 단락을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPortions()](#getPortions--) | 텍스트 부분 컬렉션을 반환합니다. |
| [getParagraphFormat()](#getParagraphFormat--) | 이 단락에 대한 서식 객체를 반환합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 동일한 서식을 가진 실행을 결합합니다. |
| [getText()](#getText--) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | 단락의 일반 텍스트를 가져오거나 설정합니다. |
| [getRect()](#getRect--) | 단락을 둘러싼 사각형의 좌표를 가져옵니다. |
| [getLinesCount()](#getLinesCount--) | 단락의 줄 수를 가져옵니다. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | 마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | 마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

텍스트 부분 컬렉션을 반환합니다. 읽기 전용 [IPortionCollection](../../com.aspose.slides/iportioncollection).

**반환값:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

이 단락에 대한 서식 객체를 반환합니다. 읽기 전용 [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**반환값:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

동일한 서식을 가진 실행을 결합합니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

단락을 둘러싼 사각형의 좌표를 가져옵니다. 이 사각형은 빈 줄을 포함한 단락의 모든 텍스트 줄을 포함합니다.

**반환값:**
android.graphics.RectF - 단락을 둘러싼 사각형 android.graphics.RectF
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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다.

**반환값:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

마지막 부분 뒤에 다른 부분이 삽입될 경우 사용할 부분 속성을 지정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |