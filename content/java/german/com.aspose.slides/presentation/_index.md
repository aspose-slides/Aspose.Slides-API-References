---
title: Presentation
second_title: Aspose.Slides for Java API-Referenz
description: Stellt eine Microsoft PowerPoint-Präsentation dar.
type: docs
url: /de/com.aspose.slides/presentation/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Stellt eine Microsoft PowerPoint-Präsentation dar.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation();
>  try {
>      // Hole die erste Folie
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Füge eine Autoform vom Typ Linie hinzu
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Speichere die Präsentationsdatei.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Lade jede unterstützte Datei in Presentation, z.B. ppt, pptx, odp usw.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Speichere die Präsentationsdatei.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Presentation()](#Presentation--) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden Präsentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden Präsentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Präsentation gelesen wird. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Präsentation gelesen wird. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Liefert oder setzt das Datum und die Uhrzeit, die den Inhalt von datetime-Feldern ersetzen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Liefert oder setzt das Datum und die Uhrzeit, die den Inhalt von datetime-Feldern ersetzen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den aktuellen HeaderFooter-Manager zurück. |
| [getProtectionManager()](#getProtectionManager--) | Erhält den Manager der Berechtigungen für diese Präsentation. |
| [getSlides()](#getSlides--) | Gibt eine Liste aller in der Präsentation definierten Folien zurück. |
| [getSections()](#getSections--) | Gibt eine Liste aller in der Präsentation definierten Folienabschnitte zurück. |
| [getSlideSize()](#getSlideSize--) | Gibt das Foliengrößenobjekt zurück. |
| [getNotesSize()](#getNotesSize--) | Gibt das Notizfoliengrößenobjekt zurück. |
| [getLayoutSlides()](#getLayoutSlides--) | Gibt eine Liste aller in der Präsentation definierten Layoutfolien zurück. |
| [getMasters()](#getMasters--) | Gibt eine Liste aller in der Präsentation definierten Masterfolien zurück. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Gibt den Notiz-Master-Manager zurück. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Gibt den Handzettel-Master-Manager zurück. |
| [getFontsManager()](#getFontsManager--) | Gibt den Schriftarten-Manager zurück. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Gibt den Standard-Textstil für Formen zurück. |
| [getCommentAuthors()](#getCommentAuthors--) | Gibt die Sammlung von Kommentarautoren zurück. |
| [getDocumentProperties()](#getDocumentProperties--) | Gibt ein DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. |
| [getImages()](#getImages--) | Gibt die Sammlung aller Bilder in der Präsentation zurück. |
| [getAudios()](#getAudios--) | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. |
| [getVideos()](#getVideos--) | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Gibt die Diashow-Einstellungen für die Präsentation zurück. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet werden. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Präsentation zurück. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Gibt alle benutzerdefinierten Datenanteile in der Präsentation zurück. |
| [getVbaProject()](#getVbaProject--) | Liest oder setzt das VBA-Projekt mit Präsentationsmakros. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Liest oder setzt das VBA-Projekt mit Präsentationsmakros. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). |
| [getViewProperties()](#getViewProperties--) | Erhält die Ansichts-Eigenschaften für die gesamte Präsentation. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stellt die erste Foliennummer in der Präsentation dar |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stellt die erste Foliennummer in der Präsentation dar |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. |
| [getSlideById(long id)](#getSlideById-long-) | Gibt eine Folie, Masterfolie oder Layoutfolie anhand der Id zurück. |
| [getSourceFormat()](#getSourceFormat--) | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. |
| [getMasterTheme()](#getMasterTheme--) | Gibt das Master-Thema zurück. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format und zusätzlichen Optionen. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und zusätzlichen Optionen. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Gibt Bildobjekte für alle Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format und behält die Seitenzahlen bei. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format und behält die Seitenzahlen bei. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen in allen Folien. |
| [dispose()](#dispose--) | Gibt alle vom Presentation-Objekt verwendeten Ressourcen frei. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines Textes zurück. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenkette. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation hat eine leere Folie.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation hat eine leere Folie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Zusätzliche Ladeoptionen. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden Präsentation.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden Präsentation.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Zusätzliche Ladeoptionen. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Präsentation gelesen wird.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Eingabedatei. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Präsentation gelesen wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Eingabedatei. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Zusätzliche Ladeoptionen. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Liefert oder setzt Datum und Uhrzeit, die den Inhalt von datetime-Feldern ersetzen. Standardmäßig die Zeit der Erstellung dieses Presentation-Objekts. Lesen/Schreiben java.util.Date.

**Rückgabewert:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Liefert oder setzt Datum und Uhrzeit, die den Inhalt von datetime-Feldern ersetzen. Standardmäßig die Zeit der Erstellung dieses Presentation-Objekts. Lesen/Schreiben java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt ein Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Gibt den aktuellen HeaderFooter-Manager zurück. Nur lesbar [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible wird verwendet, um anzuzeigen, dass ein Folien-Fußzeilen-Platzhalter nicht vorhanden ist.
>      {
>          headerFooterManager.setFooterVisibility(true); // Methode SetFooterVisibility wird verwendet, um einen Folien-Fußzeilen-Platzhalter sichtbar zu machen.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible wird verwendet, um anzuzeigen, dass ein Folien-Seitenzahlen-Platzhalter nicht vorhanden ist.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Methode SetSlideNumberVisibility wird verwendet, um einen Folien-Seitenzahlen-Platzhalter sichtbar zu machen.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible wird verwendet, um anzuzeigen, dass ein Folien-Datum-Uhrzeit-Platzhalter nicht vorhanden ist.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Methode SetFooterVisibility wird verwendet, um einen Folien-Datum-Uhrzeit-Platzhalter sichtbar zu machen.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Methode SetFooterText wird verwendet, um Text im Folien-Fußzeilen-Platzhalter zu setzen.
>      headerFooterManager.setDateTimeText("Date and time text"); // Methode SetDateTimeText wird verwendet, um Text im Folien-Datum-Uhrzeit-Platzhalter zu setzen.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Methode SetFooterAndChildFootersVisibility wird verwendet, um die Masterfolie und alle untergeordneten Fußzeilen-Platzhalter sichtbar zu machen.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Methode SetSlideNumberAndChildSlideNumbersVisibility wird verwendet, um die Masterfolie und alle untergeordneten Seitenzahlen-Platzhalter sichtbar zu machen.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Methode SetDateTimeAndChildDateTimesVisibility wird verwendet, um die Masterfolie und alle untergeordneten Datum-Uhrzeit-Platzhalter sichtbar zu machen.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Methode SetFooterAndChildFootersText wird verwendet, um Text in der Masterfolie und allen untergeordneten Fußzeilen-Platzhaltern zu setzen.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Methode SetDateTimeAndChildDateTimesText wird verwendet, um Text in der Masterfolie und allen untergeordneten Datum-Uhrzeit-Platzhaltern zu setzen.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Erhält den Manager der Berechtigungen für diese Präsentation. Nur lesbar [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Rückgabewert:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Gibt eine Liste aller in der Präsentation definierten Folien zurück. Nur lesbar [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instanziiere die Presentation-Klasse, die die Präsentationsdatei darstellt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Setze die Hintergrundfarbe der ersten ISlide auf Blau
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Instanziiere die Presentation-Klasse, die die Präsentationsdatei darstellt
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Setze den Hintergrund mit einem Bild
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Setze das Bild
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Bild zur Bildsammlung der Präsentation hinzufügen
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Schreibe die Präsentation auf die Festplatte
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instanziiere die Presentation-Klasse, um die Quellpräsentationsdatei zu laden
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Kreis-Übergang auf Folie 1 anwenden
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Kamm-Übergang auf Folie 2 anwenden
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Schreibe die Präsentation auf die Festplatte
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instanziiere die Presentation-Klasse, die eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Kreis-Übergang auf Folie 1 anwenden
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Setze die Übergangszeit auf 3 Sekunden
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Kamm-Übergang auf Folie 2 anwenden
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Setze die Übergangszeit auf 5 Sekunden
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Zoom-Übergang auf Folie 3 anwenden
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Setze die Übergangszeit auf 7 Sekunden
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Schreibe die Präsentation auf die Festplatte
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Gibt eine Liste aller in der Präsentation definierten Folienabschnitte zurück. Nur lesbar [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 wird bei newSlide2 beendet und danach startet section2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Gibt das Foliengrößenobjekt zurück. Nur lesbar [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Setze die Foliengröße der erzeugten Präsentationen auf die der Quelle
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Methode SetSize wird verwendet, um die Foliengröße mit skaliertem Inhalt passend zu setzen
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Methode SetSize wird verwendet, um die Foliengröße mit maximaler Inhaltgröße zu setzen
>          // Speichere die Präsentation auf die Festplatte
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4-Papiergröße
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Gibt das Notizfoliengrößenobjekt zurück. Nur lesbar [INotesSize](../../com.aspose.slides/inotessize).

**Rückgabewert:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Gibt eine Liste aller in der Präsentation definierten Layoutfolien zurück. Nur lesbar [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Sie können über die Eigenschaft IMasterSlide.LayoutSlides auf die alternative API zum Hinzufügen/Einfügen/Entfernen/Klonen von Layoutfolien zugreifen.

**Rückgabewert:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Gibt eine Liste aller in der Präsentation definierten Masterfolien zurück. Nur lesbar [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabewert:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Gibt den Notiz-Master-Manager zurück. Nur lesbar [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Rückgabewert:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Gibt den Handzettel-Master-Manager zurück. Nur lesbar [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Rückgabewert:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Gibt den Schriftarten-Manager zurück. Nur lesbar [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Präsentation laden
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Quellfont laden, der ersetzt werden soll
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Präsentation speichern
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Gibt den Standard-Textstil für Formen zurück. Nur lesbar [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabewert:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Gibt die Sammlung von Kommentarautoren zurück. Nur lesbar [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Rückgabewert:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Gibt ein DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur lesbar [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Rückgabewert:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur lesbar [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // erstellt eine neue Präsentation, zu der das Bild hinzugefügt wird.
>  Presentation pres = new Presentation();
>  try
>  {
>      // angenommen, wir haben die große Bilddatei, die wir in die Präsentation einfügen wollen
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // fügen wir das Bild zur Präsentation hinzu - wir wählen das KeepLocked-Verhalten, weil wir
>          // NICHT beabsichtigen, auf die Datei "largeImage.png" zuzugreifen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // speichert die Präsentation. Während eine große Präsentation ausgegeben wird, bleibt der Speicherverbrauch
>          // gering während der gesamten Lebensdauer des pres-Objekts.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // fügt ein Bild zur Präsentation hinzu
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // erstellt ein Bildrahmen auf Folie 1 basierend auf dem zuvor hinzugefügten Bild
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur lesbar [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur Lesezugriff [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabewert:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Gibt die Bildschirmeinstellungen für die Präsentation zurück.

**Rückgabewert:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet werden. Nur Lesezugriff [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur Lesezugriff [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabewert:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Gibt alle benutzerdefinierten Datenparts in der Präsentation zurück. Nur Lesezugriff ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Iterate all custom XML Parts
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Liest oder setzt das VBA-Projekt mit Präsentations-Makros. Lese-/Schreibzugriff [IVbaProject](../../com.aspose.slides/ivbaproject).

**Rückgabewert:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Liest oder setzt das VBA-Projekt mit Präsentations-Makros. Lese-/Schreibzugriff [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Bietet einfachen Zugriff auf alle Hyperlinks in allen Präsentationsfolien (nicht in Master-, Layout- oder Notizfolien). Nur Lesezugriff [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabewert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Liest präsentationsweite Ansichtseigenschaften. Nur Lesezugriff [IViewProperties](../../com.aspose.slides/iviewproperties).

**Rückgabewert:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Stellt die erste Foliennummer in der Präsentation dar

**Rückgabewert:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Stellt die erste Foliennummer in der Präsentation dar

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


Gibt die Sammlung von Sensitivitätslabels zurück, die auf das Präsentationsdokument angewendet wurden. Nur Lesezugriff [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Gib die angewendeten Labels aus
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Füge das neue Label hinzu
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Hole die Sensitivitäts-Label-ID aus der Richtlinie
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Hole die Azure AD Site-ID aus der Richtlinie
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Gibt eine Slide, MasterSlide oder LayoutSlide anhand ihrer Id zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | long | Id einer Folie. |

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-Objekt.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur Lesezugriff [SourceFormat](../../com.aspose.slides/sourceformat).

**Rückgabewert:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Gibt das Master-Theme zurück. Nur Lesezugriff [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instanziiere ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| format | int | Format der exportierten Daten. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| format | int | Format der exportierten Daten. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format und mit zusätzlichen Optionen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Die XAML-Formatoptionen. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```


Gibt Bildobjekte für alle Folien einer Präsentation zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |

**Rückgabewert:**
com.aspose.slides.IImage[] – Bildobjekte.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |

**Rückgabewert:**
com.aspose.slides.IImage[] – Bildobjekte.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| scaleX | float | Der Wert, um den das Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den das Thumbnail in y-Richtung skaliert wird. |

**Rückgabewert:**
com.aspose.slides.IImage[] – Bildobjekte.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| scaleX | float | Der Wert, um den das Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den das Thumbnail in y-Richtung skaliert wird. |

**Rückgabewert:**
com.aspose.slides.IImage[] – Bildobjekte.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit der angegebenen Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Rückgabewert:**
com.aspose.slides.IImage[] – Bildobjekte.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit der angegebenen Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Rückgabewert:**
com.aspose.slides.IImage[] – Bildobjekte.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Speichert die angegebenen Folien einer Präsentation in einer Datei im angegebenen Format unter Beibehaltung der Seitenzahlen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Speichert die angegebenen Folien einer Präsentation in einer Datei im angegebenen Format unter Beibehaltung der Seitenzahlen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Speichert die angegebenen Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitenzahlen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Speichert die angegebenen Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitenzahlen.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Verbindet Abschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen in allen Folien.

### dispose() {#dispose--}
```
public final void dispose()
```


Gibt alle von diesem Presentation-Objekt verwendeten Ressourcen frei.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Gibt die übergeordnete Präsentation eines Textes zurück. Nur Lesezugriff [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // hervorheben aller einzelnen 'the'-Vorkommen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu markierende Text. |
| highlightColor | java.awt.Color | Die Farbe, mit der der Text hervorgehoben werden soll. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Hervorhebung aller einzelnen 'the'-Vorkommen
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu markierende Text. |
| highlightColor | java.awt.Color | Die Farbe, mit der der Text hervorgehoben werden soll. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Hervorhebung aller Wörter mit 10 oder mehr Zeichen
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um zu markierende Zeichenketten zu erhalten. |
| highlightColor | java.awt.Color | Die Farbe, mit der der Text hervorgehoben werden soll. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ersetze alle einzelnen 'the'-Vorkommen durch '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldText | java.lang.String | Die zu ersetzende Zeichenkette. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen von oldText ersetzt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenkette.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Ersetze alle Wörter mit 10 oder mehr Zeichen durch '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um zu ersetzende Zeichenketten zu erhalten. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen der zu ersetzenden Zeichenketten ersetzt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |