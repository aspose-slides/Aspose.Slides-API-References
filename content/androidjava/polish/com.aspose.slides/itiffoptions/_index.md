---
title: ITiffOptions
second_title: Aspose.Slides dla Androida – odniesienie API Javy
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie TIFF.
type: docs
url: /pl/com.aspose.slides/itiffoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie TIFF.
## Metody

| Metoda | Opis |
| --- | --- |
| [getImageSize()](#getImageSize--) | Określa rozmiar wygenerowanego obrazu TIFF. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Określa rozmiar wygenerowanego obrazu TIFF. |
| [getDpiX()](#getDpiX--) | Określa poziomą rozdzielczość w punktach na cal. |
| [setDpiX(long value)](#setDpiX-long-) | Określa poziomą rozdzielczość w punktach na cal. |
| [getDpiY()](#getDpiY--) | Określa pionową rozdzielczość w punktach na cal. |
| [setDpiY(long value)](#setDpiY-long-) | Określa pionową rozdzielczość w punktach na cal. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
| [getCompressionType()](#getCompressionType--) | Określa typ kompresji. |
| [setCompressionType(int value)](#setCompressionType-int-) | Określa typ kompresji. |
| [getPixelFormat()](#getPixelFormat--) | Określa format pikseli dla wygenerowanych obrazów. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Określa format pikseli dla wygenerowanych obrazów. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Określa algorytm konwertowania obrazu kolorowego na czarno-biały. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Określa algorytm konwertowania obrazu kolorowego na czarno-biały. |
| [getInkOptions()](#getInkOptions--) | Udostępnia opcje, które kontrolują wygląd obiektów Ink w wyeksportowanym dokumencie. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Określa rozmiar wygenerowanego obrazu TIFF. Domyślna wartość to 0x0, co oznacza, że rozmiary wygenerowanego obrazu będą obliczane na podstawie rozmiaru slajdu prezentacji. Odczyt/zapis [Size](../../com.aspose.slides.android/size).

**Zwraca:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Określa rozmiar wygenerowanego obrazu TIFF. Domyślna wartość to 0x0, co oznacza, że rozmiary wygenerowanego obrazu będą obliczane na podstawie rozmiaru slajdu prezentacji. Odczyt/zapis [Size](../../com.aspose.slides.android/size).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Określa poziomą rozdzielczość w punktach na cal. Odczyt/zapis long.

**Zwraca:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Określa poziomą rozdzielczość w punktach na cal. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Określa pionową rozdzielczość w punktach na cal. Odczyt/zapis long.

**Zwraca:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Określa pionową rozdzielczość w punktach na cal. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

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

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Określa typ kompresji. Odczyt/zapis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Zwraca:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Określa typ kompresji. Odczyt/zapis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Określa format pikseli dla wygenerowanych obrazów. Odczyt/zapis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Zwraca:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Określa format pikseli dla wygenerowanych obrazów. Odczyt/zapis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Przykład:
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
public abstract int getBwConversionMode()
```

Określa algorytm konwertowania obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko wtedy, gdy CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) jest ustawiony na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) lub [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Odczyt/zapis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Domyślna wartość to [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public abstract void setBwConversionMode(int value)
```

Określa algorytm konwertowania obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko wtedy, gdy CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) jest ustawiony na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) lub [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Odczyt/zapis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Domyślna wartość to [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Udostępnia opcje, które kontrolują wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)