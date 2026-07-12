---
title: HyperlinkQueries
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.
type: docs
url: /hu/com.aspose.slides/hyperlinkqueries/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries), com.aspose.slides.IDOMObject
```
public final class HyperlinkQueries implements IHyperlinkQueries, IDOMObject
```

Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Az összes IHyperlinkContainer alobjektumot lekéri, amelyek nem null HyperlinkClick-et tartalmaznak. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Az összes IHyperlinkContainer alobjektumot lekéri, amelyek nem null HyperlinkMouseOver-t tartalmaznak. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Az összes IHyperlinkContainer alobjektumot lekéri, amelyek nem null HyperlinkMouseOver-t tartalmaznak. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Eltávolítja az összes tárolt HyperlinkClick és HyperlinkMouseOver hiperhivatkozást (az összes IHyperlinkContainer alobjektumban). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Az összes IHyperlinkContainer alobjektumot lekéri, amelyek nem null HyperlinkClick-et tartalmaznak. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Az összes IHyperlinkContainer alobjektumot lekéri, amelyek nem null HyperlinkMouseOver-t tartalmaznak. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Az összes IHyperlinkContainer alobjektumot lekéri, amelyek nem null HyperlinkMouseOver-t tartalmaznak. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

Eltávolítja az összes tárolt HyperlinkClick és HyperlinkMouseOver hiperhivatkozást (az összes IHyperlinkContainer alobjektumban).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject