---
title: IDataLabelFormat
second_title: Aspose.Slides for Java API 레퍼런스
description: DataLabel에 대한 서식 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idatalabelformat/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

DataLabel에 대한 서식 옵션을 나타냅니다.
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
| [getShowLegendKey()](#getShowLegendKey--) | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. |
| [getShowValue()](#getShowValue--) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [getShowCategoryName()](#getShowCategoryName--) | 지정된 차트의 데이터 레이블 범주 이름 표시 동작을 나타냅니다. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 지정된 차트의 데이터 레이블 범주 이름 표시 동작을 나타냅니다. |
| [getShowSeriesName()](#getShowSeriesName--) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환하거나 설정합니다. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환하거나 설정합니다. |
| [getShowPercentage()](#getShowPercentage--) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. |
| [getShowBubbleSize()](#getShowBubbleSize--) | 지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. |
| [getShowLeaderLines()](#getShowLeaderLines--) | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 지정된 차트의 데이터 레이블이 데이터 콜아웃으로 표시될지 데이터 레이블로 표시될지를 결정합니다. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 지정된 차트의 데이터 레이블이 데이터 콜아웃으로 표시될지 데이터 레이블로 표시될지를 결정합니다. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. |
| [getSeparator()](#getSeparator--) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val).

**반환:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the IsNumberFormatLinkedToSource property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the IsNumberFormatLinkedToSource property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val).

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
> ```

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

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
> ```

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this property gets or sets the default value of the NumberFormat property for the new data labels in the DataLabelCollection collection. When this property is set with a value, that value is also set for the NumberFormat property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

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

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property represents the default format for the new data labels in the DataLabelCollection collection.

**반환:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

데이터 레이블의 위치를 나타냅니다. 읽기/쓰기 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**반환:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

데이터 레이블의 위치를 나타냅니다. 읽기/쓰기 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Position property for the new data labels in the DataLabelCollection collection. Represents the position for the DataLabel objects. Set this property with value also sets this value to the Position property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. 데이터 레이블 범례 키가 보이는 경우 true. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**반환:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. 데이터 레이블 범례 키가 보이는 경우 true. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLegendKey property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLegendKey property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시합니다. false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**반환:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. true이면 백분율 값을 표시합니다. false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowValue property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowValue property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

지정된 차트의 데이터 레이블 범주 이름 표시 동작을 나타냅니다. true이면 차트의 데이터 레이블에 범주 이름을 표시합니다. false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**반환:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

지정된 차트의 데이터 레이블 범주 이름 표시 동작을 나타냅니다. true이면 차트의 데이터 레이블에 범주 이름을 표시합니다. false이면 숨깁니다. 읽기/쓰기 boolean.

--------------------
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다. True이면 시리즈 이름을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**반환값:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다. True이면 시리즈 이름을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**반환값:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True이면 백분율 값을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. True이면 버블 크기 값을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**반환값:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다. True이면 버블 크기 값을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. True이면 리더 라인을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**반환값:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. True이면 리더 라인을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

지정된 차트의 데이터 레이블이 데이터 호출선(data callout)으로 표시될지 데이터 레이블 자체로 표시될지를 결정합니다.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**반환값:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

지정된 차트의 데이터 레이블이 데이터 호출선(data callout)으로 표시될지 데이터 레이블 자체로 표시될지를 결정합니다.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. True이면 셀 값을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**반환값:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. True이면 셀 값을 표시하고, False이면 숨깁니다. 읽기/쓰기 boolean.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

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

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**반환값:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다. 읽기/쓰기 String.

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).
**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |