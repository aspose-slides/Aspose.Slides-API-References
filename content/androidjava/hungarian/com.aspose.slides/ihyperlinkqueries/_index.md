---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Könnyű hozzáférést biztosít a beágyazott hiperhivatkozásokhoz.
type: docs
url: /hu/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Könnyű hozzáférést biztosít a beágyazott hiperhivatkozásokhoz.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Az összes IHyperlinkContainer alobjektum, amely nem null HyperlinkClick-et tartalmaz. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Az összes IHyperlinkContainer alobjektum, amely nem null HyperlinkMouseOver-et tartalmaz. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Az összes IHyperlinkContainer alobjektum, amely nem null HyperlinkMouseOver-et tartalmaz. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Eltávolítja az összes beágyazott HyperlinkClick és HyperlinkMouseOver hiperhivatkozást (az összes IHyperlinkContainer alobjektumban). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Az összes IHyperlinkContainer alobjektum lekérése, amely nem null HyperlinkClick-et tartalmaz. A megadott IHyperlinkContainer objektummal kezelheti annak hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Az összes IHyperlinkContainer alobjektum, amely nem null HyperlinkClick-et tartalmaz
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Az összes IHyperlinkContainer alobjektum lekérése, amely nem null HyperlinkMouseOver-et tartalmaz. A megadott IHyperlinkContainer objektummal kezelheti annak hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Az összes IHyperlinkContainer alobjektum, amely nem null HyperlinkMouseOver-et tartalmaz
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Az összes IHyperlinkContainer alobjektum lekérése, amely nem null HyperlinkMouseOver-et tartalmaz. A megadott IHyperlinkContainer objektummal kezelheti annak hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Az összes IHyperlinkContainer alobjektum, amely nem null HyperlinkMouseOver-et tartalmaz
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Eltávolítja az összes beágyazott HyperlinkClick és HyperlinkMouseOver hiperhivatkozást (az összes IHyperlinkContainer alobjektumban).