---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides dla Androida poprzez Odniesienie API Java
description: Reprezentuje menedżera, który zarządza zachowaniem zastępczych elementów stopki, daty i godziny oraz numeru strony we wszystkich typach slajdów.
type: docs
url: /pl/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Reprezentuje menedżera, który zarządza zachowaniem zastępczych elementów stopki, daty i godziny oraz numeru strony we wszystkich typach slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Pobiera wartość wskazującą, że zastępczy element stopki jest obecny. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Pobiera wartość wskazującą, że zastępczy element numeru strony jest obecny. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Pobiera wartość wskazującą, że zastępczy element daty i godziny jest obecny. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Zmienia widoczność zastępczego elementu stopki slajdu. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Zmienia widoczność zastępczego elementu numeru strony slajdu. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Zmienia widoczność zastępczego elementu daty i godziny slajdu. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Ustawia tekst w zastępczym elemencie stopki slajdu. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Ustawia tekst w zastępczym elemencie daty i godziny slajdu. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Pobiera wartość wskazującą, że zastępczy element stopki jest obecny. Odczytuje boolean.

**Zwraca:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Pobiera wartość wskazującą, że zastępczy element numeru strony jest obecny. Odczytuje boolean.

**Zwraca:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Pobiera wartość wskazującą, że zastępczy element daty i godziny jest obecny. Odczytuje boolean.

**Zwraca:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Zmienia widoczność zastępczego elementu stopki slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że zastępczy element stopki jest widoczny, w przeciwnym razie - ukrywa go. |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Zmienia widoczność zastępczego elementu numeru strony slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że zastępczy element numeru strony jest widoczny, w przeciwnym razie - ukrywa go. |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Zmienia widoczność zastępczego elementu daty i godziny slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że zastępczy element daty i godziny jest widoczny, w przeciwnym razie - ukrywa go. |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Ustawia tekst w zastępczym elemencie stopki slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Ustawia tekst w zastępczym elemencie daty i godziny slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |