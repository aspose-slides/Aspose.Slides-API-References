---
title: LegendEntryProperties
second_title: Aspose.Slides Java API 참조
description: 차트의 범례 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/legendentryproperties/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

차트의 범례 속성을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | 텍스트 형식을 반환합니다. |
| [getHide()](#getHide--) | 범례 항목이 숨겨져 있는지 여부를 결정합니다. |
| [setHide(boolean value)](#setHide-boolean-) | 범례 항목이 숨겨져 있는지 여부를 결정합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 부모 차트를 반환합니다. |
| [getSlide()](#getSlide--) | FillFormat의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 부모 프레젠테이션을 반환합니다. |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**반환:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getHide() {#getHide--}
```
public final boolean getHide()
```

범례 항목이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setHide(boolean value) {#setHide-boolean-}
```
public final void setHide(boolean value)
```

범례 항목이 숨겨져 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 개체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

부모 차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat의 부모 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)