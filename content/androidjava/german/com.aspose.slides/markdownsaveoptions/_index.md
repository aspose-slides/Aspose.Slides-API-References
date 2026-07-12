---
title: MarkdownSaveOptions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt Optionen dar, die steuern, wie die Präsentation in Markdown gespeichert wird.
type: docs
url: /de/com.aspose.slides/markdownsaveoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Stellt Optionen dar, die steuern, wie die Präsentation in Markdown gespeichert wird.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExportType()](#getExportType--) | Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. |
| [setExportType(int value)](#setExportType-int-) | Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. |
| [getBasePath()](#getBasePath--) | Gibt den Basispfad an, in dem das Dokument mit Ressourcen gespeichert wird. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Gibt den Basispfad an, in dem das Dokument mit Ressourcen gespeichert wird. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Gibt den Ordnernamen zum Speichern von Bildern an. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Gibt den Ordnernamen zum Speichern von Bildern an. |
| [getNewLineType()](#getNewLineType--) | Gibt an, ob das erzeugte Dokument Zeilenumbrüche \\r (Macintosh), \\n (Unix) oder \\r\\n (Windows) haben soll. |
| [setNewLineType(int value)](#setNewLineType-int-) | Gibt an, ob das erzeugte Dokument Zeilenumbrüche \\r (Macintosh), \\n (Unix) oder \\r\\n (Windows) haben soll. |
| [getShowComments()](#getShowComments--) | Gibt an, ob das erzeugte Dokument Kommentare anzeigen soll oder nicht. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Gibt an, ob das erzeugte Dokument Kommentare anzeigen soll oder nicht. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll oder nicht. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Gibt an, ob das erzeugte Dokument die Nummer jeder Folie anzeigen soll oder nicht. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Gibt an, ob das erzeugte Dokument die Nummer jeder Folie anzeigen soll oder nicht. |
| [getFlavor()](#getFlavor--) | Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. |
| [setFlavor(int value)](#setFlavor-int-) | Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Liefert oder legt die Formatzeichenfolge fest, die für Foliennummernüberschriften in der Markdown-Ausgabe verwendet wird. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Liefert oder legt die Formatzeichenfolge fest, die für Foliennummernüberschriften in der Markdown-Ausgabe verwendet wird. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Gibt an, wie wiederholte reguläre Leerzeichen während des Markdown-Exports behandelt werden sollen. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Gibt an, wie wiederholte reguläre Leerzeichen während des Markdown-Exports behandelt werden sollen. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Wenn true, werden leere oder nur aus Leerzeichen bestehende Zeilen aus der endgültigen Markdown-Ausgabe entfernt. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Wenn true, werden leere oder nur aus Leerzeichen bestehende Zeilen aus der endgültigen Markdown-Ausgabe entfernt. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Tritt für jedes Nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports auf. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Tritt für jedes SVG-Bild während des Markdown-Exports auf. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Konstruktor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. Standard ist  TextOnly .

**Rückgabe:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. Standard ist  TextOnly .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Gibt den Basispfad an, in dem das Dokument mit Ressourcen gespeichert wird. Standard ist das aktuelle Arbeitsverzeichnis der Anwendung.

**Rückgabe:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Gibt den Basispfad an, in dem das Dokument mit Ressourcen gespeichert wird. Standard ist das aktuelle Arbeitsverzeichnis der Anwendung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Gibt den Ordnernamen zum Speichern von Bildern an. Standard ist  Images .

**Rückgabe:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Gibt den Ordnernamen zum Speichern von Bildern an. Standard ist  Images .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Gibt an, ob das erzeugte Dokument Zeilenumbrüche \\r (Macintosh) von \\n (Unix) oder \\r\\n (Windows) haben soll. Standard ist  Unix .

**Rückgabe:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Gibt an, ob das erzeugte Dokument Zeilenumbrüche \\r (Macintosh) von \\n (Unix) oder \\r\\n (Windows) haben soll. Standard ist  Unix .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Gibt an, ob das erzeugte Dokument Kommentare anzeigen soll oder nicht. Standard ist false.

**Rückgabe:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Gibt an, ob das erzeugte Dokument Kommentare anzeigen soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll oder nicht. Standard ist false.

**Rückgabe:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Gibt an, ob das erzeugte Dokument die Nummer jeder Folie anzeigen soll oder nicht. Standard ist false.

**Rückgabe:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Gibt an, ob das erzeugte Dokument die Nummer jeder Folie anzeigen soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. Standard ist  Multi-markdown .

**Rückgabe:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Gibt die Markdown-Spezifikation an, mit der die Präsentation konvertiert wird. Standard ist  Multi-markdown .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Liefert oder legt die Formatzeichenfolge fest, die für Foliennummernüberschriften in der Markdown-Ausgabe verwendet wird. Das Format muss den Platzhalter "\{0\}" enthalten, der beim Export durch den Folienindex ersetzt wird. Beispiel: "\# Slide \{0\}" erzeugt "\# Slide 1", "\# Slide 2" usw.

**Rückgabe:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Liefert oder legt die Formatzeichenfolge fest, die für Foliennummernüberschriften in der Markdown-Ausgabe verwendet wird. Das Format muss den Platzhalter "\{0\}" enthalten, der beim Export durch den Folienindex ersetzt wird. Beispiel: "\# Slide \{0\}" erzeugt "\# Slide 1", "\# Slide 2" usw.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Gibt an, wie wiederholte reguläre Leerzeichen während des Markdown-Exports behandelt werden sollen. Diese Eigenschaft definiert, ob aufeinanderfolgende Leerzeichen: - als reguläre Leerzeichen beibehalten werden, - zwischen regulären Leerzeichen und nicht-brechenden Leerzeichen-Entitäten (�) abwechseln, - oder nach dem ersten vollständig durch ein nicht-brechendes Leerzeichen ersetzt werden, um die visuelle Ausrichtung in der Markdown-Ausgabe zu erhalten. Der Standardwert ist [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Rückgabe:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Gibt an, wie wiederholte reguläre Leerzeichen während des Markdown-Exports behandelt werden sollen. Diese Eigenschaft definiert, ob aufeinanderfolgende Leerzeichen: - als reguläre Leerzeichen beibehalten werden, - zwischen regulären Leerzeichen und nicht-brechenden Leerzeichen-Entitäten (�) abwechseln, - oder nach dem ersten vollständig durch ein nicht-brechendes Leerzeichen ersetzt werden, um die visuelle Ausrichtung in der Markdown-Ausgabe zu erhalten. Der Standardwert ist [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


Wenn true, werden leere oder nur aus Leerzeichen bestehende Zeilen aus der endgültigen Markdown-Ausgabe entfernt. Standard ist false.

**Rückgabe:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


Wenn true, werden leere oder nur aus Leerzeichen bestehende Zeilen aus der endgültigen Markdown-Ausgabe entfernt. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


Tritt für jedes Nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports auf. Ermöglicht die Anpassung, wie das Bild gespeichert und referenziert wird. Wenn nicht behandelt, wird das Bild lokal mit einem relativen Link gespeichert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown-Bild-Speicher-Ereignis. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Tritt für jedes SVG-Bild während des Markdown-Exports auf. Ermöglicht das Überschreiben des Standard-Speicherns und der Link-Generierung. Wenn nicht behandelt, wird das SVG lokal mit einem relativen Link gespeichert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown-SVG-Bild-Speicher-Ereignis. |