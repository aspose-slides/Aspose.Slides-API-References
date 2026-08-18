---
title: SVGOptions
second_title: Aspose.Slides for Java – referencja API
description: Reprezentuje opcje SVG.
type: docs
url: /pl/com.aspose.slides/svgoptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Reprezentuje opcje SVG.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inicjalizuje nową instancję klasy SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inicjalizuje nową instancję klasy SVGOptions, określając obiekt kontrolera osadzania linków. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getUseFrameSize()](#getUseFrameSize--) | Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Określa, czy wykonać określony obrót kształtu podczas renderowania, czy nie. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Określa, czy wykonać określony obrót kształtu podczas renderowania, czy nie. |
| [getVectorizeText()](#getVectorizeText--) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. |
| [getDisable3DText()](#getDisable3DText--) | Określa, czy tekst 3D jest wyłączony w SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Określa, czy tekst 3D jest wyłączony w SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Wyłącza podział gradientów FromCornerX i FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Wyłącza podział gradientów FromCornerX i FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. |
| [getDefault()](#getDefault--) | Zwraca domyślne ustawienia. |
| [getSimple()](#getSimple--) | Zwraca ustawienia generowania najprostszego i najmniejszego pliku SVG. |
| [getWYSIWYG()](#getWYSIWYG--) | Zwraca ustawienia generowania najbardziej dokładnego pliku SVG. |
| [getJpegQuality()](#getJpegQuality--) | Określa jakość kodowania JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Określa jakość kodowania JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtów. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtów. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje poziom kompresji obrazów |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje poziom kompresji obrazów |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Flaga boolowska wskazuje, czy wycięte części pozostają częścią dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Flaga boolowska wskazuje, czy wycięte części pozostają częścią dokumentu. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Odwołanie do kontrolera osadzania linków. |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. Odczyt/zapis  boolean . Domyślna wartość to false.

**Zwraca:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Określa, czy ramka tekstowa zostanie uwzględniona w obszarze renderowania, czy nie. Odczyt/zapis  boolean . Domyślna wartość to false.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Określa, czy wykonać określony obrót kształtu podczas renderowania, czy nie. Odczyt/zapis  boolean . Domyślna wartość to true.

**Zwraca:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Określa, czy wykonać określony obrót kształtu podczas renderowania, czy nie. Odczyt/zapis  boolean . Domyślna wartość to true.

**Parametry:**
| Parameter | Type | Description |
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

Określa, czy tekst na slajdzie zostanie zapisany jako grafika. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. Odczyt/zapis int.

**Zwraca:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Zwraca lub ustawia dolny limit rozdzielczości rasteryzacji metafile. Odczyt/zapis int.

**Parametry:**
| Parameter | Type | Description |
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

Określa, czy tekst 3D jest wyłączony w SVG. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. Silnik zapisu SVG Aspose.Slides ma obejście tego problemu: przycina koniec linii z strzałką, aby linia nie nachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 nie umożliwia definiowania wcięć dla znaczników. Silnik zapisu SVG Aspose.Slides ma obejście tego problemu: przycina koniec linii z strzałką, aby linia nie nachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Odczyt/zapis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Zwraca domyślne ustawienia. Tylko do odczytu [SVGOptions](../../com.aspose.slides/svgoptions).

**Zwraca:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Zwraca ustawienia generowania najprostszego i najmniejszego pliku SVG. Tylko do odczytu [SVGOptions](../../com.aspose.slides/svgoptions).

**Zwraca:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Zwraca ustawienia generowania najbardziej dokładnego pliku SVG. Tylko do odczytu [SVGOptions](../../com.aspose.slides/svgoptions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtów. Odczyt/zapis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Zwraca:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Zwraca i ustawia interfejs zwrotny, który pozwala użytkownikowi kontrolować konwersję kształtów. Odczyt/zapis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametry:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Flaga boolowska wskazuje, czy wycięte części pozostają częścią dokumentu. Jeśli true, wycięte części zostaną usunięte, jeśli false, zostaną zserializowane w dokumencie (co może prowadzić do większego rozmiaru pliku)

**Zwraca:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Flaga boolowska wskazuje, czy wycięte części pozostają częścią dokumentu. Jeśli true, wycięte części zostaną usunięte, jeśli false, zostaną zserializowane w dokumencie (co może prowadzić do większego rozmiaru pliku)

**Parametry:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość jest ustawiona na false.

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


**Zwraca:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Pobiera lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość jest ustawiona na false.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |