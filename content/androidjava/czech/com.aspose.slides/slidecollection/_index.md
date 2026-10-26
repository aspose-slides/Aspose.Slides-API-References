---
title: SlideCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje kolekci snímků.
type: docs
url: /cs/com.aspose.slides/slidecollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Představuje kolekci snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet prvků skutečně obsažených v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadaném indexu. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Přidá kopii určeného snímku na konec kolekce. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Přidá kopii určeného snímku na konec určené sekce. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Vloží kopii určeného snímku na specifikovanou pozici v kolekci. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Přidá nový prázdný snímek na konec kolekce. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Vloží kopii určeného snímku na specifikovanou pozici v kolekci. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Přidá kopii určeného snímku na konec kolekce. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Vloží kopii určeného snímku na specifikovanou pozici v kolekci. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Přidá kopii určeného zdrojového snímku na konec kolekce. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Vloží kopii určeného zdrojového snímku na specifikovanou pozici v kolekci. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi snímky. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole se všemi snímky ze zadaného rozsahu. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Přesune snímek z kolekce na zadanou pozici. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Přesune snímky z kolekce na zadanou pozici. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Vrací index určeného snímku v kolekci. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce s ohledem na možnosti importu PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |

### size() {#size--}
```
public final int size()
```

Vrací počet prvků skutečně obsažených v kolekci. Pouze pro čtení int.

**Vrací:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Vrací prvek na zadaném indexu. Pouze pro čtení [Slide](../../com.aspose.slides/slide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Přidá kopii určeného snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) or \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) for cloning slides, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) or [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) for cloning layouts and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Přidá kopii určeného snímku na konec určené sekce.

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
>      // Nyní druhá sekce obsahuje kopii prvního snímku.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| section | [ISection](../../com.aspose.slides/isection) | Sekce pro nový snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Vloží kopii určeného snímku na specifikovanou pozici v kolekci.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Vytvořte instanci třídy Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Zkopírujte požadovaný snímek na konec kolekce snímků ve stejné prezentaci
>      ISlideCollection slds = pres.getSlides();
>      // Zkopírujte požadovaný snímek na určený index ve stejné prezentaci
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Uložte upravenou prezentaci na disk
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Vytvořte instanci třídy Presentation pro načtení zdrojového souboru prezentace
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Vytvořte instanci třídy Presentation pro cílový PPTX (kam bude snímek klonován)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Uložte cílovou prezentaci na disk
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) or \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Přidá nový prázdný snímek na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení pro snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - Added slide.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Vloží kopii určeného snímku na specifikovanou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení pro snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Přidá kopii určeného snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozložení snímku pro nový snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Vloží kopii určeného snímku na specifikovanou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozložení snímku pro nový snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Přidá kopii určeného zdrojového snímku na konec kolekce. Vhodné rozvržení bude automaticky vybráno z určeného masteru (vhodné rozvržení je rozvržení se stejným Typem nebo Názvem jako rozvržení zdrojového snímku). Pokud neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena PptxEditException (pokud je allowCloneMissingLayout false).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master snímek pro nový snímek. |
| allowCloneMissingLayout | boolean | Pokud v určeném masteru neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena PptxEditException (pokud je allowCloneMissingLayout false). |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Vloží kopii určeného zdrojového snímku na specifikovanou pozici v kolekci. Vhodné rozvržení bude automaticky vybráno z určeného masteru (vhodné rozvržení je rozvržení se stejným Typem nebo Názvem jako rozvržení zdrojového snímku). Pokud neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena PptxEditException (pokud je allowCloneMissingLayout false).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master snímek pro nový snímek. |
| allowCloneMissingLayout | boolean | Pokud v určeném masteru neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyhozena PptxEditException (pokud je allowCloneMissingLayout false). |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Odstraní první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Snímek, který má být z kolekce odstraněn. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nula-založený index prvku, který má být odstraněn. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator, který lze použít k iteraci přes kolekci.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Vrací java iterator pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator pro celou kolekci.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Vytvoří a vrátí pole se všemi snímky.

**Vrací:**
com.aspose.slides.ISlide[] - Pole [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole se všemi snímky ze zadaného rozsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního snímku k přidání. |
| count | int | Počet snímků k přidání. |

**Vrací:**
com.aspose.slides.ISlide[] - Pole [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Přesune snímek z kolekce na zadanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek k přesunu. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Přesune snímky z kolekce na zadanou pozici. Snímky budou umístěny od indexu v pořadí, v jakém se v seznamu objeví.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Snímky k přesunu. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Vrací index určeného snímku v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek k vyhledání. |

**Vrací:**
int - Index snímku nebo -1, pokud snímek není z této kolekce.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta k PDF dokumentu |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce s ohledem na možnosti importu PDF.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| path | java.lang.String | Cesta k PDF dokumentu |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Možnosti pro import PDF |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Proud, který bude použit jako zdroj PDF dokumentu |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Proud, který bude použit jako zdroj PDF dokumentu |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Možnosti pro import PDF |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML k přidání. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI určeného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML k přidání. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Stream objekt, který bude použit jako zdroj HTML souboru. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI určeného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

--------------------

> ```
> // Vytvořte instanci třídy Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Zavolejte metodu AddFromHtml a předejte HTML soubor.
>          pres.getSlides().addFromHtml(fos);
>          // Použijte metodu Save k uložení souboru jako PowerPoint dokument.
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Stream objekt, který bude použit jako zdroj HTML souboru. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI určeného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI určeného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Stream objekt, který bude použit jako zdroj HTML souboru. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI určeného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Stream objekt, který bude použit jako zdroj HTML souboru. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Callback objekt používaný k načtení externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI určeného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Stream objekt, který bude použit jako zdroj HTML souboru. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na specifikovanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Stream objekt, který bude použit jako zdroj HTML souboru. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak začít vkládání: od nového snímku nebo od snímku se zadaným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku se zadaným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] - Added slides

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object