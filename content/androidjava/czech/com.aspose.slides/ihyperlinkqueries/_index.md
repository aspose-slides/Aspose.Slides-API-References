---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Poskytuje snadný přístup k obsaženým hyperodkazům.
type: docs
url: /cs/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Poskytuje snadný přístup k obsaženým hyperodkazům.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Získá všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Získá všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Získá všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Odstraní všechny obsažené odkazy HyperlinkClick a HyperlinkMouseOver (ve všech podobjektech IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Získá všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkClick. S daným objektem IHyperlinkContainer můžete spravovat jeho hyperodkaz (číst, aktualizovat nebo odstranit). Viz rozhraní IHyperlinkContainer.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Získá všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkMouseOver. S daným objektem IHyperlinkContainer můžete spravovat jeho hyperodkaz (číst, aktualizovat nebo odstranit). Viz rozhraní IHyperlinkContainer.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Získá všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkMouseOver. S daným objektem IHyperlinkContainer můžete spravovat jeho hyperodkaz (číst, aktualizovat nebo odstranit). Viz rozhraní IHyperlinkContainer.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Všechny podobjekty IHyperlinkContainer, které obsahují nenulový HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Odstraní všechny obsažené odkazy HyperlinkClick a HyperlinkMouseOver (ve všech podobjektech IHyperlinkContainer).