---
title: Sequence
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 시퀀스 효과 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/sequence/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)  
```
public final class Sequence implements ISequence
```

시퀀스(효과 컬렉션)를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCount()](#getCount--) | 시퀀스의 효과 수를 반환합니다. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | 컬렉션에서 지정된 효과를 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 효과를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 효과를 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 효과를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE 시퀀스에 대한 shape 대상을 반환하거나 설정합니다. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE 시퀀스에 대한 shape 대상을 반환하거나 설정합니다. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 지정된 shape에 대한 효과를 제거합니다. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 지정된 shape에 대한 효과 배열을 반환합니다. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 지정된 paragraph에 대한 효과 배열을 반환합니다. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 지정된 shape에 대한 효과 수를 반환합니다. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | 시퀀스 끝에 새 효과를 추가합니다. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | 시퀀스 끝에 새 단락 애니메이션 효과를 추가합니다. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | 시퀀스 끝에 카테고리 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | 시퀀스 끝에 카테고리 또는 시리즈의 요소에 대한 새 차트 애니메이션 효과를 추가합니다. |

### getCount() {#getCount--}
```
public final int getCount()
```

시퀀스의 효과 수를 반환합니다. 읽기 전용 int.

**반환값:**  
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

컬렉션에서 지정된 효과를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 제거할 효과. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

컬렉션에서 효과를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 할 효과의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 효과를 제거합니다.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

지정된 인덱스의 효과를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 요소의 인덱스. |

**반환값:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) 객체.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - 전체 컬렉션에 대한 java.util.Iterator

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

INTERACTIVE 시퀀스에 대한 shape 대상을 반환하거나 설정합니다. 시퀀스가 인터랙티브하지 않으면 null을 반환합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**반환값:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

INTERACTIVE 시퀀스에 대한 shape 대상을 반환하거나 설정합니다. 시퀀스가 인터랙티브하지 않으면 null을 반환합니다. 읽기/쓰기 [IShape](../../com.aspose.slides/ishape).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

지정된 shape에 대한 효과를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

지정된 shape에 대한 효과 배열을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**반환값:**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

지정된 paragraph에 대한 효과 배열을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**반환값:**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

지정된 shape에 대한 효과 수를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**반환값:**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 새 효과를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 효과를 추가하기 위한 Shape 객체 [IShape](../../com.aspose.slides/ishape) |
| effectType | int | 애니메이션 효과의 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과의 하위 유형 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과의 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환값:**
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 새 단락 애니메이션 효과를 추가합니다.

> ``` 
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // 효과를 추가할 단락을 선택합니다
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // 선택된 단락에 Fly 애니메이션 효과를 추가합니다
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph 객체 [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | 애니메이션 효과의 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과의 하위 유형 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과의 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환값:**
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 카테고리 또는 시리즈에 대한 새 차트 애니메이션 효과를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart 객체 [IChart](../../com.aspose.slides/ichart) |
| type | int | 애니메이션 효과의 유형 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | 인덱스 int |
| effectType | int | 애니메이션 효과의 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과의 하위 유형 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과의 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환값:**
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

시퀀스 끝에 카테고리 또는 시리즈의 요소에 대한 새 차트 애니메이션 효과를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart 객체 [IChart](../../com.aspose.slides/ichart) |
| type | int | 애니메이션 효과의 유형 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | 차트 시리즈의 인덱스 int |
| categoriesIndex | int | 카테고리 인덱스 int |
| effectType | int | 애니메이션 효과의 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과의 하위 유형 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과의 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환값:**
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)