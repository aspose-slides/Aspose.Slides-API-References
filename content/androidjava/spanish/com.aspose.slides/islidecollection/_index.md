---
title: ISlideCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una colección de diapositivas.
type: docs
url: /es/com.aspose.slides/islidecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Representa una colección de diapositivas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Añade una copia de una diapositiva especificada al final de la colección. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Añade una copia de una diapositiva especificada al final de la sección especificada. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Añade una nueva diapositiva vacía al final de la colección. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Añade una copia de una diapositiva especificada al final de la colección. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Inserta una copia de una diapositiva especificada en la posición especificada de la colección. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Añade una copia de una diapositiva fuente especificada al final de la colección. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Inserta una copia de una diapositiva fuente especificada en la posición especificada de la colección. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Elimina la primera aparición de un objeto específico de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [toArray()](#toArray--) | Crea y devuelve una matriz con todas las diapositivas. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea y devuelve una matriz con todas las diapositivas del rango especificado. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Mueve una diapositiva de la colección a la posición especificada. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Mueve diapositivas de la colección a la posición especificada. Las diapositivas se colocarán a partir del índice en el orden en que aparecen en la lista. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Devuelve un índice de la diapositiva especificada en la colección. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Crea diapositivas a partir del documento PDF y las añade al final de la colección. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Crea diapositivas a partir del documento PDF y las añade al final de la colección considerando las opciones de importación de PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Crea diapositivas a partir del documento PDF y las añade al final de la colección. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Crea diapositivas a partir del documento PDF y las añade al final de la colección. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Crea diapositivas a partir de texto HTML y las añade al final de la colección. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [ISlide](../../com.aspose.slides/islide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Añade una copia de una diapositiva especificada al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a clonar.

--------------------

Cuando se clona una diapositiva entre presentaciones diferentes, también puede clonarse el maestro de la diapositiva. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro. La clonación manual de maestros de diapositiva no será ni impedida ni registrada. Si necesita más control sobre el proceso de clonación, use \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) o \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) para clonar diapositivas, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) o [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) para clonar diseños y [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) para clonar maestros. |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Nueva diapositiva.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Añade una copia de una diapositiva especificada al final de la sección especificada.

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
>      // Ahora la segunda sección contiene una copia de la primera diapositiva.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a clonar. |
| section | [ISection](../../com.aspose.slides/isection) | Sección para la nueva diapositiva. |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Nueva diapositiva.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a clonar.

--------------------

Cuando se clona una diapositiva entre presentaciones diferentes, también puede clonarse el maestro de la diapositiva. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro. La clonación manual de maestros de diapositiva no será ni impedida ni registrada. Si necesita más control sobre el proceso de clonación, use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) o \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) para clonar diapositivas y [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) para clonar maestros. |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva insertada.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Añade una nueva diapositiva vacía al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diseño para la diapositiva. |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva añadida.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diseño para la diapositiva. |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva insertada.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Añade una copia de una diapositiva especificada al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a clonar. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diseño de diapositiva para la nueva diapositiva. |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Nueva diapositiva.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a clonar. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diseño de diapositiva para la nueva diapositiva. |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva insertada.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Añade una copia de una diapositiva fuente especificada al final de la colección. Se seleccionará automáticamente el diseño apropiado del maestro especificado (el diseño apropiado es el que tiene el mismo Tipo o Nombre que el diseño de la diapositiva fuente). Si no existe un diseño apropiado, se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a clonar. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Maestro de diapositiva para la nueva diapositiva. |
| allowCloneMissingLayout | boolean | Si no existe un diseño apropiado en el maestro especificado, se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Nueva diapositiva.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Inserta una copia de una diapositiva fuente especificada en la posición especificada de la colección. Se seleccionará automáticamente el diseño apropiado del maestro especificado (el diseño apropiado es el que tiene el mismo Tipo o Nombre que el diseño de la diapositiva fuente). Si no existe un diseño apropiado, se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a clonar. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Maestro de diapositiva para la nueva diapositiva. |
| allowCloneMissingLayout | boolean | Si no existe un diseño apropiado en el maestro especificado, se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide) - Diapositiva insertada.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Elimina la primera aparición de un objeto específico de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | La diapositiva a eliminar de la colección. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Crea y devuelve una matriz con todas las diapositivas.

