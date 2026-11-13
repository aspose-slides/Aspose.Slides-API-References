---
title: CachedChartValue
second_title: Aspose.Slides for Java API 레퍼런스
description: 캐시된 차트 값을 나타냅니다. 예: X Y 버블 크기 또는 주요 값.
type: docs
url: /ko/com.aspose.slides/cachedchartvalue/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

캐시된 차트 값(예: X, Y, 버블 크기 또는 주요 값)을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [toString()](#toString--) | 캐시된 값의 문자열 표현을 반환합니다. |
| [toDouble()](#toDouble--) | 캐시된 값을 double 형식으로 변환합니다. |
| [getData()](#getData--) | 캐시된 데이터 객체를 가져옵니다. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


캐시된 값의 문자열 표현을 반환합니다.

**반환값:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


캐시된 값을 double 형식으로 변환합니다.

**반환값:**
double - 수치 표현이며, Data (\#getData.getData/\#setData(Object).setData(Object)) 가 null이거나 double로 변환될 수 없을 경우 Double.NaN을 반환합니다.
### getData() {#getData--}
```
public final Object getData()
```


캐시된 데이터 객체를 가져옵니다. 읽기 전용  Object .

**반환값:**
java.lang.Object