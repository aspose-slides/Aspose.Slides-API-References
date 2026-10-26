---
title: SlideCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di diapositive.
type: docs
url: /it/com.aspose.slides/slidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Rappresenta una raccolta di diapositive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Ottiene il numero di elementi effettivamente contenuti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento nell'indice specificato. |
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
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento nell'indice specificato della raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [toArray()](#toArray--) | Crea e restituisce un array con tutte le diapositive al suo interno. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array con tutte le diapositive dell'intervallo specificato al suo interno. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Sposta una diapositiva dalla raccolta alla posizione specificata. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Sposta le diapositive dalla raccolta alla posizione specificata. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Restituisce l'indice della diapositiva specificata nella raccolta. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta considerando le opzioni di importazione PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Crea diapositive dal documento PDF e le aggiunge alla fine della raccolta. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Crea diapositive dal testo HTML e le aggiunge alla fine della raccolta. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Crea diapositive dal testo HTML e le inserisce nella raccolta nella posizione specificata. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce la radice di sincronizzazione. |

### size() {#size--}
```
public final int size()
```

Ottiene il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Ottiene l'elemento nell'indice specificato. Solo lettura [Slide](../../com.aspose.slides/slide).

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

Durante la clonazione di una diapositiva tra presentazioni diverse, anche il master della diapositiva può essere clonato. Un registro interno viene utilizzato per tenere traccia dei master clonati automaticamente per evitare la creazione di più cloni dello stesso master di diapositiva. La clonazione manuale dei master non sarà né impedita né registrata. Se hai bisogno di un maggior controllo sul processo di clonazione, usa #addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) o #addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) per clonare le diapositive, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) o [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) per clonare i layout e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) per clonare i master. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Nuova diapositiva.

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
[ISlide](../../com.aspose.slides/islide) - Nuova diapositiva.

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
>  // Istanzia la classe Presentation per caricare il file di presentazione di origine
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Istanzia la classe Presentation per il PPTX di destinazione (dove la diapositiva deve essere clonata)
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

Durante la clonazione di una diapositiva tra presentazioni diverse, anche il master della diapositiva può essere clonato. Un registro interno viene utilizzato per tenere traccia dei master clonati automaticamente per evitare la creazione di più cloni dello stesso master di diapositiva. La clonazione manuale dei master non sarà né impedita né registrata. Se hai bisogno di un maggior controllo sul processo di clonazione, usa #insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) o #insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) per clonare le diapositive e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) per clonare i master. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva inserita.

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
[ISlide](../../com.aspose.slides/islide) - Diapositiva aggiunta.

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
[ISlide](../../com.aspose.slides/islide) - Diapositiva inserita.

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
[ISlide](../../com.aspose.slides/islide) - Nuova diapositiva.

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
[ISlide](../../com.aspose.slides/islide) - Diapositiva inserita.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Aggiunge una copia di una diapositiva sorgente specificata alla fine della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è il layout con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide per la nuova diapositiva. |
| allowCloneMissingLayout | boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false). |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Nuova diapositiva.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è il layout con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide per la nuova diapositiva. |
| allowCloneMissingLayout | boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false). |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva inserita.

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

Rimuove l'elemento nell'indice specificato della raccolta.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

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
| startIndex | int | Un indice della prima diapositiva da aggiungere. |
| count | int | Un numero di diapositive da aggiungere. |

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```


Sposta la diapositiva dalla collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da spostare. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```


Sposta le diapositive dalla collezione nella posizione specificata. Le diapositive saranno inserite a partire da *index* nell'ordine in cui appaiono nell'elenco.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Diapositive da spostare. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```


Restituisce l'indice della diapositiva specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da trovare. |

**Restituisce:**
int - Indice di una diapositiva o -1 se la diapositiva non appartiene a questa collezione.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```


Crea diapositive dal documento PDF e le aggiunge alla fine della collezione.

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


Crea diapositive dal documento PDF e le aggiunge alla fine della collezione considerando le opzioni di importazione PDF.

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


Crea diapositive dal documento PDF e le aggiunge alla fine della collezione.

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
| pdfStream | java.io.InputStream | Uno stream che verrà usato come sorgente del documento PDF |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```


Crea diapositive dal documento PDF e le aggiunge alla fine della collezione.

--------------------

> ```
> Esempio:
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
| pdfStream | java.io.InputStream | Uno stream che verrà usato come sorgente del documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opzioni per l'importazione PDF |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```


Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto callback usato per recuperare risorse esterne. Se questo parametro è null, tutte le risorse esterne saranno ignorate. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```


Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

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


Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto callback usato per recuperare risorse esterne. Se questo parametro è null, tutte le risorse esterne saranno ignorate. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```


Crea diapositive dal testo HTML e le aggiunge alla fine della collezione.

--------------------

> ```
> // Crea un'istanza della classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // Chiama il metodo AddFromHtml e passa il file HTML.
>      pres.getSlides().addFromHtml(html);
>      // Usa il metodo Save per salvare il file come documento PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà usato come sorgente di un file HTML. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto callback usato per recuperare risorse esterne. Se questo parametro è null, tutte le risorse esterne saranno ignorate. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto callback usato per recuperare risorse esterne. Se questo parametro è null, tutte le risorse esterne saranno ignorate. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà in uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlText | java.lang.String | HTML da aggiungere. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlText | java.lang.String | HTML da aggiungere. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà in uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto callback usato per recuperare risorse esterne. Se questo parametro è null, tutte le risorse esterne saranno ignorate. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto callback usato per recuperare risorse esterne. Se questo parametro è null, tutte le risorse esterne saranno ignorate. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà in uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà usato come sorgente di un file HTML. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```


Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione di inserimento. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà usato come sorgente di un file HTML. |
| useSlideWithIndexAsStart | boolean | Questo flag determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà in uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**
com.aspose.slides.ISlide[] - Diapositive aggiunte
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Booleano read-only.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce la radice di sincronizzazione. Oggetto read-only.

**Restituisce:**
java.lang.Object