**Devuelve:**
com.aspose.slides.ISlide[] - Matriz de [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Crea y devuelve una matriz con todas las diapositivas del rango especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Índice de la primera diapositiva a añadir. |
| count | int | Número de diapositivas a añadir. |

**Devuelve:**
com.aspose.slides.ISlide[] - Matriz de [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Mueve una diapositiva de la colección a la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice objetivo. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a mover. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Mueve diapositivas de la colección a la posición especificada. Las diapositivas se colocarán a partir del índice en el orden en que aparecen en la lista.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice objetivo. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Diapositivas a mover. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Devuelve un índice de la diapositiva especificada en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva a buscar. |

**Devuelve:**
int - Índice de una diapositiva o -1 si la diapositiva no pertenece a esta colección.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Crea diapositivas a partir del documento PDF y las añade al final de la colección.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta al documento PDF |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Crea diapositivas a partir del documento PDF y las añade al final de la colección considerando las opciones de importación de PDF.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta al documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opciones para la importación de PDF |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Crea diapositivas a partir del documento PDF y las añade al final de la colección.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Flujo que se usará como fuente del documento PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opciones para la importación de PDF |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Crea diapositivas a partir del documento PDF y las añade al final de la colección.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Flujo que se usará como fuente del documento PDF |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Crea diapositivas a partir de texto HTML y las añade al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | java.lang.String | HTML a añadir. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, se ignorarán todos los objetos externos. |
| uri | java.lang.String | URI del HTML especificado. Se usa para resolver enlaces relativos. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Crea diapositivas a partir de texto HTML y las añade al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlText | java.lang.String | HTML a añadir. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Crea diapositivas a partir de texto HTML y las añade al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objeto Stream que se usará como fuente de un archivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, se ignorarán todos los objetos externos. |
| uri | java.lang.String | URI del HTML especificado. Se usa para resolver enlaces relativos. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Crea diapositivas a partir de texto HTML y las añade al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Objeto Stream que se usará como fuente de un archivo HTML. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlText | java.lang.String | HTML a añadir. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, se ignorarán todos los objetos externos. |
| uri | java.lang.String | URI del HTML especificado. Se usa para resolver enlaces relativos. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlText | java.lang.String | HTML a añadir. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlStream | java.io.InputStream | Objeto Stream que se usará como fuente de un archivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, se ignorarán todos los objetos externos. |
| uri | java.lang.String | URI del HTML especificado. Se usa para resolver enlaces relativos. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlStream | java.io.InputStream | Objeto Stream que se usará como fuente de un archivo HTML. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlText | java.lang.String | HTML a añadir. |
| useSlideWithIndexAsStart | boolean | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlText | java.lang.String | HTML a añadir. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, se ignorarán todos los objetos externos. |
| uri | java.lang.String | URI del HTML especificado. Se usa para resolver enlaces relativos. |
| useSlideWithIndexAsStart | boolean | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlStream | java.io.InputStream | Objeto Stream que se usará como fuente de un archivo HTML. |
| useSlideWithIndexAsStart | boolean | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Posición donde insertar. |
| htmlStream | java.io.InputStream | Objeto Stream que se usará como fuente de un archivo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, se ignorarán todos los objetos externos. |
| uri | java.lang.String | URI del HTML especificado. Se usa para resolver enlaces relativos. |
| useSlideWithIndexAsStart | boolean | Esta bandera determina cómo iniciar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción comenzará en un espacio vacío de la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

**Devuelve:**
com.aspose.slides.ISlide[] - Diapositivas añadidas.