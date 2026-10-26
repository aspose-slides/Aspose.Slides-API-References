---
title: SlideCollection
second_title: Référence de l'API Aspose.Slides for Java
description: Représente une collection de diapositives.
type: docs
url: /fr/com.aspose.slides/slidecollection/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Représente une collection de diapositives.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Insère une copie d'une diapositive spécifiée à la position indiquée dans la collection. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Ajoute une nouvelle diapositive vide à la fin de la collection. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Insère une copie d'une diapositive spécifiée à la position indiquée dans la collection. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Insère une copie d'une diapositive spécifiée à la position indiquée dans la collection. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Insère une copie d'une diapositive source spécifiée à la position indiquée dans la collection. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant toutes les diapositives. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Déplace une diapositive de la collection vers la position spécifiée. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Déplace des diapositives de la collection vers la position spécifiée. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Renvoie l'index de la diapositive spécifiée dans la collection. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d'importation du PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |

### size() {#size--}
```
public final int size()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie :**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [Slide](../../com.aspose.slides/slide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner.

--------------------

Lors du clonage d'une diapositive entre différentes présentations, le master de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre les masters clonés automatiquement afin d'éviter la création de plusieurs clones du même master. Le clonage manuel des masters de diapositives ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) ou \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) pour cloner des diapositives, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) ou [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) pour cloner des mises en page et [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) pour cloner des masters. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Nouvelle diapositive.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée.

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
>      // Maintenant, la seconde section contient une copie de la première diapositive.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner. |
| section | [ISection](../../com.aspose.slides/isection) | Section pour la nouvelle diapositive. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Nouvelle diapositive.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Insère une copie d'une diapositive spécifiée à la position indiquée dans la collection.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Instancier la classe Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Cloner la diapositive désirée à la fin de la collection de diapositives de la même présentation
>      ISlideCollection slds = pres.getSlides();
>      // Cloner la diapositive désirée à l'index spécifié dans la même présentation
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Écrire la présentation modifiée sur le disque
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Instancier la classe Presentation pour charger le fichier de présentation source
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Instancier la classe Presentation pour le PPTX de destination (où la diapositive doit être clonée)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Écrire la présentation de destination sur le disque
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner.

--------------------

Lors du clonage d'une diapositive entre différentes présentations, le master de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre les masters clonés automatiquement afin d'éviter la création de plusieurs clones du même master. Le clonage manuel des masters de diapositives ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) ou \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) pour cloner des diapositives et [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) pour cloner des masters. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Diapositive insérée.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Ajoute une nouvelle diapositive vide à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Mise en page pour la diapositive. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Diapositive ajoutée.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Insère une copie d'une diapositive spécifiée à la position indiquée dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Mise en page pour la diapositive. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Diapositive insérée.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Mise en page de la nouvelle diapositive. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Nouvelle diapositive.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Insère une copie d'une diapositive spécifiée à la position indiquée dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Mise en page de la nouvelle diapositive. |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Diapositive insérée.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du master spécifié (la mise en page appropriée est celle dont le Type ou le Name correspond à celui de la mise en page de la diapositive source). S'il n'existe aucune mise en page appropriée, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master de la nouvelle diapositive. |
| allowCloneMissingLayout | boolean | Si aucun layout approprié n'existe dans le master spécifié, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false). |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Nouvelle diapositive.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Insère une copie d'une diapositive source spécifiée à la position indiquée dans la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du master spécifié (la mise en page appropriée est celle dont le Type ou le Name correspond à celui de la mise en page de la diapositive source). S'il n'existe aucune mise en page appropriée, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Diapositive à cloner. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master de la nouvelle diapositive. |
| allowCloneMissingLayout | boolean | Si aucun layout approprié n'existe dans le master spécifié, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est true) ou une PptxEditException sera levée (si allowCloneMissingLayout est false). |

**Renvoie :**
[ISlide](../../com.aspose.slides/islide) - Diapositive insérée.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Supprime la première occurrence d'un objet spécifique de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | La diapositive à supprimer de la collection. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Un java.util.Iterator pour l'ensemble de la collection.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Crée et renvoie un tableau contenant toutes les diapositives.

**Renvoie :**
com.aspose.slides.ISlide[] - Tableau de [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Index de la première diapositive à ajouter. |
| count | int | Nombre de diapositives à ajouter. |

**Renvoie :**
com.aspose.slides.ISlide[] - Tableau de [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```


Déplace la diapositive de la collection vers la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index cible. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive à déplacer. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```


Déplace les diapositives de la collection vers la position spécifiée. Les diapositives seront placées à partir de l'index dans l'ordre où elles apparaissent dans la liste.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index cible. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Diapositives à déplacer. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```


Renvoie l'index de la diapositive spécifiée dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive à rechercher. |

**Renvoie :**
int - Index d'une diapositive ou -1 si la diapositive ne provient pas de cette collection.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```


Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin vers le document PDF |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```


Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d'importation PDF.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Chemin vers le document PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options d'importation PDF |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```


Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Un flux qui sera utilisé comme source du document PDF |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```


Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Un flux qui sera utilisé comme source du document PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Options d'importation PDF |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```


Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML à ajouter. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | java.lang.String | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```


Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML à ajouter. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```


Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | java.lang.String | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```


Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

--------------------

> ```
> // Créez une instance de la classe Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // Appelez la méthode AddFromHtml et passez le fichier HTML.
>      pres.getSlides().addFromHtml(html);
>      // Utilisez la méthode Save pour enregistrer le fichier en document PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlText | java.lang.String | HTML à ajouter. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | java.lang.String | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées.
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlText | java.lang.String | HTML à ajouter. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | java.lang.String | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlText | java.lang.String | HTML à ajouter. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlText | java.lang.String | HTML à ajouter. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlStream | java.io.InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | java.lang.String | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées.
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlStream | java.io.InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | java.lang.String | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlStream | java.io.InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position d'insertion. |
| htmlStream | java.io.InputStream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| useSlideWithIndexAsStart | boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

**Renvoie :**
com.aspose.slides.ISlide[] - Diapositives ajoutées
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Booléen en lecture seule.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie la racine de synchronisation. Objet en lecture seule.

**Renvoie :**
java.lang.Object