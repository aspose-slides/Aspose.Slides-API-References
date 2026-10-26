---
title: Presentation
second_title: Aspose.Slides dla Androida – odwołanie API Java
description: Reprezentuje prezentację Microsoft PowerPoint.
type: docs
url: /pl/com.aspose.slides/presentation/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Reprezentuje prezentację Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation();
>  try {
>      // Pobierz pierwszy slajd
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Dodaj autokształt typu linia
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Zapisz plik prezentacji.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Wczytaj dowolny obsługiwany plik w Presentation e.g. ppt, pptx, odp itp.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Zapisz plik prezentacji.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Presentation()](#Presentation--) | Ten konstruktor tworzy nową prezentację od podstaw. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Ten konstruktor tworzy nową prezentację od podstaw. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego odczytywana jest zawartość prezentacji. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego odczytywana jest zawartość prezentacji. |

## Metody

| Metoda | Opis |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca aktualnego menedżera HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Pobiera menedżera uprawnień dla tej prezentacji. |
| [getSlides()](#getSlides--) | Zwraca listę wszystkich slajdów zdefiniowanych w prezentacji. |
| [getSections()](#getSections--) | Zwraca listę wszystkich sekcji slajdów zdefiniowanych w prezentacji. |
| [getSlideSize()](#getSlideSize--) | Zwraca obiekt rozmiaru slajdu. |
| [getNotesSize()](#getNotesSize--) | Zwraca obiekt rozmiaru slajdu notatek. |
| [getLayoutSlides()](#getLayoutSlides--) | Zwraca listę wszystkich slajdów układu zdefiniowanych w prezentacji. |
| [getMasters()](#getMasters--) | Zwraca listę wszystkich slajdów głównych zdefiniowanych w prezentacji. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Zwraca menedżera notatek głównych. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Zwraca menedżera materiałów do rozdania. |
| [getFontsManager()](#getFontsManager--) | Zwraca menedżera czcionek. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Zwraca domyślny styl tekstu dla kształtów. |
| [getCommentAuthors()](#getCommentAuthors--) | Zwraca kolekcję autorów komentarzy. |
| [getDocumentProperties()](#getDocumentProperties--) | Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu. |
| [getImages()](#getImages--) | Zwraca kolekcję wszystkich obrazów w prezentacji. |
| [getAudios()](#getAudios--) | Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. |
| [getVideos()](#getVideos--) | Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Zwraca ustawienia pokazu slajdów prezentacji. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Zwraca kolekcję podpisów używanych do podpisania prezentacji. |
| [getCustomData()](#getCustomData--) | Zwraca niestandardowe dane prezentacji. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Zwraca wszystkie niestandardowe części danych w prezentacji. |
| [getVbaProject()](#getVbaProject--) | Pobiera lub ustawia projekt VBA z makrami prezentacji. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Pobiera lub ustawia projekt VBA z makrami prezentacji. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Zapewnia łatwy dostęp do wszystkich hiperłączy zawartych we wszystkich slajdach prezentacji (nie w slajdach głównych, układu, notatek). |
| [getViewProperties()](#getViewProperties--) | Pobiera właściwości widoku obejmujące całą prezentację. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Reprezentuje numer pierwszego slajdu w prezentacji |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Reprezentuje numer pierwszego slajdu w prezentacji |
| [getSensitivityLabels()](#getSensitivityLabels--) | Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji. |
| [getSlideById(long id)](#getSlideById-long-) | Zwraca obiekt Slide, MasterSlide lub LayoutSlide według Id. |
| [getSourceFormat()](#getSourceFormat--) | Zwraca informacje o formacie, z którego załadowano prezentację. |
| [getMasterTheme()](#getMasterTheme--) | Zwraca motyw główny. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie i z dodatkowymi opcjami. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie i z dodatkowymi opcjami. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Zapisuje wszystkie slajdy prezentacji jako zestaw plików reprezentujących znacznik XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Zwraca obiekt Image dla wszystkich slajdów prezentacji. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji z niestandardowym skalowaniem. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji z niestandardowym skalowaniem. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji w określonym rozmiarze. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji w określonym rozmiarze. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty z tym samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach na wszystkich slajdach. |
| [dispose()](#dispose--) | Zwalnia wszystkie zasoby używane przez ten obiekt Presentation. |
| [getPresentation()](#getPresentation--) | Zwraca nadrzędną prezentację tekstu. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Podświetla wszystkie dopasowania przykładowego tekstu określonym kolorem. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie dopasowania przykładowego tekstu określonym kolorem. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie dopasowania wyrażenia regularnego określonym ciągiem znaków. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Ten konstruktor tworzy nową prezentację od podstaw. Utworzona prezentacja ma jeden pusty slajd.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Ten konstruktor tworzy nową prezentację od podstaw. Utworzona prezentacja ma jeden pusty slajd.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Dodatkowe opcje ładowania. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień wejściowy. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Dodatkowe opcje ładowania. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego odczytywana jest zawartość prezentacji.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Plik wejściowy. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego odczytywana jest zawartość prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| file | java.lang.String | Plik wejściowy. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Dodatkowe opcje ładowania. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. Domyślnie czas utworzenia tego obiektu Presentation. Odczyt/zapis java.util.Date.

**Zwraca:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. Domyślnie czas utworzenia tego obiektu Presentation. Odczyt/zapis java.util.Date.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Zwraca aktualnego menedżera HeaderFooter. Tylko do odczytu [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Właściwość IsFooterVisible jest używana do wskazania, że placeholder stopki slajdu nie jest obecny.
>      {
>          headerFooterManager.setFooterVisibility(true); // Metoda SetFooterVisibility jest używana do uczynienia placeholdera stopki slajdu widocznym.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Właściwość IsSlideNumberVisible jest używana do wskazania, że placeholder numeru strony slajdu nie jest obecny.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Metoda SetSlideNumberVisibility jest używana do uczynienia placeholdera numeru strony slajdu widocznym.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Właściwość IsDateTimeVisible jest używana do wskazania, że placeholder daty i czasu slajdu nie jest obecny.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Metoda SetFooterVisibility jest używana do uczynienia placeholdera daty i czasu slajdu widocznym.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Metoda SetFooterText jest używana do ustawiania tekstu w placeholderze stopki slajdu.
>      headerFooterManager.setDateTimeText("Date and time text"); // Metoda SetDateTimeText jest używana do ustawiania tekstu w placeholderze daty i czasu slajdu.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Metoda SetFooterAndChildFootersVisibility jest używana do uczynienia master slajdu i wszystkich podrzędnych placeholderów stopki widocznymi.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Metoda SetSlideNumberAndChildSlideNumbersVisibility jest używana do uczynienia master slajdu i wszystkich podrzędnych placeholderów numeru strony widocznymi.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Metoda SetDateTimeAndChildDateTimesVisibility jest używana do uczynienia master slajdu i wszystkich podrzędnych placeholderów daty i czasu widocznymi.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Metoda SetFooterAndChildFootersText jest używana do ustawiania tekstu w master slajdzie i wszystkich podrzędnych placeholderach stopki.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Metoda SetDateTimeAndChildDateTimesText jest używana do ustawiania tekstu w master slajdzie i wszystkich podrzędnych placeholderach daty i czasu.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Pobiera menedżera uprawnień dla tej prezentacji. Tylko do odczytu [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Zwraca:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Zwraca listę wszystkich slajdów zdefiniowanych w prezentacji. Tylko do odczytu [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
>  Presentation pres = new Presentation();
>  try
>  {
>      // Ustaw kolor tła pierwszego ISlide na niebieski
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
>  // Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Ustaw tło przy użyciu obrazu
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Ustaw obraz
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Dodaj obraz do kolekcji obrazów prezentacji
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // Zapisz prezentację na dysku
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Utwórz instancję klasy Presentation, aby wczytać źródłowy plik prezentacji
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Zastosuj przejście typu circle na slajdzie 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Zastosuj przejście typu comb na slajdzie 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Zapisz prezentację na dysku
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Zastosuj przejście typu circle na slajdzie 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Ustaw czas przejścia na 3 sekundy
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Zastosuj przejście typu comb na slajdzie 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Ustaw czas przejścia na 5 sekund
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Zastosuj przejście typu zoom na slajdzie 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Ustaw czas przejścia na 7 sekund
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Zapisz prezentację na dysku
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Zwraca listę wszystkich sekcji slajdów zdefiniowanych w prezentacji. Tylko do odczytu [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // sekcja1 zakończy się na newSlide2, a po niej rozpocznie się sekcja2
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


**Zwraca:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Zwraca obiekt rozmiaru slajdu. Tylko do odczytu [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Set the slide size of generated presentations to that of source
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize is used for set slide size with scale content to ensure fit
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize is used for set slide size with maximize size of content
>          // Save Presentation to disk
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 paper size
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Zwraca obiekt rozmiaru slajdu notatek. Tylko do odczytu [INotesSize](../../com.aspose.slides/inotessize).

**Zwraca:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Zwraca listę wszystkich slajdów układu zdefiniowanych w prezentacji. Tylko do odczytu [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Możesz uzyskać dostęp do alternatywnego API do dodawania/wstawiania/usuwania/klonowania slajdów układu, używając właściwości IMasterSlide.LayoutSlides.

**Zwraca:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Zwraca listę wszystkich slajdów głównych zdefiniowanych w prezentacji. Tylko do odczytu [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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
>  // Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
>  Presentation pres = new Presentation();
>  try
>  {
>      // Ustaw kolor tła Master ISlide na zielony leśny
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Zapisz prezentację na dysku
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Spróbuj wyszukać według typu slajdu układu
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Sytuacja, gdy prezentacja nie zawiera niektórych typów układów.
>          // Plik prezentacji zawiera tylko układy typu Blank i Custom.
>          // Jednak slajdy układu typu Custom mają różne nazwy slajdów,
>          // np. "Title", "Title and Content" itp. i można je używać
>          // nazwy do wyboru slajdu układu.
>          // Można również używać zestawu typów kształtów zastępczych. Na przykład,
>          // Slajd tytułowy powinien mieć tylko typ zastępczy Title, itp.
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
>      // Dodawanie pustego slajdu z dodanym slajdem układu
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Zapisz prezentację
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Zwraca:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Zwraca menedżera notatek głównych. Tylko do odczytu [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Zwraca:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Zwraca menedżera materiałów do rozdania. Tylko do odczytu [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Zwraca:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Zwraca menedżera czcionek. Tylko do odczytu [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Wczytaj prezentację
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Wczytaj źródłową czcionkę do zamiany
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
>      // Zapisz prezentację
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Zwraca domyślny styl tekstu dla kształtów. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Zwraca kolekcję autorów komentarzy. Tylko do odczytu [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Zwraca:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu. Tylko do odczytu [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Zwraca:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Zwraca kolekcję wszystkich obrazów w prezentacji. Tylko do odczytu [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // tworzy nową prezentację, do której zostanie dodany obraz.
>  Presentation pres = new Presentation();
>  try
>  {
>      // zakładamy, że mamy duży plik obrazu, który chcemy dołączyć do prezentacji
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Dodajmy obraz do prezentacji - wybieramy zachowanie KeepLocked, ponieważ
>          // NIE zamierzamy uzyskiwać dostępu do pliku "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Zapisuje prezentację. Podczas generowania dużej prezentacji zużycie pamięci
>          // pozostaje niskie w trakcie cyklu życia obiektu pres.
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
>          // Dodaje obraz do prezentacji
>          IPPImage image = pres.getImages().addImage(fos);
>          // Tworzy ramkę obrazu na slajdzie 1 na podstawie wcześniej dodanego obrazu
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


**Zwraca:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. Tylko do odczytu [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać hiperłącze do pliku audio.
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
```

**Zwraca:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // tworzy nową prezentację, do której zostanie dodany obraz.
>  Presentation pres = new Presentation();
>  try
>  {
>      // zakładamy, że mamy duży plik obrazu, który chcemy dołączyć do prezentacji
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Dodajmy obraz do prezentacji - wybieramy zachowanie KeepLocked, ponieważ
>          // NIE zamierzamy uzyskiwać dostępu do pliku "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Zapisuje prezentację. Podczas generowania dużej prezentacji zużycie pamięci
>          // pozostaje niskie w trakcie cyklu życia obiektu pres.
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
>          // Dodaje obraz do prezentacji
>          IPPImage image = pres.getImages().addImage(fos);
>          // Tworzy ramkę obrazu na slajdzie 1 na podstawie wcześniej dodanego obrazu
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


**Zwraca:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Zwraca ustawienia pokazu slajdów prezentacji.

**Zwraca:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Zwraca kolekcję podpisów używanych do podpisania prezentacji. Tylko do odczytu [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Zwraca:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Zwraca niestandardowe dane prezentacji. Tylko do odczytu [ICustomData](../../com.aspose.slides/icustomdata).

**Zwraca:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Zwraca wszystkie niestandardowe części danych w prezentacji. Tylko do odczytu ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Przeglądaj wszystkie niestandardowe części XML
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


**Zwraca:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Pobiera lub ustawia projekt VBA z makrami prezentacji. Odczyt/zapis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public      ...  ...  ...  ...
```

Pobiera lub ustawia projekt VBA z makrami prezentacji. Odczyt/zapis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Zapewnia łatwy dostęp do wszystkich hiperłączy zawartych we wszystkich slajdach prezentacji (nie w slajdach głównych, układu, notatek). Tylko do odczytu [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Zwraca:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Pobiera właściwości widoku obejmujące całą prezentację. Tylko do odczytu [IViewProperties](../../com.aspose.slides/iviewproperties).

**Zwraca:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Reprezentuje numer pierwszego slajdu w prezentacji

**Zwraca:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Reprezentuje numer pierwszego slajdu w prezentacji

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
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

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Zwraca Slide, MasterSlide lub LayoutSlide według Id.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | long | Id slajdu. |

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Zwraca informacje o formacie, z którego załadowano prezentację. Tylko do odczytu [SourceFormat](../../com.aspose.slides/sourceformat).

**Zwraca:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Zwraca motyw główny. Tylko do odczytu [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
  //Utwórz obiekt prezentacji, który reprezentuje plik prezentacji
  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
  try {
      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
  }
  finally
  {
      if (pres != null) pres.dispose();
  }
```

**Zwraca:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do utworzonego pliku. |
| format | int | Format eksportowanych danych. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| format | int | Format eksportowanych danych. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISSaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie i z dodatkowymi opcjami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do utworzonego pliku. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISSaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie i z dodatkowymi opcjami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
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
public final IImage[] getImages(IRenderingOptions options)
```

Zwraca obiekt Image dla wszystkich slajdów prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje Tiff. |

**Zwraca:**
com.aspose.slides.IImage[] - Obiekty Image.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje Tiff. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |

**Zwraca:**
com.aspose.slides.IImage[] - Obiekty Image.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji z niestandardowym skalowaniem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje Tiff. |
| scaleX | float | Wartość, o którą skalować tę Miniaturkę wzdłuż osi X. |
| scaleY | float | Wartość, o którą skalować tę Miniaturkę wzdłuż osi Y. |

**Zwraca:**
com.aspose.slides.IImage[] - Obiekty Image.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji z niestandardowym skalowaniem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje Tiff. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| scaleX | float | Wartość, o którą skalować tę Miniaturkę wzdłuż osi X. |
| scaleY | float | Wartość, o którą skalować tę Miniaturkę wzdłuż osi Y. |

**Zwraca:**
com.aspose.slides.IImage[] - Obiekty Image.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji w określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar obrazu do utworzenia. |

**Zwraca:**
com.aspose.slides.IImage[] - Obiekty Image.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji w określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje Tiff. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar obrazu do utworzenia. |

**Zwraca:**
com.aspose.slides.IImage[] - Obiekty Image.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Zapisuje określone slajdy prezentacji do pliku w określonym formacie z zachowaniem numeracji stron.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do utworzonego pliku. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | int | Format eksportowanych danych. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISSaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Zapisuje określone slajdy prezentacji do pliku w określonym formacie z zachowaniem numeracji stron.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do utworzonego pliku. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie z zachowaniem numeracji stron.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | int | Format eksportowanych danych. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISSaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie z zachowaniem numeracji stron.

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


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | int | Format eksportowanych danych. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatkowe opcje formatu. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Łączy fragmenty z tym samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach na wszystkich slajdach.

### dispose() {#dispose--}
```
public final void dispose()
```

Zwalnia wszystkie zasoby używane przez ten obiekt Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca nadrzędną prezentację tekstu. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Podświetla wszystkie dopasowania przykładowego tekstu określonym kolorem.

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
| text | java.lang.String | Tekst do podświetlenia. |
| highlightColor | java.lang.Integer | Kolor do podświetlenia tekstu. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Podświetla wszystkie dopasowania przykładowego tekstu określonym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // podświetlanie wszystkich oddzielnych wystąpień 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do podświetlenia. |
| highlightColor | java.lang.Integer | Kolor do podświetlenia tekstu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // podświetlanie wszystkich słów o długości 10 znaków lub więcej
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern do uzyskania ciągów do podświetlenia. |
| highlightColor | java.lang.Integer | Kolor do podświetlenia tekstu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public  ...  ...  ...  ...
```

Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Zastąp wszystkie oddzielne wystąpienia 'the' ciągiem '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| oldText | java.lang.String | Ciąg do zastąpienia. |
| newText | java.lang.String | Ciąg, który zastąpi wszystkie wystąpienia starego tekstu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Zastępuje wszystkie dopasowania wyrażenia regularnego określonym ciągiem.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Zastąp wszystkie słowa o długości 10 znaków lub więcej ciągiem '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern do uzyskania ciągów do zastąpienia. |
| newText | java.lang.String | Ciąg, który zastąpi wszystkie wystąpienia ciągów do zastąpienia. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |