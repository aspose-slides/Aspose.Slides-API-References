---
title: LegendEntryProperties
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 차트의 범례 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/legendentryproperties/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject  
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

차트의 범례 속성을 나타냅니다.

## Methods

| Method | Description |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | 텍스트 형식을 반환합니다. |
| [getHide()](#getHide--) | 범례 항목이 숨겨져 있는지 여부를 결정합니다. |
| [setHide(boolean value)](#setHide-boolean-) | 범례 항목이 숨겨져 있는지 여부를 결정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 상위 차트를 반환합니다. |
| [getSlide()](#getSlide--) | FillFormat의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 상위 프레젠테이션을 반환합니다. |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getHide() {#getHide--}
```
public final boolean getHide()
```

범례 항목이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**Returns:**  
boolean

### setHide(boolean value) {#setHide-boolean-}
```
public final void setHide(boolean value)
```

범례 항목이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 개체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

상위 차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**Returns:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat의 상위 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**  
[IPresentation](../../com.aspose.slides/ipresentation)