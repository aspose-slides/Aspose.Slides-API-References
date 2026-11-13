---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a cached chart value e.g. X Y bubble size or the main value.
type: docs
url: /ko/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

캐시된 차트 값 (예: X, Y, 버블 크기 또는 기본 값)을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getData()](#getData--) | 캐시된 데이터 객체를 가져옵니다. |
| [toDouble()](#toDouble--) | 캐시된 값을 double로 변환합니다. |
### getData() {#getData--}
```
public abstract Object getData()
```


캐시된 데이터 객체를 가져옵니다. 읽기 전용 Object .

**반환:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


캐시된 값을 double로 변환합니다.

**반환:**
double - 숫자 표현이며, Data (\#getData.getData)가 null이거나 double로 변환할 수 없는 경우 Double.NaN을 반환합니다.