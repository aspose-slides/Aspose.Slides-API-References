---
title: ILineFormat
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 라인의 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilineformat/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

라인 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | 라인 형식이 정의되지 않은 경우 true를 반환합니다 (새로 생성된 기본값처럼). |
| [getFillFormat()](#getFillFormat--) | 라인의 채우기 형식을 반환합니다. |
| [getSketchFormat()](#getSketchFormat--) | 라인의 스케치 형식을 반환합니다. |
| [getWidth()](#getWidth--) | 라인의 너비를 반환하거나 설정합니다. |
| [setWidth(double value)](#setWidth-double-) | 라인의 너비를 반환하거나 설정합니다. |
| [getDashStyle()](#getDashStyle--) | 라인 대시 스타일을 반환하거나 설정합니다. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | 라인 대시 스타일을 반환하거나 설정합니다. |
| [getCustomDashPattern()](#getCustomDashPattern--) | 사용자 지정 대시 패턴을 반환하거나 설정합니다. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | 사용자 지정 대시 패턴을 반환하거나 설정합니다. |
| [getCapStyle()](#getCapStyle--) | 라인 캡 스타일을 반환하거나 설정합니다. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | 라인 캡 스타일을 반환하거나 설정합니다. |
| [getStyle()](#getStyle--) | 라인 스타일을 반환하거나 설정합니다. |
| [setStyle(byte value)](#setStyle-byte-) | 라인 스타일을 반환하거나 설정합니다. |
| [getAlignment()](#getAlignment--) | 라인 정렬을 반환하거나 설정합니다. |
| [setAlignment(byte value)](#setAlignment-byte-) | 라인 정렬을 반환하거나 설정합니다. |
| [getJoinStyle()](#getJoinStyle--) | 선 연결 스타일을 반환하거나 설정합니다. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | 선 연결 스타일을 반환하거나 설정합니다. |
| [getMiterLimit()](#getMiterLimit--) | 라인의 마이터 제한을 반환하거나 설정합니다. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 라인의 마이터 제한을 반환하거나 설정합니다. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 라인 시작부의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | 라인 시작부의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 라인 끝부분의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | 라인 끝부분의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 라인 시작부의 화살표 머리 너비를 반환하거나 설정합니다. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | 라인 시작부의 화살표 머리 너비를 반환하거나 설정합니다. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 라인 끝부분의 화살표 머리 너비를 반환하거나 설정합니다. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | 라인 끝부분의 화살표 머리 너비를 반환하거나 설정합니다. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 라인 시작부의 화살표 머리 길이를 반환하거나 설정합니다. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | 라인 시작부의 화살표 머리 길이를 반환하거나 설정합니다. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 라인 끝부분의 화살표 머리 길이를 반환하거나 설정합니다. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | 라인 끝부분의 화살표 머리 길이를 반환하거나 설정합니다. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | 두 LineFormat 인스턴스가 같은지 여부를 결정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 라인 포맷 데이터를 가져옵니다. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

라인 형식이 정의되지 않은 경우 true를 반환합니다 (새로 생성된 기본값처럼). 읽기 전용 boolean.

**반환:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

라인의 채우기 형식을 반환합니다. 읽기 전용 [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**반환:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

라인의 스케치 형식을 반환합니다. 읽기 전용 [ISketchFormat](../../com.aspose.slides/isketchformat).

**반환:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

라인의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

라인의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

라인 대시 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineDashStyle](../../com.aspose.slides/linedashstyle).

**반환:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

라인 대시 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineDashStyle](../../com.aspose.slides/linedashstyle).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

사용자 지정 대시 패턴을 반환하거나 설정합니다. 읽기/쓰기 float[].

**반환:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

사용자 지정 대시 패턴을 반환하거나 설정합니다. 읽기/쓰기 float[].

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

라인 캡 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineCapStyle](../../com.aspose.slides/linecapstyle).

**반환:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

라인 캡 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineCapStyle](../../com.aspose.slides/linecapstyle).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

라인 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineStyle](../../com.aspose.slides/linestyle).

**반환:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

라인 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineStyle](../../com.aspose.slides/linestyle).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

라인 정렬을 반환하거나 설정합니다. 읽기/쓰기 [LineAlignment](../../com.aspose.slides/linealignment).

**반환:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

라인 정렬을 반환하거나 설정합니다. 읽기/쓰기 [LineAlignment](../../com.aspose.slides/linealignment).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

선 연결 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**반환:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

선 연결 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

라인의 마이터 제한을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

라인의 마이터 제한을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

라인 시작부의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**반환:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

라인 시작부의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

라인 끝부분의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**반환:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

라인 끝부분의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

라인 시작부의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**반환:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

라인 시작부의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

라인 끝부분의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**반환:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

라인 끝부분의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

라인 시작부의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**반환:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

라인 시작부의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

라인 끝부분의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**반환:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

라인 끝부분의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

두 LineFormat 인스턴스가 같은지 여부를 결정합니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 현재 LineFormat과 비교할 LineFormat. |

**반환:**  
boolean - 지정된 LineFormat이 현재 LineFormat과 동일하면 **true**, 그렇지 않으면 **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 라인 포맷 데이터를 가져옵니다.

**반환:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).