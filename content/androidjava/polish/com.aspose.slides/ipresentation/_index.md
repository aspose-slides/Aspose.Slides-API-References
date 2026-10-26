---
title: IPresentation
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Dokument prezentacji
type: docs
url: /pl/com.aspose.slides/ipresentation/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Dokument prezentacji
## Metody

| Metoda | Opis |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera nagłówka i stopki prezentacji. |
| [getProtectionManager()](#getProtectionManager--) | Pobiera menedżera uprawnień dla tej prezentacji. |
| [getSlides()](#getSlides--) | Zwraca listę wszystkich slajdów, które są zdefiniowane w prezentacji. |
| [getSections()](#getSections--) | Zwraca listę wszystkich sekcji slajdów, które są zdefiniowane w prezentacji. |
| [getSlideSize()](#getSlideSize--) | Zwraca obiekt rozmiaru slajdu. |
| [getNotesSize()](#getNotesSize--) | Zwraca obiekt rozmiaru slajdu notatek. |
| [getLayoutSlides()](#getLayoutSlides--) | Zwraca listę wszystkich slajdów układu, które są zdefiniowane w prezentacji. |
| [getMasters()](#getMasters--) | Zwraca listę wszystkich slajdów master, które są zdefiniowane w prezentacji. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Zwraca menedżera notatek master. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Zwraca menedżera master wersji rozdania. |
| [getFontsManager()](#getFontsManager--) | Zwraca menedżera czcionek. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Zwraca domyślny styl tekstu dla kształtów. |
| [getCommentAuthors()](#getCommentAuthors--) | Zwraca kolekcję autorów komentarzy. |
| [getDocumentProperties()](#getDocumentProperties--) | Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu. |
| [getImages()](#getImages--) | Zwraca kolekcję wszystkich obrazów w prezentacji. |
| [getAudios()](#getAudios--) | Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. |
| [getVideos()](#getVideos--) | Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. |
| [getCustomData()](#getCustomData--) | Zwraca niestandardowe dane prezentacji. |
| [getVbaProject()](#getVbaProject--) | Pobiera projekt VBA z makrami prezentacji. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Pobiera projekt VBA z makrami prezentacji. |
| [getSourceFormat()](#getSourceFormat--) | Zwraca informację o formacie, z którego załadowano prezentację. |
| [getMasterTheme()](#getMasterTheme--) | Zwraca motyw master prezentacji. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Zapewnia łatwy dostęp do wszystkich hiperłączy zawartych we wszystkich slajdach prezentacji (nie w slajdach master, układu, notatek). |
| [getViewProperties()](#getViewProperties--) | Pobiera właściwości widoku całej prezentacji. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Reprezentuje numer pierwszego slajdu w prezentacji. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Reprezentuje numer pierwszego slajdu w prezentacji. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Zwraca wszystkie niestandardowe części danych w prezentacji. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Zwraca kolekcję podpisów użytych do podpisania prezentacji. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie z dodatkowymi opcjami. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie z dodatkowymi opcjami. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Zapisuje wybrane slajdy prezentacji do pliku w określonym formacie. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Zapisuje wybrane slajdy prezentacji do pliku w określonym formacie z dodatkowymi opcjami. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Zapisuje wybrane slajdy prezentacji do strumienia w określonym formacie. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Zapisuje wybrane slajdy prezentacji do strumienia w określonym formacie z dodatkowymi opcjami. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znacznik XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Zwraca obiekty Miniatury obrazu dla wszystkich slajdów prezentacji. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Zwraca obiekty Miniatury IImage dla określonych slajdów prezentacji. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Zwraca obiekty Miniatury obrazu dla wszystkich slajdów prezentacji z niestandardowym skalowaniem. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Zwraca obiekty Miniatury obrazu dla określonych slajdów prezentacji z niestandardowym skalowaniem. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Zwraca obiekty Miniatury obrazu dla wszystkich slajdów prezentacji o określonym rozmiarze. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Zwraca obiekty Miniatury obrazu dla określonych slajdów prezentacji o określonym rozmiarze. |
| [getSlideById(long id)](#getSlideById-long-) | Zwraca Slide, MasterSlide lub LayoutSlide według Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty z tym samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach we wszystkich slajdach. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Wyróżnia wszystkie dopasowania wyrażenia regularnego podanym kolorem. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zamienia wszystkie wystąpienia określonego tekstu na inny określony tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Zamienia wszystkie dopasowania wyrażenia regularnego na określony ciąg znaków. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. Domyślnie czas utworzenia tego obiektu Presentation. Odczyt/zapis java.util.Date.

**Zwraca:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. Domyślnie czas utworzenia tego obiektu Presentation. Odczyt/zapis java.util.Date.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżera nagłówka i stopki prezentacji. Tylko do odczytu [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Zwraca:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Pobiera menedżera uprawnień dla tej prezentacji. Tylko do odczytu [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Zwraca:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Zwraca listę wszystkich slajdów, które są zdefiniowane w prezentacji. Tylko do odczytu [ISlideCollection](../../com.aspose.slides/islidecollection).

**Zwraca:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Zwraca listę wszystkich sekcji slajdów, które są zdefiniowane w prezentacji. Tylko do odczytu [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Zwraca:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Zwraca obiekt rozmiaru slajdu. Tylko do odczytu [ISlideSize](../../com.aspose.slides/islidesize).

**Zwraca:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Zwraca obiekt rozmiaru slajdu notatek. Tylko do odczytu [INotesSize](../../com.aspose.slides/inotessize).

**Zwraca:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Zwraca listę wszystkich slajdów układu, które są zdefiniowane w prezentacji. Tylko do odczytu [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Można uzyskać dostęp do alternatywnego API do dodawania/wstawiania/usuwania/klonowania slajdów układu, używając właściwości IMasterSlide.LayoutSlides.

**Zwraca:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Zwraca listę wszystkich slajdów master, które są zdefiniowane w prezentacji. Tylko do odczytu [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Zwraca:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Zwraca menedżera notatek master. Tylko do odczytu [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Zwraca:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Zwraca menedżera master wersji rozdania. Tylko do odczytu [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Zwraca:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Zwraca menedżera czcionek. Tylko do odczytu [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Zwraca:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Zwraca domyślny styl tekstu dla kształtów. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Zwraca kolekcję autorów komentarzy. Tylko do odczytu [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Zwraca:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu. Tylko do odczytu [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Zwraca:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Zwraca kolekcję wszystkich obrazów w prezentacji. Tylko do odczytu [IImageCollection](../../com.aspose.slides/iimagecollection).

**Zwraca:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. Tylko do odczytu [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Zwraca:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Zwraca:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Zwraca niestandardowe dane prezentacji. Tylko do odczytu [ICustomData](../../com.aspose.slides/icustomdata).

**Zwraca:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Pobiera projekt VBA z makrami prezentacji. Odczyt/zapis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Pobiera projekt VBA z makrami prezentacji. Odczyt/zapis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Zwraca informację o formacie, z którego załadowano prezentację. Tylko do odczytu [SourceFormat](../../com.aspose.slides/sourceformat).

**Zwraca:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Zwraca motyw master prezentacji. Tylko do odczytu [IMasterTheme](../../com.aspose.slides/imastertheme).

**Zwraca:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Zapewnia łatwy dostęp do wszystkich hiperłączy zawartych we wszystkich slajdach prezentacji (nie w slajdach master, układu, notatek). Tylko do odczytu [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Zwraca:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Pobiera właściwości widoku całej prezentacji. Tylko do odczytu [IViewProperties](../../com.aspose.slides/iviewproperties).

**Zwraca:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Reprezentuje numer pierwszego slajdu w prezentacji. Odczyt/zapis int.

**Zwraca:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Reprezentuje numer pierwszego slajdu w prezentacji. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Zwraca wszystkie niestandardowe części danych w prezentacji. Tylko do odczytu ICustomXmlPart[].

**Zwraca:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Zwraca kolekcję podpisów użytych do podpisania prezentacji. Tylko do odczytu [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**Zwraca:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji. Tylko do odczytu [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Wypisz zastosowane etykiety
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Dodaj nową etykietę
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Pobierz Id etykiety wrażliwości z polityki
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Pobierz identyfikator witryny Azure AD z polityki
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do tworzonego pliku. |
| format | int | Format eksportowanych danych. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| format | int | Format eksportowanych danych. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie z dodatkowymi opcjami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do tworzonego pliku. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie z dodatkowymi opcjami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Zapisuje wybrane slajdy prezentacji do pliku w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do tworzonego pliku. |
| slides | int[] | Tablica z pozycjami slajdów, licząc od 1. |
| format | int | Format eksportowanych danych. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Zapisuje wybrane slajdy prezentacji do pliku w określonym formacie z dodatkowymi opcjami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do tworzonego pliku. |
| slides | int[] | Tablica z pozycjami slajdów, licząc od 1. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Zapisuje wybrane slajdy prezentacji do strumienia w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| slides | int[] | Tablica z pozycjami slajdów, licząc od 1. |
| format | int | Format eksportowanych danych. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Zapisuje wybrane slajdy prezentacji do strumienia w określonym formacie z dodatkowymi opcjami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| slides | int[] | Tablica z pozycjami slajdów, licząc od 1. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znacznik XAML.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Opcje formatu XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Zwraca obiekty Miniatury obrazu dla wszystkich slajdów prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Zwraca obiekty Miniatury IImage dla określonych slajdów prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| slides | int[] | Tablica z pozycjami slajdów, licząc od 1. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Zwraca obiekty Miniatury obrazu dla wszystkich slajdów prezentacji z niestandardowym skalowaniem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| scaleX | float | Wartość, o którą skalować miniaturę wzdłuż osi X. |
| scaleY | float | Wartość, o którą skalować miniaturę wzdłuż osi Y. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Zwraca obiekty Miniatury obrazu dla określonych slajdów prezentacji z niestandardowym skalowaniem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| slides | int[] | Tablica z pozycjami slajdów, licząc od 1. |
| scaleX | float | Wartość, o którą skalować miniaturę wzdłuż osi X. |
| scaleY | float | Wartość, o którą skalować miniaturę wzdłuż osi Y. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty IImage.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Zwraca obiekty Miniatury obrazu dla wszystkich slajdów prezentacji o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar obrazu do utworzenia. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty IImage.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Zwraca obiekty Miniatury obrazu dla określonych slajdów prezentacji o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| slides | int[] | Tablica z pozycjami slajdów, licząc od 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar obrazu do utworzenia. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Zwraca Slide, MasterSlide lub LayoutSlide według Id.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | long | Id slajdu. |

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - obiekt IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Łączy fragmenty z tym samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach we wszystkich slajdach.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // podświetlanie wszystkich oddzielnych wystąpień 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do wyróżnienia. |
| highlightColor | java.lang.Integer | Kolor wyróżnienia tekstu. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // podświetlanie wszystkich oddzielnych wystąpień 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do wyróżnienia. |
| highlightColor | java.lang.Integer | Kolor wyróżnienia tekstu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Wyróżnia wszystkie dopasowania wyrażenia regularnego podanym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // podświetlanie wszystkich oddzielnych wystąpień 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern, którego dopasowania mają być wyróżnione. |
| highlightColor | java.lang.Integer | Kolor wyróżnienia tekstu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Zamienia wszystkie wystąpienia określonego tekstu na inny określony tekst.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Zamień wszystkie oddzielne wystąpienia 'the' na '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| oldText | java.lang.String | Ciąg znaków do zastąpienia. |
| newText | java.lang.String | Ciąg znaków, którym zostaną zastąpione wszystkie wystąpienia oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Zamienia wszystkie dopasowania wyrażenia regularnego na określony ciąg znaków.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Zamień wszystkie oddzielne wystąpienia 'the' na '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern, którego dopasowania mają być zamienione. |
| newText | java.lang.String | Ciąg znaków, którym zostaną zastąpione wszystkie dopasowania. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |