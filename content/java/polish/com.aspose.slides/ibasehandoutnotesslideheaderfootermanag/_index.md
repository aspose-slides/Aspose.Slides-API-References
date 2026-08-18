---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje menedżera, który przechowuje zachowanie placeholderów, w tym placeholder nagłówka dla wszystkich typów slajdów rozdania i notatek.
type: docs
url: /pl/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Reprezentuje menedżera, który przechowuje zachowanie placeholderów, w tym placeholder nagłówka dla wszystkich typów slajdów rozdania i notatek.

--------------------

Oryginalna nazwa interfejsu "IBaseHandoutNotesSlideHeaderFooterManager" jest obcięta do "IBaseHandoutNotesSlideHeaderFooterManag" w celu zgodności z COM (długość nazwy typu nie może przekraczać 39 znaków).
## Metody

| Metoda | Opis |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Pobiera wartość wskazującą, że placeholder nagłówka jest obecny. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Zmienia widoczność placeholdera nagłówka slajdu. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Ustawia tekst w placeholderze nagłówka slajdu. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Pobiera wartość wskazującą, że placeholder nagłówka jest obecny. Odczytuje wartość boolowską.

**Zwraca:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Zmienia widoczność placeholdera nagłówka slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że placeholder nagłówka jest widoczny, w przeciwnym razie - ukrywa go. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Ustawia tekst w placeholderze nagłówka slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |