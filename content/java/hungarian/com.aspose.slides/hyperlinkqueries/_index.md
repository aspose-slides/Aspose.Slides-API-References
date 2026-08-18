---
title: HyperlinkQueries
second_title: Aspose.Slides Java API referencia
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
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Az összes IHyperlinkContainer alobjektumot kapja, amelyek nem null HyperlinkClick-et tartalmaznak. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Az összes IHyperlinkContainer alobjektumot kapja, amelyek nem null HyperlinkMouseOver-ot tartalmaznak. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Az összes IHyperlinkContainer alobjektumot kapja, amelyek nem null HyperlinkMouseOver-ot tartalmaznak. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Eltávolítja az összes tartalmazott HyperlinkClick és HyperlinkMouseOver hiperhivatkozást (az összes IHyperlinkContainer alobjektumban). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Az összes IHyperlinkContainer alobjektumot kapja, amelyek nem null HyperlinkClick-et tartalmaznak. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Az összes IHyperlinkContainer alobjektumot kapja, amelyek nem null HyperlinkMouseOver-ot tartalmaznak. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public final System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Az összes IHyperlinkContainer alobjektumot kapja, amelyek nem null HyperlinkMouseOver-ot tartalmaznak. A megadott IHyperlinkContainer objektummal kezelheti a hiperhivatkozását (olvasás, frissítés vagy eltávolítás). Lásd az IHyperlinkContainer interfészt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer>
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public final void removeAllHyperlinks()
```

Eltávolítja az összes tartalmazott HyperlinkClick és HyperlinkMouseOver hiperhivatkozást (az összes IHyperlinkContainer alobjektumban).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Írásvédett IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject