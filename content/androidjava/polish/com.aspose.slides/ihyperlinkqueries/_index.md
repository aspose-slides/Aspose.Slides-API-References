---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Zapewnia łatwy dostęp do zawartych hiperlinków.
type: docs
url: /pl/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Zapewnia łatwy dostęp do zawartych hiperlinków.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Pobierz wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkClick. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Pobierz wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Pobierz wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Usuwa wszystkie zawarte HyperlinkClick i HyperlinkMouseOver hiperlinki (we wszystkich podobiektach IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Pobierz wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkClick. Mając podany obiekt IHyperlinkContainer, możesz zarządzać jego hiperlinkiem (odczyt, aktualizacja lub usunięcie). Zobacz interfejs IHyperlinkContainer.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Pobierz wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. Mając podany obiekt IHyperlinkContainer, możesz zarządzać jego hiperlinkiem (odczyt, aktualizacja lub usunięcie). Zobacz interfejs IHyperlinkContainer.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Pobierz wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver. Mając podany obiekt IHyperlinkContainer, możesz zarządzać jego hiperlinkiem (odczyt, aktualizacja lub usunięcie). Zobacz interfejs IHyperlinkContainer.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Wszystkie podobiekty IHyperlinkContainer, które zawierają nie null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Usuwa wszystkie zawarte HyperlinkClick i HyperlinkMouseOver hiperlinki (we wszystkich podobiektach IHyperlinkContainer).