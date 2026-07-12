---
title: Presentation
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
>  // Instanziieren Sie ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation();
>  try {
>      // Erhalte die erste Folie
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
>  // Ladev eine beliebige unterstützte Datei in Presentation, z.B. ppt, pptx, odp usw.
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
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Präsentation gelesen wird. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Präsentation gelesen wird. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Ruft das Datum und die Uhrzeit ab oder legt sie fest, die den Inhalt von Datums-Zeit-Feldern ersetzen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Ruft das Datum und die Uhrzeit ab oder legt sie fest, die den Inhalt von Datums-Zeit-Feldern ersetzen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den aktuellen HeaderFooter-Manager zurück. |
| [getProtectionManager()](#getProtectionManager--) | Erhält den Manager der Berechtigungen für diese Präsentation. |
| [getSlides()](#getSlides--) | Gibt eine Liste aller in der Präsentation definierten Folien zurück. |
| [getSections()](#getSections--) | Gibt eine Liste aller in der Präsentation definierten Folienabschnitte zurück. |
| [getSlideSize()](#getSlideSize--) | Gibt ein Foliengrößen-Objekt zurück. |
| [getNotesSize()](#getNotesSize--) | Gibt ein Notizfoliengrößen-Objekt zurück. |
| [getLayoutSlides()](#getLayoutSlides--) | Gibt eine Liste aller in der Präsentation definierten Layout-Folien zurück. |
| [getMasters()](#getMasters--) | Gibt eine Liste aller in der Präsentation definierten Master-Folien zurück. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Gibt den Notiz-Master-Manager zurück. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Gibt den Handzettel-Master-Manager zurück. |
| [getFontsManager()](#getFontsManager--) | Gibt den Schriftarten-Manager zurück. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Gibt den Standard-Textstil für Formen zurück. |
| [getCommentAuthors()](#getCommentAuthors--) | Gibt die Sammlung von Kommentarautoren zurück. |
| [getDocumentProperties()](#getDocumentProperties--) | Gibt ein DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. |
| [getImages()](#getImages--) | Gibt die Sammlung aller Bilder in der Präsentation zurück. |
| [getAudios()](#getAudios--) | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. |
| [getVideos()](#getVideos--) | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Gibt die Bildschirmpräsentationseinstellungen für die Präsentation zurück. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet werden. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Präsentation zurück. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Gibt alle benutzerdefinierten Datenabschnitte in der Präsentation zurück. |
| [getVbaProject()](#getVbaProject--) | Erhält oder legt das VBA-Projekt mit Präsentations-Makros fest. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Erhält oder legt das VBA-Projekt mit Präsentations-Makros fest. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). |
| [getViewProperties()](#getViewProperties--) | Erhält die view-Eigenschaften der gesamten Präsentation. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stellt die erste Foliennummer in der Präsentation dar |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stellt die erste Foliennummer in der Präsentation dar |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. |
| [getSlideById(long id)](#getSlideById-long-) | Gibt eine Folie, Master-Folie oder Layout-Folie anhand ihrer Id zurück. |
| [getSourceFormat()](#getSourceFormat--) | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. |
| [getMasterTheme()](#getMasterTheme--) | Gibt das Master-Theme zurück. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format und zusätzlichen Optionen. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Speichert alle Folien einer Präsentation in eine Menge von Dateien, die XAML-Markup darstellen. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Gibt Bildobjekte für alle Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format und behält die Seitenzahlen bei. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format und behält die Seitenzahlen bei. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Läufe mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen in allen Folien. |
| [dispose()](#dispose--) | Gibt alle vom Presentation-Objekt genutzten Ressourcen frei. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines Textes zurück. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Markiert alle Treffer des Beispieltexts mit der angegebenen Farbe. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markiert alle Treffer des Beispieltexts mit der angegebenen Farbe. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Markiert alle Treffer des regulären Ausdrucks mit der angegebenen Farbe. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette. |

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

Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation.

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

Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation.

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

Ruft das Datum und die Uhrzeit ab oder legt sie fest, die den Inhalt von Datums-Zeit-Feldern ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. Lesen/Schreiben java.util.Date.

**Rückgabe:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Ruft das Datum und die Uhrzeit ab oder legt sie fest, die den Inhalt von Datums-Zeit-Feldern ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. Lesen/Schreiben java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Gibt den aktuellen HeaderFooter-Manager zurück. Nur-Lesen [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Eigenschaft IsFooterVisible wird verwendet, um anzuzeigen, dass ein Folienfußzeilen-Platzhalter nicht vorhanden ist.
>      {
>          headerFooterManager.setFooterVisibility(true); // Methode SetFooterVisibility wird verwendet, um einen Folienfußzeilen-Platzhalter sichtbar zu machen.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Eigenschaft IsSlideNumberVisible wird verwendet, um anzuzeigen, dass ein Folienseitennummer-Platzhalter nicht vorhanden ist.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Methode SetSlideNumberVisibility wird verwendet, um einen Folienseitennummer-Platzhalter sichtbar zu machen.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Eigenschaft IsDateTimeVisible wird verwendet, um anzuzeigen, dass ein Folien-Datum-Zeit-Platzhalter nicht vorhanden ist.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Methode SetFooterVisibility wird verwendet, um einen Folien-Datum-Zeit-Platzhalter sichtbar zu machen.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Methode SetFooterText wird verwendet, um Text für den Folienfußzeilen-Platzhalter festzulegen.
>      headerFooterManager.setDateTimeText("Date and time text"); // Methode SetDateTimeText wird verwendet, um Text für den Folien-Datum-Zeit-Platzhalter festzulegen.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Methode SetFooterAndChildFootersVisibility wird verwendet, um eine Master-Folie und alle untergeordneten Fußzeilen-Platzhalter sichtbar zu machen.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Methode SetSlideNumberAndChildSlideNumbersVisibility wird verwendet, um eine Master-Folie und alle untergeordneten Seitenzahlen-Platzhalter sichtbar zu machen.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Methode SetDateTimeAndChildDateTimesVisibility wird verwendet, um eine Master-Folie und alle untergeordneten Datum-Zeit-Platzhalter sichtbar zu machen.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Methode SetFooterAndChildFootersText wird verwendet, um Text für die Master-Folie und alle untergeordneten Fußzeilen-Platzhalter festzulegen.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Methode SetDateTimeAndChildDateTimesText wird verwendet, um Text für die Master-Folie und alle untergeordneten Datum-Zeit-Platzhalter festzulegen.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Erhält den Manager der Berechtigungen für diese Präsentation. Nur-Lesen [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Rückgabe:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Gibt eine Liste aller in der Präsentation definierten Folien zurück. Nur-Lesen [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instanziiere die Presentation-Klasse, die die Präsentationsdatei repräsentiert
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
>  // Instanziiere die Presentation-Klasse, die die Präsentationsdatei repräsentiert
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Setze den Hintergrund mit Bild
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Setze das Bild
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Bild zur Bildersammlung der Präsentation hinzufügen
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
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
>      // Wende Kreis-Übergang auf Folie 1 an
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Wende Kamm-Übergang auf Folie 2 an
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
>  // Instanziiere die Presentation-Klasse, die eine Präsentationsdatei repräsentiert
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Wende Kreis-Übergang auf Folie 1 an
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Setze die Übergangszeit auf 3 Sekunden
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Wende Kamm-Übergang auf Folie 2 an
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Setze die Übergangszeit auf 5 Sekunden
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Wende Zoom-Übergang auf Folie 3 an
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


**Rückgabe:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Gibt eine Liste aller in der Präsentation definierten Folienabschnitte zurück. Nur-Lesen [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 wird bei newSlide2 beendet und danach beginnt section2
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


**Rückgabe:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Gibt ein Foliengrößen-Objekt zurück. Nur-Lesen [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei repräsentiert
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Setze die Foliengröße der erzeugten Präsentationen auf die der Quelle
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Methode SetSize wird verwendet, um die Foliengröße mit skalierter Inhalt anzupassen, um die Passform zu gewährleisten
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Methode SetSize wird verwendet, um die Foliengröße mit maximaler Inhaltgröße festzulegen
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


**Rückgabe:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Gibt ein Notizfoliengrößen-Objekt zurück. Nur-Lesen [INotesSize](../../com.aspose.slides/inotessize).

**Rückgabe:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Gibt eine Liste aller in der Präsentation definierten Layout-Folien zurück. Nur-Lesen [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Sie können über die Eigenschaft IMasterSlide.LayoutSlides auf die alternative API zum Hinzufügen/Einfügen/Entfernen/Klonen von Layout-Folien zugreifen.

**Rückgabe:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Gibt eine Liste aller in der Präsentation definierten Master-Folien zurück. Nur-Lesen [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instanziiere die Presentation-Klasse, die die Präsentationsdatei repräsentiert
>  Presentation pres = new Presentation();
>  try
>  {
>      // Setze die Hintergrundfarbe der Master-ISlide auf Waldgrün
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Schreibe die Präsentation auf die Festplatte
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instanziiere die Presentation-Klasse, die die Präsentationsdatei repräsentiert
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Versuche, nach Layout-Foliensatztyp zu suchen
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Der Fall, dass eine Präsentation keinen bestimmten Layouttyp enthält.
>          // Die Präsentationsdatei enthält nur leere und benutzerdefinierte Layouttypen.
>          // Aber Layoutfolien mit benutzerdefinierten Typen haben unterschiedliche Foliennamen,
>          // wie "Title", "Title and Content", usw. Und es ist möglich, diese
>          // Namen für die Auswahl von Layoutfolien zu verwenden.
>          // Außerdem ist es möglich, die Menge von Platzhalterformen zu verwenden. Zum Beispiel,
>          // Titelfolie sollte nur den Title-Platzhaltertyp haben, usw.
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
>      // Hinzufügen einer leeren Folie mit dem hinzugefügten Layout
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Präsentation speichern
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Gibt den Notiz-Master-Manager zurück. Nur-Lesen [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Rückgabe:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Gibt den Handzettel-Master-Manager zurück. Nur-Lesen [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Rückgabe:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Gibt den Schriftarten-Manager zurück. Nur-Lesen [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Präsentation laden
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Quellschriftart zum Ersetzen laden
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


**Rückgabe:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Gibt den Standard-Textstil für Formen zurück. Nur-Lesen [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Gibt die Sammlung von Kommentarautoren zurück. Nur-Lesen [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Rückgabe:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Gibt ein DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur-Lesen [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Rückgabe:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur-Lesen [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // erstellt eine neue Präsentation, zu der das Bild hinzugefügt wird.
>  Presentation pres = new Presentation();
>  try
>  {
>      // angenommen, wir haben die große Bilddatei, die wir in die Präsentation einfügen möchten
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // lassen Sie uns das Bild zur Präsentation hinzufügen - wir wählen das KeepLocked-Verhalten, weil wir
>          // NICHT beabsichtigen, auf die "largeImage.png"-Datei zuzugreifen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // speichert die Präsentation. Während eine große Präsentation ausgegeben wird, bleibt der
>          // speicherverbrauch gering während des gesamten Lebenszyklus des pres-Objekts
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Bild zur Präsentation hinzufügen
>          IPPImage image = pres.getImages().addImage(fos);
>          // erstellt ein Bildrahmen auf Folie 1 basierend auf dem zuvor hinzugefügten Bild
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur-Lesen [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur-Lesen [IVideoCollection](../../com.aspose.slides/ivideocollection).

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

**Rückgabe:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Gibt die Bildschirmpräsentationseinstellungen für die Präsentation zurück.

**Rückgabe:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet werden. Nur-Lesen [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**Rückgabe:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur-Lesen [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabe:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Gibt alle benutzerdefinierten Datenabschnitte in der Präsentation zurück. Nur-Lesen ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Durchlaufen aller benutzerdefinierten XML-Teile
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


**Rückgabe:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Erhält oder legt das VBA-Projekt mit Präsentations-Makros fest. Lesen/Schreiben [IVbaProject](../../com.aspose.slides/ivbaproject).

**Rückgabe:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Erhält oder legt das VBA-Projekt mit Präsentations-Makros fest. Lesen/Schreiben [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). Nur-Lesen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabe:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Erhält die view-Eigenschaften der gesamten Präsentation. Nur-Lesen [IViewProperties](../../com.aspose.slides/iviewproperties).

**Rückgabe:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Stellt die erste Foliennummer in der Präsentation dar

**Rückgabe:**
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

Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. Nur-Lesen [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Drucke die angewendeten Labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Füge das neue Label hinzu
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Hole die Sensitivitäts-Label-ID aus der Richtlinie
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Hole den Azure AD-Site-Identifikator aus der Richtlinie
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Gibt eine Folie, Master-Folie oder Layout-Folie anhand ihrer Id zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | long | Id einer Folie. |

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-Objekt.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur-Lesen [SourceFormat](../../com.aspose.slides/sourceformat).

**Rückgabe:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Gibt das Master-Theme zurück. Nur-Lesen [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instanziiere ein Präsentationsobjekt, das eine Präsentationsdatei repräsentiert
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


**Rückgabe:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| format | int | Format der exportierten Daten. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| format | int | Format der exportierten Daten. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format und zusätzlichen Optionen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen.

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

Speichert alle Folien einer Präsentation in eine Menge von Dateien, die XAML-Markup darstellen.

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

**Rückgabe:**
com.aspose.slides.IImage[] - Bildobjekte.

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

**Rückgabe:**
com.aspose.slides.IImage[] - Bildobjekte.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| scaleX | float | Der Wert, um den das Thumbnail in X-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den das Thumbnail in Y-Richtung skaliert wird. |

**Rückgabe:**
com.aspose.slides.IImage[] - Bildobjekte.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| scaleX | float | Der Wert, um den das Thumbnail in X-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den das Thumbnail in Y-Richtung skaliert wird. |

**Rückgabe:**
com.aspose.slides.IImage[] - Bildobjekte.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit angegebenen Abmessungen zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabe:**
com.aspose.slides.IImage[] - Bildobjekte.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit angegebenen Abmessungen zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabe:**
com.aspose.slides.IImage[] - Bildobjekte.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format und behält die Seitenzahlen bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format und behält die Seitenzahlen bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei.

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

Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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

Verbindet Läufe mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen in allen Folien.

### dispose() {#dispose--}
```
public final void dispose()
```

Gibt alle vom Presentation-Objekt genutzten Ressourcen frei.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines Textes zurück. Nur-Lesen [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Markiert alle Treffer des Beispieltexts mit der angegebenen Farbe.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markiert alle einzelnen 'the'-Vorkommen
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
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text markiert wird. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markiert alle Treffer des Beispieltexts mit der angegebenen Farbe.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // markiert alle einzelnen 'the'-Vorkommen
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
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text markiert wird. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Markiert alle Treffer des regulären Ausdrucks mit der angegebenen Farbe.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // markiert alle Wörter mit 10 oder mehr Zeichen
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck, dessen Treffer hervorgehoben werden sollen. |
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text markiert wird. |
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
>      // Ersetzt alle einzelnen 'the'-Vorkommen durch '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldText | java.lang.String | Der zu ersetzende String. |
| newText | java.lang.String | Der String, der alle Vorkommen von oldText ersetzt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Ersetzt alle Wörter mit 10 oder mehr Zeichen durch '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck, dessen Treffer ersetzt werden sollen. |
| newText | java.lang.String | Der String, der alle Vorkommen des zu ersetzenden Strings ersetzt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |