---
title: IColorFormat
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션에서 사용되는 색을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icolorformat/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

프레젠테이션에서 사용되는 색을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColorType()](#getColorType--) | 색 정의 방법을 반환하거나 설정합니다. |
| [setColorType(int value)](#setColorType-int-) | 색 정의 방법을 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 모든 색 변환이 적용된 결과 색을 반환합니다. |
| [setColor(Color value)](#setColor-java.awt.Color-) | 모든 색 변환이 적용된 결과 색을 반환합니다. |
| [getPresetColor()](#getPresetColor--) | 색 프리셋을 반환하거나 설정합니다. |
| [setPresetColor(int value)](#setPresetColor-int-) | 색 프리셋을 반환하거나 설정합니다. |
| [getSystemColor()](#getSystemColor--) | 시스템 색 테이블에 의해 식별되는 색을 반환하거나 설정합니다. |
| [setSystemColor(int value)](#setSystemColor-int-) | 시스템 색 테이블에 의해 식별되는 색을 반환하거나 설정합니다. |
| [getSchemeColor()](#getSchemeColor--) | 색 구성표에 의해 식별되는 색을 반환하거나 설정합니다. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | 색 구성표에 의해 식별되는 색을 반환하거나 설정합니다. |
| [getR()](#getR--) | 색의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [setR(byte value)](#setR-byte-) | 색의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [getG()](#getG--) | 색의 녹색 구성 요소를 반환하거나 설정합니다. |
| [setG(byte value)](#setG-byte-) | 색의 녹색 구성 요소를 반환하거나 설정합니다. |
| [getB()](#getB--) | 색의 파란색 구성 요소를 반환하거나 설정합니다. |
| [setB(byte value)](#setB-byte-) | 색의 파란색 구성 요소를 반환하거나 설정합니다. |
| [getFloatR()](#getFloatR--) | 색의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [setFloatR(float value)](#setFloatR-float-) | 색의 빨간색 구성 요소를 반환하거나 설정합니다. |
| [getFloatG()](#getFloatG--) | 색의 녹색 구성 요소를 반환하거나 설정합니다. |
| [setFloatG(float value)](#setFloatG-float-) | 색의 녹색 구성 요소를 반환하거나 설정합니다. |
| [getFloatB()](#getFloatB--) | 색의 파란색 구성 요소를 반환하거나 설정합니다. |
| [setFloatB(float value)](#setFloatB-float-) | 색의 파란색 구성 요소를 반환하거나 설정합니다. |
| [getHue()](#getHue--) | HSL 표현에서 색의 색상 구성 요소를 반환하거나 설정합니다. |
| [setHue(float value)](#setHue-float-) | HSL 표현에서 색의 색상 구성 요소를 반환하거나 설정합니다. |
| [getSaturation()](#getSaturation--) | HSL 표현에서 색의 채도 구성 요소를 반환하거나 설정합니다. |
| [setSaturation(float value)](#setSaturation-float-) | HSL 표현에서 색의 채도 구성 요소를 반환하거나 설정합니다. |
| [getLuminance()](#getLuminance--) | HSL 표현에서 색의 명도 구성 요소를 반환하거나 설정합니다. |
| [setLuminance(float value)](#setLuminance-float-) | HSL 표현에서 색의 명도 구성 요소를 반환하거나 설정합니다. |
| [getColorTransform()](#getColorTransform--) | 색에 적용된 색 변환 컬렉션을 반환합니다. |
| [toString(int format)](#toString-int-) | 현재 색 형식을 나타내는 문자열을 반환합니다. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | "color"에서 색 형식을 복사합니다. |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

색 정의 방법을 반환하거나 설정합니다. 읽기/쓰기 [ColorType](../../com.aspose.slides/colortype).

**반환:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

색 정의 방법을 반환하거나 설정합니다. 읽기/쓰기 [ColorType](../../com.aspose.slides/colortype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

모든 색 변환이 적용된 결과 색을 반환합니다. RGB 색을 설정하고 모든 색 변환을 지웁니다. 읽기/쓰기 java.awt.Color.

**반환:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

모든 색 변환이 적용된 결과 색을 반환합니다. RGB 색을 설정하고 모든 색 변환을 지웁니다. 읽기/쓰기 java.awt.Color.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

색 프리셋을 반환하거나 설정합니다. 읽기/쓰기 [PresetColor](../../com.aspose.slides/presetcolor).

**반환:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

색 프리셋을 반환하거나 설정합니다. 읽기/쓰기 [PresetColor](../../com.aspose.slides/presetcolor).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

시스템 색 테이블에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SystemColor](../../com.aspose.slides/systemcolor).

**반환:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

시스템 색 테이블에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SystemColor](../../com.aspose.slides/systemcolor).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

색 구성표에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SchemeColor](../../com.aspose.slides/schemecolor).

**반환:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

색 구성표에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SchemeColor](../../com.aspose.slides/schemecolor).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 byte.

**반환:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 byte.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 byte.

**반환:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 byte.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 byte.

**반환:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 byte.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**반환:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**반환:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**반환:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

HSL 표현에서 색의 색상 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**반환:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

HSL 표현에서 색의 색상 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

HSL 표현에서 색의 채도 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**반환:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

HSL 표현에서 색의 채도 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

HSL 표현에서 색의 명도 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**반환:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

HSL 표현에서 색의 명도 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

색에 적용된 색 변환 컬렉션을 반환합니다. 읽기 전용 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**반환:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

현재 색 형식을 나타내는 문자열을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | int | 색 문자열 형식의 유형. |

**반환:**
java.lang.String - 현재 색 형식을 나타내는 문자열.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

"color"에서 색 형식을 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | 색 [IColorFormat](../../com.aspose.slides/icolorformat) |