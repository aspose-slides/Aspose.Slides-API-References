---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: TextFrame의 서식 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

TextFrame의 서식 속성을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 텍스트 스타일을 반환합니다. |
| [getMarginLeft()](#getMarginLeft--) | TextFrame에서 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame에서 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | TextFrame에서 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame에서 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginTop()](#getMarginTop--) | TextFrame에서 위쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame에서 위쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginBottom()](#getMarginBottom--) | TextFrame에서 아래쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame에서 아래쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getWrapText()](#getWrapText--) | TextFrame의 여백에서 텍스트가 래핑되는 경우 true를 반환합니다. |
| [setWrapText(byte value)](#setWrapText-byte-) | TextFrame의 여백에서 텍스트가 래핑되는 경우 true를 반환합니다. |
| [getAnchoringType()](#getAnchoringType--) | TextFrame에서 수직 고정 텍스트를 반환하거나 설정합니다. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame에서 수직 고정 텍스트를 반환하거나 설정합니다. |
| [getCenterText()](#getCenterText--) | NullableBool.True인 경우 텍스트가 박스 안에서 수평으로 가운데 정렬되어야 함을 나타냅니다. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True인 경우 텍스트가 박스 안에서 수평으로 가운데 정렬되어야 함을 나타냅니다. |
| [getTextVerticalType()](#getTextVerticalType--) | 텍스트 방향을 결정합니다. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 텍스트 방향을 결정합니다. |
| [getAutofitType()](#getAutofitType--) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [getColumnCount()](#getColumnCount--) | 텍스트 영역의 열 수를 반환하거나 설정합니다. |
| [setColumnCount(int value)](#setColumnCount-int-) | 텍스트 영역의 열 수를 반환하거나 설정합니다. |
| [getColumnSpacing()](#getColumnSpacing--) | 텍스트 영역의 텍스트 열 사이 간격(포인트)을 반환하거나 설정합니다. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | 텍스트 영역의 텍스트 열 사이 간격(포인트)을 반환하거나 설정합니다. |
| [getThreeDFormat()](#getThreeDFormat--) | 텍스트에 대한 3D 효과 속성을 나타내는 ThreeDFormat 객체를 반환합니다. |
| [getKeepTextFlat()](#getKeepTextFlat--) | 텍스트를 3D 장면에서 완전히 제외하도록 반환하거나 설정합니다. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 텍스트를 3D 장면에서 완전히 제외하도록 반환하거나 설정합니다. |
| [getRotationAngle()](#getRotationAngle--) | 경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. |
| [getTransform()](#getTransform--) | 텍스트 래핑 모양을 가져오거나 설정합니다. |
| [setTransform(byte value)](#setTransform-byte-) | 텍스트 래핑 모양을 가져오거나 설정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

텍스트 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame에서 왼쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame에서 왼쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame에서 오른쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame에서 오른쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame에서 위쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame에서 위쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame에서 아래쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame에서 아래쪽 여백(포인트)을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

TextFrame의 여백에서 텍스트가 래핑되는 경우 true를 반환합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

TextFrame의 여백에서 텍스트가 래핑되는 경우 true를 반환합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

TextFrame에서 수직 고정 텍스트를 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**반환:**  
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

TextFrame에서 수직 고정 텍스트를 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True인 경우 텍스트가 박스 안에서 수평으로 가운데 정렬되어야 함을 나타냅니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True인 경우 텍스트가 박스 안에서 수평으로 가운데 정렬되어야 함을 나타냅니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 지정 각도에서 요약된 시각적 텍스트 회전 값이 결과로 나타납니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**반환:**  
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 지정 각도에서 요약된 시각적 텍스트 회전 값이 결과로 나타납니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

**반환:**  
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

텍스트 영역의 열 수를 반환하거나 설정합니다. 이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 int.

**반환:**  
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

텍스트 영역의 열 수를 반환하거나 설정합니다. 이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

텍스트 영역의 텍스트 열 사이 간격(포인트)을 반환하거나 설정합니다. 이는 1개 이상의 열이 존재할 때만 적용됩니다. 이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. 읽기/쓰기 double.

**반환:**  
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

텍스트 영역의 텍스트 열 사이 간격(포인트)을 반환하거나 설정합니다. 이는 1개 이상의 열이 존재할 때만 적용됩니다. 이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

텍스트에 대한 3D 효과 속성을 나타내는 ThreeDFormat 객체를 반환합니다. 읽기 전용 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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
>      // 윤곽선 설정
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

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

텍스트를 3D 장면에서 완전히 제외하도록 반환하거나 설정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

텍스트를 3D 장면에서 완전히 제외하도록 반환하거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 해당 모양의 회전이 사용됩니다. 지정된 경우, 모양과는 독립적으로 적용됩니다. 즉, 모양에 회전이 적용된 상태에서 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 TextVerticalType 속성의 미리 정의된 수직 유형에서 요약된 시각적 텍스트 회전 값이 결과로 나타납니다. 읽기/쓰기 float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```


**반환:**  
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 해당 모양의 회전이 사용됩니다. 지정된 경우, 모양과는 독립적으로 적용됩니다. 즉, 모양에 회전이 적용된 상태에서 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 TextVerticalType 속성의 미리 정의된 수직 유형에서 요약된 시각적 텍스트 회전 값이 결과로 나타납니다. 읽기/쓰기 float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

텍스트 래핑 모양을 가져오거나 설정합니다. 읽기/쓰기 [TextShapeType](../../com.aspose.slides/textshapetype).

**반환:**  
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

텍스트 래핑 모양을 가져오거나 설정합니다. 읽기/쓰기 [TextShapeType](../../com.aspose.slides/textshapetype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다.

**반환:**  
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).