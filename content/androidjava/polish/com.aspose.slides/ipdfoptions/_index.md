---
title: IPdfOptions
second_title: Aspose.Slides dla Androida za pośrednictwem odwołania API Javy
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie PDF.
type: docs
url: /pl/com.aspose.slides/ipdfoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Zapewnia opcje kontrolujące sposób zapisywania prezentacji w formacie PDF.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Określa typ kompresji, który ma być używany dla całej treści tekstowej w dokumencie. |
| [setTextCompression(int value)](#setTextCompression-int-) | Określa typ kompresji, który ma być używany dla całej treści tekstowej w dokumencie. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True, aby osadzić czcionki True Type dla znaków ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True, aby osadzić czcionki True Type dla znaków ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. |
| [getJpegQuality()](#getJpegQuality--) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [getCompliance()](#getCompliance--) | Pożądany poziom zgodności dla wygenerowanego dokumentu PDF. |
| [setCompliance(int value)](#setCompliance-int-) | Pożądany poziom zgodności dla wygenerowanego dokumentu PDF. |
| [getPassword()](#getPassword--) | Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument jest otwierany z dostępem użytkownika. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument jest otwierany z dostępem użytkownika. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, aby narysować czarną ramkę wokół każdego slajdu. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, aby narysować czarną ramkę wokół każdego slajdu. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Stosuje określony przezroczysty kolor do obrazu, jeśli true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Stosuje określony przezroczysty kolor do obrazu, jeśli true. |
| [getInkOptions()](#getInkOptions--) | Zapewnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getIncludeOleData()](#getIncludeOleData--) | True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Określa typ kompresji używany dla całej treści tekstowej w dokumencie. Odczyt/zapis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Domyślna wartość to [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Zwraca:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Określa typ kompresji używany dla całej treści tekstowej w dokumencie. Odczyt/zapis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Domyślna wartość to [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. Jeśli ustawione na true, dla każdego obrazu w prezentacji zostanie wybrany najbardziej odpowiedni algorytm kompresji, co spowoduje mniejszy rozmiar wynikowego dokumentu PDF.

--------------------

Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej ilości pamięci RAM, a ta opcja jest domyślnie ustawiona na false.

--------------------

Domyślna wartość to false.

**Zwraca:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. Jeśli ustawione na true, dla każdego obrazu w prezentacji zostanie wybrany najbardziej odpowiedni algorytm kompresji, co spowoduje mniejszy rozmiar wynikowego dokumentu PDF.

--------------------

Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej ilości pamięci RAM, a ta opcja jest domyślnie ustawiona na false.

--------------------

Domyślna wartość to false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True, aby osadzić czcionki True Type dla znaków ASCII 32-127. Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **true**.

**Zwraca:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True, aby osadzić czcionki True Type dla znaków ASCII 32-127. Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **true**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie jest false.

**Zwraca:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie jest false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. Odczyt/zapis String[].

**Zwraca:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. Odczyt/zapis String[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **false**.

**Zwraca:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. To podejście może poprawić jakość tekstu w wynikowym PDF dla niektórych czcionek. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **false**.

**Zwraca:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. To podejście może poprawić jakość tekstu w wynikowym PDF dla niektórych czcionek. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------

Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby odczytać lub ustawić jakość obrazów w dokumencie podczas zapisywania w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **100**.

**Zwraca:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------

Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby odczytać lub ustawić jakość obrazów w dokumencie podczas zapisywania w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **100**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Pożądany poziom zgodności dla wygenerowanego dokumentu PDF. Odczyt/zapis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Domyślna wartość to [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Zwraca:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Pożądany poziom zgodności dla wygenerowanego dokumentu PDF. Odczyt/zapis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Domyślna wartość to [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Zawiera zestaw flag określających, które uprawnienia dostępu powinny zostać przyznane, gdy dokument jest otwierany z dostępem użytkownika. Zobacz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Zawiera zestaw flag określających, które uprawnienia dostępu powinny zostać przyznane, gdy dokument jest otwierany z dostępem użytkownika. Zobacz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **true**. Dokument PDF może zawierać grafikę wektorową i obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, źródłowy obraz Metafile jest konwertowany do formatu PNG i zapisywany w PDF jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, źródłowy Metafile jest konwertowany do grafiki wektorowej PDF. Każde podejście ma swoje zalety i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, może dojść do utraty jakości podczas skalowania wynikowego dokumentu. Jeśli Metafile jest konwertowany do grafiki wektorowej PDF, mogą wystąpić problemy z wydajnością w narzędziu do przeglądania PDF.

**Zwraca:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **true**. Dokument PDF może zawierać grafikę wektorową i obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, źródłowy obraz Metafile jest konwertowany do formatu PNG i zapisywany w PDF jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, źródłowy Metafile jest konwertowany do grafiki wektorowej PDF. Każde podejście ma swoje zalety i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, może dojść do utraty jakości podczas skalowania wynikowego dokumentu. Jeśli Metafile jest konwertowany do grafiki wektorowej PDF, mogą wystąpić problemy z wydajnością w narzędziu do przeglądania PDF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. Odczyt/zapis float.

Wartość: Efekt tego parametru zależy od kilku czynników. Algorytm stara się uzyskać najlepszy rozmiar wyjściowego obrazu zgodnie z wartością właściwości, rozmiarem obrazu źródłowego i rozmiarem ramki obrazu. Użycie podobnych wartości właściwości może dawać ten sam rezultat. Zaleca się użycie kroku 16 lub 32, aby uzyskać widoczny efekt.

--------------------

Właściwość wpływa na rozmiar pliku, czas eksportu i jakość obrazu.

Domyślna wartość to **96**.

**Zwraca:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. Odczyt/zapis float.

Wartość: Efekt tego parametru zależy od kilku czynników. Algorytm stara się uzyskać najlepszy rozmiar wyjściowego obrazu zgodnie z wartością właściwości, rozmiarem obrazu źródłowego i rozmiarem ramki obrazu. Użycie podobnych wartości właściwości może dawać ten sam rezultat. Zaleca się użycie kroku 16 lub 32, aby uzyskać widoczny efekt.

--------------------

Właściwość wpływa na rozmiar pliku, czas eksportu i jakość obrazu.

Domyślna wartość to **96**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, aby narysować czarną ramkę wokół każdego slajdu. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **false**.

**Zwraca:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, aby narysować czarną ramkę wokół każdego slajdu. Odczyt/zapis boolean.

--------------------

Domyślna wartość to **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

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
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Pobiera lub ustawia przezroczysty kolor obrazu.

Wartość: Kolor przezroczystości obrazu.

**Zwraca:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Pobiera lub ustawia przezroczysty kolor obrazu.

Wartość: Kolor przezroczystości obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Stosuje określony przezroczysty kolor do obrazu, jeśli true.

**Zwraca:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Stosuje określony przezroczysty kolor do obrazu, jeśli true.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Zapewnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Odczyt/zapis boolean.

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Domyślna wartość to **false**.

**Zwraca:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Odczyt/zapis boolean.

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Domyślna wartość to **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |