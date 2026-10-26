---
title: IDataLabelFormat
second_title: Java API 레퍼런스를 통해 Android용 Aspose.Slides
description: DataLabel에 대한 형식 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idatalabelformat/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

DataLabel에 대한 형식 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 읽기/쓰기 boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 읽기/쓰기 boolean. |
| [getNumberFormat()](#getNumberFormat--) | DataLabels 개체에 대한 형식 문자열을 나타냅니다. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels 개체에 대한 형식 문자열을 나타냅니다. |
| [getFormat()](#getFormat--) | 데이터 레이블의 형식을 나타냅니다. |
| [getPosition()](#getPosition--) | 데이터 레이블의 위치를 나타냅니다. |
| [setPosition(int value)](#setPosition-int-) | 데이터 레이블의 위치를 나타냅니다. |
| [getShowLegendKey()](#getShowLegendKey--) | 특정 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 특정 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. |
| [getShowValue()](#getShowValue--) | 특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [getShowCategoryName()](#getShowCategoryName--) | 특정 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 특정 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. |
| [getShowSeriesName()](#getShowSeriesName--) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환하거나 설정합니다. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환하거나 설정합니다. |
| [getShowPercentage()](#getShowPercentage--) | 특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [getShowBubbleSize()](#getShowBubbleSize--) | 특정 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 특정 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. |
| [getShowLeaderLines()](#getShowLeaderLines--) | 특정 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 특정 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 특정 차트의 데이터 레이블이 데이터 콜아웃으로 표시될지 데이터 레이블로 표시될지 결정합니다. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 특정 차트의 데이터 레이블이 데이터 콜아웃으로 표시될지 데이터 레이블로 표시될지 결정합니다. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 특정 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 특정 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. |
| [getSeparator()](#getSeparator--) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 IsNumberFormatLinkedToSource 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 IsNumberFormatLinkedToSource 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" 로 인해 모든 DataLabels.get_Item(i).isNumberFormatLinkedToSource()가 val과 동일해짐).

**반환:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 IsNumberFormatLinkedToSource 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 IsNumberFormatLinkedToSource 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" 로 인해 모든 DataLabels.get_Item(i).isNumberFormatLinkedToSource()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

DataLabels 개체에 대한 형식 문자열을 나타냅니다. 읽기/쓰기 String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
```

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 NumberFormat 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 로 인해 모든 DataLabels.get_Item(i).getNumberFormat()가 val과 동일해짐).

**반환:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

DataLabels 개체에 대한 형식 문자열을 나타냅니다. 읽기/쓰기 String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
```

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 NumberFormat 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" 로 인해 모든 DataLabels.get_Item(i).getNumberFormat()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

데이터 레이블의 형식을 나타냅니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 기본 형식을 나타냅니다.

**반환:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

데이터 레이블의 위치를 나타냅니다. 읽기/쓰기 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Position 속성의 기본값을 가져오거나 설정합니다. DataLabel 객체의 위치를 나타냅니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 Position 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setPosition(val)" 로 인해 모든 DataLabels.get_Item(i).getPosition()가 val과 동일해짐).

**반환:**  
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

데이터 레이블의 위치를 나타냅니다. 읽기/쓰기 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Position 속성의 기본값을 가져오거나 설정합니다. DataLabel 객체의 위치를 나타냅니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 Position 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setPosition(val)" 로 인해 모든 DataLabels.get_Item(i).getPosition()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

특정 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. 데이터 레이블 범례 키가 보이면 true. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLegendKey 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLegendKey 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLegendKey()가 val과 동일해짐).

**반환:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

특정 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. 데이터 레이블 범례 키가 보이면 true. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLegendKey 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLegendKey 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLegendKey()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시합니다. false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowValue 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowValue 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" 로 인해 모든 DataLabels.get_Item(i).getShowValue()가 val과 동일해짐).

**반환:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시합니다. false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowValue 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowValue 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" 로 인해 모든 DataLabels.get_Item(i).getShowValue()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

특정 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. 차트의 데이터 레이블에 카테고리 이름을 표시하려면 true, 숨기려면 false.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowCategoryName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowCategoryName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 로 인해 모든 DataLabels.get_Item(i).getShowCategoryName()가 val과 동일해짐).

**반환:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

특정 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다. 차트의 데이터 레이블에 카테고리 이름을 표시하려면 true, 숨기려면 false.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowCategoryName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowCategoryName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" 로 인해 모든 DataLabels.get_Item(i).getShowCategoryName()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환하거나 설정합니다. true이면 시리즈 이름을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowSeriesName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowSeriesName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 로 인해 모든 DataLabels.get_Item(i).getShowSeriesName()가 val과 동일해짐).

**반환:**  
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환하거나 설정합니다. true이면 시리즈 이름을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowSeriesName 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowSeriesName 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" 로 인해 모든 DataLabels.get_Item(i).getShowSeriesName()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowPercentage 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowPercentage 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 로 인해 모든 DataLabels.get_Item(i).getShowPercentage()가 val과 동일해짐).

**반환:**  
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowPercentage 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowPercentage 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" 로 인해 모든 DataLabels.get_Item(i).getShowPercentage()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

특정 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. true이면 버블 크기 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowBubbleSize 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowBubbleSize 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 로 인해 모든 DataLabels.get_Item(i).getShowBubbleSize()가 val과 동일해짐).

**반환:**  
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

특정 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. true이면 버블 크기 값을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowBubbleSize 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowBubbleSize 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" 로 인해 모든 DataLabels.get_Item(i).getShowBubbleSize()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

특정 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. true이면 리더 라인을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLeaderLines 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLeaderLines 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLeaderLines()가 val과 동일해짐).

**반환:**  
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

특정 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. true이면 리더 라인을 표시하고, false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLeaderLines 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLeaderLines 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLeaderLines()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

특정 차트의 데이터 레이블이 데이터 콜아웃으로 표시될지 데이터 레이블로 표시될지 결정합니다.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelAsDataCallout 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLabelAsDataCallout 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLabelAsDataCallout()가 val과 동일해짐).

**반환:**  
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

특정 차트의 데이터 레이블이 데이터 콜아웃으로 표시될지 데이터 레이블로 표시될지 결정합니다.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelAsDataCallout 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLabelAsDataCallout 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLabelAsDataCallout()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

특정 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. 셀 값을 표시하려면 true, 숨기려면 false. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelValueFromCell 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLabelValueFromCell 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLabelValueFromCell()가 val과 동일해짐).

**반환:**  
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

특정 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. 셀 값을 표시하려면 true, 숨기려면 false. 읽기/쓰기 boolean.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLabelValueFromCell 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLabelValueFromCell 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" 로 인해 모든 DataLabels.get_Item(i).getShowLabelValueFromCell()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 읽기/쓰기 String.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Separator 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 Separator 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 로 인해 모든 DataLabels.get_Item(i).getSeparator()가 val과 동일해짐).

**반환:**  
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 읽기/쓰기 String.

--------------------

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Separator 속성의 기본값을 가져오거나 설정합니다. 값을 사용하여 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 Separator 속성에도 동일한 값이 설정됩니다(예: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" 로 인해 모든 DataLabels.get_Item(i).getSeparator()가 val과 동일해짐).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |