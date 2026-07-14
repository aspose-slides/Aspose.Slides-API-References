---
title: DoubleChartValue
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: pptx 프레젠테이션 문서에 저장될 수 있는 double 값을 두 가지 방식으로 나타냅니다: 1) 차트와 연관된 워크북의 셀/셀들에, 2) 리터럴 값으로.
type: docs
url: /ko/com.aspose.slides/doublechartvalue/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)  
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

pptx 프레젠테이션 문서에 저장될 수 있는 double 값을 두 가지 방식으로 나타냅니다: 1) 차트와 연관된 워크북의 셀/셀들에; 2) 리터럴 값으로.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAsCell()](#getAsCell--) | 차트 데이터 셀을 반환하거나 설정합니다. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 차트 데이터 셀을 반환하거나 설정합니다. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | 값을 리터럴 double로 반환하거나 설정합니다. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | 값을 리터럴 double로 반환하거나 설정합니다. |
| [getData()](#getData--) | Data 객체를 반환하거나 설정합니다. |
| [setData(Object value)](#setData-java.lang.Object-) | Data 객체를 반환하거나 설정합니다. |
| [toDouble()](#toDouble--) | double로 변환합니다. |
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

double로 변환합니다.

**반환:**
double - DataSourceType이 DoubleLiterals와 같으면 LiteralDouble를 반환합니다. DataSourceType이 Worksheet와 같으면 double 셀 값으로 성공적으로 변환된 값을 반환하고, 그렇지 않으면 NaN을 반환합니다.