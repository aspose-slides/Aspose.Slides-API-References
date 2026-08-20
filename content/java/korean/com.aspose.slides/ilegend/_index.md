---
title: ILegend
second_title: Aspose.Slides for Java API 레퍼런스
description: 차트 범례 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilegend/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

차트 범례 속성을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | 다른 차트 요소가 범례와 겹치도록 허용할지 여부를 결정합니다. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 다른 차트 요소가 범례와 겹치도록 허용할지 여부를 결정합니다. |
| [getPosition()](#getPosition--) | 차트에서 범례의 위치를 지정합니다. |
| [setPosition(int value)](#setPosition-int-) | 차트에서 범례의 위치를 지정합니다. |
| [getFormat()](#getFormat--) | 범례의 형식을 반환합니다. |
| [getEntries()](#getEntries--) | 범례 항목을 가져옵니다. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


다른 차트 요소가 범례와 겹치도록 허용할지 여부를 결정합니다. 읽기/쓰기 boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


다른 차트 요소가 범례와 겹치도록 허용할지 여부를 결정합니다. 읽기/쓰기 boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


차트에서 범례의 위치를 지정합니다. X, Y, Width, Heigt 속성의 NaN이 아닌 값은 이 속성의 효과를 재정의합니다. 읽기/쓰기 [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


차트에서 범례의 위치를 지정합니다. X, Y, Width, Heigt 속성의 NaN이 아닌 값은 이 속성의 효과를 재정의합니다. 읽기/쓰기 [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


범례의 형식을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


범례 항목을 가져옵니다. 읽기 전용 [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Returns:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)