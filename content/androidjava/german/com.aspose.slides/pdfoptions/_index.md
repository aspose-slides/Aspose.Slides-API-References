---
title: PdfOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/pdfoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Stellt Optionen bereit, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instanziert die PdfOptions-Klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Setzt die JPEG-Qualität
>      pdfOptions.setJpegQuality((byte)90);
>      // Setzt das Verhalten für Metadateien
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Setzt die Textkomprimierungsstufe
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Definiert den PDF-Standard
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Speichert die Präsentation als PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instanziert eine Presentation-Klasse, die eine PowerPoint-Datei repräsentiert
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instanziert die PdfOptions-Klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Fügt ausgeblendete Folien hinzu
>      pdfOptions.setShowHiddenSlides(true);
>      // Speichert die Präsentation als PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instanziert ein Presentation-Objekt, das eine PowerPoint-Datei darstellt
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instanziert die PdfOptions-Klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Setzt das PDF-Passwort und die Zugriffsrechte
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Speichert die Präsentation als PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instanziert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Festlegen von Folientyp und -größe
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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Standardkonstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Liest oder setzt den Modus, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Liest oder setzt den Modus, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden. |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Erscheinungsbild von Ink-Objekten im exportierten Dokument steuern. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. |
| [getTextCompression()](#getTextCompression--) | Gibt den zu verwendenden Kompressionstyp für alle Textinhalte im Dokument an. |
| [setTextCompression(int value)](#setTextCompression-int-) | Gibt den zu verwendenden Kompressionstyp für alle Textinhalte im Dokument an. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Gibt an, ob für jedes Bild die effektivste Kompression (statt der Standardkompression) automatisch ausgewählt werden soll. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Gibt an, ob für jedes Bild die effektivste Kompression (statt der Standardkompression) automatisch ausgewählt werden soll. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Bestimmt, ob Aspose.Slides gängige Schriftarten für ASCII (33..127 Codebereich)-Text einbetten wird. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Bestimmt, ob Aspose.Slides gängige Schriftarten für ASCII (33..127 Codebereich)-Text einbetten wird. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Liest oder setzt ein Array von benutzerdefinierten Namen von Schriftfamilien, die Aspose.Slides als gängig betrachten soll. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Liest oder setzt ein Array von benutzerdefinierten Namen von Schriftfamilien, die Aspose.Slides als gängig betrachten soll. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein verwendeter Teil. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein verwendeter Teil. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. |
| [getJpegQuality()](#getJpegQuality--) | Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [getCompliance()](#getCompliance--) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [getPassword()](#getPassword--) | Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. |
| [getAccessPermissions()](#getAccessPermissions--) | Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. |
| [getSufficientResolution()](#getSufficientResolution--) | Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Liest oder setzt die transparente Farbe des Bildes. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Liest oder setzt die transparente Farbe des Bildes. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Wendet die angegebene transparente Farbe auf ein Bild an, wenn true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Wendet die angegebene transparente Farbe auf ein Bild an, wenn true. |
| [getIncludeOleData()](#getIncludeOleData--) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Standardkonstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Liest oder setzt den Modus, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden.

--------------------

> ```
> Beispiel:
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

**Rückgabewert:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Liest oder setzt den Modus, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite platziert werden.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Stellt Optionen bereit, die das Erscheinungsbild von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. Standard ist false.

**Rückgabewert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument ausgeblendete Folien enthalten soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Gibt den zu verwendenden Kompressionstyp für alle Textinhalte im Dokument an. Lese/Schreib [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standard ist [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Rückgabewert:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Gibt den zu verwendenden Kompressionstyp für alle Textinhalte im Dokument an. Lese/Schreib [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standard ist [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Gibt an, ob für jedes Bild die effektivste Kompression (statt der Standardkompression) automatisch ausgewählt werden soll. Ist der Wert true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechnerisch aufwendig und benötigt zusätzlichen RAM; diese Option ist standardmäßig false.

--------------------

Standard ist false.

**Rückgabewert:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Gibt an, ob für jedes Bild die effektivste Kompression (statt der Standardkompression) automatisch ausgewählt werden soll. Ist der Wert true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechnerisch aufwendig und benötigt zusätzlichen RAM; diese Option ist standardmäßig false.

--------------------

Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Bestimmt, ob Aspose.Slides gängige Schriftarten für ASCII (33..127 Codebereich)-Text einbetten wird. Schriftarten für Zeichen-Codes größer als 127 werden immer eingebettet. Die Liste gängiger Schriftarten beinhaltet die 14 Basis-PDF-Schriftarten und zusätzlich benutzerdefinierte Schriftarten. Lese/Schreib Boolean.

--------------------

Standard ist **true**.

**Rückgabewert:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Bestimmt, ob Aspose.Slides gängige Schriftarten für ASCII (33..127 Codebereich)-Text einbetten wird. Schriftarten für Zeichen-Codes größer als 127 werden immer eingebettet. Die Liste gängiger Schriftarten beinhaltet die 14 Basis-PDF-Schriftarten und zusätzlich benutzerdefinierte Schriftarten. Lese/Schreib Boolean.

--------------------

Standard ist **true**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Liest oder setzt ein Array von benutzerdefinierten Namen von Schriftfamilien, die Aspose.Slides als gängig betrachten soll. Lese/Schreib String[].

**Rückgabewert:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Liest oder setzt ein Array von benutzerdefinierten Namen von Schriftfamilien, die Aspose.Slides als gängig betrachten soll. Lese/Schreib String[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein verwendeter Teil. Lese/Schreib Boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein verwendeter Teil. Lese/Schreib Boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriftarten verbessern. Lese/Schreib Boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriftarten verbessern. Lese/Schreib Boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese/Schreib Byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Bildqualität beim Speichern im PDF-Format zu erhalten oder zu ändern. Der Wert kann von 0 bis 100 reichen, wobei 0 die schlechteste Qualität bei maximaler Kompression und 100 die beste Qualität bei minimaler Kompression bedeutet.

Der Standardwert ist **100**.

**Rückgabewert:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese/Schreib Byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Bildqualität beim Speichern im PDF-Format zu erhalten oder zu ändern. Der Wert kann von 0 bis 100 reichen, wobei 0 die schlechteste Qualität bei maximaler Kompression und 100 die beste Qualität bei minimaler Kompression bedeutet.

Der Standardwert ist **100**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lese/Schreib [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standard ist [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Rückgabewert:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lese/Schreib [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standard ist [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. Lese/Schreib String.

**Rückgabewert:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Rückgabewert:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese/Schreib Boolean.

--------------------

Standard ist **true**. Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Ist SaveMetafilesAsPng auf true gesetzt, wird die Quell-Metadatei in das Png-Format konvertiert und als Rasterbild im Pdf gespeichert. Ist SaveMetafilesAsPng auf false gesetzt, wird die Quell-Metadatei in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Beispielsweise kann beim Konvertieren einer Metadatei zu PNG ein Qualitätsverlust bei der Skalierung des resultierenden Dokuments auftreten. Beim Konvertieren zu Pdf-Vektorgrafiken können Performance-Probleme im Pdf-Betrachtungsprogramm auftreten.

**Rückgabewert:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese/Schreib Boolean.

--------------------

Standard ist **true**. Pdf-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Ist SaveMetafilesAsPng auf true gesetzt, wird die Quell-Metadatei in das Png-Format konvertiert und als Rasterbild im Pdf gespeichert. Ist SaveMetafilesAsPng auf false gesetzt, wird die Quell-Metadatei in Pdf-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Beispielsweise kann beim Konvertieren einer Metadatei zu PNG ein Qualitätsverlust bei der Skalierung des resultierenden Dokuments auftreten. Beim Konvertieren zu Pdf-Vektorgrafiken können Performance-Probleme im Pdf-Betrachtungsprogramm auftreten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lese/Schreib Float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die beste Ausgabe-Bildgröße basierend auf dem Eigenschaftswert, der Größe des Quellbildes und der Bildrahmengröße zu ermitteln. Ähnliche Eigenschaftswerte können zum gleichen Ergebnis führen. Empfohlen wird ein Schritt von 16 oder 32, um eine sichtbare Wirkung zu erzielen.

--------------------

Die Eigenschaft beeinflusst Dateigröße, Exportzeit und Bildqualität.

Der Standardwert ist **96**.

**Rückgabewert:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lese/Schreib Float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die beste Ausgabe-Bildgröße basierend auf dem Eigenschaftswert, der Größe des Quellbildes und der Bildrahmengröße zu ermitteln. Ähnliche Eigenschaftswerte können zum gleichen Ergebnis führen. Empfohlen wird ein Schritt von 16 oder 32, um eine sichtbare Wirkung zu erzielen.

--------------------

Die Eigenschaft beeinflusst Dateigröße, Exportzeit und Bildqualität.

Der Standardwert ist **96**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese/Schreib Boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese/Schreib Boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

Liest oder setzt die transparente Farbe des Bildes.

Wert: Die transparente Farbe des Bildes.

**Rückgabewert:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

Liest oder setzt die transparente Farbe des Bildes.

Wert: Die transparente Farbe des Bildes.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Wendet die angegebene transparente Farbe auf ein Bild an, wenn true.

**Rückgabewert:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Wendet die angegebene transparente Farbe auf ein Bild an, wenn true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese/Schreib Boolean.

--------------------

> ```
> Beispiel:
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

Standard ist **false**.

**Rückgabewert:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese/Schreib Boolean.

--------------------

> ```
> Beispiel:
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

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |