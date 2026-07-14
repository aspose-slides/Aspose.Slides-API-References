---
title: TextFrameFormat
second_title: Java API 참조용 Android용 Aspose.Slides
description: TextFrames의 formatTextFrameFormatting 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/textframeformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

TextFrame의 formatTextFrameFormatting 속성을 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | [TextFrameFormat](../../com.aspose.slides/textframeformat) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | 텍스트 스타일을 반환합니다. |
| [getThreeDFormat()](#getThreeDFormat--) | 텍스트에 대한 3d 효과 속성을 나타내는 ThreeDFormat 객체를 반환합니다. |
| [getMarginLeft()](#getMarginLeft--) | TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginTop()](#getMarginTop--) | TextFrame의 상단 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame의 상단 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginBottom()](#getMarginBottom--) | TextFrame의 하단 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame의 하단 여백(포인트)을 반환하거나 설정합니다. |
| [getWrapText()](#getWrapText--) | 텍스트가 TextFrame의 여백에 맞게 줄바꿈되는 경우 True. |
| [setWrapText(byte value)](#setWrapText-byte-) | 텍스트가 TextFrame의 여백에 맞게 줄바꿈되는 경우 True. |
| [getAnchoringType()](#getAnchoringType--) | TextFrame에서 수직 앵커 텍스트를 반환하거나 설정합니다. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame에서 수직 앵커 텍스트를 반환하거나 설정합니다. |
| [getCenterText()](#getCenterText--) | NullableBool.True인 경우 텍스트가 상자 안에서 수평으로 가운데 정렬됩니다. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True인 경우 텍스트가 상자 안에서 수평으로 가운데 정렬됩니다. |
| [getTextVerticalType()](#getTextVerticalType--) | 텍스트 방향을 결정합니다. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 텍스트 방향을 결정합니다. |
| [getAutofitType()](#getAutofitType--) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [getColumnCount()](#getColumnCount--) | 텍스트 영역의 열 수를 반환하거나 설정합니다. |
| [setColumnCount(int value)](#setColumnCount-int-) | 텍스트 영역의 열 수를 반환하거나 설정합니다. |
| [getColumnSpacing()](#getColumnSpacing--) | 텍스트 영역에서 텍스트 열 사이의 간격을 (포인트 단위로) 반환하거나 설정합니다. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | 텍스트 영역에서 텍스트 열 사이의 간격을 (포인트 단위로) 반환하거나 설정합니다. |
| [getRotationAngle()](#getRotationAngle--) | 경계 상자 내에서 텍스트에 적용되는 회전을 사용자 지정으로 지정합니다. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 경계 상자 내에서 텍스트에 적용되는 회전을 사용자 지정으로 지정합니다. |
| [getTransform()](#getTransform--) | 텍스트 래핑 모양을 가져오거나 설정합니다. |
| [setTransform(byte value)](#setTransform-byte-) | 텍스트 래핑 모양을 가져오거나 설정합니다. |
| [getKeepTextFlat()](#getKeepTextFlat--) | 3-D 회전 효과가 적용되었더라도 텍스트를 평면으로 유지하도록 가져오거나 설정합니다. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 3-D 회전 효과가 적용되었더라도 텍스트를 평면으로 유지하도록 가져오거나 설정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

[TextFrameFormat](../../com.aspose.slides/textframeformat) 클래스의 새 인스턴스를 초기화합니다.

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

텍스트 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

텍스트에 대한 3d 효과 속성을 나타내는 ThreeDFormat 객체를 반환합니다. 읽기 전용 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // 텍스트 변환 설정
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // 돌출 설정
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // 컨투어 설정
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // 깊이 설정
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // 재질 설정
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // 조명 설정
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // 카메라 유형 설정
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

TextFrame의 상단 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

TextFrame의 상단 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

TextFrame의 하단 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

TextFrame의 하단 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

텍스트가 TextFrame의 여백에 맞게 줄바꿈되는 경우 True. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

텍스트가 TextFrame의 여백에 맞게 줄바꿈되는 경우 True. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

TextFrame에서 수직 앵커 텍스트를 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**반환:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

TextFrame에서 수직 앵커 텍스트를 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

NullableBool.True인 경우 텍스트가 상자 안에서 수평으로 가운데 정렬됩니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

NullableBool.True인 경우 텍스트가 상자 안에서 수평으로 가운데 정렬됩니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 지정 각도에서 요약된 시각적 텍스트 회전값이 결과값이 됩니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**반환:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 지정 각도에서 요약된 시각적 텍스트 회전값이 결과값이 됩니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

텍스트 영역의 열 수를 반환하거나 설정합니다. 이 값은 양수여야 합니다. 그렇지 않으면 0으로 설정됩니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

텍스트 영역의 열 수를 반환하거나 설정합니다. 이 값은 양수여야 합니다. 그렇지 않으면 0으로 설정됩니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

텍스트 영역에서 텍스트 열 사이의 간격을 (포인트 단위로) 반환하거나 설정합니다. 이 값은 1개 이상의 열이 존재할 때만 적용됩니다. 이 값은 양수여야 합니다. 그렇지 않으면 0으로 설정됩니다. 읽기/쓰기 double.

**반환:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

텍스트 영역에서 텍스트 열 사이의 간격을 (포인트 단위로) 반환하거나 설정합니다. 이 값은 1개 이상의 열이 존재할 때만 적용됩니다. 이 값은 양수여야 합니다. 그렇지 않으면 0으로 설정됩니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

경계 상자 내에서 텍스트에 적용되는 회전을 사용자 지정으로 지정합니다. 지정되지 않은 경우 연결된 모양의 회전이 사용됩니다. 지정된 경우 모양과 독립적으로 적용됩니다. 즉, 모양에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 TextVerticalType 속성의 사전 정의된 수직 유형에서 요약된 시각적 텍스트 회전값이 결과값이 됩니다. 읽기/쓰기 float.

--------------------

> ```
> 도형에 시계 방향으로 90도 회전이 적용된 경우를 고려하십시오. 
>  이에 더해, 텍스트 본문 자체에도 -90도 반시계 방향 회전이 적용됩니다. 
>  반시계 방향으로 적용됩니다. 그러면 결과 도형은
>  회전된 것처럼 보이지만, 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다.
```

**반환:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

경계 상자 내에서 텍스트에 적용되는 회전을 사용자 지정으로 지정합니다. 지정되지 않은 경우 연결된 모양의 회전이 사용됩니다. 지정된 경우 모양과 독립적으로 적용됩니다. 즉, 모양에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 TextVerticalType 속성의 사전 정의된 수직 유형에서 요약된 시각적 텍스트 회전값이 결과값이 됩니다. 읽기/쓰기 float.

--------------------

> ```
> 도형에 시계 방향으로 90도 회전이 적용된 경우를 고려하십시오. 
>  이에 더해, 텍스트 본문 자체에도 -90도 반시계 방향으로 적용됩니다. 
>  그러면 결과 도형은 회전된 것처럼 보이지만, 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다. 
```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

텍스트 래핑 모양을 가져오거나 설정합니다. 읽기/쓰기 [TextShapeType](../../com.aspose.slides/textshapetype).

**반환:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

텍스트 래핑 모양을 가져오거나 설정합니다. 읽기/쓰기 [TextShapeType](../../com.aspose.slides/textshapetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

3-D 회전 효과가 적용되었더라도 텍스트를 평면으로 유지하도록 가져오거나 설정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

3-D 회전 효과가 적용되었더라도 텍스트를 평면으로 유지하도록 가져오거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).