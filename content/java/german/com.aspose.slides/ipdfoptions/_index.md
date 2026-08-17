---
title: IPdfOptions
second_title: Aspose.Slides für Java API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im PDF-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/ipdfoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Bietet Optionen, die steuern, wie eine Präsentation im PDF-Format gespeichert wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Gibt den Kompressionstyp an, der für alle textuellen Inhalte im Dokument verwendet werden soll. |
| [setTextCompression(int value)](#setTextCompression-int-) | Gibt den Kompressionstyp an, der für alle textuellen Inhalte im Dokument verwendet werden soll. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True, um True-Type-Schriften für ASCII-Zeichen 32-127 einzubetten. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True, um True-Type-Schriften für ASCII-Zeichen 32-127 einzubetten. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Gibt ein Array benutzerdefinierter Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als üblich betrachten soll. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. |
| [getJpegQuality()](#getJpegQuality--) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [getCompliance()](#getCompliance--) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [getPassword()](#getPassword--) | Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. |
| [getAccessPermissions()](#getAccessPermissions--) | Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. |
| [getSufficientResolution()](#getSufficientResolution--) | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Ruft die transparente Bildfarbe ab oder legt sie fest. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Ruft die transparente Bildfarbe ab oder legt sie fest. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Wendet die angegebene transparente Farbe auf ein Bild an, falls true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Wendet die angegebene transparente Farbe auf ein Bild an, falls true. |
| [getInkOptions()](#getInkOptions--) | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getIncludeOleData()](#getIncludeOleData--) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Gibt den Kompressionstyp an, der für alle textuellen Inhalte im Dokument verwendet werden soll. Lesen/Schreiben [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standard ist [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Rückgabewert:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Gibt den Kompressionstyp an, der für alle textuellen Inhalte im Dokument verwendet werden soll. Lesen/Schreiben [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standard ist [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. Wenn true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und benötigt zusätzlichen RAM, und diese Option ist standardmäßig false.

--------------------

Standard ist false.

**Rückgabewert:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. Wenn true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechenintensiv und benötigt zusätzlichen RAM, und diese Option ist standardmäßig false.

--------------------

Standard ist false.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True, um True-Type-Schriften für ASCII-Zeichen 32-127 einzubetten. Schriften für Zeichenkodierungen größer als 127 werden immer eingebettet. Lesen/Schreiben boolean.

--------------------

Standard ist **true**.

**Rückgabewert:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True, um True-Type-Schriften für ASCII-Zeichen 32-127 einzubetten. Schriften für Zeichenkodierungen größer als 127 werden immer eingebettet. Lesen/Schreiben boolean.

--------------------

Standard ist **true**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist false.

**Rückgabewert:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Gibt ein Array benutzerdefinierter Namen von Schriftfamilien zurück oder legt es fest, das Aspose.Slides als üblich betrachten soll. Lesen/Schreiben String[].

**Rückgabewert:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Gibt ein Array benutzerdefinierter Namen von Schriftfamilien zurück oder legt es fest, das Aspose.Slides als üblich betrachten soll. Lesen/Schreiben String[].

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine Fettdarstellung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Property, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität aber maximale Kompression bedeutet und 100 die beste Qualität aber minimale Kompression.

Der Standardwert ist **100**.

**Rückgabewert:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Property, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität aber maximale Kompression bedeutet und 100 die beste Qualität aber minimale Kompression.

Der Standardwert ist **100**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lesen/Schreiben [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standard ist [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Rückgabewert:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lesen/Schreiben [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standard ist [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Festlegen des Benutzerpassworts zum Schutz des PDF-Dokuments. Lesen/Schreiben String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

Enthält eine Menge von Flags, die angeben, welche Zugriffsrechte gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. Lesen/Schreiben boolean.

--------------------

Standard ist **true**. Ein PDF-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metafile-Bild in das PNG-Format konvertiert und als Rasterbild im PDF gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metafile in PDF-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Zum Beispiel kann bei der Konvertierung eines Metafiles zu PNG beim Skalieren des resultierenden Dokuments ein Qualitätsverlust auftreten. Wird das Metafile zu PDF-Vektorgrafiken konvertiert, können Leistungsprobleme im PDF-Betrachter auftreten.

**Rückgabewert:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. Lesen/Schreiben boolean.

--------------------

Standard ist **true**. Ein PDF-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng auf true gesetzt ist, wird das Quell-Metafile-Bild in das PNG-Format konvertiert und als Rasterbild im PDF gespeichert. Wenn SaveMetafilesAsPng auf false gesetzt ist, wird das Quell-Metafile in PDF-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Zum Beispiel kann bei der Konvertierung eines Metafiles zu PNG beim Skalieren des resultierenden Dokuments ein Qualitätsverlust auftreten. Wird das Metafile zu PDF-Vektorgrafiken konvertiert, können Leistungsprobleme im PDF-Betrachter auftreten.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lesen/Schreiben float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die beste Ausgabebildgröße basierend auf dem Property-Wert, der Größe des Quellbildes und der Bildrahmengröße zu ermitteln. Die Verwendung ähnlicher Property-Werte kann zum selben Ergebnis führen. Es wird empfohlen, Schritte von 16 oder 32 zu verwenden, um einen sichtbaren Effekt zu erzielen.

--------------------

Die Property wirkt sich auf Dateigröße, Exportzeit und Bildqualität aus.

Der Standardwert ist **96**.

**Rückgabewert:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lesen/Schreiben float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die beste Ausgabebildgröße basierend auf dem Property-Wert, der Größe des Quellbildes und der Bildrahmengröße zu ermitteln. Die Verwendung ähnlicher Property-Werte kann zum selben Ergebnis führen. Es wird empfohlen, Schritte von 16 oder 32 zu verwenden, um einen sichtbaren Effekt zu erzielen.

--------------------

Die Property wirkt sich auf Dateigröße, Exportzeit und Bildqualität aus.

Der Standardwert ist **96**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Rückgabewert:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lesen/Schreiben boolean.

--------------------

Standard ist **false**.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden.

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Ruft den Modus ab oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

Ruft die transparente Bildfarbe ab oder legt sie fest.

Wert: Die transparente Farbe des Bildes.

**Rückgabewert:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Ruft die transparente Bildfarbe ab oder legt sie fest.

Wert: Die transparente Farbe des Bildes.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Wendet die angegebene transparente Farbe auf ein Bild an, falls true.

**Rückgabewert:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Wendet die angegebene transparente Farbe auf ein Bild an, falls true.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lesen/Schreiben boolean .

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

Standard ist  **false** .

**Rückgabewert:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lesen/Schreiben boolean .

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

Standard ist  **false** .

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |