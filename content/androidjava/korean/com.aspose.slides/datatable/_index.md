---
title: DataTable
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 데이터 테이블 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/datatable/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDataTable](../../com.aspose.slides/idatatable)
```
public class DataTable extends DomObject<Chart> implements IDataTable
```

데이터 테이블 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) | 객체의 선, 채우기 및 효과 스타일을 반환합니다. |
| [hasBorderHorizontal()](#hasBorderHorizontal--) | 차트 데이터 테이블에 수평 셀 테두리가 있는 경우 True를 반환합니다. |
| [setBorderHorizontal(boolean value)](#setBorderHorizontal-boolean-) | 차트 데이터 테이블에 수평 셀 테두리가 있는 경우 True를 반환합니다. |
| [hasBorderOutline()](#hasBorderOutline--) | 차트 데이터 테이블에 외곽선 테두리가 있는 경우 True를 반환합니다. |
| [setBorderOutline(boolean value)](#setBorderOutline-boolean-) | 차트 데이터 테이블에 외곽선 테두리가 있는 경우 True를 반환합니다. |
| [hasBorderVertical()](#hasBorderVertical--) | 차트 데이터 테이블에 수직 셀 테두리가 있는 경우 True를 반환합니다. |
| [setBorderVertical(boolean value)](#setBorderVertical-boolean-) | 차트 데이터 테이블에 수직 셀 테두리가 있는 경우 True를 반환합니다. |
| [getShowLegendKey()](#getShowLegendKey--) | 데이터 레이블 범례 키가 표시되는 경우 True를 반환합니다. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 데이터 레이블 범례 키가 표시되는 경우 True를 반환합니다. |
| [getChart()](#getChart--) | 차트를 반환합니다. |
| [getTextFormat()](#getTextFormat--) | 텍스트 형식을 반환합니다. |
| [getSlide()](#getSlide--) | FillFormat의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 상위 프레젠테이션을 반환합니다. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


객체의 선, 채우기 및 효과 스타일을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)
### hasBorderHorizontal() {#hasBorderHorizontal--}
```
public final boolean hasBorderHorizontal()
```


차트 데이터 테이블에 수평 셀 테두리가 있는 경우 True를 반환합니다. 읽기/쓰기 부울.

**반환:**
boolean
### setBorderHorizontal(boolean value) {#setBorderHorizontal-boolean-}
```
public final void setBorderHorizontal(boolean value)
```


차트 데이터 테이블에 수평 셀 테두리가 있는 경우 True를 반환합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasBorderOutline() {#hasBorderOutline--}
```
public final boolean hasBorderOutline()
```


차트 데이터 테이블에 외곽선 테두리가 있는 경우 True를 반환합니다. 읽기/쓰기 부울.

**반환:**
boolean
### setBorderOutline(boolean value) {#setBorderOutline-boolean-}
```
public final void setBorderOutline(boolean value)
```


차트 데이터 테이블에 외곽선 테두리가 있는 경우 True를 반환합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasBorderVertical() {#hasBorderVertical--}
```
public final boolean hasBorderVertical()
```


차트 데이터 테이블에 수직 셀 테두리가 있는 경우 True를 반환합니다. 읽기/쓰기 부울.

**반환:**
boolean
### setBorderVertical(boolean value) {#setBorderVertical-boolean-}
```
public final void setBorderVertical(boolean value)
```


차트 데이터 테이블에 수직 셀 테두리가 있는 경우 True를 반환합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```


데이터 레이블 범례 키가 표시되는 경우 True를 반환합니다. 읽기/쓰기 부울.

**반환:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```


데이터 레이블 범례 키가 표시되는 경우 True를 반환합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```


차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환:**
[IChart](../../com.aspose.slides/ichart)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**반환:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


FillFormat의 상위 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


FillFormat의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)