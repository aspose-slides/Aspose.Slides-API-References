---
title: DataLabelFormat
second_title: Aspose.Slides for Android를 통한 Java API 참조
description: DataLabel에 대한 서식 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/datalabelformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)  
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

DataLabel에 대한 서식 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 읽기/쓰기 boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 읽기/쓰기 boolean. |
| [getNumberFormat()](#getNumberFormat--) | DataLabels 객체의 형식 문자열을 나타냅니다. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels 객체의 형식 문자열을 나타냅니다. |
| [getFormat()](#getFormat--) | 데이터 레이블의 형식을 나타냅니다. |
| [getPosition()](#getPosition--) | 데이터 레이블의 위치를 나타냅니다. |
| [setPosition(int value)](#setPosition-int-) | 데이터 레이블의 위치를 나타냅니다. |
| [getShowLegendKey()](#getShowLegendKey--) | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. |
| [getShowValue()](#getShowValue--) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [getShowCategoryName()](#getShowCategoryName--) | 지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. |
| [getShowSeriesName()](#getShowSeriesName--) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다. |
| [getShowPercentage()](#getShowPercentage--) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [getShowBubbleSize()](#getShowBubbleSize--) | 지정된 차트의 데이터 레이블 말풍선 크기 값 표시 동작을 나타냅니다. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 지정된 차트의 데이터 레이블 말풍선 크기 값 표시 동작을 나타냅니다. |
| [getShowLeaderLines()](#getShowLeaderLines--) | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 지정된 차트의 데이터 레이블이 데이터 콜아웃 또는 데이터 레이블로 표시될지 결정합니다. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 지정된 차트의 데이터 레이블이 데이터 콜아웃 또는 데이터 레이블로 표시될지 결정합니다. |
| [getSeparator()](#getSeparator--) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. |
| [getTextFormat()](#getTextFormat--) | 차트 텍스트 형식을 반환합니다. |
| [getChart()](#getChart--) | 차트를 반환합니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 IsNumberFormatLinkedToSource 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 IsNumberFormatLinkedToSource 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" 은 모든 DataLabels.get_Item(i).isNumberFormatLinkedToSource()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 IsNumberFormatLinkedToSource 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 IsNumberFormatLinkedToSource 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" 은 모든 DataLabels.get_Item(i).isNumberFormatLinkedToSource()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

DataLabels 객체의 형식 문자열을 나타냅니다. 읽기/쓰기 String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

이 DataLabelFormat 객체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 NumberFormat 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 은 모든 DataLabels.get_Item(i).getNumberFormat()가 val과 동일하도록 합니다).

**반환:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

DataLabels 객체의 형식 문자열을 나타냅니다. 읽기/쓰기 String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

이 DataLabelFormat 객체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 NumberFormat 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 은 모든 DataLabels.get_Item(i).getNumberFormat()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

데이터 레이블의 형식을 나타냅니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 새 데이터 레이블에 대한 기본 형식을 나타냅니다.

**반환:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

데이터 레이블의 위치를 나타냅니다. 읽기/쓰기 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Position 속성의 기본값을 가져오거나 설정합니다. DataLabel 객체의 위치를 나타냅니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 Position 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" 은 모든 DataLabels.get_Item(i).getPosition()가 val과 동일하도록 합니다).

**반환:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

데이터 레이블의 위치를 나타냅니다. 읽기/쓰기 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Position 속성의 기본값을 가져오거나 설정합니다. DataLabel 객체의 위치를 나타냅니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 Position 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" 은 모든 DataLabels.get_Item(i).getPosition()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. 키가 표시되면 true. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLegendKey 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLegendKey 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" 은 모든 DataLabels.get_Item(i).getShowLegendKey()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. 키가 표시되면 true. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLegendKey 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLegendKey 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" 은 모든 DataLabels.get_Item(i).getShowLegendKey()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowValue 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowValue 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" 은 모든 DataLabels.get_Item(i).getShowValue()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowValue 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowValue 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" 은 모든 DataLabels.get_Item(i).getShowValue()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. true이면 카테고리 이름을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowCategoryName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowCategoryName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 은 모든 DataLabels.get_Item(i).getShowCategoryName()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. true이면 카테고리 이름을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowCategoryName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowCategoryName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 은 모든 DataLabels.get_Item(i).getShowCategoryName()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다. true이면 시리즈 이름을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowSeriesName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowSeriesName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 은 모든 DataLabels.get_Item(i).getShowSeriesName()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다. true이면 시리즈 이름을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowSeriesName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowSeriesName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 은 모든 DataLabels.get_Item(i).getShowSeriesName()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowPercentage 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowPercentage 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 은 모든 DataLabels.get_Item(i).getShowPercentage()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowPercentage 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowPercentage 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 은 모든 DataLabels.get_Item(i).getShowPercentage()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

지정된 차트의 데이터 레이블 말풍선 크기 값 표시 동작을 나타냅니다. true이면 말풍선 크기 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowBubbleSize 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowBubbleSize 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 은 모든 DataLabels.get_Item(i).getShowBubbleSize()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

지정된 차트의 데이터 레이블 말풍선 크기 값 표시 동작을 나타냅니다. true이면 말풍선 크기 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowBubbleSize 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowBubbleSize 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 은 모든 DataLabels.get_Item(i).getShowBubbleSize()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. true이면 리더 라인을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLeaderLines 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLeaderLines 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 은 모든 DataLabels.get_Item(i).getShowLeaderLines()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. true이면 리더 라인을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLeaderLines 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLeaderLines 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 은 모든 DataLabels.get_Item(i).getShowLeaderLines()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. true이면 셀 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelValueFromCell 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLabelValueFromCell 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 은 모든 DataLabels.get_Item(i).getShowLabelValueFromCell()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. true이면 셀 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelValueFromCell 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLabelValueFromCell 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 은 모든 DataLabels.get_Item(i).getShowLabelValueFromCell()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

지정된 차트의 데이터 레이블이 데이터 콜아웃 또는 데이터 레이블로 표시될지 결정합니다.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelAsDataCallout 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLabelAsDataCallout 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 은 모든 DataLabels.get_Item(i).getShowLabelAsDataCallout()가 val과 동일하도록 합니다).

**반환:**  
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

지정된 차트의 데이터 레이블이 데이터 콜아웃 또는 데이터 레이블로 표시될지 결정합니다.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelAsDataCallout 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 ShowLabelAsDataCallout 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 은 모든 DataLabels.get_Item(i).getShowLabelAsDataCallout()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 읽기/쓰기 String.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Separator 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 Separator 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 은 모든 DataLabels.get_Item(i).getSeparator()가 val과 동일하도록 합니다).

**반환:**  
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 읽기/쓰기 String.

--------------------

이 DataLabelFormat 객체의 상위가 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Separator 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 모든 데이터 레이블에 대해 Separator 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 은 모든 DataLabels.get_Item(i).getSeparator()가 val과 동일하도록 합니다).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

차트 텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**반환:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환:**  
[IChart](../../com.aspose.slides/ichart)