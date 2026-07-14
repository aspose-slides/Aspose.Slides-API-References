---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 효과적인 텍스트 프레임 서식 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

효과적인 텍스트 프레임 서식 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [ITextFrameFormat](../../com.aspose.slides/itextframeformat) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 유효한 텍스트 스타일을 반환합니다. |
| [getMarginLeft()](#getMarginLeft--) | TextFrame의 왼쪽 여백(포인트)을 반환합니다. |
| [getMarginRight()](#getMarginRight--) | TextFrame의 오른쪽 여백(포인트)을 반환합니다. |
| [getMarginTop()](#getMarginTop--) | TextFrame의 위쪽 여백(포인트)을 반환합니다. |
| [getMarginBottom()](#getMarginBottom--) | TextFrame의 아래쪽 여백(포인트)을 반환합니다. |
| [getWrapText()](#getWrapText--) | TextFrame의 여백에서 텍스트가 줄바꿈되는지 여부를 반환합니다. |
| [getAnchoringType()](#getAnchoringType--) | TextFrame의 수직 앵커 텍스트를 반환합니다. |
| [getCenterText()](#getCenterText--) | 텍스트가 가로로 박스 중앙에 배치되어야 하는지 여부를 반환합니다. |
| [getTextVerticalType()](#getTextVerticalType--) | 텍스트 방향을 반환합니다. |
| [getAutofitType()](#getAutofitType--) | 텍스트 자동 맞춤 모드를 반환합니다. |
| [getColumnCount()](#getColumnCount--) | 경계 사각형 내 텍스트 열 수를 지정합니다. |
| [getColumnSpacing()](#getColumnSpacing--) | 텍스트 영역 내 텍스트 열 사이의 간격(포인트)을 지정합니다. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


유효한 텍스트 스타일을 반환합니다. 읽기 전용 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**반환값:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


TextFrame의 왼쪽 여백(포인트)을 반환합니다. 읽기 전용 double.

**반환값:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


TextFrame의 오른쪽 여백(포인트)을 반환합니다. 읽기 전용 double.

**반환값:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


TextFrame의 위쪽 여백(포인트)을 반환합니다. 읽기 전용 double.

**반환값:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


TextFrame의 아래쪽 여백(포인트)을 반환합니다. 읽기 전용 double.

**반환값:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


TextFrame의 여백에서 텍스트가 줄바꿈되는지 여부를 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


TextFrame의 수직 앵커 텍스트를 반환합니다. 읽기 전용 [TextAnchorType](../../com.aspose.slides/textanchortype).

**반환값:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


텍스트가 가로로 박스 중앙에 배치되어야 하는지 여부를 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


텍스트 방향을 반환합니다. 읽기 전용 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**반환값:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


텍스트 자동 맞춤 모드를 반환합니다. 읽기 전용 [TextAutofitType](../../com.aspose.slides/textautofittype).

**반환값:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


경계 사각형 내 텍스트 열 수를 지정합니다. 읽기 전용 int.

**반환값:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


텍스트 영역 내 텍스트 열 사이의 간격(포인트)을 지정합니다. 읽기 전용 float.

**반환값:**
float