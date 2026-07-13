---
title: IXpsOptions
second_title: Aspose.Slides dla Androida - referencja API Java
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie XPS.
type: docs
url: /pl/com.aspose.slides/ixpsoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Umożliwia opcje sterujące sposobem zapisywania prezentacji w formacie XPS.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Ustawienie true powoduje konwersję wszystkich metafile używanych w prezentacji na obrazy PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Ustawienie true powoduje konwersję wszystkich metafile używanych w prezentacji na obrazy PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Ustawienie true powoduje rysowanie czarnej ramki wokół każdego slajdu. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Ustawienie true powoduje rysowanie czarnej ramki wokół każdego slajdu. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


Ustawienie true powoduje konwersję wszystkich metafile używanych w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślnie **true**.

**Zwraca:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


Ustawienie true powoduje konwersję wszystkich metafile używanych w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślnie **true**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


Ustawienie true powoduje rysowanie czarnej ramki wokół każdego slajdu. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


Ustawienie true powoduje rysowanie czarnej ramki wokół każdego slajdu. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |