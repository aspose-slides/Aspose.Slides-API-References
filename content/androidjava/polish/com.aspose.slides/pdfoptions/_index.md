---
title: PdfOptions
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
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
>      // Ustawia jakość Jpeg
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
>  // Tworzy instancję klasy Presentation, która reprezentuje plik PowerPoint
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
>  // Tworzy instancję obiektu Presentation, który reprezentuje plik PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Tworzy instancję klasy PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Ustawia hasło PDF i uprawnienia dostępu
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
>  // Tworzy instancję obiektu Presentation, który reprezentuje plik prezentacji
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
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. |
| [getTextCompression()](#getTextCompression--) | Określa typ kompresji używany dla całej treści tekstowej w dokumencie. |
| [setTextCompression(int value)](#setTextCompression-int-) | Określa typ kompresji używany dla całej treści tekstowej w dokumencie. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Wskazuje, czy najbardziej efektywna kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Wskazuje, czy najbardziej efektywna kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Określa, czy Aspose.Slides osadzi popularne czcionki dla tekstu ASCII (zakres kodów 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Określa, czy Aspose.Slides osadzi popularne czcionki dla tekstu ASCII (zakres kodów 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za popularne. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za popularne. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. |
| [getJpegQuality()](#getJpegQuality--) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [getCompliance()](#getCompliance--) | Pożądany poziom zgodności dla generowanego dokumentu PDF. |
| [setCompliance(int value)](#setCompliance-int-) | Pożądany poziom zgodności dla generowanego dokumentu PDF. |
| [getPassword()](#getPassword--) | Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ustawianie hasła użytkownika w celu ochrony dokumentu PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Zawiera zestaw flag określających, które uprawnienia dostępu mają być przyznane po otwarciu dokumentu z dostępem użytkownika. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Zawiera zestaw flag określających, które uprawnienia dostępu mają być przyznane po otwarciu dokumentu z dostępem użytkownika. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Prawda, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Prawda, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Prawda, aby rysować czarną ramkę wokół każdego slajdu. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Prawda, aby rysować czarną ramkę wokół każdego slajdu. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Pobiera lub ustawia przezroczysty kolor obrazu. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Stosuje określony przezroczysty kolor do obrazu, jeśli prawda. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Stosuje określony przezroczysty kolor do obrazu, jeśli prawda. |
| [getIncludeOleData()](#getIncludeOleData--) | Prawda, aby konwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Prawda, aby konwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Domyślny konstruktor.

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

Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie false.

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

Domyślna wartość to [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Zwraca:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
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
public final boolean getBestImagesCompressionRatio()
```

Wskazuje, czy najbardziej efektywna kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. Jeśli ustawione na prawda, dla każdego obrazu w prezentacji zostanie wybrany najodpowiedniejszy algorytm kompresji, co doprowadzi do mniejszego rozmiaru powstałego dokumentu PDF.

--------------------

Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej ilości pamięci RAM, a ta opcja domyślnie ma wartość false.

--------------------

Domyślnie false.

**Zwraca:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Wskazuje, czy najbardziej efektywna kompresja (zamiast domyślnej) dla każdego obrazu ma być wybierana automatycznie. Jeśli ustawione na prawda, dla każdego obrazu w prezentacji zostanie wybrany najodpowiedniejszy algorytm kompresji, co doprowadzi do mniejszego rozmiaru powstałego dokumentu PDF.

--------------------

Wybór najlepszego współczynnika kompresji obrazu jest kosztowny obliczeniowo i wymaga dodatkowej ilości pamięci RAM, a ta opcja domyślnie ma wartość false.

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

Określa, czy Aspose.Slides osadzi popularne czcionki dla tekstu ASCII (zakres kodów 33..127). Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Lista popularnych czcionek zawiera bazowe 14 czcionek PDF oraz dodatkowe czcionki określone przez użytkownika. Odczyt/zapis boolean.

--------------------

Domyślnie **true**.

**Zwraca:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Określa, czy Aspose.Slides osadzi popularne czcionki dla tekstu ASCII (zakres kodów 33..127). Czcionki dla kodów znaków większych niż 127 są zawsze osadzane. Lista popularnych czcionek zawiera bazowe 14 czcionek PDF oraz dodatkowe czcionki określone przez użytkownika. Odczyt/zapis boolean.

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

Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za popularne. Odczyt/zapis String[].

**Zwraca:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Zwraca lub ustawia tablicę nazw rodzin czcionek zdefiniowanych przez użytkownika, które Aspose.Slides powinien uznać za popularne. Odczyt/zapis String[].

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Określa, czy wszystkie znaki czcionki mają być osadzone, czy tylko używany podzbiór. Odczyt/zapis boolean.

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

Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. To podejście może poprawić jakość tekstu w powstałym PDF dla niektórych czcionek. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Wskazuje, czy tekst powinien być rasteryzowany jako bitmapa i zapisywany do PDF, gdy czcionka nie obsługuje pogrubienia. To podejście może poprawić jakość tekstu w powstałym PDF dla niektórych czcionek. Odczyt/zapis boolean.

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

Pożądany poziom zgodności dla generowanego dokumentu PDF. Odczyt/zapis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Domyślna wartość to [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Zwraca:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Pożądany poziom zgodności dla generowanego dokumentu PDF. Odczyt/zapis [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Domyślna wartość to [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

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

Zawiera zestaw flag określających, które uprawnienia dostępu mają być przyznane po otwarciu dokumentu z dostępem użytkownika. See [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Zawiera zestaw flag określających, które uprawnienia dostępu mają być przyznane po otwarciu dokumentu z dostępem użytkownika. See [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Prawda, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślnie **true**. Dokument PDF może zawierać grafikę wektorową oraz obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, źródłowy obraz Metafile zostaje przekonwertowany do formatu PNG i zapisany w PDF jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, źródłowy Metafile zostaje skonwertowany do grafiki wektorowej PDF. Każde podejście ma zalety i wady. Na przykład, konwersja Metafile do PNG może powodować utratę jakości przy skalowaniu powstałego dokumentu. Konwersja Metafile do grafiki wektorowej PDF może powodować problemy z wydajnością w czytniku PDF.

**Zwraca:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Prawda, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczyt/zapis boolean.

--------------------

Domyślnie **true**. Dokument PDF może zawierać grafikę wektorową oraz obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, źródłowy obraz Metafile zostaje przekonwertowany do formatu PNG i zapisany w PDF jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, źródłowy Metafile zostaje skonwertowany do grafiki wektorowej PDF. Każde podejście ma zalety i wady. Na przykład, konwersja Metafile do PNG może powodować utratę jakości przy skalowaniu powstałego dokumentu. Konwersja Metafile do grafiki wektorowej PDF może powodować problemy z wydajnością w czytniku PDF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. Odczyt/zapis float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

The default value is **96**.

**Zwraca:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Zwraca lub ustawia wartość określającą rozdzielczość obrazów w dokumencie PDF. Odczyt/zapis float.

Value: Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

--------------------

Property affects on file size, time of export and image quality.

The default value is **96**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Prawda, aby rysować czarną ramkę wokół każdego slajdu. Odczyt/zapis boolean.

--------------------

Domyślnie **false**.

**Zwraca:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Prawda, aby rysować czarną ramkę wokół każdego slajdu. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Pobiera lub ustawia przezroczysty kolor obrazu.

Value: The color of the image transparent.

**Zwraca:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Pobiera lub ustawia przezroczysty kolor obrazu.

Value: The color of the image transparent.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Stosuje określony przezroczysty kolor do obrazu, jeśli prawda.

**Zwraca:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Stosuje określony przezroczysty kolor do obrazu, jeśli prawda.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Prawda, aby konwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. Odczyt/zapis boolean .

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

Prawda, aby konwertować wszystkie dane OLE z prezentacji na osadzone pliki w powstałym PDF. Odczyt/zapis boolean .

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