---
title: IHyperlinkQueries
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Removes all contained HyperlinkClick and HyperlinkMouseOver hyperlinks (in all IHyperlinkContainer subobjects). |

### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Rufen Sie alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkClick enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe die IHyperlinkContainer-Schnittstelle.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-Teilobjekte, die nicht null HyperlinkClick enthalten

### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Rufen Sie alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkMouseOver enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe die IHyperlinkContainer-Schnittstelle.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-Teilobjekte, die nicht null HyperlinkMouseOver enthalten

### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Rufen Sie alle IHyperlinkContainer-Teilobjekte ab, die nicht null HyperlinkMouseOver enthalten. Mit dem angegebenen IHyperlinkContainer-Objekt können Sie dessen Hyperlink verwalten (lesen, aktualisieren oder entfernen). Siehe die IHyperlinkContainer-Schnittstelle.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Alle IHyperlinkContainer-Teilobjekte, die nicht null HyperlinkMouseOver enthalten

### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Entfernt alle enthaltenen HyperlinkClick- und HyperlinkMouseOver-Hyperlinks (in allen IHyperlinkContainer-Teilobjekten).