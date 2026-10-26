---
title: IPdfOptions
second_title: Aspose.Slides für Android über Java API Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/ipdfoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Gibt den Kompressionstyp an, der für alle textlichen Inhalte im Dokument verwendet wird. |
| [setTextCompression(int value)](#setTextCompression-int-) | Gibt den Kompressionstyp an, der für alle textlichen Inhalte im Dokument verwendet wird. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden soll. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden soll. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True, um TrueType-Schriften für ASCII-Zeichen 32-127 einzubetten. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True, um TrueType-Schriften für ASCII-Zeichen 32-127 einzubetten. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als gemeinsam betrachten soll. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als gemeinsam betrachten soll. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Bestimmt, ob alle Zeichen der Schrift eingebettet werden sollen oder nur ein Teil davon. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Bestimmt, ob alle Zeichen der Schrift eingebettet werden sollen oder nur ein Teil davon. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schrift keine fette Formatierung unterstützt. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schrift keine fette Formatierung unterstützt. |
| [getJpegQuality()](#getJpegQuality--) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [getCompliance()](#getCompliance--) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [setCompliance(int value)](#setCompliance-int-) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [getPassword()](#getPassword--) | Festlegen eines Benutzerkennworts zum Schutz des PDF-Dokuments. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Festlegen eines Benutzerkennworts zum Schutz des PDF-Dokuments. |
| [getAccessPermissions()](#getAccessPermissions--) | Enthält einen Satz von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Enthält einen Satz von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. |
| [getSufficientResolution()](#getSufficientResolution--) | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Liest oder legt die transparente Bildfarbe fest. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Liest oder legt die transparente Bildfarbe fest. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Wendet die angegebene transparente Farbe auf ein Bild an, falls true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Wendet die angegebene transparente Farbe auf ein Bild an, falls true. |
| [getInkOptions()](#getInkOptions--) | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getIncludeOleData()](#getIncludeOleData--) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Gibt den Kompressionstyp an, der für alle textlichen Inhalte im Dokument verwendet wird. Lese-/Schreib-[PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standardwert ist [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Rückgabewert:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Gibt den Kompressionstyp an, der für alle textlichen Inhalte im Dokument verwendet wird. Lese-/Schreib-[PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Standardwert ist [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden soll. Wenn true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechnerisch aufwendig und verbraucht zusätzlichen RAM; diese Option ist standardmäßig false.

--------------------

Standardwert ist false.

**Rückgabewert:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden soll. Wenn true, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt.

--------------------

Die Auswahl des besten Bildkompressionsverhältnisses ist rechnerisch aufwendig und verbraucht zusätzlichen RAM; diese Option ist standardmäßig false.

--------------------

Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True, um TrueType-Schriften für ASCII-Zeichen 32-127 einzubetten. Schriften für Zeichencodes über 127 werden immer eingebettet. Lese-/Schreib-boolean.

--------------------

Standardwert ist **true**.

**Rückgabewert:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True, um TrueType-Schriften für ASCII-Zeichen 32-127 einzubetten. Schriften für Zeichencodes über 127 werden immer eingebettet. Lese-/Schreib-boolean.

--------------------

Standardwert ist **true**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Rückgabewert:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als gemeinsam betrachten soll. Lese-/Schreib-String[].

**Rückgabewert:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Gibt ein Array von benutzerdefinierten Namen von Schriftfamilien zurück oder legt es fest, die Aspose.Slides als gemeinsam betrachten soll. Lese-/Schreib-String[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Bestimmt, ob alle Zeichen der Schrift eingebettet werden sollen oder nur ein Teil davon. Lese-/Schreib-boolean.

--------------------

Standardwert ist **false**.

**Rückgabewert:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Bestimmt, ob alle Zeichen der Schrift eingebettet werden sollen oder nur ein Teil davon. Lese-/Schreib-boolean.

--------------------

Standardwert ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schrift keine fette Formatierung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lese-/Schreib-boolean.

--------------------

Standardwert ist **false**.

**Rückgabewert:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schrift keine fette Formatierung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriften verbessern. Lese-/Schreib-boolean.

--------------------

Standardwert ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese-/Schreib-byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression bedeutet und 100 die beste Qualität bei minimaler Kompression.

Der Standardwert ist **100**.

**Rückgabewert:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese-/Schreib-byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression bedeutet und 100 die beste Qualität bei minimaler Kompression.

Der Standardwert ist **100**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lese-/Schreib-[PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standardwert ist [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Rückgabewert:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Lese-/Schreib-[PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Standardwert ist [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Festlegen eines Benutzerkennworts zum Schutz des PDF-Dokuments. Lese-/Schreib-String.

**Rückgabewert:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Festlegen eines Benutzerkennworts zum Schutz des PDF-Dokuments. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Enthält einen Satz von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

Enthält einen Satz von Flags, die angeben, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzerzugriff geöffnet wird. Siehe [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract boolean getSaveMetafilesAsPng()
```

True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. Lese-/Schreib-boolean.

--------------------

Standardwert ist **true**. PDF-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng true ist, wird das Quell-Metadatei-Bild in das PNG-Format konvertiert und als Rasterbild im PDF gespeichert. Wenn SaveMetafilesAsPng false ist, wird das Quell-Metadatei-Bild in PDF-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Beispielsweise kann bei einer Konvertierung in PNG ein Qualitätsverlust beim Skalieren des resultierenden Dokuments auftreten. Bei einer Konvertierung in PDF-Vektorgrafiken können Leistungsprobleme im PDF-Betrachter auftreten.

**Rückgabewert:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, um alle Metadateien, die in einer Präsentation verwendet werden, in PNG-Bilder zu konvertieren. Lese-/Schreib-boolean.

--------------------

Standardwert ist **true**. PDF-Dokument kann Vektorgrafiken und Rasterbilder enthalten. Wenn SaveMetafilesAsPng true ist, wird das Quell-Metadatei-Bild in das PNG-Format konvertiert und als Rasterbild im PDF gespeichert. Wenn SaveMetafilesAsPng false ist, wird das Quell-Metadatei-Bild in PDF-Vektorgrafiken konvertiert. Jeder Ansatz hat Vor- und Nachteile. Beispielsweise kann bei einer Konvertierung in PNG ein Qualitätsverlust beim Skalieren des resultierenden Dokuments auftreten. Bei einer Konvertierung in PDF-Vektorgrafiken können Leistungsprobleme im PDF-Betrachter auftreten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lese-/Schreib-float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die beste Ausgabebildgröße basierend auf dem Eigenschaftswert, der Größe des Quellbildes und der Bildrahmengröße zu ermitteln. Die Verwendung ähnlicher Eigenschaftswerte kann zum selben Ergebnis führen. Empfohlen wird die Verwendung von Schritten von 16 oder 32, um einen sichtbaren Effekt zu erzielen.

--------------------

Die Eigenschaft wirkt sich auf Dateigröße, Exportzeit und Bildqualität aus.

Der Standardwert ist **96**.

**Rückgabewert:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Gibt einen Wert zurück oder legt ihn fest, der die Auflösung der Bilder im PDF-Dokument bestimmt. Lese-/Schreib-float.

Wert: Die Wirkung dieses Parameters hängt von mehreren Faktoren ab. Der Algorithmus versucht, die beste Ausgabebildgröße basierend auf dem Eigenschaftswert, der Größe des Quellbildes und der Bildrahmengröße zu ermitteln. Die Verwendung ähnlicher Eigenschaftswerte kann zum selben Ergebnis führen. Empfohlen wird die Verwendung von Schritten von 16 oder 32, um einen sichtbaren Effekt zu erzielen.

--------------------

Die Eigenschaft wirkt sich auf Dateigröße, Exportzeit und Bildqualität aus.

Der Standardwert ist **96**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese-/Schreib-boolean.

--------------------

Standardwert ist **false**.

**Rückgabewert:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lese-/Schreib-boolean.

--------------------

Standardwert ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Liest oder legt die transparente Bildfarbe fest.

Wert: Die Farbe der transparenten Bildfarbe.

**Rückgabewert:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Liest oder legt die transparente Bildfarbe fest.

Wert: Die Farbe der transparenten Bildfarbe.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Integer |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur-Lese-[IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese-/Schreib-boolean.

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

Standardwert ist **false**.

**Rückgabewert:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lese-/Schreib-boolean.

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

Standardwert ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |