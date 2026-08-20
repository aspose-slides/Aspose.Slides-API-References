---
title: HyperlinkQueries
second_title: Aspose.Slides for Java API 참조
description: 포함된 하이퍼링크에 쉽게 접근할 수 있도록 제공합니다.
type: docs
url: /ko/com.aspose.slides/hyperlinkqueries/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

포함된 하이퍼링크에 쉽게 접근할 수 있도록 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | null이 아닌 HyperlinkClick을 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | 모든 IHyperlinkContainer 하위 객체에 포함된 HyperlinkClick 및 HyperlinkMouseOver 하이퍼링크를 모두 제거합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

null이 아닌 HyperlinkClick을 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. 지정된 IHyperlinkContainer 객체를 사용하여 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 제거). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. 지정된 IHyperlinkContainer 객체를 사용하여 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 제거). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. 지정된 IHyperlinkContainer 객체를 사용하여 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 제거). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

모든 IHyperlinkContainer 하위 객체에 포함된 HyperlinkClick 및 HyperlinkMouseOver 하이퍼링크를 모두 제거합니다.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject