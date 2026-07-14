---
title: StringOrDoubleChartValue
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: pptx 프레젠테이션 문서에 저장될 수 있는 문자열 또는 실수 값을 두 가지 방법으로 나타냅니다: 1) 차트와 관련된 워크북의 셀/셀에, 2) 리터럴 값으로.
type: docs
url: /ko/com.aspose.slides/stringordoublechartvalue/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)  
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

pptx 프레젠테이션 문서에 저장될 수 있는 문자열 또는 실수 값을 두 가지 방법으로 표현합니다: 1) 차트와 관련된 워크북의 셀/셀에; 2) 리터럴 값으로.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAsCell()](#getAsCell--) | 차트 데이터 셀을 반환하거나 설정합니다. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 차트 데이터 셀을 반환하거나 설정합니다. |
| [getAsLiteralString()](#getAsLiteralString--) | 값을 리터럴 문자열로 반환하거나 설정합니다. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | 값을 리터럴 문자열로 반환하거나 설정합니다. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 값을 리터럴 double로 반환하거나 설정합니다. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 값을 리터럴 double로 반환하거나 설정합니다. |
| [getData()](#getData--) | Data 객체를 반환하거나 설정합니다. |
| [setData(Object value)](#setData-java.lang.Object-) | Data 객체를 반환하거나 설정합니다. |
| [toDouble()](#toDouble--) | double 로 변환합니다. |

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

차트 데이터 셀을 반환하거나 설정합니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**반환:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

차트 데이터 셀을 반환하거나 설정합니다. 읽기/쓰기 [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

값을 리터럴 문자열로 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

값을 리터럴 문자열로 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

값을 리터럴 double로 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

값을 리터럴 double로 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Data 객체를 반환하거나 설정합니다. 읽기/쓰기 Object.

**반환:**  
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

### toDouble() {#toDouble--}
```
public final double toDouble()
```

double 로 변환합니다.

**반환:**  
double - Double 값.