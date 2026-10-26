---
title: ColorFormat
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션에서 사용되는 색을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/colorformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)  
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

프레젠테이션에서 사용되는 색을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColorType()](#getColorType--) | 색 정의 방식을 반환하거나 설정합니다. |
| [setColorType(int value)](#setColorType-int-) | 색 정의 방식을 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 모든 색 변환이 적용된 결과 색을 반환합니다. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 모든 색 변환이 적용된 결과 색을 반환합니다. |
| [getPresetColor()](#getPresetColor--) | 색 사전 설정을 반환하거나 설정합니다. |
| [setPresetColor(int value)](#setPresetColor-int-) | 색 사전 설정을 반환하거나 설정합니다. |
| [getSystemColor()](#getSystemColor--) | 시스템 색 표에 의해 식별되는 색을 반환하거나 설정합니다. |
| [setSystemColor(int value)](#setSystemColor-int-) | 시스템 색 표에 의해 식별되는 색을 반환하거나 설정합니다. |
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
| [getHue()](#getHue--) | HSL 표현에서 색의 색상(Hue) 구성 요소를 반환하거나 설정합니다. |
| [setHue(float value)](#setHue-float-) | HSL 표현에서 색의 색상(Hue) 구성 요소를 반환하거나 설정합니다. |
| [getSaturation()](#getSaturation--) | HSL 표현에서 색의 채도(Saturation) 구성 요소를 반환하거나 설정합니다. |
| [setSaturation(float value)](#setSaturation-float-) | HSL 표현에서 색의 채도(Saturation) 구성 요소를 반환하거나 설정합니다. |
| [getLuminance()](#getLuminance--) | HSL 표현에서 색의 명도(Luminance) 구성 요소를 반환하거나 설정합니다. |
| [setLuminance(float value)](#setLuminance-float-) | HSL 표현에서 색의 명도(Luminance) 구성 요소를 반환하거나 설정합니다. |
| [getColorTransform()](#getColorTransform--) | 색에 적용된 색 변환 컬렉션을 반환합니다. |
| [toString(int format)](#toString-int-) | 현재 색 형식을 나타내는 문자열을 반환합니다. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | "color"에서 색 형식을 복사합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체와의 동등성을 확인합니다. |
| [hashCode()](#hashCode--) | 해시 코드를 반환합니다. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

색 정의 방식을 반환하거나 설정합니다. 읽기/쓰기 [ColorType](../../com.aspose.slides/colortype).

**반환:**  
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

색 정의 방식을 반환하거나 설정합니다. 읽기/쓰기 [ColorType](../../com.aspose.slides/colortype).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Integer getColor()
```

모든 색 변환이 적용된 결과 색을 반환합니다. RGB 색을 설정하고 모든 색 변환을 지웁니다. 읽기/쓰기 java.lang.Integer.

**반환:**  
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

모든 색 변환이 적용된 결과 색을 반환합니다. RGB 색을 설정하고 모든 색 변환을 지웁니다. 읽기/쓰기 java.lang.Integer.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

색 사전 설정을 반환하거나 설정합니다. 읽기/쓰기 [PresetColor](../../com.aspose.slides/presetcolor).

**반환:**  
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

색 사전 설정을 반환하거나 설정합니다. 읽기/쓰기 [PresetColor](../../com.aspose.slides/presetcolor).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

시스템 색 표에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SystemColor](../../com.aspose.slides/systemcolor).

**반환:**  
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

시스템 색 표에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SystemColor](../../com.aspose.slides/systemcolor).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

색 구성표에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SchemeColor](../../com.aspose.slides/schemecolor).

**반환:**  
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

색 구성표에 의해 식별되는 색을 반환하거나 설정합니다. 읽기/쓰기 [SchemeColor](../../com.aspose.slides/schemecolor).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  byte .

**반환:**  
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  byte .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다.

**반환:**  
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  byte .

**반환:**  
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  byte .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**반환:**  
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

색의 빨간색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**반환:**  
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

색의 녹색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**반환:**  
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

색의 파란색 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

HSL 표현에서 색의 색상(Hue) 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**반환:**  
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

HSL 표현에서 색의 색상(Hue) 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

HSL 표현에서 색의 채도(Saturation) 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**반환:**  
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

HSL 표현에서 색의 채도(Saturation) 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

HSL 표현에서 색의 명도(Luminance) 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**반환:**  
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

HSL 표현에서 색의 명도(Luminance) 구성 요소를 반환하거나 설정합니다. 모든 색 변환은 무시됩니다. 읽기/쓰기  float .

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

색에 적용된 색 변환 컬렉션을 반환합니다. 읽기 전용 [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**반환:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
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
public final void copyFrom(IColorFormat color)
```

"color"에서 색 형식을 복사합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 객체와의 동등성을 확인합니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 객체. |

**반환:**  
boolean - 객체가 동일하면 true, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

해시 코드를 반환합니다.

**반환:**  
int - 해시 코드.

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**반환:**  
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)