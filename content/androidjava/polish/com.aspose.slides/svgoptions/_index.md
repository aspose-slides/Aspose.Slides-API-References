---
title: SVGOptions
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje opcje SVG.
type: docs
url: /pl/com.aspose.slides/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Reprezentuje opcje SVG.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inicjalizuje nową instancję klasy SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inicjalizuje nową instancję klasy SVGOptions, określając obiekt kontrolera osadzania linków. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Udostępnia opcje, które kontrolują wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getUseFrameSize()](#getUseFrameSize--) | Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Określa, czy przy renderowaniu wykonać określony obrót kształtu, czy nie. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Określa, czy przy renderowaniu wykonać określony obrót kształtu, czy nie. |
| [getVectorizeText()](#getVectorizeText--) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji pliku metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji pliku metafile. |
| [getDisable3DText()](#getDisable3DText--) | Określa, czy tekst 3D jest wyłączony w SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Określa, czy tekst 3D jest wyłączony w SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Wyłącza podział gradientów FromCornerX i FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Wyłącza podział gradientów FromCornerX i FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. |
| [getDefault()](#getDefault--) | Zwraca ustawienia domyślne. |
| [getSimple()](#getSimple--) | Zwraca ustawienia najprostszej i najmniejszej generacji pliku SVG. |
| [getWYSIWYG()](#getWYSIWYG--) | Zwraca ustawienia najbardziej dokładnej generacji pliku SVG. |
| [getJpegQuality()](#getJpegQuality--) | Określa jakość kodowania JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Określa jakość kodowania JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtu. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtu. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje poziom kompresji obrazów |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje poziom kompresji obrazów |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Flaga typu boolean wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Flaga typu boolean wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Określa sposób obsługi zewnętrznie ładowanych czcionek. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Określa sposób obsługi zewnętrznie ładowanych czcionek. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Inicjalizuje nową instancję klasy SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Inicjalizuje nową instancję klasy SVGOptions, określając obiekt kontrolera osadzania linków.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Odwołanie do kontrolera osadzania linków. |

Link embedding controller jest obiektem delegowanym, odpowiedzialnym za podejmowanie decyzji, czy zasoby (takie jak obrazy) muszą być osadzone, czy odwoływać się do nich jako zasobów zewnętrznych.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Udostępnia opcje, które kontrolują wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. Odczyt/zapis boolean. Domyślna wartość to false.

**Zwraca:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Ustawia, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. Odczyt/zapis boolean. Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Określa, czy przy renderowaniu wykonać określony obrót kształtu, czy nie. Odczyt/zapis boolean. Domyślna wartość to true.

**Zwraca:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Ustawia, czy przy renderowaniu wykonać określony obrót kształtu, czy nie. Odczyt/zapis boolean. Domyślna wartość to true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Określa, czy tekst na slajdzie zostanie zapisany jako grafika. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Ustawia, czy tekst na slajdzie zostanie zapisany jako grafika. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji pliku metafile. Odczyt/zapis int.

**Zwraca:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji pliku metafile. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Określa, czy tekst 3D jest wyłączony w SVG. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Ustawia, czy tekst 3D jest wyłączony w SVG. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Wyłącza podział gradientów FromCornerX i FromCenter. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Wyłącza podział gradientów FromCornerX i FromCenter. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. Silnik zapisu SVG w Aspose.Slides ma obejście tego problemu: przycina koniec linii z strzałką, tak aby linia nie nachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. Silnik zapisu SVG w Aspose.Slides ma obejście tego problemu: przycina koniec linii z strzałką, tak aby linia nie nachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Zwraca ustawienia domyślne. Tylko do odczytu [SVGOptions](../../com.aspose.slides/svgoptions).

**Zwraca:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Zwraca ustawienia najprostszej i najmniejszej generacji pliku SVG. Tylko do odczytu [SVGOptions](../../com.aspose.slides/svgoptions).

**Zwraca:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Zwraca ustawienia najbardziej dokładnej generacji pliku SVG. Tylko do odczytu [SVGOptions](../../com.aspose.slides/svgoptions).

**Zwraca:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Określa jakość kodowania JPEG. Odczyt/zapis int.

**Zwraca:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Określa jakość kodowania JPEG. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtu. Odczyt/zapis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Zwraca:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtu. Odczyt/zapis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Reprezentuje poziom kompresji obrazów

**Zwraca:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Reprezentuje poziom kompresji obrazów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Flaga typu boolean wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte, jeśli false, będą serializowane w dokumencie (co może prowadzić do większego pliku).

**Zwraca:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Flaga typu boolean wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte, jeśli false, będą serializowane w dokumencie (co może prowadzić do większego pliku).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Określa sposób obsługi zewnętrznie ładowanych czcionek. Odczyt/zapis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Zwraca:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Określa sposób obsługi zewnętrznie ładowanych czcionek. Odczyt/zapis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie właściwość ma wartość false.

**Zwraca:**
boolean
> ```
> Przykład:
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


### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie właściwość ma wartość false.

> ```
> Przykład:
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