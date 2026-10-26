---
title: PdfOptions
second_title: Aspose.Slides dla Java – Referencja API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie PDF.
type: docs
url: /pl/com.aspose.slides/pdfoptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie PDF.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Tworzy instancję klasy PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ustawia jakość JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // Ustawia zachowanie dla metafili
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Ustawia poziom kompresji tekstu
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Definiuje standard PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Zapisuje prezentację jako PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Tworzy instancję klasy Presentation reprezentującej plik PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Tworzy instancję klasy PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Dodaje ukryte slajdy
>      pdfOptions.setShowHiddenSlides(true);
>      // Zapisuje prezentację jako PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Tworzy instancję obiektu Presentation reprezentującego plik PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Tworzy instancję klasy PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ustawia hasło PDF oraz uprawnienia dostępu
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Zapisuje prezentację jako PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Tworzy instancję obiektu Presentation reprezentującego plik prezentacji
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Ustawianie typu i rozmiaru slajdu
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Domyślny konstruktor. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [getTextCompression()](#getTextCompression--) | Określa typ kompresji używany dla całej treści tekstowej w dokumencie. |
| [setTextCompression(int value)](#setTextCompression-int-) | Określa typ kompresji używany dla całej treści tekstowej w dokumencie. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu powinna być wybierana automatycznie. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu powinna być wybierana automatycznie. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Określa, czy Aspose.Slides osadzi wspólne czcionki dla tekstu ASCII (zakres kodów 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Określa, czy Aspose.Slides osadzi wspólne czcionki dla tekstu ASCII (zakres kodów 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Określa, czy wszystkie znaki czcionki powinny być osadzone, czy tylko użyty podzbiór. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Określa, czy wszystkie znaki czcionki powinny być osadzone, czy tylko użyty podzbiór. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. |
| [getJpegQuality()](#getJpegQuality--) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [getCompliance()](#getCompliance--) | Pożądany poziom zgodności generowanego dokumentu PDF. |
| [setCompliance(int value)](#setCompliance-int-) | Pożądany poziom zgodności generowanego dokumentu PDF. |
| [getPassword()](#getPassword--) | Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Prawda, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Prawda, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Prawda, aby narysować czarną ramkę wokół każdego slajdu. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Prawda, aby narysować czarną ramkę wokół każdego slajdu. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Stosuje określony przezroczysty kolor do obrazu, jeśli wartość jest prawdziwa. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Stosuje określony przezroczysty kolor do obrazu, jeśli wartość jest prawdziwa. |
| [getIncludeOleData()](#getIncludeOleData--) | Prawda, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Prawda, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Domyślny konstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

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

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Określa typ kompresji używany dla całej treści tekstowej w dokumencie. Odczyt/zapis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Domyślnie [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Zwraca:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Określa typ kompresji używany dla całej treści tekstowej w dokumencie. Odczyt/zapis [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Domyślnie [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu powinna być wybierana automatycznie. Jeśli ustawiona na true, dla każdego obrazu w prezentacji zostanie wybrany najbardziej odpowiedni algorytm kompresji, co spowoduje mniejszy rozmiar wynikowego dokumentu PDF.

--------------------

Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej pamięci RAM, a ta opcja domyślnie ma wartość false.

--------------------

Domyślnie false.

**Zwraca:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Wskazuje, czy najskuteczniejsza kompresja (zamiast domyślnej) dla każdego obrazu powinna być wybierana automatycznie. Jeśli ustawiona na true, dla każdego obrazu w prezentacji zostanie wybrany najbardziej odpowiedni algorytm kompresji, co spowoduje mniejszy rozmiar wynikowego dokumentu PDF.

--------------------

Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej pamięci RAM, a ta opcja domyślnie ma wartość false.

--------------------

Domyślnie false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Określa, czy Aspose.Slides osadzi wspólne czcionki dla tekstu ASCII (zakres kodów 33..127). Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Lista wspólnych czcionek obejmuje podstawowe 14 czcionek PDF oraz dodatkowe czcionki określone przez użytkownika. Odczyt/zapis boolean.

--------------------

Domyślnie **true**.

**Zwraca:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Określa, czy Aspose.Slides osadzi wspólne czcionki dla tekstu ASCII (zakres kodów 33..127). Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Lista wspólnych czcionek obejmuje podstawowe 14 czcionek PDF oraz dodatkowe czcionki określone przez użytkownika. Odczyt/zapis boolean.

--------------------

Domyślnie **true**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. Odczyt/zapis String[].

**Zwraca:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za wspólne. Odczyt/zapis String[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Określa, czy wszystkie znaki czcionki powinny być osadzone, czy tylko użyty podzbiór. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Określa, czy wszystkie znaki czcionki powinny być osadzone, czy tylko użyty podzbiór. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. To podejście może poprawić jakość tekstu w wynikowym PDF dla niektórych czcionek. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. To podejście może poprawić jakość tekstu w wynikowym PDF dla niektórych czcionek. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------

Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby uzyskać lub ustawić jakość obrazów w dokumencie przy zapisie w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **100**.

**Zwraca:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------

Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby uzyskać lub ustawić jakość obrazów w dokumencie przy zapisie w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **100**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Pożądany poziom zgodności generowanego dokumentu PDF. Odczyt/zapis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Domyślnie [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Zwraca:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Pożądany poziom zgodności generowanego dokumentu PDF. Odczyt/zapis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Domyślnie [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. Zobacz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final void setAccessPermissions(int value)
```

Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. Zobacz [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final boolean getSaveMetafilesAsPng()
```

Prawda, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślnie **true**. Dokument PDF może zawierać grafikę wektorową i obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, źródłowy obraz Metafile jest konwertowany do formatu PNG i zapisywany w PDF jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, źródłowy Metafile jest konwertowany do grafiki wektorowej PDF. Każde podejście ma zalety i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, może dojść do utraty jakości podczas skalowania wynikowego dokumentu. Jeśli Metafile jest konwertowany do grafiki wektorowej PDF, mogą wystąpić problemy z wydajnością w narzędziu do przeglądania PDF.

**Zwraca:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Prawda, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślnie **true**. Dokument PDF może zawierać grafikę wektorową i obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, źródłowy obraz Metafile jest konwertowany do formatu PNG i zapisywany w PDF jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, źródłowy Metafile jest konwertowany do grafiki wektorowej PDF. Każde podejście ma zalety i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, może dojść do utraty jakości podczas skalowania wynikowego dokumentu. Jeśli Metafile jest konwertowany do grafiki wektorowej PDF, mogą wystąpić problemy z wydajnością w narzędziu do przeglądania PDF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. Odczyt/zapis float.

Wartość: Efekt tego parametru zależy od kilku czynników. Algorytm stara się uzyskać najlepszy rozmiar wyjściowego obrazu zgodnie z wartością właściwości, rozmiarem obrazu źródłowego i rozmiarem ramki obrazu. Użycie podobnych wartości właściwości może dawać ten sam rezultat. Zaleca się używać kroku 16 lub 32, aby uzyskać widoczny efekt.

--------------------

Właściwość wpływa na rozmiar pliku, czas eksportu i jakość obrazu.

Domyślna wartość to **96**.

**Zwraca:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. Odczyt/zapis float.

Wartość: Efekt tego parametru zależy od kilku czynników. Algorytm stara się uzyskać najlepszy rozmiar wyjściowego obrazu zgodnie z wartością właściwości, rozmiarem obrazu źródłowego i rozmiarem ramki obrazu. Użycie podobnych wartości właściwości może dawać ten sam rezultat. Zaleca się używać kroku 16 lub 32, aby uzyskać widoczny efekt.

--------------------

Właściwość wpływa na rozmiar pliku, czas eksportu i jakość obrazu.

Domyślna wartość to **96**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Prawda, aby narysować czarną ramkę wokół każdego slajdu. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Prawda, aby narysować czarną ramkę wokół każdego slajdu. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Pobiera lub ustawia przezroczysty kolor obrazu.

Wartość: Kolor przezroczysty obrazu.

**Zwraca:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Pobiera lub ustawia przezroczysty kolor obrazu.

Wartość: Kolor przezroczysty obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Stosuje określony przezroczysty kolor do obrazu, jeśli wartość jest prawdziwa.

**Zwraca:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Stosuje określony przezroczysty kolor do obrazu, jeśli wartość jest prawdziwa.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Prawda, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. Odczyt/zapis boolean.

--------------------

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

Domyślnie **false**.

**Zwraca:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Prawda, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. Odczyt/zapis boolean.

--------------------

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

Domyślnie **false**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |