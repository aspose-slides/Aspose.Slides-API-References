---
title: IPresentation
second_title: Aspose.Slides für Java API-Referenz
description: Präsentationsdokument
type: docs
url: /de/com.aspose.slides/ipresentation/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Präsentationsdokument
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt von Datumszeitfeldern ersetzen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt von Datumszeitfeldern ersetzen. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Präsentation zurück. |
| [getProtectionManager()](#getProtectionManager--) | Gibt den Manager der Berechtigungen für diese Präsentation zurück. |
| [getSlides()](#getSlides--) | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. |
| [getSections()](#getSections--) | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. |
| [getSlideSize()](#getSlideSize--) | Gibt ein Foliengrößenobjekt zurück. |
| [getNotesSize()](#getNotesSize--) | Gibt ein Notizfoliengrößenobjekt zurück. |
| [getLayoutSlides()](#getLayoutSlides--) | Gibt eine Liste aller Layoutfolien zurück, die in der Präsentation definiert sind. |
| [getMasters()](#getMasters--) | Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Gibt den Notizmaster-Manager zurück. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Gibt den Handout-Master-Manager zurück. |
| [getFontsManager()](#getFontsManager--) | Gibt den Schriftarten-Manager zurück. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Gibt den Standard-Textstil für Formen zurück. |
| [getCommentAuthors()](#getCommentAuthors--) | Gibt die Sammlung der Kommentarautoren zurück. |
| [getDocumentProperties()](#getDocumentProperties--) | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. |
| [getImages()](#getImages--) | Gibt die Sammlung aller Bilder in der Präsentation zurück. |
| [getAudios()](#getAudios--) | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. |
| [getVideos()](#getVideos--) | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Präsentation zurück. |
| [getVbaProject()](#getVbaProject--) | Gibt das VBA-Projekt mit Präsentationsmakros zurück. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Gibt das VBA-Projekt mit Präsentationsmakros zurück. |
| [getSourceFormat()](#getSourceFormat--) | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. |
| [getMasterTheme()](#getMasterTheme--) | Gibt das Master-Thema der Präsentation zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). |
| [getViewProperties()](#getViewProperties--) | Gibt die präsentationsweiten Ansichtseigenschaften zurück. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stellt die erste Foliennummer in der Präsentation dar. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stellt die erste Foliennummer in der Präsentation dar. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Gibt alle benutzerdefinierten Datenparts in der Präsentation zurück. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Gibt die Sammlung der Signaturen zurück, die zum Signieren der Präsentation verwendet werden. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gibt die Sammlung der Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format und zusätzlichen Optionen. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und zusätzlichen Optionen. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Speichert alle Folien einer Präsentation in ein Satz von Dateien, die XAML-Markup repräsentieren. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Gibt Thumbnail-IImage-Objekte für die angegebenen Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit benutzerdefinierten Skalierungen zurück. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit benutzerdefinierten Skalierungen zurück. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück. |
| [getSlideById(long id)](#getSlideById-long-) | Gibt ein Slide, MasterSlide oder LayoutSlide anhand der Id zurück. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Läufe mit gleicher Formatierung in allen Absätzen in allen akzeptablen Formen in allen Folien. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette. |
| [refreshChartsData()](#refreshChartsData--) | Lädt die Daten für alle Diagramme in der Präsentation aus ihren Quell-Arbeitsmappen neu. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Lädt die Daten für alle Diagramme in der Präsentation aus ihren Quell-Arbeitsmappen neu. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt von Datumszeitfeldern ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. **Lese/Schreib** java.util.Date.

**Rückgabe:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt von Datumszeitfeldern ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. **Lese/Schreib** java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Präsentation zurück. **Nur-Lesen** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Rückgabe:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Gibt den Manager der Berechtigungen für diese Präsentation zurück. **Nur-Lesen** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Rückgabe:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. **Nur-Lesen** [ISlideCollection](../../com.aspose.slides/islidecollection).

**Rückgabe:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. **Nur-Lesen** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Rückgabe:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Gibt ein Foliengrößenobjekt zurück. **Nur-Lesen** [ISlideSize](../../com.aspose.slides/islidesize).

**Rückgabe:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Gibt ein Notizfoliengrößenobjekt zurück. **Nur-Lesen** [INotesSize](../../com.aspose.slides/inotessize).

**Rückgabe:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Gibt eine Liste aller Layoutfolien zurück, die in der Präsentation definiert sind. **Nur-Lesen** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Sie können über die Eigenschaft IMasterSlide.LayoutSlides auf alternative APIs zum Hinzufügen/Einfügen/Entfernen/Klonen von Layoutfolien zugreifen.

**Rückgabe:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. **Nur-Lesen** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Rückgabe:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Gibt den Notizmaster-Manager zurück. **Nur-Lesen** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Rückgabe:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Gibt den Handout-Master-Manager zurück. **Nur-Lesen** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Rückgabe:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Gibt den Schriftarten-Manager zurück. **Nur-Lesen** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Rückgabe:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Gibt den Standard-Textstil für Formen zurück. **Nur-Lesen** [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabe:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Gibt die Sammlung der Kommentarautoren zurück. **Nur-Lesen** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Rückgabe:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. **Nur-Lesen** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Rückgabe:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Gibt die Sammlung aller Bilder in der Präsentation zurück. **Nur-Lesen** [IImageCollection](../../com.aspose.slides/iimagecollection).

**Rückgabe:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. **Nur-Lesen** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Rückgabe:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. **Nur-Lesen** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Rückgabe:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Präsentation zurück. **Nur-Lesen** [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabe:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Gibt das VBA-Projekt mit Präsentationsmakros zurück. **Lese/Schreib** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Rückgabe:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Setzt das VBA-Projekt mit Präsentationsmakros. **Lese/Schreib** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. **Nur-Lesen** [SourceFormat](../../com.aspose.slides/sourceformat).

**Rückgabe:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Gibt das Master-Thema der Präsentation zurück. **Nur-Lesen** [IMasterTheme](../../com.aspose.slides/imastertheme).

**Rückgabe:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). **Nur-Lesen** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabe:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Gibt die präsentationsweiten Ansichtseigenschaften zurück. **Nur-Lesen** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Rückgabe:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Stellt die erste Foliennummer in der Präsentation dar. **Lese/Schreib** int.

**Rückgabe:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Setzt die erste Foliennummer in der Präsentation. **Lese/Schreib** int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Gibt alle benutzerdefinierten Datenparts in der Präsentation zurück. **Nur-Lesen** ICustomXmlPart[].

**Rückgabe:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Gibt die Sammlung der Signaturen zurück, die zum Signieren der Präsentation verwendet werden. **Nur-Lesen** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Gibt die Sammlung der Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden. **Nur-Lesen** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Die angewendeten Labels ausgeben
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Neues Label hinzufügen
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Sensitivitäts-Label-ID aus der Richtlinie abrufen
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Azure AD Site-ID aus der Richtlinie abrufen
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| format | int | Format der exportierten Daten. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| format | int | Format der exportierten Daten. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
Saves all slides of a presentation to a file with the specified format and with additional options.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```


Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```


Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```


Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur erstellten Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```


Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der exportierten Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Die XAML-Formatoptionen. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```


Gibt Thumbnail Image-Objekte für alle Folien einer Präsentation zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```


Gibt Thumbnail IImage-Objekte für die angegebenen Folien einer Präsentation zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Gibt Thumbnail Image-Objekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| scaleX | float | Der Wert, um den das Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den das Thumbnail in y-Richtung skaliert wird. |

**Returns:**
com.aspose.slides.IImage[] - Bitmap objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Gibt Thumbnail Image-Objekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| scaleX | float | Der Wert, um den das Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den das Thumbnail in y-Richtung skaliert wird. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Gibt Thumbnail Image-Objekte für alle Folien einer Präsentation mit der angegebenen Größe zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Gibt Thumbnail Image-Objekte für die angegebenen Folien einer Präsentation mit der angegebenen Größe zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```


Gibt eine Slide, MasterSlide oder LayoutSlide anhand der Id zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | long | Id einer Folie. |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Führt Textabschnitte mit gleicher Formatierung in allen Absätzen in allen geeigneten Formen in allen Folien zusammen.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```


Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // Hervorheben aller einzelnen 'the'-Vorkommen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorgehobene Text. |
| highlightColor | java.awt.Color | Die Farbe, mit der der Text hervorgehoben wird. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Hebt alle Vorkommen des Beispieltexts mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // Hervorheben aller einzelnen 'the'-Vorkommen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorgehobene Text. |
| highlightColor | java.awt.Color | Die Farbe, mit der der Text hervorgehoben wird. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuche-Optionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // Hervorheben aller einzelnen 'the'-Vorkommen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um die zu hervorhebenden Zeichenketten zu ermitteln. |
| highlightColor | java.awt.Color | Die Farbe, mit der der Text hervorgehoben wird. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
>      // Ersetzen aller einzelnen 'the'-Vorkommen durch '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldText | java.lang.String | Die zu ersetzende Zeichenkette. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen von oldText ersetzen soll. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuche-Optionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenkette.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ersetzen aller einzelnen 'the'-Vorkommen durch '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um die zu ersetzenden Zeichenketten zu ermitteln. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen der zu ersetzenden Zeichenketten ersetzen soll. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```


Lädt die Daten für alle Diagramme in der Präsentation aus ihren Quellarbeitsmappen neu.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public abstract void refreshChartsData(boolean skipFailedCharts)
```


Lädt die Daten für alle Diagramme in der Präsentation aus ihren Quellarbeitsmappen neu.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| skipFailedCharts | boolean | Bestimmt, ob der Aktualisierungsvorgang fortgesetzt wird, wenn ein Diagramm nicht aktualisiert werden kann. Wenn true, werden Diagramme, die eine Ausnahme auslösen, übersprungen; andernfalls wird die Ausnahme weitergereicht. |