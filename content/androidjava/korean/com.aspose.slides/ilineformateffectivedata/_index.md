---
title: ILineFormatEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 효과적인 선 서식 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ilineformateffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

효과적인 선 서식 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [ILineFormat](../../com.aspose.slides/ilineformat) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 라인의 채우기 서식을 반환합니다. |
| [getSketchFormat()](#getSketchFormat--) | 라인의 스케치 서식을 반환합니다. |
| [getWidth()](#getWidth--) | 라인의 너비를 반환합니다. |
| [getDashStyle()](#getDashStyle--) | 라인 대시 스타일을 반환합니다. |
| [getCustomDashPattern()](#getCustomDashPattern--) | 사용자 정의 대시 패턴을 반환합니다. |
| [getCapStyle()](#getCapStyle--) | 라인 캡 스타일을 반환합니다. |
| [getStyle()](#getStyle--) | 라인 스타일을 반환합니다. |
| [getAlignment()](#getAlignment--) | 라인 정렬을 반환합니다. |
| [getJoinStyle()](#getJoinStyle--) | 라인 연결 스타일을 반환합니다. |
| [getMiterLimit()](#getMiterLimit--) | 라인의 마이터 제한을 반환합니다. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 라인 시작점의 화살표 머리 스타일을 반환합니다. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 라인 끝점의 화살표 머리 스타일을 반환합니다. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 라인 시작점의 화살표 머리 너비를 반환합니다. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 라인 끝점의 화살표 머리 너비를 반환합니다. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 라인 시작점의 화살표 머리 길이를 반환합니다. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 라인 끝점의 화살표 머리 길이를 반환합니다. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | 두 ILineFormatEffectiveData 인스턴스가 동일한지 여부를 결정합니다. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

라인의 채우기 서식을 반환합니다. 읽기 전용 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**반환:**  
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

라인의 스케치 서식을 반환합니다. 읽기 전용 [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**반환:**  
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

라인의 너비를 반환합니다. 읽기 전용 double.

**반환:**  
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

라인 대시 스타일을 반환합니다. 읽기 전용 [LineDashStyle](../../com.aspose.slides/linedashstyle).

**반환:**  
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

사용자 정의 대시 패턴을 반환합니다. 읽기 전용 float[].

**반환:**  
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

라인 캡 스타일을 반환합니다. 읽기 전용 [LineCapStyle](../../com.aspose.slides/linecapstyle).

**반환:**  
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

라인 스타일을 반환합니다. 읽기 전용 [LineStyle](../../com.aspose.slides/linestyle).

**반환:**  
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

라인 정렬을 반환합니다. 읽기 전용 [LineAlignment](../../com.aspose.slides/linealignment).

**반환:**  
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

라인 연결 스타일을 반환합니다. 읽기 전용 [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**반환:**  
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

라인의 마이터 제한을 반환합니다. 읽기 전용 float.

**반환:**  
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

라인 시작점의 화살표 머리 스타일을 반환합니다. 읽기 전용 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**반환:**  
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

라인 끝점의 화살표 머리 스타일을 반환합니다. 읽기 전용 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**반환:**  
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

라인 시작점의 화살표 머리 너비를 반환합니다. 읽기 전용 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**반환:**  
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

라인 끝점의 화살표 머리 너비를 반환합니다. 읽기 전용 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**반환:**  
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

라인 시작점의 화살표 머리 길이를 반환합니다. 읽기 전용 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**반환:**  
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

라인 끝점의 화살표 머리 길이를 반환합니다. 읽기 전용 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**반환:**  
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

두 ILineFormatEffectiveData 인스턴스가 동일한지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | 현재 ILineFormatEffectiveData와 비교할 ILineFormatEffectiveData. |

**반환:**  
boolean - 지정된 ILineFormatEffectiveData가 현재 ILineFormatEffectiveData와 동일하면 **true**, 그렇지 않으면 **false**.