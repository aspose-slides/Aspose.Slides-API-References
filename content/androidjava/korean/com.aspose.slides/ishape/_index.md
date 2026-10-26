---
title: IShape
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 슬라이드의 도형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ishape/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

슬라이드의 도형을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 도형이 TextHolder인지 확인합니다. |
| [getPlaceholder()](#getPlaceholder--) | 도형에 대한 자리 표시자를 반환합니다. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | 새 자리 표시자가 없으면 추가하고, 지정된 자리 표시자 속성을 설정합니다. |
| [removePlaceholder()](#removePlaceholder--) | 이 도형이 자리 표시자가 아님을 정의합니다. |
| [getCustomData()](#getCustomData--) | 도형의 사용자 정의 데이터를 반환합니다. |
| [getRawFrame()](#getRawFrame--) | 원시 도형 프레임 속성을 반환하거나 설정합니다. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 원시 도형 프레임 속성을 반환하거나 설정합니다. |
| [getFrame()](#getFrame--) | 도형 프레임 속성을 반환하거나 설정합니다. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | 도형 프레임 속성을 반환하거나 설정합니다. |
| [getLineFormat()](#getLineFormat--) | 도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. |
| [getThreeDFormat()](#getThreeDFormat--) | 도형의 3D 서식 속성을 포함하는 ThreeDFormat 객체를 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | 도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. |
| [getFillFormat()](#getFillFormat--) | 도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. |
| [getImage()](#getImage--) | 도형 썸네일을 반환합니다. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | 도형 썸네일을 반환합니다. |
| [getHidden()](#getHidden--) | 도형이 숨겨져 있는지 확인합니다. |
| [setHidden(boolean value)](#setHidden-boolean-) | 도형이 숨겨져 있는지 확인합니다. |
| [getZOrderPosition()](#getZOrderPosition--) | z-순서에서 도형의 위치를 반환합니다. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | 도형의 연결 위치 수를 반환합니다. |
| [getRotation()](#getRotation--) | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. |
| [setRotation(float value)](#setRotation-float-) | 지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. |
| [getX()](#getX--) | 도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다. |
| [setX(float value)](#setX-float-) | 도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다. |
| [getY()](#getY--) | 도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다. |
| [setY(float value)](#setY-float-) | 도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다. |
| [getWidth()](#getWidth--) | 도형의 너비를 포인트 단위로 반환하거나 설정합니다. |
| [setWidth(float value)](#setWidth-float-) | 도형의 너비를 포인트 단위로 반환하거나 설정합니다. |
| [getHeight()](#getHeight--) | 도형의 높이를 포인트 단위로 반환하거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 도형의 높이를 포인트 단위로 반환하거나 설정합니다. |
| [getAlternativeText()](#getAlternativeText--) | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 도형에 연결된 대체 텍스트를 반환하거나 설정합니다. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | 도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. |
| [getName()](#getName--) | 도형의 이름을 반환하거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 도형의 이름을 반환하거나 설정합니다. |
| [isDecorative()](#isDecorative--) | 'Mark as decorative' 옵션을 읽기/쓰기 boolean으로 가져오거나 설정합니다. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 'Mark as decorative' 옵션을 읽기/쓰기 boolean으로 가져오거나 설정합니다. |
| [getShapeLock()](#getShapeLock--) | 도형의 잠금 정보를 반환합니다. |
| [getUniqueId()](#getUniqueId--) | 부가 기능이나 기타 코드에서 사용하도록 설계된 프레젠테이션 범위의 내부 식별자를 반환합니다. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | 도형의 수명 동안 일정하게 유지되는 슬라이드 범위 고유 식별자를 반환하며, PowerPoint 또는 인터옵 코드는 문서 어디서든 도형을 안정적으로 참조할 수 있습니다. |
| [isGrouped()](#isGrouped--) | 도형이 그룹화되어 있는지 확인합니다. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | 속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | 속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. |
| [getParentGroup()](#getParentGroup--) | 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 도형 내용을 SVG 파일로 저장합니다. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 도형 내용을 SVG 파일로 저장합니다. |
| [getBasePlaceholder()](#getBasePlaceholder--) | 기본 자리 표시자 도형을 반환합니다(레이아웃 또는 마스터 슬라이드에서 현재 도형이 상속받은 도형). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

도형이 TextHolder인지 확인합니다. 읽기 전용 boolean.

**반환:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

도형에 대한 자리 표시자를 반환합니다. 읽기 전용 [IPlaceholder](../../com.aspose.slides/iplaceholder).

**반환:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

새 자리 표시자가 없으면 추가하고, 지정된 자리 표시자 속성을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 내용을 복사할 자리 표시자. |

**반환:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 새 [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

이 도형이 자리 표시자가 아님을 정의합니다.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

도형의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../com.aspose.slides/icustomdata).

**반환:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
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
>  // 이러한 코드는 불명확한 상황을 초래할 수 있습니다. 따라서 IShape.getFrame()에 대해 정의되지 않은 값을 사용하는 경우에 제한이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어야 합니다 (Float.NaN 또는 NullableBool.NotDefined가 아니어야 함). 위의 예제 코드는 이제 ArgumentException 예외를 발생시킵니다.
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape은 placeholder에 연결되어 있습니다
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 이제 shape은 placeholder에서 x, y, height, flipH, flipV 값을 상속받고 width=100 및 rotationAngle=0을 덮어씁니다.
```

**반환:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
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
>  //이러한 코드는 불명확한 상황을 초래할 수 있습니다. 따라서 IShape.getFrame()에 정의되지 않은 값을 사용하는 경우에 제한이 추가되었습니다. x, y, width, height, flipH, flipV 및 rotationAngle 값은 정의되어야 합니다 (Float.NaN 또는 NullableBool.NotDefined가 아니어야 함). 위의 예제 코드는 이제 ArgumentException 예외를 발생시킵니다.
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape은 placeholder에 연결되어 있습니다
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 이제 shape은 placeholder에서 x, y, height, flipH, flipV 값을 상속받고 width=100 및 rotationAngle=0을 덮어씁니다.
```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

도형 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
반환된 IShapeFrame 인스턴스의 각 속성 값은 undefined가 아닙니다(NaN 또는 NotDefined가 아님). 할당된 IShapeFrame 인스턴스의 각 속성 값은 undefined가 아니어야 합니다(NaN 또는 NotDefined가 아님). RawFrame 인스턴스 속성에 undefined 값을 설정할 수 있습니다.

**반환:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

도형 프레임 속성을 반환하거나 설정합니다. 읽기/쓰기 [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
반환된 IShapeFrame 인스턴스의 각 속성 값은 undefined가 아닙니다(NaN 또는 NotDefined가 아님). 할당된 IShapeFrame 인스턴스의 각 속성 값은 undefined가 아니어야 합니다(NaN 또는 NotDefined가 아님). RawFrame 인스턴스 속성에 undefined 값을 설정할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

도형의 선 서식 속성을 포함하는 LineFormat 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

도형의 3D 서식 속성을 포함하는 ThreeDFormat 객체를 반환합니다. 읽기 전용 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**반환:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

도형에 적용된 픽셀 효과를 포함하는 EffectFormat 객체를 반환합니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**반환:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

도형의 채우기 서식 속성을 포함하는 FillFormat 객체를 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

도형 썸네일을 반환합니다. 기본적으로 ShapeThumbnailBounds.Shape 도형 썸네일 경계 유형이 사용됩니다.

**반환:**
[IImage](../../com.aspose.slides/iimage) - 도형 썸네일.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

도형 썸네일을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bounds | int | 도형 썸네일 경계 유형. |
| scaleX | float | X 스케일 |
| scaleY | float | Y 스케일 |

**반환:**
[IImage](../../com.aspose.slides/iimage) - ShapeThumbnailBounds.Appearance이 사용되고 도형에 보이는 요소가 없을 경우 null을 반환합니다.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

도형이 숨겨져 있는지 확인합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

도형이 숨겨져 있는지 확인합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

z-순서에서 도형의 위치를 반환합니다. Shapes[0]은 z-순서 맨 뒤의 도형을 반환하고, Shapes[Shapes.Count - 1]은 z-순서 앞쪽의 도형을 반환합니다. 읽기 전용 int.

**반환:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

도형의 연결 위치 수를 반환합니다. 읽기 전용 int.

**반환:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있습니다(is not Float.NaN). 할당된 값도 정의되어야 합니다(not Float.NaN). RawFrame 인스턴스 속성에 undefined 값을 설정할 수 있습니다.

**반환:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

지정된 도형이 z축을 중심으로 회전된 각도를 반환하거나 설정합니다. 양수 값은 시계 방향 회전을, 음수 값은 반시계 방향 회전을 나타냅니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있습니다(is not Float.NaN). 할당된 값도 정의되어야 합니다(not Float.NaN). RawFrame 인스턴스 속성에 undefined 값을 설정할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**반환:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

도형 왼쪽 위 모서리의 x좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**반환:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

도형 왼쪽 위 모서리의 y좌표를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

도형의 너비를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**반환:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

도형의 너비를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

도형의 높이를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**반환:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

도형의 높이를 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

반환된 값은 항상 정의되어 있고 Float.NaN이 아닙니다. 할당된 값도 정의되어 있어야 하며, Float.NaN은 RawFrame 인스턴스의 속성에만 할당할 수 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

도형에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

도형에 연결된 대체 텍스트를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

도형에 연결된 대체 텍스트의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

도형의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

도형의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

'Mark as decorative' 옵션을 읽기/쓰기 boolean으로 가져오거나 설정합니다.

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
public abstract void setDecorative(boolean value)
```

'Mark as decorative' 옵션을 읽기/쓰기 boolean으로 가져오거나 설정합니다.

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

도형의 잠금 정보를 반환합니다. 읽기 전용 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**반환:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

부가 기능이나 기타 코드에서 사용하도록 설계된 프레젠테이션 범위의 내부 식별자를 반환합니다. 이 값은 사용자나 프로그램에 의해 재할당될 수 있으므로 영구적인 고유 키로 취급해서는 안 됩니다. 읽기 전용 long. 또한 \#getOfficeInteropShapeId.getOfficeInteropShapeId를 참조하십시오.

**반환:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

슬라이드 범위의 고유 식별자를 반환합니다. 이 식별자는 도형의 수명 동안 일정하게 유지되며, PowerPoint 또는 인터옵 코드는 문서 어디서든 도형을 안정적으로 참조할 수 있습니다. 읽기 전용 long. 또한 \#getUniqueId.getUniqueId를 참조하십시오.

**반환:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

도형이 그룹화되어 있는지 확인합니다. 읽기 전용 boolean.

Property \#getParentGroup.getParentGroup은 도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다.

**반환:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**반환:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

속성은 도형이 흑백 표시 모드에서 렌더링되는 방식을 지정합니다. 읽기/쓰기 [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

도형이 그룹화된 경우 상위 GroupShape 객체를 반환합니다. 그렇지 않으면 null을 반환합니다. 읽기 전용 [IGroupShape](../../com.aspose.slides/igroupshape).

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**반환:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

도형 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

도형 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

기본 자리 표시자 도형을 반환합니다(레이아웃 또는 마스터 슬라이드에서 현재 도형이 상속받은 도형).

> ```
> // 플레이스홀더 도형의 모든 (마스터/레이아웃/슬라이드) 애니메이션 효과를 가져옵니다
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


A null is returned if the current shape is not inherited.

**반환:**
[IShape](../../com.aspose.slides/ishape)