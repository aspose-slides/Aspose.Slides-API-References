---
title: IStringChartValue
second_title: Aspose.Slides for Android Java API 참조
description: pptx 프레젠테이션 문서에 저장될 수 있는 문자열 값을 두 가지 방법으로 나타냅니다: 1) 차트와 관련된 워크북의 셀/셀들에, 2) 리터럴 값으로.
type: docs
url: /ko/com.aspose.slides/istringchartvalue/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

pptx 프레젠테이션 문서에 저장될 수 있는 문자열 값을 두 가지 방법으로 나타냅니다: 1) 차트와 관련된 워크북의 셀/셀들에; 2) 리터럴 값으로.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. |
| [toString()](#toString--) | 문자열 표현을 반환합니다. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 지정된 셀에서 값을 설정합니다. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | DataSourceType 속성이 DataSourceType.Worksheet인 경우, 이 메서드는 문자열 데이터를 나타내는 워크북 내 셀들의 주소를 반환합니다. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. 읽기/쓰기 문자열.

**반환:**  
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. 읽기/쓰기 문자열.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### toString() {#toString--}
```
public abstract String toString()
```

문자열 표현을 반환합니다.

**반환:**  
java.lang.String - 값 문자열의 문자열 표현
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

지정된 셀에서 값을 설정합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

DataSourceType 속성이 DataSourceType.Worksheet인 경우, 이 메서드는 문자열 데이터를 나타내는 워크북 내 셀들의 주소를 반환합니다. 그렇지 않으면 빈 문자열을 반환합니다.

**반환:**  
java.lang.String - 문자열 값 문자열