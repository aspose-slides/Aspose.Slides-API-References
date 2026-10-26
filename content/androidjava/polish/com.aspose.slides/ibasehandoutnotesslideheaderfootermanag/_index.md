---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides dla Androida – odniesienie do Java API
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

Oryginalna nazwa interfejsu "IBaseHandoutNotesSlideHeaderFooterManager" została skrócona do "IBaseHandoutNotesSlideHeaderFooterManag" dla zgodności z COM (długość nazwy typu nie może przekraczać 39 znaków).
## Metody

| Metoda | Opis |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Zwraca wartość wskazującą, że placeholder nagłówka jest obecny. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Zmienia widoczność placeholdera nagłówka slajdu. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Ustawia tekst w placeholderze nagłówka slajdu. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Zwraca wartość wskazującą, że placeholder nagłówka jest obecny. Odczyt boolean.

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
| isVisible | boolean | true - sprawia, że placeholder nagłówka jest widoczny, w przeciwnym razie - ukrywa go. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Ustawia tekst w placeholderze nagłówka slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |