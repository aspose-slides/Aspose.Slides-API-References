---
title: IDoubleChartValue
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: pptx 프레젠테이션 문서에 저장될 수 있는 double 값을 두 가지 방법으로 나타냅니다: 1) 차트와 관련된 워크북의 셀/셀에, 2) 리터럴 값으로.
type: docs
url: /ko/com.aspose.slides/idoublechartvalue/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

pptx 프레젠테이션 문서에 저장될 수 있는 double 값을 두 가지 방식으로 나타냅니다: 1) 차트와 관련된 워크북의 셀/셀에; 2) 리터럴 값으로.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType = Charts.DataSourceType.DoubleLiterals인 경우 리터럴 double 값을 반환하거나 설정합니다. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType = Charts.DataSourceType.DoubleLiterals인 경우 리터럴 double 값을 반환하거나 설정합니다. |
| [toDouble()](#toDouble--) | double로 변환합니다. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

DataSourceType = Charts.DataSourceType.DoubleLiterals인 경우 리터럴 double 값을 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**  
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

DataSourceType = Charts.DataSourceType.DoubleLiterals인 경우 리터럴 double 값을 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

double로 변환합니다.

**반환:**  
double - Double 값.