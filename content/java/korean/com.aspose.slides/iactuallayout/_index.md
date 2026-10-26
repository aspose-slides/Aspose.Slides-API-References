---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: 차트 요소의 실제 위치를 지정합니다.
type: docs
url: /ko/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

차트 요소의 실제 위치를 지정합니다.
## 메서드

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | 차트 요소의 실제 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. |
| [getActualY()](#getActualY--) | 차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. |
| [getActualWidth()](#getActualWidth--) | 차트 요소의 실제 너비를 지정합니다. |
| [getActualHeight()](#getActualHeight--) | 차트 요소의 실제 높이를 지정합니다. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

차트 요소의 실제 x 위치(왼쪽)를 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. IChart.ValidateChartLayout() 메서드를 먼저 호출하여 실제 값을 가져옵니다. 읽기 전용 float.

**반환:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

차트 요소의 실제 상단을 차트의 왼쪽 상단 모서리를 기준으로 지정합니다. IChart.ValidateChartLayout() 메서드를 먼저 호출하여 실제 값을 가져옵니다. 읽기 전용 float.

**반환:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

차트 요소의 실제 너비를 지정합니다. IChart.ValidateChartLayout() 메서드를 먼저 호출하여 실제 값을 가져옵니다. 읽기 전용 float.

**반환:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

차트 요소의 실제 높이를 지정합니다. IChart.ValidateChartLayout() 메서드를 먼저 호출하여 실제 값을 가져옵니다. 읽기 전용 float.

**반환:**
float