---
title: StringChartValue
second_title: Aspose.Slides for Android Java API 레퍼런스
description: pptx 프레젠테이션 문서에 저장될 수 있는 문자열 값을 두 가지 방법으로 나타냅니다: 1) 차트와 관련된 워크북의 셀/셀에, 2) 리터럴 값으로.
type: docs
url: /ko/com.aspose.slides/stringchartvalue/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**전체 구현 인터페이스:**  
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

pptx 프레젠테이션 문서에 저장될 수 있는 문자열 값을 두 가지 방법으로 나타냅니다: 1) 차트와 관련된 워크북의 셀/셀에; 2) 리터럴 값으로.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAsCells()](#getAsCells--) | null 값 할당은 허용되지 않습니다. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | null 값 할당은 허용되지 않습니다. |
| [getAsLiteralString()](#getAsLiteralString--) | 값을 리터럴 String으로 반환하거나 설정합니다. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 값을 리터럴 String으로 반환하거나 설정합니다. |
| [getData()](#getData--) | Data 객체를 반환하거나 설정합니다. |
| [setData(Object value)](#setData-java.lang.Object-) | Data 객체를 반환하거나 설정합니다. |
| [toString()](#toString--) | 문자열 값 데이터를 반환합니다. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 지정된 셀에서 값을 설정합니다. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | DataSourceType 속성이 DataSourceType.Worksheet인 경우, 이 메서드는 문자열 데이터를 나타내는 워크북의 셀 주소를 반환합니다. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

null 값 할당은 허용되지 않습니다. 반환 값은 항상 null이 아닙니다. 읽기/쓰기 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**반환값:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

null 값 할당은 허용되지 않습니다. 반환 값은 항상 null이 아닙니다. 읽기/쓰기 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

값을 리터럴 String으로 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

값을 리터럴 String으로 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Data 객체를 반환하거나 설정합니다. 읽기/쓰기 Object.

**반환값:**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data 객체를 반환하거나 설정합니다. 읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

문자열 값 데이터를 반환합니다. DataSourceType이 false이고 문자열 값이 할당되지 않은 경우 null을 반환합니다.

**반환값:**  
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

지정된 셀에서 값을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

DataSourceType 속성이 DataSourceType.Worksheet인 경우, 이 메서드는 문자열 데이터를 나타내는 워크북의 셀 주소를 반환합니다. 그렇지 않으면 빈 문자열을 반환합니다.

**반환값:**  
java.lang.String