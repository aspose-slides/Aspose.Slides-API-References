---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /ko/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

차트 텍스트 요소에 대한 서식 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | TextFrame에서 수직 고정 텍스트를 반환하거나 설정합니다. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame에서 수직 고정 텍스트를 반환하거나 설정합니다. |
| [getCenterText()](#getCenterText--) | NullableBool.True이면 텍스트가 박스 내에서 가로로 가운데 정렬되어야 합니다. |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True이면 텍스트가 박스 내에서 가로로 가운데 정렬되어야 합니다. |
| [getTextVerticalType()](#getTextVerticalType--) | 텍스트 방향을 결정합니다. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 텍스트 방향을 결정합니다. |
| [getMarginLeft()](#getMarginLeft--) | TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginTop()](#getMarginTop--) | TextFrame의 위쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame의 위쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getMarginBottom()](#getMarginBottom--) | TextFrame의 아래쪽 여백(포인트)을 반환하거나 설정합니다. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame의 아래쪽 여백(포인트)을 반환하거나 설정합니다. |
| [getWrapText()](#getWrapText--) | TextFrame의 여백에서 텍스트가 줄 바꿈되는 경우 true. |
| [setWrapText(byte value)](#setWrapText-byte-) | TextFrame의 여백에서 텍스트가 줄 바꿈되는 경우 true. |
| [getAutofitType()](#getAutofitType--) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. |
| [getRotationAngle()](#getRotationAngle--) | 경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. |
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

NullableBool.True이면 텍스트가 박스 내에서 가로로 가운데 정렬되어야 합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True이면 텍스트가 박스 내에서 가로로 가운데 정렬되어야 합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

텍스트 방향을 결정합니다. 이 속성 및 RotationAngle 속성의 사용자 지정 각도로 요약된 시각적 텍스트 회전값을 반환합니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**반환:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

텍스트 방향을 결정합니다. 이 속성 및 RotationAngle 속성의 사용자 지정 각도로 요약된 시각적 텍스트 회전값을 반환합니다. 읽기/쓰기 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**반환:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**반환:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame의 위쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**반환:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame의 위쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame의 아래쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**반환:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame의 아래쪽 여백(포인트)을 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

TextFrame의 여백에서 텍스트가 줄 바꿈되는 경우 true. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2007/2013에서 전체 지원). 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

TextFrame의 여백에서 텍스트가 줄 바꿈되는 경우 true. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2007/2013에서 전체 지원). 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

**반환:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

텍스트의 자동 맞춤 모드를 반환하거나 설정합니다. 이 속성의 변경은 다음 차트 부분에만 특정 영향을 미칠 수 있습니다: DataLabel 및 DataLabelFormat (PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없습니다). 읽기/쓰기 [TextAutofitType](../../com.aspose.slides/textautofittype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우 부속 도형의 회전이 사용됩니다. 지정된 경우 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 별도로 회전이 적용됩니다. 이 속성과 TextVerticalType 속성의 사전 정의된 수직 유형에서 요약된 시각적 텍스트 회전값을 반환합니다. 읽기/쓰기 float.

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

경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우 부속 도형의 회전이 사용됩니다. 지정된 경우 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 별도로 회전이 적용됩니다. 이 속성과 TextVerticalType 속성의 사전 정의된 수직 유형에서 요약된 시각적 텍스트 회전값을 반환합니다. 읽기/쓰기 float.

--------------------

> ```
> 도형에 시계 방향으로 90도 회전이 적용된 경우를 고려하십시오. 
>  이에 추가로 텍스트 본문 자체에는 -90도 반시계 방향 회전이 적용됩니다. 
>  반시계 방향으로 적용됩니다. 그러면 결과 도형은 
>  회전된 것처럼 보이지만, 그 안의 텍스트는 전혀 회전되지 않은 것처럼 보입니다. 
```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |