---
title: ISlideCollection
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje kolekcję slajdów.
type: docs
url: /pl/com.aspose.slides/islidecollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Reprezentuje kolekcję slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Dodaje kopię określonego slajdu na koniec określonej sekcji. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Wstawia kopię określonego slajdu na określone miejsce w kolekcji. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Dodaje nowy pusty slajd na koniec kolekcji. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Wstawia kopię określonego slajdu na określone miejsce w kolekcji. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Dodaje kopię określonego slajdu na koniec kolekcji. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Wstawia kopię określonego slajdu na określone miejsce w kolekcji. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Dodaje kopię określonego źródłowego slajdu na koniec kolekcji. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Wstawia kopię określonego źródłowego slajdu na określone miejsce w kolekcji. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem w kolekcji. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę ze wszystkimi slajdami. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę ze wszystkimi slajdami z określonego zakresu. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Przemieszcza slajd z kolekcji na określone miejsce. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Przemieszcza slajdy z kolekcji na określone miejsce. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Zwraca indeks określonego slajdu w kolekcji. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Pobiera element pod określonym indeksem. Tylko do odczytu [ISlide](../../com.aspose.slides/islide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Dodaje kopię określonego slajdu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania.

--------------------

Podczas klonowania slajdu między różnymi prezentacjami można również sklonować master slajdu. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego mastera slajdu. Ręczne klonowanie masterów slajdów nie będzie ani zapobiegane, ani rejestrowane. Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) lub \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) do klonowania slajdów, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) lub [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) do klonowania układów i [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) do klonowania masterów. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Nowy slajd.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
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
[ISlide](../../com.aspose.slides/islide) – Nowy slajd.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Wstawia kopię określonego slajdu na określone miejsce w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania.

--------------------

Podczas klonowania slajdu między różnymi prezentacjami można również sklonować master slajdu. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego mastera slajdu. Ręczne klonowanie masterów slajdów nie będzie ani zapobiegane, ani rejestrowane. Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) lub \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) do klonowania slajdów i [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) do klonowania masterów. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Wstawiony slajd.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Dodaje nowy pusty slajd na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ dla slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Dodany slajd.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Wstawia kopię określonego slajdu na określone miejsce w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ dla slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Wstawiony slajd.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Dodaje kopię określonego slajdu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ slajdu dla nowego slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Nowy slajd.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Wstawia kopię określonego slajdu na określone miejsce w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Układ slajdu dla nowego slajdu. |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Wstawiony slajd.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Dodaje kopię określonego źródłowego slajdu na koniec kolekcji. Odpowiedni układ zostanie automatycznie wybrany z podanego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ źródłowego slajdu). Jeśli nie ma odpowiedniego układu, układ źródłowego slajdu zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout jest false).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slajd dla nowego slajdu. |
| allowCloneMissingLayout | boolean | Jeśli w podanym masterze nie ma odpowiedniego układu, układ źródłowego slajdu zostanie sklonowany (gdy allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (gdy allowCloneMissingLayout jest false). |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Nowy slajd.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Wstawia kopię określonego źródłowego slajdu na określone miejsce w kolekcji. Odpowiedni układ zostanie automatycznie wybrany z podanego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ źródłowego slajdu). Jeśli nie ma odpowiedniego układu, układ źródłowego slajdu zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout jest false).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slajd dla nowego slajdu. |
| allowCloneMissingLayout | boolean | Jeśli w podanym masterze nie ma odpowiedniego układu, układ źródłowego slajdu zostanie sklonowany (gdy allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (gdy allowCloneMissingLayout jest false). |

**Zwraca:**
[ISlide](../../com.aspose.slides/islide) – Wstawiony slajd.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Slajd do usunięcia z kolekcji. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element pod określonym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks (zerowy) elementu do usunięcia. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Tworzy i zwraca tablicę ze wszystkimi slajdami.

**Zwraca:**
com.aspose.slides.ISlide[] – Tablica [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę ze wszystkimi slajdami z określonego zakresu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego slajdu do dodania. |
| count | int | Liczba slajdów do dodania. |

**Zwraca:**
com.aspose.slides.ISlide[] – Tablica [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Przemieszcza slajd z kolekcji na określone miejsce.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd do przeniesienia. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Przemieszcza slajdy z kolekcji na określone miejsce. Slajdy zostaną umieszczone zaczynając od indeksu w kolejności, w jakiej występują na liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Slajdy do przeniesienia. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Zwraca indeks określonego slajdu w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slajd do wyszukania. |

**Zwraca:**
int – Indeks slajdu lub -1, jeśli slajd nie należy do tej kolekcji.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
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
com.aspose.slides.ISlide[] – Dodane slajdy
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF.

--------------------

> ```
> Przykład:
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
com.aspose.slides.ISlide[] – Dodane slajdy
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

--------------------

> ```
> Przykład:
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
com.aspose.slides.ISlide[] – Dodane slajdy
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

--------------------

> ```
> Przykład:
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
com.aspose.slides.ISlide[] – Dodane slajdy
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotny używany do pobierania zasobów zewnętrznych. Jeśli jest null, wszystkie zasoby zewnętrzne zostaną zignorowane. |
| uri | java.lang.String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML do dodania. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Obiekt Strumienia używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotny używany do pobierania zasobów zewnętrznych. Jeśli jest null, wszystkie zasoby zewnętrzne zostaną zignorowane. |
| uri | java.lang.String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Tworzy slajdy z tekstu HTML i dodaje je na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Obiekt Strumienia używany jako źródło pliku HTML. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotny używany do pobierania zasobów zewnętrznych. Jeśli jest null, wszystkie zasoby zewnętrzne zostaną zignorowane. |
| uri | java.lang.String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Strumienia używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotny używany do pobierania zasobów zewnętrznych. Jeśli jest null, wszystkie zasoby zewnętrzne zostaną zignorowane. |
| uri | java.lang.String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Strumienia używany jako źródło pliku HTML. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu czy od slajdu o podanym indeksie. Jeśli **true**, dane będą wstawiane w pustą przestrzeń slajdu o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlText | java.lang.String | HTML do dodania. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotny używany do pobierania zasobów zewnętrznych. Jeśli jest null, wszystkie zasoby zewnętrzne zostaną zignorowane. |
| uri | java.lang.String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu czy od slajdu o podanym indeksie. Jeśli **true**, dane będą wstawiane w pustą przestrzeń slajdu o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Strumienia używany jako źródło pliku HTML. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu czy od slajdu o podanym indeksie. Jeśli **true**, dane będą wstawiane w pustą przestrzeń slajdu o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tworzy slajdy z tekstu HTML i wstawia je do kolekcji w określonym miejscu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Pozycja wstawienia. |
| htmlStream | java.io.InputStream | Obiekt Strumienia używany jako źródło pliku HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt zwrotny używany do pobierania zasobów zewnętrznych. Jeśli jest null, wszystkie zasoby zewnętrzne zostaną zignorowane. |
| uri | java.lang.String | URI określonego HTML. Używany do rozwiązywania względnych odnośników. |
| useSlideWithIndexAsStart | boolean | Flaga określająca, jak rozpocząć wstawianie: od nowego slajdu czy od slajdu o podanym indeksie. Jeśli **true**, dane będą wstawiane w pustą przestrzeń slajdu o podanym indeksie. Jeśli **false**, dane zostaną dodane do utworzonych slajdów. |

**Zwraca:**
com.aspose.slides.ISlide[] – Dodane slajdy.