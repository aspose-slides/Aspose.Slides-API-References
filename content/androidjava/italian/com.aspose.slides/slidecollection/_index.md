---
title: SlideCollection
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta una raccolta di diapositive.
type: docs
url: /it/com.aspose.slides/slidecollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Rappresenta una raccolta di diapositive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Aggiunge una copia di una diapositiva specificata alla fine della raccolta. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Aggiunge una nuova diapositiva vuota alla fine della raccolta. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una diapositiva specificata alla fine della raccolta. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Aggiunge una copia di una diapositiva sorgente specificata alla fine della raccolta. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della raccolta. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera raccolta. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutte le diapositive al suo interno. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutte le diapositive dell'intervallo specificato al suo interno. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Sposta la diapositiva nella raccolta alla posizione specificata. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Sposta le diapositive nella raccolta alla posizione specificata. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Restituisce l'indice della diapositiva specificata nella raccolta. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta tenendo conto delle opzioni di importazione PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Crea diapositive da testo HTML e le aggiunge alla fine della raccolta. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce la radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi effettivamente contenuti nella raccolta. **Solo lettura** int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Restituisce l'elemento all'indice specificato. **Solo lettura** [Slide](../../com.aspose.slides/slide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare.

--------------------

Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anch'esso. Viene utilizzato un registro interno per tenere traccia dei master clonati automaticamente, evitando la creazione di più cloni dello stesso master. Il clonaggio manuale dei master non è né impedito né registrato. Se serve un maggiore controllo sul processo di clonazione, usare \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) o \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) per clonare diapositive, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) o [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) per clonare layout e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) per clonare master. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Nuova diapositiva.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata.

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
>      // Ora la seconda sezione contiene una copia della prima diapositiva.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| section | [ISection](../../com.aspose.slides/isection) | Sezione per la nuova diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Nuova diapositiva.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Istanzia la classe Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Clona la diapositiva desiderata alla fine della raccolta di diapositive nella stessa presentazione
>      ISlideCollection slds = pres.getSlides();
>      // Clona la diapositiva desiderata all'indice specificato nella stessa presentazione
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Scrivi la presentazione modificata su disco
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Istanzia la classe Presentation per caricare il file di presentazione sorgente
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Istanzia la classe Presentation per il PPTX di destinazione (dove la diapositiva sarà clonata)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Scrivi la presentazione di destinazione su disco
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare.

--------------------

Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anch'esso. Viene utilizzato un registro interno per tenere traccia dei master clonati automaticamente, evitando la creazione di più cloni dello stesso master. Il clonaggio manuale dei master non è né impedito né registrato. Se serve un maggiore controllo sul processo di clonazione, usare \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) o \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) per clonare diapositive e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) per clonare master. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Diapositiva inserita.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Aggiunge una nuova diapositiva vuota alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout per la diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Diapositiva aggiunta.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una nuova diapositiva. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout per la diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Diapositiva inserita.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout della diapositiva per la nuova diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Nuova diapositiva.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout della diapositiva per la nuova diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Diapositiva inserita.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Aggiunge una copia di una diapositiva sorgente specificata alla fine della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) oppure verrà lanciata una PptxEditException (se allowCloneMissingLayout è false).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master della diapositiva per la nuova diapositiva. |
| allowCloneMissingLayout | boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) oppure verrà lanciata una PptxEditException (se allowCloneMissingLayout è false). |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Nuova diapositiva.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) oppure verrà lanciata una PptxEditException (se allowCloneMissingLayout è false).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master della diapositiva per la nuova diapositiva. |
| allowCloneMissingLayout | boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) oppure verrà lanciata una PptxEditException (se allowCloneMissingLayout è false). |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) – Diapositiva inserita.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | La diapositiva da rimuovere dalla raccolta. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Un IGenericEnumerator utilizzabile per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Restituisce un iteratore Java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Un java.util.Iterator per l'intera raccolta.
### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Crea e restituisce un array con tutte le diapositive al suo interno.

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [Slide](../../com.aspose.slides/slide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Crea e restituisce un array con tutte le diapositive dell'intervallo specificato al suo interno.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Indice della prima diapositiva da aggiungere. |
| count | int | Numero di diapositive da aggiungere. |

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Sposta la diapositiva nella raccolta alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice target. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da spostare. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Sposta le diapositive nella raccolta alla posizione specificata. Le diapositive saranno posizionate a partire dall'indice, nell'ordine in cui appaiono nell'elenco.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice target. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Diapositive da spostare. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Restituisce l'indice della diapositiva specificata nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da trovare. |

**Restituisce:**
int - Indice della diapositiva o -1 se la diapositiva non appartiene a questa raccolta.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso al documento PDF |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta tenendo conto delle opzioni di importazione PDF.

--------------------

> ```
> Esempio:
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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso al documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opzioni per l'importazione PDF |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta.

--------------------

> ```
> Esempio:
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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Stream utilizzato come sorgente del documento PDF |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Stream utilizzato come sorgente del documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opzioni per l'importazione PDF |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le aggiunge alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto di callback usato per recuperare oggetti esterni. Se nullo, tutti gli oggetti esterni verranno ignorati. |
| uri | java.lang.String | URI dell'HTML specificato. Usato per risolvere collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Crea diapositive da testo HTML e le aggiunge alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | java.lang.String | HTML da aggiungere. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le aggiunge alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Stream utilizzato come sorgente del file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto di callback usato per recuperare oggetti esterni. Se nullo, tutti gli oggetti esterni verranno ignorati. |
| uri | java.lang.String | URI dell'HTML specificato. Usato per risolvere collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Crea diapositive da testo HTML e le aggiunge alla fine della raccolta.

--------------------

> ```
> // Crea un'istanza della classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Chiama il metodo AddFromHtml e passa il file HTML.
>          pres.getSlides().addFromHtml(fos);
>          // Usa il metodo Save per salvare il file come documento PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Stream utilizzato come sorgente del file HTML. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto di callback usato per recuperare oggetti esterni. Se nullo, tutti gli oggetti esterni verranno ignorati. |
| uri | java.lang.String | URI dell'HTML specificato. Usato per risolvere collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto di callback usato per recuperare oggetti esterni. Se nullo, tutti gli oggetti esterni verranno ignorati. |
| uri | java.lang.String | URI dell'HTML specificato. Usato per risolvere collegamenti relativi. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Stream utilizzato come sorgente del file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto di callback usato per recuperare oggetti esterni. Se nullo, tutti gli oggetti esterni verranno ignorati. |
| uri | java.lang.String | URI dell'HTML specificato. Usato per risolvere collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Stream utilizzato come sorgente del file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto di callback usato per recuperare oggetti esterni. Se nullo, tutti gli oggetti esterni verranno ignorati. |
| uri | java.lang.String | URI dell'HTML specificato. Usato per risolvere collegamenti relativi. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Stream utilizzato come sorgente del file HTML. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella raccolta nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Stream utilizzato come sorgente del file HTML. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). **Solo lettura** boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce la radice di sincronizzazione. **Solo lettura** Object.

**Restituisce:**
java.lang.Object