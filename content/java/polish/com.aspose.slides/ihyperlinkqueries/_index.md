---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Umożliwia łatwy dostęp do zawartych hiperłączy.
type: docs
url: /pl/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Umożliwia łatwy dostęp do zawartych hiperłączy.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Pobiera wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Pobiera wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Pobiera wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Usuwa wszystkie zawarte hiperłącza HyperlinkClick i HyperlinkMouseOver (we wszystkich podobiektach IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Pobiera wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkClick. Za pomocą podanego obiektu IHyperlinkContainer możesz zarządzać jego hiperłączem (odczyt, aktualizacja lub usunięcie). Zobacz interfejs IHyperlinkContainer.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Pobiera wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. Za pomocą podanego obiektu IHyperlinkContainer możesz zarządzać jego hiperłączem (odczyt, aktualizacja lub usunięcie). Zobacz interfejs IHyperlinkContainer.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Pobiera wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. Za pomocą podanego obiektu IHyperlinkContainer możesz zarządzać jego hiperłączem (odczyt, aktualizacja lub usunięcie). Zobacz interfejs IHyperlinkContainer.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Usuwa wszystkie zawarte hiperłącza HyperlinkClick i HyperlinkMouseOver (we wszystkich podobiektach IHyperlinkContainer).