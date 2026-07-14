---
title: ISequence
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 효과의 시퀀스 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isequence/
---
**모든 구현된 인터페이스:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

시퀀스(효과 컬렉션)를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 시퀀스의 효과 수를 반환합니다. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | 지정된 효과를 컬렉션에서 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 효과를 컬렉션에서 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 효과를 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 효과를 반환합니다. |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE 시퀀스에 대한 shape 대상 반환 또는 설정합니다. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE 시퀀스에 대한 shape 대상 반환 또는 설정합니다. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 지정된 shape에 대한 효과를 제거합니다. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 지정된 shape에 대한 효과 배열을 반환합니다. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 지정된 paragraph에 대한 효과 배열을 반환합니다. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 지정된 shape에 대한 효과 수를 반환합니다. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | 시퀀스 끝에 새 효과를 추가합니다. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | 시퀀스 끝에 단락에 대한 새 애니메이션 효과를 추가합니다. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | 시퀀스 끝에 범주 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | 시퀀스 끝에 범주 또는 시리즈 내 요소에 대한 새 차트 애니메이션 효과를 추가합니다. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

시퀀스의 효과 수를 반환합니다. 읽기 전용 int.

**반환:**  
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

지정된 효과를 컬렉션에서 제거합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 제거할 효과. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 효과를 제거합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 제거할 효과의 인덱스 int |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 효과를 제거합니다.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

지정된 인덱스에 있는 효과를 반환합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환:**  
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) 객체.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

INTERACTIVE 시퀀스에 대한 shape 대상 반환 또는 설정합니다. 시퀀스가 인터랙티브하지 않으면 null을 반환합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**반환:**  
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

INTERACTIVE 시퀀스에 대한 shape 대상 반환 또는 설정합니다. 시퀀스가 인터랙티브하지 않으면 null을 반환합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

지정된 shape에 대한 효과를 제거합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape 객체 [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

지정된 shape에 대한 효과 배열을 반환합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape 객체 [IShape](../../com.aspose.slides/ishape) |

**반환:**  
com.aspose.slides.IEffect[] - 효과 배열 [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

지정된 paragraph에 대한 효과 배열을 반환합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph 객체 [IParagraph](../../com.aspose.slides/iparagraph) |

**반환:**  
com.aspose.slides.IEffect[] - 효과 배열 [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

지정된 shape에 대한 효과 수를 반환합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape 객체 [IShape](../../com.aspose.slides/ishape) |

**반환:**  
int - 효과 수 int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 새 효과를 추가합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape 객체 [IShape](../../com.aspose.slides/ishape) (효과 추가용) |
| effectType | int | 애니메이션 효과 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과 서브 타입 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환:**  
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 단락에 대한 새 애니메이션 효과를 추가합니다.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // 효과를 추가할 단락 선택
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // 선택한 단락에 Fly 애니메이션 효과 추가
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph 객체 [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | 애니메이션 효과 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과 서브 타입 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환:**  
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 범주 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart 객체 [IChart](../../com.aspose.slides/ichart) |
| type | int | 애니메이션 효과 유형 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | 인덱스 int |
| effectType | int | 애니메이션 효과 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과 서브 타입 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환:**  
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 범주 또는 시리즈 내 요소에 대한 새 차트 애니메이션 효과를 추가합니다.

**매개 변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart 객체 [IChart](../../com.aspose.slides/ichart) |
| type | int | 애니메이션 효과 유형 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | 차트 시리즈 인덱스 int |
| categoriesIndex | int | 범주 인덱스 int |
| effectType | int | 애니메이션 효과 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과 서브 타입 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환:**  
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)