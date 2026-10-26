---
title: TiffOptions
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Umożliwia ustawienie opcji kontrolujących sposób zapisywania prezentacji w formacie TIFF.
type: docs
url: /pl/com.aspose.slides/tiffoptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Umożliwia ustawienie opcji kontrolujących sposób zapisywania prezentacji w formacie TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Zapisywanie prezentacji do dokumentu TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Utwórz instancję klasy TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Ustawianie typu kompresji
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Typy kompresji
>      // Domyślny - Określa domyślny schemat kompresji (LZW).
>      // Brak - Określa brak kompresji.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Głębokość zależy od typu kompresji i nie może być ustawiona ręcznie.
>      // Jednostka rozdzielczości jest zawsze równa 2 (punkty na cal)
>      // Ustawianie DPI obrazu
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Ustaw rozmiar obrazu
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Zapisz prezentację do TIFF z określonym rozmiarem obrazu
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat zawiera następujące wartości (jak można zobaczyć w dokumentacji):
>      //Format1bppIndexed; // 1 bit na piksel, indeksowany.
>      //Format4bppIndexed; // 4 bity na piksel, indeksowany.
>      //Format8bppIndexed; // 8 bitów na piksel, indeksowany.
>      //Format24bppRgb; // 24 bity na piksel, RGB.
>      //Format32bppArgb; // 32 bity na piksel, ARGB.
> 
>      // Zapisz prezentację do TIFF z określonym rozmiarem obrazu
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Konstruktor domyślny. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Umożliwia ustawienie opcji kontrolujących wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [getImageSize()](#getImageSize--) | Określa rozmiar wygenerowanego obrazu TIFF. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Określa rozmiar wygenerowanego obrazu TIFF. |
| [getDpiX()](#getDpiX--) | Określa poziomą rozdzielczość w punktach na cal. |
| [setDpiX(long value)](#setDpiX-long-) | Określa poziomą rozdzielczość w punktach na cal. |
| [getDpiY()](#getDpiY--) | Określa pionową rozdzielczość w punktach na cal. |
| [setDpiY(long value)](#setDpiY-long-) | Określa pionową rozdzielczość w punktach na cal. |
| [getCompressionType()](#getCompressionType--) | Określa typ kompresji. |
| [setCompressionType(int value)](#setCompressionType-int-) | Określa typ kompresji. |
| [getPixelFormat()](#getPixelFormat--) | Określa format pikseli dla wygenerowanych obrazów. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Określa format pikseli dla wygenerowanych obrazów. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Określa algorytm konwersji obrazu kolorowego na czarno-biały. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Określa algorytm konwersji obrazu kolorowego na czarno-biały. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Konstruktor domyślny.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Umożliwia ustawienie opcji kontrolujących wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

Określa rozmiar wygenerowanego obrazu TIFF. Domyślna wartość to 0x0, co oznacza, że rozmiary wygenerowanych obrazów będą obliczane na podstawie wartości rozmiaru slajdu prezentacji. Odczyt/zapis [Size](../../com.aspose.slides.android/size).

**Zwraca:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

Określa rozmiar wygenerowanego obrazu TIFF. Domyślna wartość to 0x0, co oznacza, że rozmiary wygenerowanych obrazów będą obliczane na podstawie wartości rozmiaru slajdu prezentacji. Odczyt/zapis [Size](../../com.aspose.slides.android/size).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Określa poziomą rozdzielczość w punktach na cal. Odczyt/zapis long.

**Zwraca:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Określa poziomą rozdzielczość w punktach na cal. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Określa pionową rozdzielczość w punktach na cal. Odczyt/zapis long.

**Zwraca:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Określa pionową rozdzielczość w punktach na cal. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Określa typ kompresji. Odczyt/zapis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Zwraca:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Określa typ kompresji. Odczyt/zapis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Określa format pikseli dla wygenerowanych obrazów. Odczyt/zapis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Zwraca:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Określa format pikseli dla wygenerowanych obrazów. Odczyt/zapis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Określa algorytm konwersji obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko wtedy, gdy CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) jest ustawiony na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) lub [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Odczyt/zapis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Domyślnie [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Zwraca:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

Określa algorytm konwersji obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko wtedy, gdy CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) jest ustawiony na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) lub [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Odczyt/zapis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Domyślnie [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |