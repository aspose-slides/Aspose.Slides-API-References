---
title: ISlideCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di diapositive.
type: docs
url: /it/com.aspose.slides/islidecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Rappresenta una collezione di diapositive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Aggiunge una copia di una diapositiva specificata alla fine della collezione. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Aggiunge una nuova diapositiva vuota alla fine della collezione. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una diapositiva specificata alla fine della collezione. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Aggiunge una copia di una diapositiva di origine specificata alla fine della collezione. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Inserisce una copia di una diapositiva di origine specificata nella posizione specificata della collezione. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
| [toArray()](#toArray--) | Crea e restituisce un array contenente tutte le diapositive. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array contenente tutte le diapositive dell'intervallo specificato. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Sposta la diapositiva dalla collezione alla posizione specificata. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Sposta le diapositive dalla collezione alla posizione specificata. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Restituisce l'indice della diapositiva specificata nella collezione. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Crea diapositive dal documento PDF e le aggiunge alla fine della collezione. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Crea diapositive dal documento PDF e le aggiunge alla fine della collezione considerando le opzioni di importazione PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Crea diapositive dal documento PDF e le aggiunge alla fine della collezione. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Crea diapositive dal documento PDF e le aggiunge alla fine della collezione. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le aggiunge alla fine della collezione. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Crea diapositive dal testo HTML e le aggiunge alla fine della collezione. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le aggiunge alla fine della collezione. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Crea diapositive dal testo HTML e le aggiunge alla fine della collezione. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositive dal testo HTML e le inserisce nella collezione nella posizione specificata. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Solo lettura [ISlide](../../com.aspose.slides/islide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Aggiunge una copia di una diapositiva specificata alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |

--------------------

Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anche. Un registro interno è usato per tenere traccia dei master clonati automaticamente per evitare la creazione di più cloni dello stesso master. Il clonaggio manuale dei master non sarà né prevenuto né registrato. Se necessiti di un maggiore controllo sul processo di clonazione usa \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) o \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) per clonare le diapositive, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) o [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) per clonare i layout e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) per clonare i master.

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Nuova diapositiva.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
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
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |

--------------------

Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anche. Un registro interno è usato per tenere traccia dei master clonati automaticamente per evitare la creazione di più cloni dello stesso master. Il clonaggio manuale dei master non sarà né prevenuto né registrato. Se necessiti di un maggiore controllo sul processo di clonazione usa \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) o \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) per clonare le diapositive e [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) per clonare i master.

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva inserita.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Aggiunge una nuova diapositiva vuota alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout per la diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva aggiunta.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout per la diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva inserita.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Aggiunge una copia di una diapositiva specificata alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout della diapositiva per la nuova diapositiva. |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Nuova diapositiva.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.

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
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Aggiunge una copia di una diapositiva di origine alla fine della collezione. Il layout appropriato sarà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva di origine). Se non esiste un layout appropriato, il layout della diapositiva di origine sarà clonato (se allowCloneMissingLayout è true) o verrà lanciata PptxEditException (se allowCloneMissingLayout è false).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master della diapositiva per la nuova diapositiva. |
| allowCloneMissingLayout | boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva di origine sarà clonato (se allowCloneMissingLayout è true) o verrà lanciata PptxEditException (se allowCloneMissingLayout è false). |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Nuova diapositiva.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Inserisce una copia di una diapositiva di origine nella posizione specificata della collezione. Il layout appropriato sarà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva di origine). Se non esiste un layout appropriato, il layout della diapositiva di origine sarà clonato (se allowCloneMissingLayout è true) o verrà lanciata PptxEditException (se allowCloneMissingLayout è false).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master della diapositiva per la nuova diapositiva. |
| allowCloneMissingLayout | boolean | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva di origine sarà clonato (se allowCloneMissingLayout è true) o verrà lanciata PptxEditException (se allowCloneMissingLayout è false). |

**Restituisce:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva inserita.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | La diapositiva da rimuovere dalla collezione. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Crea e restituisce un array contenente tutte le diapositive.

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Crea e restituisce un array contenente tutte le diapositive dell'intervallo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Indice della prima diapositiva da aggiungere. |
| count | int | Numero di diapositive da aggiungere. |

**Restituisce:**
com.aspose.slides.ISlide[] - Array di [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Sposta la diapositiva dalla collezione alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva da spostare. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Sposta le diapositive dalla collezione alla posizione specificata. Le diapositive saranno inserite a partire dall'indice nell'ordine in cui appaiono nell'elenco.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Diapositive da spostare. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
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
public abstract ISlide[] addFromPdf(String path)
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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Un percorso al documento PDF |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Crea diapositive dal documento PDF e le aggiunge alla fine della collezione tenendo conto delle opzioni di importazione PDF.

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


**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Un percorso al documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opzioni per l'importazione PDF |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Crea diapositive dal documento PDF e le aggiunge alla fine della collezione.

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
| pdfStream | java.io.InputStream | Un flusso che verrà utilizzato come origine del documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opzioni per l'importazione PDF |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Crea diapositive dal documento PDF e le aggiunge alla fine della collezione.

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


**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Un flusso che verrà utilizzato come origine del documento PDF |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le aggiunge alla fine della collezione.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Crea diapositive da testo HTML e le aggiunge alla fine della collezione.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlText | java.lang.String | HTML da aggiungere. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le aggiunge alla fine della collezione.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà utilizzato come fonte di un file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Crea diapositive da testo HTML e le aggiunge alla fine della collezione.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà utilizzato come fonte di un file HTML. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà utilizzato come fonte di un file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà utilizzato come fonte di un file HTML. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |
| useSlideWithIndexAsStart | boolean | Questa opzione determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlText | java.lang.String | HTML da aggiungere. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | boolean | Questa opzione determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà utilizzato come fonte di un file HTML. |
| useSlideWithIndexAsStart | boolean | Questa opzione determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Crea diapositive da testo HTML e le inserisce nella collezione nella posizione specificata.

**Parametri:**  
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire. |
| htmlStream | java.io.InputStream | Un oggetto Stream che verrà utilizzato come fonte di un file HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| uri | java.lang.String | Un URI dell'HTML specificato. Usato per risolvere i collegamenti relativi. |
| useSlideWithIndexAsStart | boolean | Questa opzione determina come avviare l'inserimento: da una nuova diapositiva o dalla diapositiva con l'indice specificato. Se **true**, l'inserimento dei dati inizierà da uno spazio vuoto sulla diapositiva con l'indice specificato. Se **false**, i dati saranno aggiunti alle diapositive create. |

**Restituisce:**  
com.aspose.slides.ISlide[] - Diapositive aggiunte.