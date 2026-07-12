---
title: IPresentation
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getCurrentDateTime()](#getCurrentDateTime--) | Gibt Datum und Uhrzeit zurück oder setzt sie, die den Inhalt von datetime-Feldern ersetzen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Gibt Datum und Uhrzeit zurück oder setzt sie, die den Inhalt von datetime-Feltern ersetzen. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Präsentation zurück. |
| [getProtectionManager()](#getProtectionManager--) | Liefert den Manager der Berechtigungen für diese Präsentation. |
| [getSlides()](#getSlides--) | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. |
| [getSections()](#getSections--) | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. |
| [getSlideSize()](#getSlideSize--) | Gibt ein Foliengrößen-Objekt zurück. |
| [getNotesSize()](#getNotesSize--) | Gibt ein Notizfolien-Größen-Objekt zurück. |
| [getLayoutSlides()](#getLayoutSlides--) | Gibt eine Liste aller Layout-Folien zurück, die in der Präsentation definiert sind. |
| [getMasters()](#getMasters--) | Gibt eine Liste aller Master-Folien zurück, die in der Präsentation definiert sind. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Gibt den Notizmaster-Manager zurück. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Gibt den Handzettel-Master-Manager zurück. |
| [getFontsManager()](#getFontsManager--) | Gibt den Schriftarten-Manager zurück. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Gibt den Standardschrift-Stil für Formen zurück. |
| [getCommentAuthors()](#getCommentAuthors--) | Gibt die Sammlung der Kommentarautoren zurück. |
| [getDocumentProperties()](#getDocumentProperties--) | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. |
| [getImages()](#getImages--) | Gibt die Sammlung aller Bilder in der Präsentation zurück. |
| [getAudios()](#getAudios--) | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. |
| [getVideos()](#getVideos--) | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Präsentation zurück. |
| [getVbaProject()](#getVbaProject--) | Liefert das VBA-Projekt mit Präsentations-Makros. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Liefert das VBA-Projekt mit Präsentations-Makros. |
| [getSourceFormat()](#getSourceFormat--) | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. |
| [getMasterTheme()](#getMasterTheme--) | Gibt das Master-Design der Präsentation zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Ermöglicht einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). |
| [getViewProperties()](#getViewProperties--) | Liefert die Ansichts-Eigenschaften der gesamten Präsentation. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stellt die erste Foliennummer in der Präsentation dar. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stellt die erste Foliennummer in der Präsentation dar. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Gibt alle benutzerdefinierten Daten-Teile in der Präsentation zurück. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Gibt die Sammlung der Signaturen zurück, die zum Signieren der Präsentation verwendet werden. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gibt die Sammlung der Sensitivitäts-Labels zurück, die auf das Präsentationsdokument angewendet wurden. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format und mit zusätzlichen Optionen. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Speichert angegebene Folien einer Präsentation in einer Datei im angegebenen Format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Speichert angegebene Folien einer Präsentation in einer Datei im angegebenen Format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Gibt Thumbnail-IImage-Objekte für die angegebenen Folien einer Präsentation zurück. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück. |
| [getSlideById(long id)](#getSlideById-long-) | Gibt eine Slide, MasterSlide oder LayoutSlide anhand der Id zurück. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Textabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen in allen Folien. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Gibt Datum und Uhrzeit zurück oder setzt sie, die den Inhalt von datetime-Feldern ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. Lesen/Schreiben java.util.Date.

**Rückgabewert:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Gibt Datum und Uhrzeit zurück oder setzt sie, die den Inhalt von datetime-Feldern ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. Lesen/Schreiben java.util.Date.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Präsentation zurück. Nur lesbar [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Rückgabewert:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Liefert den Manager der Berechtigungen für diese Präsentation. Nur lesbar [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Rückgabewert:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur lesbar [ISlideCollection](../../com.aspose.slides/islidecollection).

**Rückgabewert:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Nur lesbar [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Rückgabewert:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Gibt ein Foliengrößen-Objekt zurück. Nur lesbar [ISlideSize](../../com.aspose.slides/islidesize).

**Rückgabewert:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Gibt ein Notizfolien-Größen-Objekt zurück. Nur lesbar [INotesSize](../../com.aspose.slides/inotessize).

**Rückgabewert:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Gibt eine Liste aller Layout-Folien zurück, die in der Präsentation definiert sind. Nur lesbar [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Sie können über die Eigenschaft IMasterSlide.LayoutSlides auf alternative APIs zum Hinzufügen/Einfügen/Entfernen/Klonen von Layout-Folien zugreifen.

**Rückgabewert:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Gibt eine Liste aller Master-Folien zurück, die in der Präsentation definiert sind. Nur lesbar [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Rückgabewert:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Gibt den Notizmaster-Manager zurück. Nur lesbar [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Rückgabewert:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Gibt den Handzettel-Master-Manager zurück. Nur lesbar [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Rückgabewert:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Gibt den Schriftarten-Manager zurück. Nur lesbar [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Rückgabewert:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Gibt den Standardschrift-Stil für Formen zurück. Nur lesbar [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabewert:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Gibt die Sammlung der Kommentarautoren zurück. Nur lesbar [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Rückgabewert:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur lesbar [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Rückgabewert:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur lesbar [IImageCollection](../../com.aspose.slides/iimagecollection).

**Rückgabewert:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur lesbar [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Rückgabewert:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur lesbar [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Rückgabewert:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur lesbar [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabewert:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Liefert das VBA-Projekt mit Präsentations-Makros. Lesen/Schreiben [IVbaProject](../../com.aspose.slides/ivbaproject).

**Rückgabewert:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Liefert das VBA-Projekt mit Präsentations-Makros. Lesen/Schreiben [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur lesbar [SourceFormat](../../com.aspose.slides/sourceformat).

**Rückgabewert:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Gibt das Master-Design der Präsentation zurück. Nur lesbar [IMasterTheme](../../com.aspose.slides/imastertheme).

**Rückgabewert:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Ermöglicht einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). Nur lesbar [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabewert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Liefert die Ansichts-Eigenschaften der gesamten Präsentation. Nur lesbar [IViewProperties](../../com.aspose.slides/iviewproperties).

**Rückgabewert:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Stellt die erste Foliennummer in der Präsentation dar. Lesen/Schreiben int.

**Rückgabewert:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Stellt die erste Foliennummer in der Präsentation dar. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Gibt alle benutzerdefinierten Daten-Teile in der Präsentation zurück. Nur lesbar ICustomXmlPart[].

**Rückgabewert:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Gibt die Sammlung der Signaturen zurück, die zum Signieren der Präsentation verwendet werden. Nur lesbar [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```java
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

**Rückgabewert:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Gibt die Sammlung der Sensitivitäts-Labels zurück, die auf das Präsentationsdokument angewendet wurden. Nur lesbar [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```java
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Gibt die angewendeten Labels aus
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Fügt das neue Label hinzu
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Holt die Sensitivitäts-Label-Id aus der Richtlinie
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Holt die Azure-AD-Site-Kennung aus der Richtlinie
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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| format | int | Format der zu exportierenden Daten. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| format | int | Format der zu exportierenden Daten. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format und mit zusätzlichen Optionen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| format | int | Format der zu exportierenden Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| format | int | Format der zu exportierenden Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Speichert angegebene Folien einer Präsentation in einer Datei im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der zu exportierenden Daten. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Speichert angegebene Folien einer Präsentation in einer Datei im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fname | java.lang.String | Pfad zur zu erstellenden Datei. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der zu exportierenden Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der zu exportierenden Daten. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ausgabestream. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| format | int | Format der zu exportierenden Daten. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Zusätzliche Formatoptionen. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen.

--------------------

> ```java
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
public abstract IImage[] getImages(IRenderingOptions options)
```

Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |

**Rückgabewert:**
com.aspose.slides.IImage[] - IImage-Objekte.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Gibt Thumbnail-IImage-Objekte für die angegebenen Folien einer Präsentation zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |

**Rückgabewert:**
com.aspose.slides.IImage[] - IImage-Objekte.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| scaleX | float | Der Skalierungswert in X-Richtung. |
| scaleY | float | Der Skalierungswert in Y-Richtung. |

**Rückgabewert:**
com.aspose.slides.IImage[] - Bitmap-Objekte.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| scaleX | float | Der Skalierungswert in X-Richtung. |
| scaleY | float | Der Skalierungswert in Y-Richtung. |

**Rückgabewert:**
com.aspose.slides.IImage[] - IImage-Objekte.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit angegebener Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabewert:**
com.aspose.slides.IImage[] - IImage-Objekte.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| slides | int[] | Array mit Folienpositionen, beginnend bei 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabewert:**
com.aspose.slides.IImage[] - IImage-Objekte.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Gibt eine Slide, MasterSlide oder LayoutSlide anhand der Id zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | long | Id einer Folie. |

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-Objekt.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Verbindet Textabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen in allen Folien.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // hebt alle einzelnen 'the'-Vorkommen hervor
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorhebende Text. |
| highlightColor | java.lang.Integer | Die Farbe zum Hervorheben des Textes. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // hebt alle einzelnen 'the'-Vorkommen hervor
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorhebende Text. |
| highlightColor | java.lang.Integer | Die Farbe zum Hervorheben des Textes. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text-Suchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // hebt alle einzelnen 'the'-Vorkommen hervor
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck zum Ermitteln der zu hervorhebenden Zeichenketten. |
| highlightColor | java.lang.Integer | Die Farbe zum Hervorheben des Textes. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man eine angegebene Zeichenkette durch eine andere angegebene Zeichenkette ersetzt.
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
| oldText | java.lang.String | Die zu ersetzende Zeichenkette. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen von oldText ersetzt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text-Suchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.

--------------------

> ``` 
> The following code sample shows how to replace text using regular expression with the specified string.
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
| regex | java.util.regex.Pattern | Der reguläre Ausdruck zum Ermitteln der zu ersetzenden Zeichenketten. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen der zu ersetzenden Zeichenketten ersetzt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |