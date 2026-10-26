---
title: LineFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 라인의 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/lineformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현한 모든 인터페이스:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

라인의 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | 라인 형식이 정의되지 않은 경우 true를 반환합니다 (방금 생성된 기본값). |
| [getFillFormat()](#getFillFormat--) | 라인의 채우기 형식을 반환합니다. |
| [getSketchFormat()](#getSketchFormat--) | 라인의 스케치 형식을 반환합니다. |
| [getWidth()](#getWidth--) | 라인의 너비를 반환하거나 설정합니다. |
| [setWidth(double value)](#setWidth-double-) | 라인의 너비를 반환하거나 설정합니다. |
| [getDashStyle()](#getDashStyle--) | 라인 대시 스타일을 반환하거나 설정합니다. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | 라인 대시 스타일을 반환하거나 설정합니다. |
| [getCustomDashPattern()](#getCustomDashPattern--) | 사용자 정의 대시 패턴을 반환하거나 설정합니다. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | 사용자 정의 대시 패턴을 반환하거나 설정합니다. |
| [getCapStyle()](#getCapStyle--) | 라인 캡 스타일을 반환하거나 설정합니다. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | 라인 캡 스타일을 반환하거나 설정합니다. |
| [getStyle()](#getStyle--) | 라인 스타일을 반환하거나 설정합니다. |
| [setStyle(byte value)](#setStyle-byte-) | 라인 스타일을 반환하거나 설정합니다. |
| [getAlignment()](#getAlignment--) | 라인 정렬을 반환하거나 설정합니다. |
| [setAlignment(byte value)](#setAlignment-byte-) | 라인 정렬을 반환하거나 설정합니다. |
| [getJoinStyle()](#getJoinStyle--) | 라인 조인 스타일을 반환하거나 설정합니다. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | 라인 조인 스타일을 반환하거나 설정합니다. |
| [getMiterLimit()](#getMiterLimit--) | 라인의 마이터 제한을 반환하거나 설정합니다. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 라인의 마이터 제한을 반환하거나 설정합니다. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 라인 시작 부분의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | 라인 시작 부분의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 라인 끝 부분의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | 라인 끝 부분의 화살표 머리 스타일을 반환하거나 설정합니다. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 라인 시작 부분의 화살표 머리 너비를 반환하거나 설정합니다. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | 라인 시작 부분의 화살표 머리 너비를 반환하거나 설정합니다. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 라인 끝 부분의 화살표 머리 너비를 반환하거나 설정합니다. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | 라인 끝 부분의 화살표 머리 너비를 반환하거나 설정합니다. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 라인 시작 부분의 화살표 머리 길이를 반환하거나 설정합니다. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | 라인 시작 부분의 화살표 머리 길이를 반환하거나 설정합니다. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 라인 끝 부분의 화살표 머리 길이를 반환하거나 설정합니다. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | 라인 끝 부분의 화살표 머리 길이를 반환하거나 설정합니다. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | 두 LineFormat 인스턴스가 같은지 여부를 결정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 라인 서식 데이터를 가져옵니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. 읽기 전용 long.

**반환:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

지정된 객체와 비교합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**반환:**  
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

라인 형식이 정의되지 않은 경우 true를 반환합니다 (방금 생성된 기본값). 읽기 전용 boolean .

**반환:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

라인의 채우기 형식을 반환합니다. 읽기 전용 [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**반환:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

라인의 스케치 형식을 반환합니다. 읽기 전용 [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**반환:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

라인의 너비를 반환하거나 설정합니다. 읽기/쓰기 double .

**반환:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

라인의 너비를 반환하거나 설정합니다. 읽기/쓰기 double .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

라인 대시 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineDashStyle](../../com.aspose.slides/linedashstyle).

**반환:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

라인 대시 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineDashStyle](../../com.aspose.slides/linedashstyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

사용자 정의 대시 패턴을 반환하거나 설정합니다. 읽기/쓰기 float[] .

**반환:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

사용자 정의 대시 패턴을 반환하거나 설정합니다. 읽기/쓰기 float[] .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

라인 캡 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineCapStyle](../../com.aspose.slides/linecapstyle).

**반환:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

라인 캡 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineCapStyle](../../com.aspose.slides/linecapstyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

라인 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineStyle](../../com.aspose.slides/linestyle).

**반환:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

라인 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineStyle](../../com.aspose.slides/linestyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

라인 정렬을 반환하거나 설정합니다. 읽기/쓰기 [LineAlignment](../../com.aspose.slides/linealignment).

**반환:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

라인 정렬을 반환하거나 설정합니다. 읽기/쓰기 [LineAlignment](../../com.aspose.slides/linealignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

라인 조인 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**반환:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

라인 조인 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

라인의 마이터 제한을 반환하거나 설정합니다. 읽기/쓰기 float .

**반환:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

라인의 마이터 제한을 반환하거나 설정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

라인 시작 부분의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**반환:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

라인 시작 부분의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

라인 끝 부분의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**반환:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

라인 끝 부분의 화살표 머리 스타일을 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

라인 시작 부분의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**반환:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

라인 시작 부분의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

라인 끝 부분의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**반환:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

라인 끝 부분의 화살표 머리 너비를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

라인 시작 부분의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**반환:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

라인 시작 부분의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

라인 끝 부분의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**반환:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

라인 끝 부분의 화살표 머리 길이를 반환하거나 설정합니다. 읽기/쓰기 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

두 LineFormat 인스턴스가 같은지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 현재 LineFormat과 비교할 LineFormat. |

**반환:**  
boolean - 지정된 LineFormat이 현재 LineFormat과 동일하면 **true**; 그렇지 않으면 **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 라인 서식 데이터를 가져옵니다.

--------------------

> ```
> 이 예제는 도형의 효과적인 라인 형식 속성을 가져오는 방법을 보여줍니다.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**반환:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - 하나의 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).