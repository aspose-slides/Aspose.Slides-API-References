---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Egyszerű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.
type: docs
url: /hu/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Egyszerű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Removes all contained HyperlinkClick and HyperlinkMouseOver hyperlinks (in all IHyperlinkContainer subobjects). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Az összes IHyperlinkContainer alobjektum lekérdezése, amelyik nem null HyperlinkClick-et tartalmaz. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszaadja:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Minden IHyperlinkContainer alobjektum, amelyik nem null HyperlinkClick-et tartalmaz
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Az összes IHyperlinkContainer alobjektum lekérdezése, amelyik nem null HyperlinkMouseOver-t tartalmaz. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszaadja:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Minden IHyperlinkContainer alobjektum, amelyik nem null HyperlinkMouseOver-t tartalmaz
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Az összes IHyperlinkContainer alobjektum lekérdezése, amelyik nem null HyperlinkMouseOver-t tartalmaz. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszaadja:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Minden IHyperlinkContainer alobjektum, amelyik nem null HyperlinkMouseOver-t tartalmaz
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Az összes beágyazott HyperlinkClick és HyperlinkMouseOver hiperhivatkozás eltávolítása (az összes IHyperlinkContainer alobjektumban).