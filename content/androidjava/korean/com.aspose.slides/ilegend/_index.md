---
title: ILegend
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: 차트 레전드 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilegend/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

차트 레전드 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap legend. |
| [getPosition()](#getPosition--) | Specifies the position of the legend on a chart. |
| [setPosition(int value)](#setPosition-int-) | Specifies the position of the legend on a chart. |
| [getFormat()](#getFormat--) | Returns the format of a legend. |
| [getEntries()](#getEntries--) | Gets legend entries. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Determines whether other chart elements shall be allowed to overlap legend. 읽기/쓰기 boolean.

**반환:**  
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Determines whether other chart elements shall be allowed to overlap legend. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. 읽기/쓰기 [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**반환:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Specifies the position of the legend on a chart. Non-NaN values of X, Y, Width, Heigt properties override effect of this property. 읽기/쓰기 [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returns the format of a legend. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**  
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Gets legend entries. 읽기 전용 [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**반환:**  
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)