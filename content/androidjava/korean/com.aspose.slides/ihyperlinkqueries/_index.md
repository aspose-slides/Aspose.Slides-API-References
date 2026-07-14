---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다.
type: docs
url: /ko/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | null이 아닌 HyperlinkClick을 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | 모든 IHyperlinkContainer 하위 객체에 포함된 HyperlinkClick 및 HyperlinkMouseOver 하이퍼링크를 제거합니다(모든 IHyperlinkContainer 하위 객체에서). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

null이 아닌 HyperlinkClick을 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. 주어진 IHyperlinkContainer 객체를 사용하면 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 제거). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - null이 아닌 HyperlinkClick을 포함하는 모든 IHyperlinkContainer 하위 객체

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. 주어진 IHyperlinkContainer 객체를 사용하면 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 제거). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체를 가져옵니다. 주어진 IHyperlinkContainer 객체를 사용하면 해당 하이퍼링크를 관리할 수 있습니다(읽기, 업데이트 또는 제거). IHyperlinkContainer 인터페이스를 참조하십시오.

**반환:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - null이 아닌 HyperlinkMouseOver를 포함하는 모든 IHyperlinkContainer 하위 객체

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

모든 IHyperlinkContainer 하위 객체에 포함된 HyperlinkClick 및 HyperlinkMouseOver 하이퍼링크를 제거합니다.