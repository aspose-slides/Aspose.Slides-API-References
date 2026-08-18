---
title: PdfOptions
second_title: Aspose.Slides für Java API Referenz
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

Stellt Optionen bereit, die steuern, wie eine Präsentation im PDF-Format gespeichert wird.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instanziiert die PdfOptions-Klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Setzt die Jpeg-Qualität
>      pdfOptions.setJpegQuality((byte)90);
>      // Setzt das Verhalten für Metadateien
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Setzt das Textkomprimierungslevel
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
>  // Instanziiert eine Presentation-Klasse, die eine PowerPoint-Datei darstellt
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instanziiert die PdfOptions-Klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Fügt verborgene Folien hinzu
>      pdfOptions.setShowHiddenSlides(true);
>      // Speichert die Präsentation als PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instanziiert ein Presentation-Objekt, das eine PowerPoint-Datei darstellt
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instanziiert die PdfOptions-Klasse
>      PdfOptions pdfOptions = new PdfOptions();
>      // Setzt das PDF-Passwort und die Zugriffsberechtigungen
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
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Setzt Folientyp und -größe
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
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [getTextCompression()](#getTextCompression--) | Gibt den zu verwendenden Kompressionstyp für sämtlichen Textinhalt im Dokument an. |
| [setTextCompression(int value)](#setTextCompression-int-) | Gibt den zu verwendenden Kompressionstyp für sämtlichen Textinhalt im Dokument an. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Zeigt an, ob die effektivste Kompression (statt der Standard-Kompression) für jedes Bild automatisch ausgewählt werden soll. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Zeigt an, ob die effektivste Kompression (statt der Standard-Kompression) für jedes Bild automatisch ausgewählt werden soll. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Bestimmt, ob Aspose.Slides gängige Schriften für ASCII-Text (Code-Bereich 33..127) einbetten wird. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Bestimmt, ob Aspose.Slides gängige Schriften für ASCII-Text (Code-Bereich 33..127) einbetten wird. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Liest oder setzt ein Array von benutzerdefinierten Schriftenfamiliennamen, die Aspose.Slides als gängig betrachten soll. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Liest oder setzt ein Array von benutzerdefinierten Schriftenfamiliennamen, die Aspose.Slides als gängig betrachten soll. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Zeigt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettschrift unterstützt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Zeigt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettschrift unterstützt. |
| [getJpegQuality()](#getJpegQuality--) | Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [getCompliance()](#getCompliance--) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [getPassword()](#getPassword--) | Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. |
| [getAccessPermissions()](#getAccessPermissions--) | Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. |
| [getSufficientResolution()](#getSufficientResolution--) | Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, um um jede Folie einen schwarzen Rahmen zu zeichnen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, um um jede Folie einen schwarzen Rahmen zu zeichnen. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Liest oder setzt die transparente Farbe des Bildes. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Liest oder setzt die transparente Farbe des Bildes. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Wendet die angegebene transparente Farbe auf ein Bild an, falls true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Wendet die angegebene transparente Farbe auf ein Bild an, falls true. |
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

Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standard ist false.

**Rückgabewert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Gibt den zu verwendenden Kompressionstyp für sämtlichen Textinhalt im Dokument an. Lesen/Schreiben [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standard ist [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Rückgabewert:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Gibt den zu verwendenden Kompressionstyp für sämtlichen Textinhalt im Dokument an. Lesen/Schreiben [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

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

Zeigt an, ob die effektivste Kompression (statt der Standard-Kompression) für jedes Bild automatisch ausgewählt werden soll. Wenn true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Dateigröße des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und verbraucht zusätzlichen RAM; diese Option ist standardmäßig false.

--------------------

Standard ist false.

**Rückgabewert:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Zeigt an, ob die effektivste Kompression (statt der Standard-Kompression) für jedes Bild automatisch ausgewählt werden soll. Wenn true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Dateigröße des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und verbraucht zusätzlichen RAM; diese Option ist standardmäßig false.

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

Bestimmt, ob Aspose.Slides gängige Schriften für ASCII-Text (Code-Bereich 33..127) einbetten wird. Schriften für Code-Bereiche > 127 werden immer eingebettet. Die Liste gängiger Schriften umfasst die 14 Basis-PDF-Schriften sowie zusätzlich benutzerdefinierte Schriften. Lesen/Schreiben boolean.

--------------------

Standard ist **true**.

**Rückgabewert:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Bestimmt, ob Aspose.Slides gängige Schriften für ASCII-Text (Code-Bereich 33..127) einbetten wird. Schriften für Code-Bereiche > 127 werden immer eingebettet. Die Liste gängiger Schriften umfasst die 14 Basis-PDF-Schriften sowie zusätzlich benutzerdefinierte Schriften. Lesen/Schreiben boolean.

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

Liest oder setzt ein Array von benutzerdefinierten Schriftenfamiliennamen, die Aspose.Slides als gängig betrachten soll. Lesen/Schreiben String[].

**Rückgabewert:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Liest oder setzt ein Array von benutzerdefinierten Schriftenfamiliennamen, die Aspose.Slides als gängig betrachten soll. Lesen/Schreiben String[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Lesen/Schreiben boolean.

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

Zeigt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettschrift unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Zeigt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettschrift unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lesen/Schreiben boolean.

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

Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn das Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Bildqualität beim Speichern im PDF-Format zu erhalten oder zu ändern. Der Wert kann von 0 bis 100 reichen, wobei 0 die schlechteste Qualität bei maximaler Kompression und 100 die beste Qualität bei minimaler Kompression bedeutet.

Der Standardwert ist **100**.

**Rückgabewert:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Liest oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn das Dokument JPEG-Bilder enthält.

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

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lesen/Schreiben [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standard ist [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Rückgabewert:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lesen/Schreiben [PdfCompliance](../../com.aspose.slides/pdfcompliance).

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

Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen/Schreiben boolean.

--------------------

Standard ist **true**. PDF-Dokumente können Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metadatei-Bild in PNG-Format konvertiert und als Rasterbild im PDF gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metadatei in PDF-Vektorgrafik konvertiert. Jede Methode hat Vor- und Nachteile. Wird das Metadatei-Bild z. B. in PNG konvertiert, kann beim Skalieren des resultierenden Dokuments Qualitätsverlust auftreten. Wird das Metadatei-Bild in PDF-Vektorgrafik konvertiert, können Leistungsprobleme im PDF-Betrachter auftreten.

**Rückgabewert:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen/Schreiben boolean.

--------------------

Standard ist **true**. PDF-Dokumente können Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metadatei-Bild in PNG-Format konvertiert und als Rasterbild im PDF gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metadatei in PDF-Vektorgrafik konvertiert. Jede Methode hat Vor- und Nachteile. Wird das Metadatei-Bild z. B. in PNG konvertiert, kann beim Skalieren des resultierenden Dokuments Qualitätsverlust auftreten. Wird das Metadatei-Bild in PDF-Vektorgrafik konvertiert, können Leistungsprobleme im PDF-Betrachter auftreten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lesen/Schreiben float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die optimale Bildgröße anhand des Property-Werts, der Quell-Bildgröße und der Bildrahmengröße zu ermitteln. Ähnliche Property-Werte können zum selben Ergebnis führen. Empfohlen wird ein Schritt von 16 oder 32, um einen sichtbaren Effekt zu erzielen.

--------------------

Die Property beeinflusst Dateigröße, Exportzeit und Bildqualität.

Der Standardwert ist **96**.

**Rückgabewert:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Liest oder setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lesen/Schreiben float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die optimale Bildgröße anhand des Property-Werts, der Quell-Bildgröße und der Bildrahmengröße zu ermitteln. Ähnliche Property-Werte können zum selben Ergebnis führen. Empfohlen wird ein Schritt von 16 oder 32, um einen sichtbaren Effekt zu erzielen.

--------------------

Die Property beeinflusst Dateigröße, Exportzeit und Bildqualität.

Der Standardwert ist **96**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True, um um jede Folie einen schwarzen Rahmen zu zeichnen. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True, um um jede Folie einen schwarzen Rahmen zu zeichnen. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Liest oder setzt die transparente Farbe des Bildes.

Wert: Die Farbe des Bildes, das transparent sein soll.

**Rückgabewert:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Liest oder setzt die transparente Farbe des Bildes.

Wert: Die Farbe des Bildes, das transparent sein soll.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Wendet die angegebene transparente Farbe auf ein Bild an, falls true.

**Rückgabewert:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Wendet die angegebene transparente Farbe auf ein Bild an, falls true.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lesen/Schreiben boolean.

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

Standard ist **false**.

**Rückgabewert:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lesen/Schreiben boolean.

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

Standard ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |