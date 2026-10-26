---
title: AutoShape
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: AutoShape을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/autoshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
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
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 이 autoshape을 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 이 autoshape을 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | shape에 새 TextFrame을 추가합니다. |
| [isTextBox()](#isTextBox--) | shape가 텍스트 상자인지 지정합니다. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

shape의 잠금을 반환합니다. 읽기 전용 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returns:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

autoshape의 잠금을 반환합니다. 읽기 전용 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returns:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

AutoShape에 대한 TextFrame 객체를 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

이 autoshape을 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. 읽기/쓰기 부울.

**Returns:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

이 autoshape을 스타일이나 채우기 형식으로 지정하는 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. 읽기/쓰기 부울.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

shape에 새 TextFrame을 추가합니다. shape에 이미 TextFrame이 있으면 단순히 텍스트를 변경합니다.

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
>  // 프레젠테이션을 인스턴스화합니다
>  Presentation pres = new Presentation();
>  try {
>      // 프레젠테이션의 첫 번째 슬라이드를 가져옵니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 형식을 Rectangle로 설정한 AutoShape을 추가합니다
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Rectangle에 TextFrame을 추가합니다
>      ashp.addTextFrame(" ");
>      // 텍스트 프레임에 접근합니다
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // 텍스트 프레임용 Paragraph 객체를 생성합니다
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Paragraph에 대한 Portion 객체를 생성합니다
>      IPortion portion = para.getPortions().get_Item(0);
>      // 텍스트를 설정합니다
>      portion.setText("Aspose TextBox");
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // 프레젠테이션의 첫 번째 슬라이드를 가져옵니다
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 형식을 Rectangle로 설정한 AutoShape을 추가합니다
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Rectangle에 TextFrame을 추가합니다
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // TextFrame의 텍스트 형식을 가져옵니다
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // TextFrame의 열 수를 지정합니다
>      format.setColumnCount(3);
>      // 열 사이의 간격을 지정합니다
>      format.setColumnSpacing(10);
>      // 프레젠테이션을 저장합니다
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrame의 기본 텍스트. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

shape가 텍스트 상자인지 지정합니다.

--------------------

shape가 텍스트 상자로 지정되지 않았다고 해서 텍스트를 첨부할 수 없는 것은 아닙니다. 텍스트 상자는 특정 속성을 가진 특수한 shape입니다.

**Returns:**
boolean