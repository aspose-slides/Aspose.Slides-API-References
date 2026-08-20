---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /ko/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Line 차트 또는 Stock 차트의 up/down 바에 대한 액세스를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | 업 바의 형식을 반환합니다. |
| [getDownBarsFormat()](#getDownBarsFormat--) | 다운 바의 형식을 반환합니다. |
| [hasUpDownBars()](#hasUpDownBars--) | 차트에 up/down 바가 있는지 여부를 확인합니다. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | 차트에 up/down 바가 있는지 여부를 확인합니다. |
| [getGapWidth()](#getGapWidth--) | gap width를 반환하거나 설정합니다. |
| [setGapWidth(int value)](#setGapWidth-int-) | gap width를 반환하거나 설정합니다. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

업 바의 형식을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

다운 바의 형식을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

차트에 up/down 바가 있는지 여부를 확인합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

차트에 up/down 바가 있는지 여부를 확인합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

gap width를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

gap width를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |