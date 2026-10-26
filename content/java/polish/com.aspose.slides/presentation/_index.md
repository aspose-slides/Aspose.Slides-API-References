---
title: Presentation
second_title: Referencja API Aspose.Slides dla Javy
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
>  // Wczytaj dowolny obsługiwany plik w Presentation, np. ppt, pptx, odp itd.
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
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca aktualny menedżer HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Pobiera menedżera uprawnień dla tej prezentacji. |
| [getSlides()](#getSlides--) | Zwraca listę wszystkich slajdów zdefiniowanych w prezentacji. |
| [getSections()](#getSections--) | Zwraca listę wszystkich sekcji slajdów zdefiniowanych w prezentacji. |
| [getSlideSize()](#getSlideSize--) | Zwraca obiekt rozmiaru slajdu. |
| [getNotesSize()](#getNotesSize--) | Zwraca obiekt rozmiaru slajdu notatek. |
| [getLayoutSlides()](#getLayoutSlides--) | Zwraca listę wszystkich slajdów układu zdefiniowanych w prezentacji. |
| [getMasters()](#getMasters--) | Zwraca listę wszystkich slajdów głównych zdefiniowanych w prezentacji. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Zwraca menedżera notatek głównych. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Zwraca menedżera materiałów rozdawniczych. |
| [getFontsManager()](#getFontsManager--) | Zwraca menedżera czcionek. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Zwraca domyślny styl tekstu dla kształtów. |
| [getCommentAuthors()](#getCommentAuthors--) | Zwraca kolekcję autorów komentarzy. |
| [getDocumentProperties()](#getDocumentProperties--) | Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu. |
| [getImages()](#getImages--) | Zwraca kolekcję wszystkich obrazów w prezentacji. |
| [getAudios()](#getAudios--) | Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. |
| [getVideos()](#getVideos--) | Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Zwraca ustawienia pokazu slajdów dla prezentacji. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Zwraca kolekcję podpisów użytych do podpisania prezentacji. |
| [getCustomData()](#getCustomData--) | Zwraca niestandardowe dane prezentacji. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Zwraca wszystkie niestandardowe części danych w prezentacji. |
| [getVbaProject()](#getVbaProject--) | Pobiera lub ustawia projekt VBA z makrami prezentacji. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Pobiera lub ustawia projekt VBA z makrami prezentacji. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Zapewnia łatwy dostęp do wszystkich hiperłączy zawartych we wszystkich slajdach prezentacji (nie w slajdach głównych, układu, notatek). |
| [getViewProperties()](#getViewProperties--) | Pobiera właściwości widoku całej prezentacji. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Reprezentuje numer pierwszego slajdu w prezentacji. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Reprezentuje numer pierwszego slajdu w prezentacji. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji. |
| [getSlideById(long id)](#getSlideById-long-) | Zwraca obiekt Slide, MasterSlide lub LayoutSlide według Id. |
| [getSourceFormat()](#getSourceFormat--) | Zwraca informacje o formacie, z którego wczytano prezentację. |
| [getMasterTheme()](#getMasterTheme--) | Zwraca motyw główny. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie i z dodatkowymi opcjami. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie i z dodatkowymi opcjami. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Zapisuje wszystkie slajdy prezentacji do zestawu plików przedstawiających znacznik XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Zwraca obiekty Image dla wszystkich slajdów prezentacji. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Zwraca obiekty obrazów miniatur dla określonych slajdów prezentacji. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Zwraca obiekty obrazów miniatur dla wszystkich slajdów prezentacji ze skalowaniem niestandardowym. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Zwraca obiekty obrazów miniatur dla określonych slajdów prezentacji ze skalowaniem niestandardowym. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Zwraca obiekty obrazów miniatur dla wszystkich slajdów prezentacji o określonym rozmiarze. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Zwraca obiekty obrazów miniatur dla określonych slajdów prezentacji o określonym rozmiarze. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numerację stron. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numerację stron. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numerację stron. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numerację stron. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy segmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach na wszystkich slajdach. |
| [dispose()](#dispose--) | Zwalnia wszystkie zasoby używane przez ten obiekt Presentation. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną tekstu. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Podświetla wszystkie wystąpienia przykładowego tekstu określonym kolorem. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie wystąpienia przykładowego tekstu określonym kolorem. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Podświetla wszystkie dopasowania wyrażenia regularnego określonym kolorem. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie wystąpienia określonego tekstu innym podanym tekstem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem znaków. |

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

Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. Domyślnie jest to czas utworzenia tego obiektu Presentation. Odczyt/zapis java.util.Date.

**Zwraca:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. Domyślnie jest to czas utworzenia tego obiektu Presentation. Odczyt/zapis java.util.Date.

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

Zwraca aktualny menedżer HeaderFooter. Tylko do odczytu [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Właściwość IsFooterVisible jest używana do wskazywania, że placeholder stopki slajdu nie jest obecny.
>      {
>          headerFooterManager.setFooterVisibility(true); // Metoda SetFooterVisibility jest używana do wyświetlenia placeholdera stopki slajdu.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Właściwość IsSlideNumberVisible jest używana do wskazywania, że placeholder numeru strony slajdu nie jest obecny.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Metoda SetSlideNumberVisibility jest używana do wyświetlenia placeholdera numeru strony slajdu.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Właściwość IsDateTimeVisible jest używana do wskazywania, że placeholder daty i czasu slajdu nie jest obecny.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Metoda SetFooterVisibility jest używana do wyświetlenia placeholdera daty i czasu slajdu.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Metoda SetFooterAndChildFootersVisibility jest używana do wyświetlenia master slajdu i wszystkich podrzędnych placeholderów stopki.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Metoda SetSlideNumberAndChildSlideNumbersVisibility jest używana do wyświetlenia master slajdu i wszystkich podrzędnych placeholderów numerów stron.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Metoda SetDateTimeAndChildDateTimesVisibility jest używana do wyświetlenia master slajdu i wszystkich podrzędnych placeholderów daty i czasu.
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
>      // Ustaw kolor tła pierwszego slajdu ISlide na niebieski
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
>      // Ustaw tło za pomocą obrazu
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Ustaw obraz
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Dodaj obraz do kolekcji obrazów prezentacji
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
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
>      // Zastosuj przejście typu koło na slajdzie 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Zastosuj przejście typu grzebień na slajdzie 2
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
>      // Zastosuj przejście typu koło na slajdzie 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Ustaw czas przejścia na 3 sekundy
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Zastosuj przejście typu grzebień na slajdzie 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Ustaw czas przejścia na 5 sekund
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Zastosuj przejście typu powiększenie na slajdzie 3
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
>      // sekcja1 zostanie zakończona na newSlide2, a po niej sekcja2 rozpocznie się
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
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Ustaw rozmiar slajdu wygenerowanych prezentacji na rozmiar źródła
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Metoda SetSize jest używana do ustawiania rozmiaru slajdu z skalowaniem treści w celu zapewnienia dopasowania
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Metoda SetSize jest używana do ustawiania rozmiaru slajdu z maksymalizacją rozmiaru treści
>          // Zapisz prezentację na dysku
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Rozmiar papieru A4
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

Możesz uzyskać dostęp do alternatywnego API do dodawania/wstawiania/usuwania/kopiowania slajdów układu, używając własności IMasterSlide.LayoutSlides property.

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
Zwraca menedżera materiałów rozdawniczych. Tylko do odczytu [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

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
>          // pozostaje niskie przez cały cykl życia obiektu pres
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
>      // Dodaje obraz do prezentacji
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Tworzy ramkę obrazu na slajdzie 1 na podstawie wcześniej dodanego obrazu
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


**Zwraca:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. Tylko do odczytu [IAudioCollection](../../com.aspose.slides/iaudiocollection).

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


**Zwraca:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu [IVideoCollection](../../com.aspose.slides/ivideocollection).

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

**Zwraca:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public                                   SlideShowSettings                                getSlideShowSettings()
```

Zwraca ustawienia pokazu slajdów dla prezentacji.

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

Zwraca wszystkie części danych niestandardowych w prezentacji. Tylko do odczytu ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Iteruj wszystkie niestandardowe części XML
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
public final void setVbaProject(IVbaProject value)
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

Zapewnia łatwy dostęp do wszystkich hiperłączy zawartych we wszystkich slajdach prezentacji (z wyjątkiem slajdów master, układu, notatek). Tylko do odczytu [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Zwraca:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Pobiera właściwości widoku prezentacji. Tylko do odczytu [IViewProperties](../../com.aspose.slides/iviewproperties).

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
>      // Wyświetl zastosowane etykiety
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Dodaj nową etykietę
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Pobierz identyfikator etykiety wrażliwości z polityki
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

Zwraca obiekt Slide, MasterSlide lub LayoutSlide na podstawie Id.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | long | Id slajdu. |

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - obiekt IBaseSlide.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Zwraca informacje o formacie, z którego została wczytana prezentacja. Tylko do odczytu [SourceFormat](../../com.aspose.slides/sourceformat).

**Zwraca:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Zwraca temat nadrzędny. Tylko do odczytu [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // Utwórz obiekt klasy Presentation, który reprezentuje plik prezentacji
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

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
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

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
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

Zwraca obiekty Image dla wszystkich slajdów prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje TIFF. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty Image.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Zwraca obiekty miniatur Image dla określonych slajdów prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje TIFF. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty Image.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Zwraca obiekty miniatur Image dla wszystkich slajdów prezentacji z niestandardowym skalowaniem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje TIFF. |
| scaleX | float | Wartość, o którą skalować tę miniaturę w kierunku osi x. |
| scaleY | float | Wartość, o którą skalować tę miniaturę w kierunku osi y. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty Image.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Zwraca obiekty miniatur Image dla określonych slajdów prezentacji z niestandardowym skalowaniem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje TIFF. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| scaleX | float | Wartość, o którą skalować tę miniaturę w kierunku osi x. |
| scaleY | float | Wartość, o którą skalować tę miniaturę w kierunku osi y. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty Image.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Zwraca obiekty miniatur Image dla wszystkich slajdów prezentacji o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje TIFF. |
| imageSize | java.awt.Dimension | Rozmiar obrazu do utworzenia. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty Image.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Zwraca obiekty miniatur Image dla określonych slajdów prezentacji o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje TIFF. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| imageSize | java.awt.Dimension | Rozmiar obrazu do utworzenia. |

**Zwraca:**
com.aspose.slides.IImage[] - obiekty Image.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fname | java.lang.String | Ścieżka do utworzonego pliku. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | int | Format eksportowanych danych. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron.

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

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień wyjściowy. |
| slides | int[] | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | int | Format eksportowanych danych. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron.

--------------------

> ```
> Poniższy przykład pokazuje, jak przekształcić prezentację PowerPoint do formatu PNG.
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
> Poniższy przykład pokazuje, jak przekształcić prezentację PowerPoint do formatu PNG z niestandardowymi wymiarami.
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
> Poniższy przykład pokazuje, jak przekształcić prezentację PowerPoint do formatu PNG o niestandardowym rozmiarze.
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

Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach we wszystkich slajdach.

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
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Podświetla wszystkie wystąpienia przykładowego tekstu podanym kolorem.

--------------------

> ```
> Poniższy przykład kodu pokazuje, jak podświetlić tekst w prezentacji PowerPoint.
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
| highlightColor | java.awt.Color | Kolor podświetlenia tekstu. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Podświetla wszystkie wystąpienia przykładowego tekstu podanym kolorem.

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
| highlightColor | java.awt.Color | Kolor podświetlenia tekstu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt zwrotny odbierający wyniki wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Podświetla wszystkie dopasowania wyrażenia regularnego podanym kolorem.

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
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern, którego ciągi mają być podświetlone. |
| highlightColor | java.awt.Color | Kolor podświetlenia tekstu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt zwrotny odbierający wyniki wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem.

--------------------

> ```
> Poniższy przykładowy kod pokazuje, jak zastąpić jeden określony ciąg znaków innym określonym ciągiem znaków.
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
| oldText | java.lang.String | Ciąg znaków do zastąpienia. |
| newText | java.lang.String | Ciąg znaków, który zastąpi wszystkie wystąpienia oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opcje wyszukiwania tekstu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Zastępuje wszystkie dopasowania wyrażenia regularnego podanym łańcuchem.

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
| regex | java.util.regex.Pattern | Wyrażenie regularne java.util.regex.Pattern służące do pobierania łańcuchów do zastąpienia. |
| newText | java.lang.String | Ciąg znaków, który zastąpi wszystkie wystąpienia łańcuchów do zastąpienia. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Obiekt wywołania zwrotnego służący do odbierania wyników wyszukiwania [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |