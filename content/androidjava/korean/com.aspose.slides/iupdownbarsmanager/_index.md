---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /ko/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

라인 또는 주식 차트의 업/다운 바에 대한 액세스를 제공합니다.
## 메서드

| Method | Description |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | 업 바의 형식을 반환합니다. |
| [getDownBarsFormat()](#getDownBarsFormat--) | 다운 바의 형식을 반환합니다. |
| [hasUpDownBars()](#hasUpDownBars--) | 차트에 업/다운 바가 있는지 확인합니다. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | 차트에 업/다운 바가 있는지 확인합니다. |
| [getGapWidth()](#getGapWidth--) | 갭 너비를 반환하거나 설정합니다. |
| [setGapWidth(int value)](#setGapWidth-int-) | 갭 너비를 반환하거나 설정합니다. |
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


차트에 업/다운 바가 있는지 확인합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


차트에 업/다운 바가 있는지 확인합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


갭 너비를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


갭 너비를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |