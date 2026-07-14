---
title: Shape
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드의 도형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/shape/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

슬라이드의 도형을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 텍스트 보류자(TextHolder_PPT)인지 여부를 확인합니다. |
| [getPlaceholder()](#getPlaceholder--) | 도형의 자리 표시자를 반환합니다. |
| [removePlaceholder()](#removePlaceholder--) | 이 도형이 자리 표시자가 아님을 정의합니다. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 자리 표시자가 없을 경우 새 자리 표시자를 추가하고 지정된 자리 표시자 속성을 설정합니다. |
| [getBasePlaceholder()](#getBasePlaceholder--) | 기본 자리 표시자 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형). |
| [getCustomData()](#getCustomData--) | 도형의 사용자 정의 데이터를 반환합니다. |
| [getRawFrame()](#getRawFrame--) | 원시 도형 프레임 속성을 반환하거나 설정합니다. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 원시 도형 프레임 속성을 반환하거나 설정합니다. |
| [getFrame()](#getFrame--) | 원시 도형 프레임 속성을 반환하거나 설정합니다. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 원시 도형 프레임 속성을 반환하거나 설정합니다. |
| [getLineFormat()](#getLineFormat--) | 도형에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. |
| [getThreeDFormat()](#getThreeDFormat--) | 도형에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. |
| [getFillFormat()](#getFillFormat--) | 도형에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. |
| [getImage()](#getImage--) | 도형 썸네일을 반환합니다. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 도형 썸네일을 반환합니다. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 도형의 내용을 SVG 파일로 저장합니다. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 도형의 내용을 SVG 파일로 저장합니다. |
| [getHyperlinkClick()](#getHyperlinkClick--) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. |
| [getHyperlinkManager()](#getHyperlinkManager--) | 하이퍼링크 관리자를 반환합니다. |
| [getHidden()](#getHidden--) | 도형이 숨겨져 있는지 여부를 확인합니다. |
| [setHidden(boolean value)](#setHidden-boolean-) | 도형이 숨겨져 있는지 여부를 확인합니다. |
| [getZOrderPosition()](#getZOrderPosition--) | z-순서에서 도형의 위치를 반환합니다. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 도형의 연결 지점 수를 반환합니다. |
| [getRotation()](#getRotation--) | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. |
| [setRotation(float value)](#setRotation-float-) | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. |
| [getX()](#getX--) | 도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다. |
| [setX(float value)](#setX-float-) | 도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다. |
| [getY()](#getY--) | 도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다. |
| [setY(float value)](#setY-float-) | 도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 도형의 너비를 포인트 단위로 가져오거나 설정합니다. |
| [getHeight()](#getHeight--) | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 도형의 높이를 포인트 단위로 가져오거나 설정합니다. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. |
| [getUniqueId()](#getUniqueId--) | 애드인 또는 기타 코드에서 사용하도록 의도된 프레젠테이션 범위 내부 식별자를 반환합니다. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 신뢰성 있게 참조할 수 있게 합니다. |
| [getAlternativeText()](#getAlternativeText--) | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. |
| [getName()](#getName--) | 도형의 이름을 반환하거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 도형의 이름을 반환하거나 설정합니다. |
| [isDecorative()](#isDecorative--) | ‘장식용으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | ‘장식용으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean. |
| [getShapeLock()](#getShapeLock--) | 도형의 잠금을 반환합니다. |
| [isGrouped()](#isGrouped--) | 도형이 그룹화되어 있는지 여부를 확인합니다. |
| [getParentGroup()](#getParentGroup--) | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | 렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다. |
| [getSlide()](#getSlide--) | 도형의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 슬라이드의 상위 프레젠테이션을 반환합니다. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

도형이 TextHolder_PPT인지 여부를 확인합니다. 읽기 전용 boolean .

**반환:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

도형의 자리 표시자를 반환합니다. 도형에 자리 표시자가 없으면 null을 반환합니다. 읽기 전용 [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Presentation 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // 첫 번째 슬라이드에 접근합니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 자리 표시자를 찾기 위해 도형을 반복합니다
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // 각 자리 표시자의 텍스트를 변경합니다
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // 슬라이드를 반복합니다
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint에서 "Click to add title"을 표시합니다
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // 자막을 추가합니다
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```


**반환:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

이 도형이 자리 표시자가 아님을 정의합니다.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

새 자리 표시자가 없을 경우 추가하고 지정된 자리 표시자 속성을 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 복사할 내용이 있는 자리 표시자. |

**반환:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

기본 자리 표시자 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형).

--------------------

> ```
> // 자리 표시자 도형의 (마스터/레이아웃/슬라이드) 모든 애니메이션 효과를 가져옵니다
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

현재 도형이 상속받지 않은 경우 null을 반환합니다.

**반환:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../com.aspose.slides/icustomdata).

**반환:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

원시 도형 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> // IShape.getFrame()에 정의되지 않은 프레임을 할당하려는 코드는 일반적인 경우(특히 상위 GroupShape가 다른 GroupShape에 여러 번 중첩된 경우)에 의미가 없습니다. 예시:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //또는
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //이러한 코드는 불명확한 상황을 초래할 수 있습니다. 따라서 IShape.getFrame()에 정의되지 않은 값을 사용하는 데 제한이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어 있어야 합니다 (Float.NaN 또는 NullableBool.NotDefined가 아니어야 함). 위의 예제 코드는 이제 ArgumentException 예외를 발생시킵니다.
>  //이 경우에 적용됩니다:
>  IShape shape = ...;
>  shape.setFrame(...); // 정의될 수 없습니다
>  IShapeCollection shapes = ...;
>  // x, y, width, height 매개변수는 Float.NaN일 수 없습니다:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //하지만 IShape.RawFrame 프레임 속성은 정의되지 않을 수 있습니다. 이는 도형이 자리 표시자에 연결된 경우에 의미가 있습니다. 그런 경우 정의되지 않은 도형 프레임 값은 상위 자리 표시자 도형에서 대체됩니다. 해당 도형에 상위 자리 표시자 도형이 없으면 IShape.RawFrame을 기반으로 유효 프레임을 평가할 때 기본값을 사용합니다. 기본값은 x, y, width, height, flipH, flipV 및 rotationAngle에 대해 0 및 NullableBool.False 입니다. 예시:
>  IShape shape = ...; // 도형이 자리 표시자에 연결됩니다
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 이제 도형은 자리 표시자에서 x, y, height, flipH, flipV 값을 상속하고 width=100 및 rotationAngle=0을 재정의합니다.{code}
> ```


**반환:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

원시 도형 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //또는
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //이러한 코드는 불명확한 상황을 초래할 수 있습니다. 따라서 IShape.getFrame()에 정의되지 않은 값을 사용하는 데 제한이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어야 합니다 (Float.NaN 또는 NullableBool.NotDefined가 아님). 위의 예제 코드는 이제 ArgumentException 예외를 발생시킵니다.
>  //이는 다음 사용 사례에 적용됩니다:
>  IShape shape = ...;
>  shape.setFrame(...); // 정의될 수 없습니다
>  IShapeCollection shapes = ...;
>  // x, y, width, height 매개변수는 Float.NaN일 수 없습니다:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //하지만 IShape.RawFrame 프레임 속성은 정의되지 않을 수 있습니다. 이는 도형이 자리 표시자에 연결된 경우에 의미가 있습니다. 그런 경우 정의되지 않은 도형 프레임 값은 상위 자리 표시자 도형에서 덮어씌워집니다. 해당 도형에 상위 자리 표시자 도형이 없으면 IShape.RawFrame을 기반으로 유효 프레임을 평가할 때 기본값을 사용합니다. 기본값은 x, y, width, height, flipH, flipV 및 rotationAngle에 대해 0과 NullableBool.False입니다. 예시:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 이제 도형은 자리 표시자에서 x, y, height, flipH, flipV 값을 상속하고 width=100 및 rotationAngle=0을 재정의합니다.{code}
```

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

도형 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

반환된 IShapeFrame 인스턴스의 각 속성 값은 정의되어 있어야 하며(undefined가 아님) NaN이 아닙니다. 할당된 IShapeFrame 인스턴스의 각 속성도 정의되어 있어야 합니다(NaN이 아님). RawFrame 인스턴스 속성에 대해서는 undefined 값을 설정할 수 있습니다.

**반환:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

도형 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

반환된 IShapeFrame 인스턴스의 각 속성 값은 정의되어 있어야 하며(undefined가 아님) NaN이 아닙니다. 할당된 IShapeFrame 인스턴스의 각 속성도 정의되어 있어야 합니다(NaN이 아님). RawFrame 인스턴스 속성에 대해서는 undefined 값을 설정할 수 있습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

도형에 대한 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

도형에 대한 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**반환:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**반환:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

도형에 대한 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 도형 유형에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, 더 밝게 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, 더 밝게 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, 더 밝게 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, 더 어둡게 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, 더 어둡게 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

도형 썸네일을 반환합니다. ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 기본값으로 사용됩니다.

**반환:**
[IImage](../../com.aspose.slides/iimage) - 도형 썸네일.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

도형 썸네일을 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| bounds | int | 도형 썸네일 경계 유형. |
| scaleX | float | X 축 스케일 |
| scaleY | float | Y 축 스케일 |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 도형 썸네일 또는 ShapeThumbnailBounds.Appearance이 사용되고 도형에 보이는 요소가 없을 경우 null.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

도형의 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

도형의 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 생성 옵션 |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

하이퍼링크 관리자를 반환합니다. 읽기 전용 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**반환:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

도형이 숨겨져 있는지 여부를 확인합니다. 읽기/쓰기 boolean .

**반환:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

도형이 숨겨져 있는지 여부를 확인합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

z-순서에서 도형의 위치를 반환합니다. Shapes[0]은 z-순서 뒤쪽에 있는 도형을, Shapes[Shapes.Count - 1]은 앞쪽에 있는 도형을 반환합니다. 읽기 전용 int .

**반환:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

도형의 연결 지점 수를 반환합니다. 읽기 전용 int .

**반환:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며(Float.NaN이 아님) 할당값도 정의되어 있어야 합니다(Float.NaN이 아님). RawFrame 인스턴스 속성에 대해서는 undefined 값을 설정할 수 있습니다.

**반환:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며(Float.NaN이 아님) 할당값도 정의되어 있어야 합니다(Float.NaN이 아님). RawFrame 인스턴스 속성에 대해서는 undefined 값을 설정할 수 있습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**반환:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**반환:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

도형의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**반환:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

도형의 너비를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

도형의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**반환:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

도형의 높이를 포인트 단위로 가져오거나 설정합니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있으며 Float.NaN이 아닙니다. 할당값도 정의되어 있어야 하며, RawFrame 인스턴스 속성에만 Float.NaN을 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**반환:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

애드인 또는 기타 코드에서 사용하도록 의도된 프레젠테이션 범위 내부 식별자를 반환합니다. 이 값은 사용자 또는 프로그램에 의해 재할당될 수 있으므로 지속적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 long. 또한 \#getOfficeInteropShapeId.getOfficeInteropShapeId를 참조하십시오.

**반환:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

슬라이드 범위 고유 식별자를 반환하며, 이는 도형의 수명 동안 일정하게 유지되어 PowerPoint 또는 인터옵 코드가 문서 어디서든 도형을 신뢰성 있게 참조할 수 있게 합니다. 읽기 전용 long. 또한 \#getUniqueId.getUniqueId를 참조하십시오.

**반환:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

도형에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

도형에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

도형의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요하면 빈 문자열을 사용하십시오. 읽기/쓰기 String.

**반환:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

도형의 이름을 반환하거나 설정합니다. null이 될 수 없습니다. 필요하면 빈 문자열을 사용하십시오. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

‘장식용으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

‘장식용으로 표시’ 옵션을 가져오거나 설정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

도형의 잠금을 반환합니다. 읽기 전용 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**반환:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

도형이 그룹화되어 있는지 여부를 확인합니다. 읽기 전용 boolean.

--------------------

속성 \#getParentGroup.getParentGroup은 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다.

**반환:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

속성 \#isGrouped.isGrouped은 도형이 그룹화되어 있는지 여부를 결정합니다.

**반환:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

렌더링된 콘텐츠에서 계산된 도형의 시각적 경계를 가져옵니다.

**반환:**
android.graphics.RectF - 슬라이드 좌표계에서 도형의 시각적 경계를 나타내는 android.graphics.RectF.

--------------------

반환된 사각형은 슬라이드 좌표 공간에서 도형이 렌더링되는 동안 생성된 모든 콘텐츠의 축에 정렬된 경계를 나타냅니다. 이 경계는 도형의 모델 경계(\#getX.getX/\#setX(float), \#getY.getY/\#setY(float), \#getWidth.getWidth/\#setWidth(float), \#getHeight.getHeight/\#setHeight(float))와 다를 수 있으며, 렌더링된 콘텐츠가 슬라이드 원점을 넘어설 경우 음수 좌표를 포함할 수 있습니다. 시각적 경계는 회전, 스트로크 너비 및 조인, 텍스트 레이아웃 및 오버플로, SmartArt 기하학 및 최종 렌더링 외관에 영향을 주는 기타 레이아웃 효과와 같은 렌더링 관련 측면을 고려합니다. 반환된 경계는 슬라이드 사각형으로 잘리지 않습니다.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

도형의 상위 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
IP
```

슬라이드의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)