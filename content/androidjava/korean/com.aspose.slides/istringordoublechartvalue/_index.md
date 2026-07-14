---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: pptx 프레젠테이션 문서에 저장될 수 있는 문자열 또는 실수 값을 두 가지 방법으로 표현합니다: 1) 차트와 연관된 워크북의 셀/셀에, 2) 리터럴 값으로.
type: docs
url: /ko/com.aspose.slides/istringordoublechartvalue/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

pptx 프레젠테이션 문서에 저장될 수 있는 문자열 또는 실수 값을 두 가지 방법으로 표현합니다: 1) 차트와 연결된 워크북의 셀/셀에; 2) 리터럴 값으로.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType 속성이 DataSourceType.DoubleLiterals인 경우 리터럴 실수를 반환하거나 설정합니다. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType 속성이 DataSourceType.DoubleLiterals인 경우 리터럴 실수를 반환하거나 설정합니다. |
| [toDouble()](#toDouble--) | 값을 double로 변환합니다. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


DataSourceType 속성이 DataSourceType.DoubleLiterals인 경우 리터럴 실수를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


DataSourceType 속성이 DataSourceType.DoubleLiterals인 경우 리터럴 실수를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


값을 double로 변환합니다.

**반환:**
double - Double 값 double