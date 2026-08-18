---
title: SlideCollection
second_title: Odniesienie API Aspose.Slides dla Javy
description: Reprezentuje kolekcję slajdów.
type: docs
url: /pl/com.aspose.slides/slidecollection/
---
**Dziedziczenie:**  
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)  
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Reprezentuje kolekcję slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Adds a copy of a specified slide to the end of the collection. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Adds a copy of a specified slide to the end of the specified section. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Adds a new empty slide to the end of the collection. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified slide to the end of the collection. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Adds a copy of a specified source slide to the end of the collection. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Inserts a copy of a specified source slide to specified position of the collection. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [toArray()](#toArray--) | Creates and returns an array with all slides in it. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all slides from the specified range in it. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Moves slide from the collection to the specified position. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Moves slides from the collection to the specified position. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Returns an index of the specified slide in the collection. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Creates slides from HTML text and adds them to the end of the collection. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |

### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Zwraca element o podanym indeksie. Tylko do odczytu [Slide](../../com.aspose.slides/slide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Dodaje kopię określonego slajdu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) or \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) for cloning slides, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) or [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) for cloning layouts and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters.

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Nowy slajd.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Dodaje kopię określonego slajdu na koniec określonej sekcji.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Teraz druga sekcja zawiera kopię pierwszego slajdu.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| section | [ISection](../../com.aspose.slides/isection) | Sekcja dla nowego slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Nowy slajd.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Wstawia kopię określonego slajdu na określoną pozycję w kolekcji.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Sklonuj wybrany slajd na koniec kolekcji slajdów w tej samej prezentacji
>      ISlideCollection slds = pres.getSlides();
>      // Sklonuj wybrany slajd do określonego indeksu w tej samej prezentacji
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Zapisz zmodyfikowaną prezentację na dysku
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Utwórz instancję klasy Presentation, aby załadować plik źródłowej prezentacji
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Utwórz instancję klasy Presentation dla pliku docelowego PPTX (gdzie slajd ma zostać sklonowany)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Zapisz prezentację docelową na dysku
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) or \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters.

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Wstawiony slajd.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Dodaje nowy pusty slajd na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ dla slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Dodany slajd.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Wstawia kopię określonego slajdu na określoną pozycję w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ dla slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Wstawiony slajd.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Dodaje kopię określonego slajdu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ slajdu dla nowego slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Nowy slajd.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Wstawia kopię określonego slajdu na określoną pozycję w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ slajdu dla nowego slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Wstawiony slajd.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Dodaje kopię określonego slajdu źródłowego na koniec kolekcji. Odpowiedni układ zostanie wybrany automatycznie z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slajd dla nowego slajdu. |
| allowCloneMissingLayout | boolean | Jeśli nie ma odpowiedniego układu w określonym masterze, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false). |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Nowy slajd.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Wstawia kopię określonego slajdu źródłowego na określoną pozycję w kolekcji. Odpowiedni układ zostanie wybrany automatycznie z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slajd dla nowego slajdu. |
| allowCloneMissingLayout | boolean | Jeśli nie ma odpowiedniego układu w określonym masterze, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false). |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Wstawiony slajd.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Slajd do usunięcia z kolekcji. |

### removeAt(int index) {#removeAt-int-}
```
public final void remove(ISlide value)
```

Usuwa element o podanym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Zwraca java iterator for the entire collection.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Tworzy i zwraca tablicę zawierającą wszystkie slajdy.

**Zwraca:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę zawierającą wszystkie slajdy z określonego zakresu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego slajdu do dodania. |
| count | int | Liczba slajdów do dodania. |

**Zwraca:**
com.aspose.slides.ISlide[] - Array of [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Przenosi slajd z kolekcji na określoną pozycję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd do przeniesienia. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Przenosi slajdy z kolekcji na określoną pozycję. Slajdy będą rozmieszczane zaczynając od indeksu w kolejności, w jakiej występują na liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slajdy do przeniesienia. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISSlide-}
```
public final int indexOf(ISlide slide)
```

Zwraca indeks określonego slajdu w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd do znalezienia. |

**Zwraca:**
int – Indeks slajdu lub -1, jeśli slajd nie pochodzi z tej kolekcji.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka do dokumentu PDF |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji z uwzględnieniem opcji importu PDF.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka do dokumentu PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opcje importu PDF |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Strumień używany jako źródło dokumentu PDF |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Strumień używany jako źródło dokumentu PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opcje importu PDF |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z kodu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zasobów zewnętrznych. Jeśli parametr jest null, wszystkie zasoby zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego dokumentu HTML. Używane do rozwiązywania linków względnych. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Tworzy slajdy z kodu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML do dodania. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z kodu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Obiekt strumienia używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zasobów zewnętrznych. Jeśli parametr jest null, wszystkie zasoby zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego dokumentu HTML. Używane do rozwiązywania linków względnych. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Tworzy slajdy z kodu HTML i dodaje je na koniec kolekcji.

--------------------

> ```
> // Utwórz instancję klasy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // Wywołaj metodę AddFromHtml i przekaż plik HTML.
>      pres.getSlides().addFromHtml(html);
>      // Użyj metody Save, aby zapisać plik jako dokument PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Obiekt strumienia używany jako źródło pliku HTML. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zasobów zewnętrznych. Jeśli parametr jest null, wszystkie zasoby zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego dokumentu HTML. Używane do rozwiązywania linków względnych. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zasobów zewnętrznych. Jeśli parametr jest null, wszystkie zasoby zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego dokumentu HTML. Używane do rozwiązywania linków względnych. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt strumienia używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zasobów zewnętrznych. Jeśli parametr jest null, wszystkie zasoby zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego dokumentu HTML. Używane do rozwiązywania linków względnych. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt strumienia używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania zasobów zewnętrznych. Jeśli parametr jest null, wszystkie zasoby zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego dokumentu HTML. Używane do rozwiązywania linków względnych. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt strumienia używany jako źródło pliku HTML. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z kodu HTML i wstawia je do kolekcji na określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt strumienia używany jako źródło pliku HTML. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISSlide[] - Dodane slajdy

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Indeks początkowy w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (bezpieczny wątkowo). Tylko do odczytu, typ boolean.

**Zwraca:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu, typ Object.

**Zwraca:**
java.lang.Object