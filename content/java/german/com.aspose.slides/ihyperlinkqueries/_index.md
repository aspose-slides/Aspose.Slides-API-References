---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Bietet einfachen Zugriff auf enthaltene Hyperlinks.
type: docs
url: /de/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Bietet einfachen Zugriff auf enthaltene Hyperlinks.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Ruft alle IHyperlinkContainer-Teilobjekte ab, die ein nicht null HyperlinkClick enthalten. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Ruft alle IHyperlinkContainer-Teilobjekte ab, die ein nicht null HyperlinkMouseOver enthalten. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Ruft alle IHyperlinkContainer-Teilobjekte ab, die ein nicht null HyperlinkMouseOver enthalten. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Entfernt alle enthaltenen HyperlinkClick- und HyperlinkMouseOver-Hyperlinks (in allen IHyperlinkContainer-Teilobjekten). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Ruft alle IHyperlinkContainer-Teilobjekte ab, die ein nicht null HyperlinkClick enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe das IHyperlinkContainer-Interface.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-Teilobjekte, die ein nicht null HyperlinkClick enthalten
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Ruft alle IHyperlinkContainer-Teilobjekte ab, die ein nicht null HyperlinkMouseOver enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe das IHyperlinkContainer-Interface.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-Teilobjekte, die ein nicht null HyperlinkMouseOver enthalten
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Ruft alle IHyperlinkContainer-Teilobjekte ab, die ein nicht null HyperlinkMouseOver enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe das IHyperlinkContainer-Interface.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-Teilobjekte, die ein nicht null HyperlinkMouseOver enthalten
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Entfernt alle enthaltenen HyperlinkClick- und HyperlinkMouseOver-Hyperlinks (in allen IHyperlinkContainer-Teilobjekten).