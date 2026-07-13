---
title: ISlideCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje kolekci snímků.
type: docs
url: /cs/com.aspose.slides/islidecollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Představuje kolekci snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Přidá kopii zadaného snímku na konec kolekce. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Přidá kopii zadaného snímku na konec zadané sekce. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Přidá nový prázdný snímek na konec kolekce. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Přidá kopii zadaného snímku na konec kolekce. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Vloží kopii zadaného snímku na určenou pozici v kolekci. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Přidá kopii zadaného zdrojového snímku na konec kolekce. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Vloží kopii zadaného zdrojového snímku na určenou pozici v kolekci. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [toArray()](#toArray--) | Vytvoří a vrátí pole se všemi snímky. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Vytvoří a vrátí pole se všemi snímky ze zadaného rozsahu. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Přesune snímek z kolekce na určenou pozici. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Přesune snímky z kolekce na určenou pozici. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Vrátí index zadaného snímku v kolekci. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce s ohledem na možnosti importu PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Vytvoří snímky z HTML textu a přidá je na konec kolekce. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Získá prvek na zadaném indexu. Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Přidá kopii zadaného snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování.

--------------------

Při klonování snímku mezi různými prezentacemi může být také klonován master snímku. Interní registr se používá k automatickému sledování klonovaných masterů, aby se zabránilo vytvoření více klonů stejného master snímku. Ruční klonování master snímků nebude ani zabráněno, ani zaznamenáno. Pokud potřebujete větší kontrolu nad procesem klonování, použijte \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) nebo \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) pro klonování snímků, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) nebo [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) pro klonování rozvržení a [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) pro klonování masterů. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Nový snímek.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Přidá kopii zadaného snímku na konec zadané sekce.

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
[ISlide](../../com.aspose.slides/islide) – Nový snímek.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Vloží kopii zadaného snímku na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování.

--------------------

Při klonování snímku mezi různými prezentacemi může být také klonován master snímku. Interní registr se používá k automatickému sledování klonovaných masterů, aby se zabránilo vytvoření více klonů stejného master snímku. Ruční klonování master snímků nebude ani zabráněno, ani zaznamenáno. Pokud potřebujete větší kontrolu nad procesem klonování, použijte \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) nebo \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) pro klonování snímků a [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) pro klonování masterů. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Vložený snímek.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Přidá nový prázdný snímek na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení pro snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Přidaný snímek.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Vloží kopii zadaného snímku na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení pro snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Vložený snímek.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Přidá kopii zadaného snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení snímku pro nový snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Nový snímek.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Vloží kopii zadaného snímku na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení snímku pro nový snímek. |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Vložený snímek.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Přidá kopii zadaného zdrojového snímku na konec kolekce. Vhodné rozvržení bude automaticky vybráno ze zadaného masteru (vhodné rozvržení je rozvržení se stejným Typem nebo názvem jako rozvržení zdrojového snímku). Pokud neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master snímek pro nový snímek. |
| allowCloneMissingLayout | boolean | Pokud v určeném masteru neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Nový snímek.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Vloží kopii zadaného zdrojového snímku na určenou pozici v kolekci. Vhodné rozvržení bude automaticky vybráno ze zadaného masteru (vhodné rozvržení je rozvržení se stejným Typem nebo názvem jako rozvržení zdrojového snímku). Pokud neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master snímek pro nový snímek. |
| allowCloneMissingLayout | boolean | Pokud v určeném masteru neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |

**Vrací:**
[ISlide](../../com.aspose.slides/islide) – Vložený snímek.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Odstraní první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Snímek, který má být odstraněn z kolekce. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Vytvoří a vrátí pole se všemi snímky.

**Vrací:**
com.aspose.slides.ISlide[] – Pole [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Vytvoří a vrátí pole se všemi snímky ze zadaného rozsahu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | int | Index prvního snímku, který se má přidat. |
| count | int | Počet snímků, které se mají přidat. |

**Vrací:**
com.aspose.slides.ISlide[] – Pole [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Přesune snímek z kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek k přesunu. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Přesune snímky z kolekce na určenou pozici. Snímek bude umístěn od zadaného indexu v pořadí, v jakém se objeví v seznamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Snímky k přesunu. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Vrátí index zadaného snímku v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Snímek k vyhledání. |

**Vrací:**
int – Index snímku nebo -1, pokud snímek není součástí této kolekce.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
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
com.aspose.slides.ISlide[] – Přidané snímky

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Možnosti importu PDF |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Možnosti importu PDF |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.

--------------------

> ```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Proud, který bude použit jako zdroj PDF dokumentu |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML k přidání. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání pro získání externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlText | java.lang.String | HTML k přidání. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objekt proudu, který bude použit jako zdroj HTML souboru. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání pro získání externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Vytvoří snímky z HTML textu a přidá je na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objekt proudu, který bude použit jako zdroj HTML souboru. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání pro získání externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Objekt proudu, který bude použit jako zdroj HTML souboru. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání pro získání externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Objekt proudu, který bude použit jako zdroj HTML souboru. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak zahájit vkládání: od nového snímku nebo od snímku s daným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku s daným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlText | java.lang.String | HTML k přidání. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání pro získání externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak zahájit vkládání: od nového snímku nebo od snímku s daným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku s daným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Objekt proudu, který bude použit jako zdroj HTML souboru. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak zahájit vkládání: od nového snímku nebo od snímku s daným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku s daným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Vytvoří snímky z HTML textu a vloží je do kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Pozice pro vložení. |
| htmlStream | java.io.InputStream | Objekt proudu, který bude použit jako zdroj HTML souboru. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání pro získání externích objektů. Pokud je tento parametr null, budou všechny externí objekty ignorovány. |
| uri | java.lang.String | URI specifikovaného HTML. Používá se k řešení relativních odkazů. |
| useSlideWithIndexAsStart | boolean | Toto nastavení určuje, jak zahájit vkládání: od nového snímku nebo od snímku s daným indexem. Pokud je **true**, data se začnou vkládat do prázdného prostoru na snímku s daným indexem. Pokud je **false**, data budou přidána do vytvořených snímků. |

**Vrací:**
com.aspose.slides.ISlide[] – Přidané snímky.