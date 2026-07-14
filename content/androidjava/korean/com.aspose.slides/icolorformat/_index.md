---
title: IColorFormat
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션에서 사용되는 색상을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icolorformat/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

프레젠테이션에서 사용되는 색상을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColorType()](#getColorType--) | 색상 정의 방식을 반환하거나 설정합니다. |
| [setColorType(int value)](#setColorType-int-) | 색상 정의 방식을 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 모든 색상 변환이 적용된 결과 색상을 반환합니다. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 모든 색상 변환이 적용된 결과 색상을 반환합니다. |
| [getPresetColor()](#getPresetColor--) | 색상 프리셋을 반환하거나 설정합니다. |
| [setPresetColor(int value)](#setPresetColor-int-) | 색상 프리셋을 반환하거나 설정합니다. |
| [getSystemColor()](#getSystemColor--) | 시스템 색상 테이블에서 식별된 색상을 반환하거나 설정합니다. |
| [setSystemColor(int value)](#setSystemColor-int-) | 시스템 색상 테이블에서 식별된 색상을 반환하거나 설정합니다. |
| [getSchemeColor()](#getSchemeColor--) | 색상 스키마에서 식별된 색상을 반환하거나 설정합니다. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | 색상 스키마에서 식별된 색상을 반환하거나 설정합니다. |
| [getR()](#getR--) | 색상의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [setR(byte value)](#setR-byte-) | 색상의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [getG()](#getG--) | 색상의 녹색 구성 요소를 반환하거나 설정합니다. |
| [setG(byte value)](#setG-byte-) | 색상의 녹색 구성 요소를 반환하거나 설정합니다. |
| [getB()](#getB--) | 색상의 파란색 구성 요소를 반환하거나 설정합니다. |
| [setB(byte value)](#setB-byte-) | 색상의 파란색 구성 요소를 반환하거나 설정합니다. |
| [getFloatR()](#getFloatR--) | 색상의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [setFloatR(float value)](#setFloatR-float-) | 색상의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [getFloatG()](#getFloatG--) | 색상의 녹색 구성 요소를 반환하거나 설정합니다. |
| [setFloatG(float value)](#setFloatG-float-) | 색상의 녹색 구성 요소를 반환하거나 설정합니다. |
| [getFloatB()](#getFloatB--) | 색상의 파란색 구성 요소를 반환하거나 설정합니다. |
| [setFloatB(float value)](#setFloatB-float-) | 색상의 파란색 구성 요소를 반환하거나 설정합니다. |
| [getHue()](#getHue--) | HSL 표현에서 색상의 색조 구성 요소를 반환하거나 설정합니다. |
| [setHue(float value)](#setHue-float-) | HSL 표현에서 색상의 색조 구성 요소를 반환하거나 설정합니다. |
| [getSaturation()](#getSaturation--) | HSL 표현에서 색상의 채도 구성 요소를 반환하거나 설정합니다. |
| [setSaturation(float value)](#setSaturation-float-) | HSL 표현에서 색상의 채도 구성 요소를 반환하거나 설정합니다. |
| [getLuminance()](#getLuminance--) | HSL 표현에서 색상의 명도 구성 요소를 반환하거나 설정합니다. |
| [setLuminance(float value)](#setLuminance-float-) | HSL 표현에서 색상의 명도 구성 요소를 반환하거나 설정합니다. |
| [getColorTransform()](#getColorTransform--) | 색상에 적용된 색상 변환 컬렉션을 반환합니다. |
| [toString(int format)](#toString-int-) | 현재 색상 형식을 나타내는 문자열을 반환합니다. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | "color"에서 색상 형식을 복사합니다. |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

색상 정의 방식을 반환하거나 설정합니다. 읽기/쓰기 [ColorType](../../com.aspose.slides/colortype).

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

색상 정의 방식을 반환하거나 설정합니다. 읽기/쓰기 [ColorType](../../com.aspose.slides/colortype).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

모든 색상 변환이 적용된 결과 색상을 반환합니다. RGB 색상을 설정하고 모든 색상 변환을 지웁니다. 읽기/쓰기 java.lang.Integer.

**Returns:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

모든 색상 변환이 적용된 결과 색상을 반환합니다. RGB 색상을 설정하고 모든 색상 변환을 지웁니다. 읽기/쓰기 java.lang.Integer.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

색상 프리셋을 반환하거나 설정합니다. 읽기/쓰기 [PresetColor](../../com.aspose.slides/presetcolor).

**Returns:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

색상 프리셋을 반환하거나 설정합니다. 읽기/쓰기 [PresetColor](../../com.aspose.slides/presetcolor).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

시스템 색상 테이블에서 식별된 색상을 반환하거나 설정합니다. 읽기/쓰기 [SystemColor](../../com.aspose.slides/systemcolor).

**Returns:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemAudio(int value)
```

시스템 색상 테이블에서 식별된 색상을 반환하거나 설정합니다. 읽기/쓰기 [SystemColor](../../com.aspose.slides/systemcolor).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

색상 스키마에서 식별된 색상을 반환하거나 설정합니다. 읽기/쓰기 [SchemeColor](../../com.aspose.slides/schemecolor).

**Returns:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

색상 스키마에서 식별된 색상을 반환하거나 설정합니다. 읽기/쓰기 [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

색상의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 byte.

**Returns:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

색상의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 byte.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

색상의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 byte.

**Returns:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

색상의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 byte.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

색상의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 byte.

**Returns:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

색상의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 byte.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

색상의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Returns:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

색상의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

색상의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Returns:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

색상의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

색상의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Returns:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

색상의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

HSL 표현에서 색상의 색조 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Returns:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

HSL 표현에서 색상의 색조 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

HSL 표현에서 색상의 채도 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Returns:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

HSL 표현에서 색상의 채도 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

HSL 표현에서 색상의 명도 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Returns:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

HSL 표현에서 색상의 명도 구성 요소를 반환하거나 설정합니다. 모든 색상 변환이 무시됩니다. 읽기/쓰기 float.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

색상에 적용된 색상 변환 컬렉션을 반환합니다. 읽기 전용 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Returns:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

현재 색상 형식을 나타내는 문자열을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | int | 색상 문자열 형식의 유형. |

**Returns:**
java.lang.String - 현재 색상 형식을 나타내는 문자열.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

"color"에서 색상 형식을 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |