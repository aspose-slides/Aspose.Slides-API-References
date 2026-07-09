---
title: MasterSlideCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de diapositives maîtresses.
type: docs
url: /fr/com.aspose.slides/masterslidecollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Représente une collection de diapositives maîtresses.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Supprime les diapositives maîtresses inutilisées. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Ajoute une copie d'une diapositive maîtresse spécifiée à la fin de la collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Insère une copie d'une diapositive maîtresse spécifiée à la position indiquée de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### size() {#size--}
```
public final int size()
```


Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Obtient l'élément à l'index spécifié. Lecture seule [MasterSlide](../../com.aspose.slides/masterslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Supprime la première occurrence d'un objet spécifique de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | La diapositive maîtresse à supprimer de la collection. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime l'élément à l'index spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer.

--------------------

Pour éviter le lancement de PptxEditException, vérifiez la propriété HasDependingSlides du maître au préalable. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Supprime les diapositives maîtresses inutilisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | Détermine si cette méthode doit supprimer les maîtres inutilisés même si leur propriété [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) est définie sur true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Ajoute une copie d'une diapositive maîtresse spécifiée à la fin de la collection. Les diapositives de disposition liées seront également copiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive à cloner. |

**Renvoie :**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositive ajoutée.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Insère une copie d'une diapositive maîtresse spécifiée à la position indiquée de la collection. Les diapositives de disposition liées seront également copiées.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instantiate Presentation class for destination presentation (where slide is to be cloned)
>      Presentation destPres = new Presentation();
>      try {
>          // Instantiate ISlide from the collection of slides in source presentation along with
>          // Master slide
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Get Master Slides of destination presentation
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clone the desired master slide from the source presentation to the collection of masters in the
>          // Destination presentation
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Collection of slides in the destination presentation
>          ISlideCollection slds = destPres.getSlides();
>          // Clone source slide to destination slides collection.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Save the destination presentation to disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide to clone. |

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Inserted master slide.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copies all elements from the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()


Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Un java.util.Iterator pour l'ensemble de la collection.