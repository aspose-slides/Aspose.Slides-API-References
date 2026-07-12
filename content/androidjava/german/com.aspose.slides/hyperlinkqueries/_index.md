---
title: HyperlinkQueries
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Ermöglicht einfachen Zugriff auf enthaltene Hyperlinks.
type: docs
url: /de/com.aspose.slides/hyperlinkqueries/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

Stellt einfachen Zugriff auf enthaltene Hyperlinks bereit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Ruft alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkClick enthalten. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Ruft alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkMouseOver enthalten. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Ruft alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkMouseOver enthalten. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Entfernt alle enthaltenen HyperlinkClick- und HyperlinkMouseOver-Hyperlinks (in allen IHyperlinkContainer-Teilobjekten). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Ruft alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkClick enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe die IHyperlinkContainer-Schnittstelle.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Ruft alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkMouseOver enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe die IHyperlinkContainer-Schnittstelle.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Ruft alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkMouseOver enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe die IHyperlinkContainer-Schnittstelle.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```


Entfernt alle enthaltenen HyperlinkClick- und HyperlinkMouseOver-Hyperlinks (in allen IHyperlinkContainer-Teilobjekten).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur lesbares IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject