---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides dla Java – odniesienie do API
description: Reprezentuje menedżer, który przechowuje zachowanie pól zastępczych stopki, daty i godziny, numeru strony dla wszystkich typów slajdów.
type: docs
url: /pl/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Reprezentuje menedżer, który przechowuje zachowanie pól zastępczych stopki, daty i godziny, numeru strony dla wszystkich typów slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Pobiera wartość wskazującą, że pole zastępcze stopki jest obecne. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Pobiera wartość wskazującą, że pole zastępcze numeru strony jest obecne. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Pobiera wartość wskazującą, że pole zastępcze daty i godziny jest obecne. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Zmienia widoczność pola zastępczego stopki slajdu. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Zmienia widoczność pola zastępczego numeru strony slajdu. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Zmienia widoczność pola zastępczego daty i godziny slajdu. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Ustawia tekst w polu zastępczym stopki slajdu. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Ustawia tekst w polu zastępczym daty i godziny slajdu. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Pobiera wartość wskazującą, że pole zastępcze stopki jest obecne. Odczyt typu bool.

**Zwraca:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Pobiera wartość wskazującą, że pole zastępcze numeru strony jest obecne. Odczyt typu bool.

**Zwraca:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Pobiera wartość wskazującą, że pole zastępcze daty i godziny jest obecne. Odczyt typu bool.

**Zwraca:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Zmienia widoczność pola zastępczego stopki slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pole zastępcze stopki jest widoczne, w przeciwnym razie - ukrywa je. |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Zmienia widoczność pola zastępczego numeru strony slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pole zastępcze numeru strony jest widoczne, w przeciwnym razie - ukrywa je. |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Zmienia widoczność pola zastępczego daty i godziny slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pole zastępcze daty i godziny jest widoczne, w przeciwnym razie - ukrywa je. |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Ustawia tekst w polu zastępczym stopki slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Ustawia tekst w polu zastępczym daty i godziny slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |