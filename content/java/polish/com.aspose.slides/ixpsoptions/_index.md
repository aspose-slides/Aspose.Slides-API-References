---
title: IXpsOptions
second_title: Dokumentacja API Aspose.Slides dla języka Java
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie XPS.
type: docs
url: /pl/com.aspose.slides/ixpsoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Zapewnia opcje kontrolujące sposób zapisywania prezentacji w formacie XPS.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, aby rysować czarną ramkę wokół każdego slajdu. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, aby rysować czarną ramkę wokół każdego slajdu. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Boolean odczyt/zapis.

--------------------

Domyślnie **true**.

**Zwraca:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Boolean odczyt/zapis.

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

True, aby rysować czarną ramkę wokół każdego slajdu. Boolean odczyt/zapis.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, aby rysować czarną ramkę wokół każdego slajdu. Boolean odczyt/zapis.

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

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |