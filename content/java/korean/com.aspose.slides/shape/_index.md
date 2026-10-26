---
title: Shape
second_title: Aspose.Slides for Java API 레퍼런스
description: 슬라이드에 있는 도형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/shape/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

슬라이드상의 모양을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 형상이 TextHolder_PPT인지 여부를 결정합니다. |
| [getPlaceholder()](#getPlaceholder--) | 형상의 placeholder를 반환합니다. |
| [removePlaceholder()](#removePlaceholder--) | 이 형상이 placeholder가 아님을 정의합니다. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 새 placeholder가 없으면 추가하고, 지정된 placeholder에 대한 속성을 설정합니다. |
| [getBasePlaceholder()](#getBasePlaceholder--) | 기본 placeholder shape를 반환합니다(현재 형상이 상속받은 레이아웃 및/또는 마스터 슬라이드의 shape). |
| [getCustomData()](#getCustomData--) | 형상의 사용자 정의 데이터를 반환합니다. |
| [getRawFrame()](#getRawFrame--) | 원시 shape 프레임 속성을 반환하거나 설정합니다. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 원시 shape 프레임 속성을 반환하거나 설정합니다. |
| [getFrame()](#getFrame--) | shape 프레임 속성을 반환하거나 설정합니다. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | shape 프레임 속성을 반환하거나 설정합니다. |
| [getLineFormat()](#getLineFormat--) | 형상의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. |
| [getThreeDFormat()](#getThreeDFormat--) | 형상의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | 형상에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. |
| [getFillFormat()](#getFillFormat--) | 형상의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. |
| [getImage()](#getImage--) | shape 썸네일을 반환합니다. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | shape 썸네일을 반환합니다. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Shape 내용을 SVG 파일로 저장합니다. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Shape 내용을 SVG 파일로 저장합니다. |
| [getHyperlinkClick()](#getHyperlinkClick--) | 마우스 클릭에 정의된 hyperlink를 반환하거나 설정합니다. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | 마우스 클릭에 정의된 hyperlink를 반환하거나 설정합니다. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 마우스 오버에 정의된 hyperlink를 반환하거나 설정합니다. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | 마우스 오버에 정의된 hyperlink를 반환하거나 설정합니다. |
| [getHyperlinkManager()](#getHyperlinkManager--) | hyperlink 관리자를 반환합니다. |
| [getHidden()](#getHidden--) | 형상이 숨겨져 있는지 여부를 결정합니다. |
| [setHidden(boolean value)](#setHidden-boolean-) | 형상이 숨겨져 있는지 여부를 결정합니다. |
| [getZOrderPosition()](#getZOrderPosition--) | z-순서에서 형상의 위치를 반환합니다. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 형상의 연결 지점 수를 반환합니다. |
| [getRotation()](#getRotation--) | 지정된 형상이 z축을 기준으로 회전된 각도를 반환하거나 설정합니다. |
| [setRotation(float value)](#setRotation-float-) | 지정된 형상이 z축을 기준으로 회전된 각도를 반환하거나 설정합니다. |
| [getX()](#getX--) | 포인트 단위로 측정된 shape의 왼쪽 위 모서리의 x좌표를 가져오거나 설정합니다. |
| [setX(float value)](#setX-float-) | 포인트 단위로 측정된 shape의 왼쪽 위 모서리의 x좌표를 가져오거나 설정합니다. |
| [getY()](#getY--) | 포인트 단위로 측정된 shape의 왼쪽 위 모서리의 y좌표를 가져오거나 설정합니다. |
| [setY(float value)](#setY-float-) | 포인트 단위로 측정된 shape의 왼쪽 위 모서리의 y좌표를 가져오거나 설정합니다. |
| [getWidth()](#getWidth--) | 포인트 단위로 측정된 shape의 너비를 가져오거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 포인트 단위로 측정된 shape의 너비를 가져오거나 설정합니다. |
| [getHeight()](#getHeight--) | 포인트 단위로 측정된 shape의 높이를 가져오거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 포인트 단위로 측정된 shape의 높이를 가져오거나 설정합니다. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 속성은 shape가 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 속성은 shape가 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. |
| [getUniqueId()](#getUniqueId--) | 애드인 또는 기타 코드에서 사용하도록 의도된 내부 프레젠테이션 범위 식별자를 반환합니다. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | shape의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint나 인터옵 코드가 문서 어디서든 shape를 안정적으로 참조할 수 있게 합니다. |
| [getAlternativeText()](#getAlternativeText--) | shape와 연결된 대체 텍스트를 반환하거나 설정합니다. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | shape와 연결된 대체 텍스트를 반환하거나 설정합니다. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | shape와 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. |
| [getName()](#getName--) | shape의 이름을 반환하거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | shape의 이름을 반환하거나 설정합니다. |
| [isDecorative()](#isDecorative--) | 'Mark as decorative' 옵션을 읽기/쓰기 부울로 가져오거나 설정합니다. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 'Mark as decorative' 옵션을 읽기/쓰기 부울로 가져오거나 설정합니다. |
| [getShapeLock()](#getShapeLock--) | shape의 잠금 정보를 반환합니다. |
| [isGrouped()](#isGrouped--) | shape가 그룹화되어 있는지 여부를 결정합니다. |
| [getParentGroup()](#getParentGroup--) | shape가 그룹화된 경우 상위 GroupShape 객체를 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | 렌더링된 콘텐츠로부터 계산된 shape의 시각적 경계값을 가져옵니다. |
| [getSlide()](#getSlide--) | shape의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 슬라이드의 상위 프레젠테이션을 반환합니다. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

형상이 TextHolder_PPT인지 여부를 결정합니다. 읽기 전용  boolean .

**반환:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

shape의 placeholder를 반환합니다. shape에 placeholder가 없으면 null을 반환합니다. 읽기 전용 [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // 프레젠테이션 클래스를 인스턴스화합니다
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // 첫 번째 슬라이드에 접근합니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 플레이스홀더를 찾기 위해 셰이프를 순회합니다
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // 각 플레이스홀더의 텍스트를 변경합니다
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
>      for (IShape shape : slide.getSlide().getShapes()) // 슬라이드를 순회합니다
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint가 "Click to add title"을 표시합니다
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
> ```


**반환:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```
Defines that this shape isn’t a placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

새 자리 표시자가 없을 경우 추가하고, 지정된 자리 표시자에 대한 속성을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 복사할 내용이 있는 자리 표시자. |

**Returns:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New \#getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

기본 자리 표시자 도형을 반환합니다(레이아웃 및/또는 마스터 슬라이드에서 현재 도형이 상속되는 도형).

--------------------

> ```
> // 플래이스홀더 도형의 (마스터/레이아웃/슬라이드) 모든 애니메이션 효과를 가져옵니다
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

현재 도형이 상속되지 않은 경우 null이 반환됩니다.

**Returns:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

도형의 사용자 지정 데이터를 반환합니다. 읽기 전용 [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

원시 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //또는
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //이러한 코드는 모호한 상황을 초래할 수 있습니다. 따라서 IShape.getFrame()에 정의되지 않은 값을 사용하는 제한이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어야 합니다 (Float.NaN 또는 NullableBool.NotDefined가 아니어야 함). 위 예제 코드는 이제 ArgumentException 예외를 발생시킵니다.
>  //다음 사용 사례에 적용됩니다:
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
>  //하지만 IShape.RawFrame 프레임 속성은 정의되지 않을 수 있습니다. 이는 shape가 placeholder에 연결된 경우에 의미가 있습니다. 그런 경우 정의되지 않은 shape 프레임 값은 부모 placeholder shape에서 재정의됩니다. 해당 shape에 부모 placeholder shape가 없으면 IShape.RawFrame을 기반으로 실제 프레임을 계산할 때 기본값을 사용합니다. 기본값은 x, y, width, height, flipH, flipV 및 rotationAngle에 대해 0 및 NullableBool.False입니다. 예를 들어:
>  IShape shape = ...; // shape는 placeholder에 연결됨
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 이제 shape는 placeholder에서 x, y, height, flipH, flipV 값을 상속하고 width=100 및 rotationAngle=0을 재정의합니다.{code}
> ```


**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

원시 도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //또는
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //이러한 코드는 모호한 상황을 초래할 수 있습니다. 따라서 IShape.getFrame()에 정의되지 않은 값을 사용하는 것을 제한하는 규칙이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어야 합니다 (Float.NaN 또는 NullableBool.NotDefined가 아니어야 함). 위 예제 코드는 이제 ArgumentException 예외를 발생시킵니다.
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
>  //하지만 IShape.RawFrame 프레임 속성은 정의되지 않을 수 있습니다. 이는 shape가 placeholder에 연결된 경우에 의미가 있습니다. 그런 경우 정의되지 않은 shape 프레임 값은 부모 placeholder shape에서 재정의됩니다. 해당 shape에 부모 placeholder shape가 없으면 IShape.RawFrame을 기반으로 실제 프레임을 계산할 때 기본값을 사용합니다. 기본값은 x, y, width, height, flipH, flipV 및 rotationAngle에 대해 0 및 NullableBool.False입니다. 예를 들어:
>  IShape shape = ...; // shape는 placeholder에 연결되어 있습니다
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 이제 shape는 placeholder에서 x, y, height, flipH, flipV 값을 상속하고 width=100 및 rotationAngle=0을 재정의합니다.{code}
> ```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

반환된 IShapeFrame 인스턴스의 각 속성 값은 undefined가 아니어야 합니다(NaN 또는 NotDefined가 아님). 할당된 IShapeFrame 인스턴스의 각 속성 값도 undefined가 아니어야 합니다(NaN 또는 NotDefined가 아님). RawFrame 인스턴스 속성에 undefined 값을 설정할 수 있습니다.

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

도형 프레임의 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

반환된 IShapeFrame 인스턴스의 각 속성 값은 undefined가 아니어야 합니다(NaN 또는 NotDefined가 아님). 할당된 IShapeFrame 인스턴스의 각 속성 값도 undefined가 아니어야 합니다(NaN 또는 NotDefined가 아님). RawFrame 인스턴스 속성에 undefined 값을 설정할 수 있습니다.
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

형상의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 참고: 선 속성이 없는 특정 종류의 형상에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환값:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

형상의 3D 효과 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 참고: 3D 속성이 없는 특정 종류의 형상에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**반환값:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

형상에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 참고: 효과 속성이 없는 특정 종류의 형상에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**반환값:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

형상의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 참고: 채우기 속성이 없는 특정 종류의 형상에 대해서는 null을 반환할 수 있습니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

형상의 썸네일을 반환합니다. 기본값으로 ShapeThumbnailBounds.Shape 형태 썸네일 경계 유형이 사용됩니다.

**반환값:**  
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

형상의 썸네일을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bounds | int | 형상 썸네일 경계 유형. |
| scaleX | float | X 스케일 |
| scaleY | float | Y 스케일 |

**반환값:**  
[IImage](../../com.aspose.slides/iimage) - ShapeThumbnailBounds.Appearance이 사용되고 형상에 가시적인 요소가 없을 경우 null을 반환하는 형상 썸네일.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

형상의 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

형상의 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 생성 옵션 |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환값:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

마우스 클릭에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환값:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

마우스 오버에 정의된 하이퍼링크를 반환하거나 설정합니다. 읽기/쓰기 [IHyperlink](../../com.aspose.slides/ihyperlink).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

하이퍼링크 관리자를 반환합니다. 읽기 전용 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**반환값:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

형상이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

형상이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

z-순서에서 형상의 위치를 반환합니다. Shapes[0]은 z-순서의 뒤쪽에 있는 형상을 반환하고, Shapes[Shapes.Count - 1]은 앞쪽에 있는 형상을 반환합니다. 읽기 전용 int.

**반환값:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

형상의 연결 지점 수를 반환합니다. 읽기 전용 int.

**반환값:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

지정된 형상이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을 나타내며, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 float.

--------------------

반환값은 항상 정의되어 있습니다 (Float.NaN이 아님). 할당된 값도 정의되어 있어야 합니다 (Float.NaN이 아님). RawFrame 인스턴스 속성에 대해 정의되지 않은 값을 설정할 수 있습니다.

**반환값:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. 읽기/쓰기 float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Gets or sets the width of the shape, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Gets or sets the width of the shape, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Gets or sets the height of the shape, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Gets or sets the height of the shape, measured in points. 읽기/쓰기 float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Property specifies how a shape will render in black-and-white display mode.. 읽기/쓰기 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returns:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Property specifies how a shape will render in black-and-white display mode.. 읽기/쓰기 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. 읽기 전용 long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returns:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. 읽기 전용 long. See also \#getUniqueId.getUniqueId.

**Returns:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Returns or sets the alternative text associated with a shape. 읽기/쓰기 String.

**Returns:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Returns or sets the alternative text associated with a shape. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Returns or sets the title of alternative text associated with a shape. 읽기/쓰기 String.

**Returns:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Returns or sets the title of alternative text associated with a shape. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. 읽기/쓰기 String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Gets or sets 'Mark as decorative' option Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Gets or sets 'Mark as decorative' option Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Returns shape's locks. 읽기 전용 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returns:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determines whether the shape is grouped. 읽기 전용 boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Returns:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Returns parent GroupShape object if shape is grouped. Otherwise returns null. 읽기 전용 [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. 읽기 전용 IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Gets the visual bounds of the shape calculated from its rendered content.

**Returns:**
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float that represents the visual bounds of the shape in slide coordinates.

--------------------

The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space. These bounds may differ from the shape's model bounds \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) and may contain negative coordinates if the rendered content extends beyond the slide origin. The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, SmartArt geometry, and other layout effects that influence the final rendered appearance of the shape. The returned bounds are not clipped to the slide rectangle.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a shape. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a slide. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)