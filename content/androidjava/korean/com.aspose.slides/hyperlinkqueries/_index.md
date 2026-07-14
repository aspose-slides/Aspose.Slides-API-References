---
title: HyperlinkQueries
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 포함된 하이퍼링크에 쉽게 접근할 수 있습니다.
type: docs
url: /ko/com.aspose.slides/hyperlinkqueries/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject  
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

포함된 하이퍼링크에 쉽게 접근할 수 있습니다.
## 메서드

| Method | Description |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Removes all contained HyperlinkClick and HyperlinkMouseOver hyperlinks (in all IHyperlinkContainer subobjects). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

null이 아닌 HyperlinkClick을 포함하는 모든 IHyperlinkContainer 하위 개체를 가져옵니다. 주어진 IHyperlinkContainer 객체를 사용하여 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 삭제). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 개체를 가져옵니다. 주어진 IHyperlinkContainer 객체를 사용하여 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 삭제). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 개체를 가져옵니다. 주어진 IHyperlinkContainer 객체를 사용하여 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 삭제). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

모든 IHyperlinkContainer 하위 개체에 포함된 HyperlinkClick 및 HyperlinkMouseOver 하이퍼링크를 모두 제거합니다.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject