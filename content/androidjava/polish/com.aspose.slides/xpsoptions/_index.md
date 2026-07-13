---
title: XpsOptions
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie XPS.
type: docs
url: /pl/com.aspose.slides/xpsoptions/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**  
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)  
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Utwórz obiekt Presentation reprezentujący plik prezentacji
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Zapisywanie prezentacji do dokumentu XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Utwórz obiekt Presentation reprezentujący plik prezentacji
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Utwórz obiekt klasy TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Zapisz metafile jako PNG
>      options.setSaveMetafilesAsPng(true);
>      // Zapisywanie prezentacji do dokumentu XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| Konstruktor | Opis |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Domyślny konstruktor. |
## Methods

| Metoda | Opis |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, aby narysować czarną ramkę wokół każdego slajdu. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, aby narysować czarną ramkę wokół każdego slajdu. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Domyślny konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie **false**.

**Zwraca:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie **false**.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Boolean odczyt/zapis.

--------------------

Domyślnie **true**.

**Zwraca:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Boolean odczyt/zapis.

--------------------

Domyślnie **true**.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True, aby narysować czarną ramkę wokół każdego slajdu. Boolean odczyt/zapis.

--------------------

Domyślnie **false**.

**Zwraca:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True, aby narysować czarną ramkę wokół każdego slajdu. Boolean odczyt/zapis.

--------------------

Domyślnie **false**.

**Parametry:**  
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |