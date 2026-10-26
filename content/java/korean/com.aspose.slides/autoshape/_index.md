---
title: AutoShape
second_title: Aspose.Slides for Java API 레퍼런스
description: AutoShape을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/autoshape/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)  
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

AutoShape을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | shape의 잠금을 반환합니다. |
| [getAutoShapeLock()](#getAutoShapeLock--) | autoshape의 잠금을 반환합니다. |
| [getTextFrame()](#getTextFrame--) | AutoShape에 대한 TextFrame 객체를 반환합니다. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 이 autoshape을(를) 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 이 autoshape을(를) 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | shape에 새로운 TextFrame을 추가합니다. |
| [isTextBox()](#isTextBox--) | shape이 텍스트 상자인지 지정합니다. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

shape의 잠금을 반환합니다. 읽기 전용 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**반환:**  
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

autoshape의 잠금을 반환합니다. 읽기 전용 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**반환:**  
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

AutoShape에 대한 TextFrame 객체를 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

이 autoshape을(를) 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. 읽기/쓰기 부울.

**반환:**  
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

이 autoshape을(를) 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

shape에 새로운 TextFrame을 추가합니다. shape에 이미 TextFrame이 있는 경우 해당 텍스트만 변경합니다.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // Instantiates Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adds an AutoShape with type set as Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Adds TextFrame to the Rectangle
>      ashp.addTextFrame(" ");
>      // Accesses the text frame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Creates the Paragraph object for text frame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Creates a Portion object for the paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // Sets the text
>      portion.setText("Aspose TextBox");
>      // Saves the presentation to disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Add an AutoShape with type set as Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Add TextFrame to the Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Gets the text format of TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Specifies the number of columns in TextFrame
>      format.setColumnCount(3);
>      // Specifies the spacing between columns
>      format.setColumnSpacing(10);
>      // Saves the presentation
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrame에 대한 기본 텍스트. |

**반환:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

shape이 텍스트 상자인지 지정합니다.

--------------------

shape이 텍스트 상자로 지정되지 않았다고 해서 텍스트를 붙일 수 없다는 의미는 아닙니다. 텍스트 상자는 단지 특정 속성을 가진 특수한 shape에 불과합니다.

**반환:**  
boolean