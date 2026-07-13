---
title: ISVGOptions
second_title: Aspose.Slides dla Androida - odwołanie API Java
description: Reprezentuje opcje SVG.
type: docs
url: /pl/com.aspose.slides/isvgoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Reprezentuje opcje SVG.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. |
| [getDisable3DText()](#getDisable3DText--) | Określa, czy tekst 3D jest wyłączony w SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Określa, czy tekst 3D jest wyłączony w SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Wyłącza dzielenie gradientów FromCornerX i FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Wyłącza dzielenie gradientów FromCornerX i FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. |
| [getJpegQuality()](#getJpegQuality--) | Określa jakość kodowania JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Określa jakość kodowania JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Zwraca i ustawia interfejs wywołania zwrotnego, który pozwala użytkownikowi kontrolować konwersję kształtów. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Zwraca i ustawia interfejs wywołania zwrotnego, który pozwala użytkownikowi kontrolować konwersję kształtów. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje poziom kompresji obrazów Odczyt/zapis #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje poziom kompresji obrazów Odczyt/zapis #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Flaga boolean wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Flaga boolean wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [getUseFrameSize()](#getUseFrameSize--) | Określa, czy ramka tekstowa zostanie włączona do obszaru renderowania. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Określa, czy ramka tekstowa zostanie włączona do obszaru renderowania. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Określa, czy wykonać określony obrót kształtu podczas renderowania. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Określa, czy wykonać określony obrót kształtu podczas renderowania. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Określa sposób obsługi zewnętrznie ładowanych czcionek. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Określa sposób obsługi zewnętrznie ładowanych czcionek. |
| [getInkOptions()](#getInkOptions--) | Zapewnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Określa, czy tekst na slajdzie zostanie zapisany jako grafika. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Określa, czy tekst na slajdzie zostanie zapisany jako grafika. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. Odczyt/zapis int.

**Zwraca:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Określa, czy tekst 3D jest wyłączony w SVG. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Określa, czy tekst 3D jest wyłączony w SVG. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Wyłącza dzielenie gradientów FromCornerX i FromCenter. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Wyłącza dzielenie gradientów FromCornerX i FromCenter. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. Silnik zapisu SVG w Aspose.Slides ma obejście tego problemu: przycina koniec linii z strzałką, tak aby linia nie zachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. Silnik zapisu SVG w Aspose.Slides ma obejście tego problemu: przycina koniec linii z strzałką, tak aby linia nie zachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Określa jakość kodowania JPEG. Odczyt/zapis int.

**Zwraca:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Określa jakość kodowania JPEG. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Zwraca i ustawia interfejs wywołania zwrotnego, który pozwala użytkownikowi kontrolować konwersję kształtów. Odczyt/zapis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Zwraca:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Zwraca i ustawia interfejs wywołania zwrotnego, który pozwala użytkownikowi kontrolować konwersję kształtów. Odczyt/zapis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Reprezentuje poziom kompresji obrazów Odczyt/zapis #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Zwraca:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Reprezentuje poziom kompresji obrazów Odczyt/zapis #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Flaga boolean wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte; jeśli false, będą serializowane w dokumencie (co może prowadzić do większego pliku). Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Flaga boolean wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte; jeśli false, będą serializowane w dokumencie (co może prowadzić do większego pliku). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Określa, czy ramka tekstowa zostanie włączona do obszaru renderowania. Odczyt/zapis boolean. Domyślna wartość to false.

**Zwraca:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Określa, czy ramka tekstowa zostanie włączona do obszaru renderowania. Odczyt/zapis boolean. Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Określa, czy wykonać określony obrót kształtu podczas renderowania. Odczyt/zapis boolean. Domyślna wartość to true.

**Zwraca:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Określa, czy wykonać określony obrót kształtu podczas renderowania. Odczyt/zapis boolean. Domyślna wartość to true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Określa sposób obsługi zewnętrznie ładowanych czcionek. Odczyt/zapis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Zwraca:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Określa sposób obsługi zewnętrznie ładowanych czcionek. Odczyt/zapis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Zapewnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyniku. Domyślnie ta właściwość jest ustawiona na false.

--------------------

> ```markdown
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyniku. Domyślnie ta właściwość jest ustawiona na false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |