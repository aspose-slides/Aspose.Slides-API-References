---
title: ISlideCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de diapositives.
type: docs
url: /fr/com.aspose.slides/islidecollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Représente une collection de diapositives.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Ajoute une nouvelle diapositive vide à la fin de la collection. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Insère une copie d'une diapositive source spécifiée à la position spécifiée de la collection. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les diapositives. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Déplace la diapositive de la collection vers la position spécifiée. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Déplace les diapositives de la collection vers la position spécifiée. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Retourne l'index de la diapositive spécifiée dans la collection. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d'importation PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [ISlide](../../com.aspose.slides/islide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner. |

--------------------

Lors du clonage d'une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre les maîtres clonés automatiquement afin d'éviter la création de multiples clones du même maître de diapositive. Le clonage manuel des maîtres de diapositives ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) ou \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) pour cloner les diapositives, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) ou [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) pour cloner les mises en page et [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) pour cloner les maîtres. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Nouvelle diapositive.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée.

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
>      // Maintenant, la deuxième section contient une copie de la première diapositive.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| section | [ISection](../../com.aspose.slides/isection) | Section for a new slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - New slide.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Inserts a copy of a specified slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone.

--------------------

When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) or \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) for cloning masters. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Adds a new empty slide to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout for a slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Added slide.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Inserts a copy of a specified slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a new slide. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout for a slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Adds a copy of a specified slide to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide for a new slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - New slide.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Inserts a copy of a specified slide to specified position of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide for a new slide. |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - New slide.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

**Returns:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Removes the first occurrence of a specific object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | The slide to remove from the collection. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Creates and returns an array with all slides in it.

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Creates and returns an array with all slides from the specified range in it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first slide to add. |
| count | int | A number of slides to add. |

**Returns:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Déplace la diapositive de la collection vers la position spécifiée.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index cible. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive à déplacer. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Déplace les diapositives de la collection vers la position spécifiée. Les diapositives seront placées à partir de l'index dans l'ordre où elles apparaissent dans la liste.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index cible. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Diapositives à déplacer. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Returns an index of the specified slide in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide to find. |

**Returns:**
int - Index of a slide or -1 if slide not from this collection.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```
Creates slides from the PDF document and adds them to the end of the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | A path to the PDF document |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | A path to the PDF document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options for pdf import |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```
Creates slides from the PDF document and adds them to the end of the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | A stream which will be used as a source of the PDF document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options for pdf import |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Creates slides from the PDF document and adds them to the end of the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | A stream which will be used as a source of the PDF document |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | Html to add. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Creates slides from HTML text and adds them to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```
Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```


Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```
Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| useSlideWithIndexAsStart | boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | java.lang.String | Html to add. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | java.lang.String | An URI of the specified HTML. Used to resolve relative links. |
| useSlideWithIndexAsStart | boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Creates slides from HTML text and inserts them to the collection at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlStream | java.io.InputStream | A Stream object which will be used as a source of a HTML file. |
| useSlideWithIndexAsStart | boolean | This flag determines how to start insertion: from a new slide or from the slide with the specified index. If **true**, then data insertion will start from an empty space on the slide with the specified index. If **false**, then data will be added to the created slides. |

**Returns:**
com.aspose.slides.ISlide[] - Added slides
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)

Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlStream | java.io.InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | java.lang.String | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées.