---
title: SlideCollection
second_title: Aspose.Slides dla Androida - referencja API Java
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
| [size()](#size--) | Zwraca liczbę elementów faktycznie zawartych w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o podanym indeksie. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Dodaje kopię określonego slajdu na koniec określonej sekcji. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Wstawia kopię określonego slajdu w podane miejsce kolekcji. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Dodaje nowy pusty slajd na koniec kolekcji. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Wstawia kopię określonego slajdu w podane miejsce kolekcji. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Wstawia kopię określonego slajdu w podane miejsce kolekcji. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Dodaje kopię określonego slajdu źródłowego na koniec kolekcji. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Wstawia kopię określonego slajdu źródłowego w podane miejsce kolekcji. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie w kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi slajdami. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę ze slajdami z określonego zakresu. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Przenosi slajd w kolekcji na określoną pozycję. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Przenosi slajdy w kolekcji na określoną pozycję. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Zwraca indeks określonego slajdu w kolekcji. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (bezpieczny dla wątków). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |

### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. tylko do odczytu int.

**Zwraca:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Zwraca element o podanym indeksie. tylko do odczytu [Slide](../../com.aspose.slides/slide).

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

Podczas klonowania slajdu między różnymi prezentacjami możliwe jest także sklonowanie mastera slajdu. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego mastera slajdu. Ręczne klonowanie masterów slajdów nie będzie ani zapobiegane, ani rejestrowane. Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) lub \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) do klonowania slajdów, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) lub [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) do klonowania układów oraz [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) do klonowania masterów. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Dodaje kopię określonego slajdu na koniec określonej sekcji.

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
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Wstawia kopię określonego slajdu w podane miejsce kolekcji.

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Utwórz klasę Presentation, która reprezentuje plik prezentacji
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Skopiuj wybrany slajd na koniec kolekcji slajdów w tej samej prezentacji
>      ISlideCollection slds = pres.getSlides();
>      // Skopiuj wybrany slajd do określonego indeksu w tej samej prezentacji
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
>  // Utwórz klasę Presentation, aby wczytać plik źródłowy prezentacji
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Utwórz klasę Presentation dla docelowego pliku PPTX (gdzie slajd ma być sklonowany)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Zapisz docelową prezentację na dysku
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

Podczas klonowania slajdu między różnymi prezentacjami możliwe jest także sklonowanie mastera slajdu. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego mastera slajdu. Ręczne klonowanie masterów slajdów nie będzie ani zapobiegane, ani rejestrowane. Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) lub \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) do klonowania slajdów oraz [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) do klonowania masterów. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

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
[ISlide](../../com.aspose.slides/islide) - Added slide.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Wstawia kopię określonego slajdu w podane miejsce kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ dla slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

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
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Wstawia kopię określonego slajdu w podane miejsce kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ slajdu dla nowego slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Dodaje kopię określonego slajdu źródłowego na koniec kolekcji. Odpowiedni układ zostanie automatycznie wybrany z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout jest false).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slajd dla nowego slajdu. |
| allowCloneMissingLayout | boolean | Jeśli w określonym masterze nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout jest false). |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Wstawia kopię określonego slajdu źródłowego w podane miejsce kolekcji. Odpowiedni układ zostanie automatycznie wybrany z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout jest false).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slajd dla nowego slajdu. |
| allowCloneMissingLayout | boolean | Jeśli w określonym masterze nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout jest false). |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

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
public final void removeAt(int index)
```

Usuwa element o podanym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks elementu do usunięcia. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Enumerator, który może być użyty do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator dla całej kolekcji.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Tworzy i zwraca tablicę ze wszystkimi slajdami.

**Zwraca:**
com.aspose.slides.ISlide[] - Tablica [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę ze slajdami z określonego zakresu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego slajdu do dodania. |
| count | int | Liczba slajdów do dodania. |

**Zwraca:**
com.aspose.slides.ISlide[] - Tablica [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Przenosi slajd w kolekcji na określoną pozycję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd do przeniesienia. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Przenosi slajdy w kolekcji na określoną pozycję. Slajdy będą umieszczane począwszy od indeksu w kolejności, w jakiej występują na liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slides to move. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Zwraca indeks określonego slajdu w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd do znalezienia. |

**Zwraca:**
int - Indeks slajdu lub -1, jeśli slajd nie pochodzi z tej kolekcji.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

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

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF.

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
| pdfStream | java.io.InputStream | Strumień, który będzie używany jako źródło dokumentu PDF |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

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
| pdfStream | java.io.InputStream | Strumień, który będzie używany jako źródło dokumentu PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opcje importu PDF |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest null, wszystkie obiekty zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego HTML. Używane do rozwiązywania względnych linków. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML do dodania. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest null, wszystkie obiekty zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego HTML. Używane do rozwiązywania względnych linków. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

--------------------

> ```
> // Utwórz instancję klasy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Wywołaj metodę AddFromHtml i przekaż plik HTML.
>          pres.getSlides().addFromHtml(fos);
>          // Użyj metody Save, aby zapisać plik jako dokument PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest null, wszystkie obiekty zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego HTML. Używane do rozwiązywania względnych linków. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest null, wszystkie obiekty zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego HTML. Używane do rozwiązywania względnych linków. |
| useSlideWithIndexAsStart | boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| useSlideWithIndexAsStart | boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest null, wszystkie obiekty zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego HTML. Używane do rozwiązywania względnych linków. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest null, wszystkie obiekty zewnętrzne będą ignorowane. |
| uri | java.lang.String | URI określonego HTML. Używane do rozwiązywania względnych linków. |
| useSlideWithIndexAsStart | boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonej pozycji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja do wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Stream, który będzie używany jako źródło pliku HTML. |
| useSlideWithIndexAsStart | boolean | Ta flaga określa, jak rozpocząć wstawianie: od nowego slajdu lub od slajdu o podanym indeksie. Jeśli **true**, wstawianie danych rozpocznie się od pustej przestrzeni na slajdzie o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] - Dodane slajdy

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (bezpieczny wątkowo). tylko do odczytu boolean.

**Zwraca:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. tylko do odczytu Object.

**Zwraca:**
java.lang.Object