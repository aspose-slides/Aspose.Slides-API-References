---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 차트 텍스트 요소에 대한 서식 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

차트 텍스트 요소에 대한 서식 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | 텍스트 프레임에서 수직 앵커 텍스트를 반환하거나 설정합니다. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 텍스트 프레임에서 수직 앵커 텍스트를 반환하거나 설정합니다. |
| [getCenterText()](#getCenterText--) | NullableBool.True이면 텍스트가 박스 안에서 수평으로 중앙에 배치되어야 합니다. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True이면 텍스트가 박스 안에서 수평으로 중앙에 배치되어야 합니다. |
| [getTextVerticalType()](#getTextVerticalType--) | 텍스트 방향을 결정합니다. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 텍스트 방향을 결정합니다. |
| [getMarginLeft()](#getMarginLeft--) | 텍스트 프레임의 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 텍스트 프레임의 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | 텍스트 프레임의 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginRight(double value)](#setMarginRight-double-) | 텍스트 프레임의 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginTop()](#getMarginTop--) | 텍스트 프레임의 위쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginTop(double value)](#setMarginTop-double-) | 텍스트 프레임의 위쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginBottom()](#getMarginBottom--) | 텍스트 프레임의 아래쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 텍스트 프레임의 아래쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getWrapText()](#getWrapText--) | 텍스트가 텍스트 프레임의 여백에서 줄바꿈되는 경우 true를 반환합니다. |
| [setWrapText(byte value)](#setWrapText-byte-) | 텍스트가 텍스트 프레임의 여백에서 줄바꿈되는 경우 true를 반환합니다. |
| [getAutofitType()](#getAutofitType--) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [getRotationAngle()](#getRotationAngle--) | 경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

텍스트 프레임에서 수직 앵커 텍스트를 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**반환:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

텍스트 프레임에서 수직 앵커 텍스트를 반환하거나 설정합니다. 읽기/쓰기 [TextAnchorType](../../com.aspose.slides/textanchortype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True이면 텍스트가 박스 안에서 수평으로 중앙에 배치되어야 합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True이면 텍스트가 박스 안에서 수평으로 중앙에 배치되어야 합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 정의 각도에서 요약된 시각적 텍스트 회전 값이 결과값으로 제공됩니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**반환:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 정의 각도에서 요약된 시각적 텍스트 회전 값이 결과값으로 제공됩니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

텍스트 프레임의 왼쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**반환:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

텍스트 프레임의 왼쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

텍스트 프레임의 오른쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**반환:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

텍스트 프레임의 오른쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

텍스트 프레임의 위쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**반환:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

텍스트 프레임의 위쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

텍스트 프레임의 아래쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**반환:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

텍스트 프레임의 아래쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

텍스트가 텍스트 프레임의 여백에서 줄바꿈되는 경우 true를 반환합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2007/2013에서 완전 지원). 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

텍스트가 텍스트 프레임의 여백에서 줄바꿈되는 경우 true를 반환합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2007/2013에서 완전 지원). 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

**반환:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 줄 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 완전 지원; PowerPoint 2007에서는 렌더링에 영향 없음). 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우, 해당 도형의 회전이 사용됩니다. 지정된 경우, 이는 도형과는 독립적으로 적용됩니다. 즉, 도형에 회전이 적용된 상태에서 텍스트 자체에도 별도로 회전이 적용될 수 있습니다. 이 속성과 TextVerticalType 속성의 사전 정의된 수직 유형에서 요약된 시각적 텍스트 회전 값이 결과값으로 제공됩니다. 읽기/쓰기 float.

--------------------

> ```
> 형상에 시계 방향으로 90도 회전이 적용된 경우를 고려하십시오. 
>  추가로, 텍스트 본문 자체에도 -90도 반시계 방향 회전이 적용됩니다. 
>  반시계 방향으로 적용됩니다. 그러면 결과적인 형태는 회전된 것처럼 보이지만, 
>  그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다.
> ```


**반환:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우, 해당 도형의 회전이 사용됩니다. 지정된 경우, 이는 도형과는 독립적으로 적용됩니다. 즉, 도형에 회전이 적용된 상태에서 텍스트 자체에도 별도로 회전이 적용될 수 있습니다. 이 속성과 TextVerticalType 속성의 사전 정의된 수직 유형에서 요약된 시각적 텍스트 회전 값이 결과값으로 제공됩니다. 읽기/쓰기 float.

--------------------

> ```
> 형상에 시계 방향으로 90도 회전이 적용된 경우를 고려하십시오. 
>  이에 더해, 텍스트 본문 자체에도 -90도 
>  반시계 방향으로 적용됩니다. 그런 다음 결과 형상은 
>  회전된 것처럼 보이지만 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다.
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |