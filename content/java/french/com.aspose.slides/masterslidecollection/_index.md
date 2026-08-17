---
title: MasterSlideCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection de diapositives maîtres.
type: docs
url: /fr/com.aspose.slides/masterslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Représente une collection de diapositives maîtres.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Supprime les diapositives maîtres inutilisées. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Ajoute une copie d'une diapositive maître spécifiée à la fin de la collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Insère une copie d'une diapositive maître spécifiée à la position spécifiée de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### size() {#size--}
```
public final int size()
```


Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Obtient l'élément à l'index spécifié. Lecture seule [MasterSlide](../../com.aspose.slides/masterslide).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Supprime la première occurrence d'un objet spécifique de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | La diapositive maître à supprimer de la collection. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Supprime l'élément à l'index spécifié de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer.

--------------------

Pour éviter le lancement de PptxEditException, vérifiez la propriété HasDependingSlides du maître au préalable. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Supprime les diapositives maîtres inutilisées.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | Détermine si cette méthode doit supprimer les maîtres inutilisés même si la propriété [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) est définie sur true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Ajoute une copie d'une diapositive maître spécifiée à la fin de la collection. Les diapositives de mise en page liées seront également copiées.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive à dupliquer. |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositive ajoutée.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Insère une copie d'une diapositive maître spécifiée à la position spécifiée de la collection. Les diapositives de mise en page liées seront également copiées.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instancier la classe Presentation pour charger le fichier de présentation source
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instancier la classe Presentation pour la présentation destination (où la diapositive sera clonée)
>      Presentation destPres = new Presentation();
>      try {
>          // Instancier ISlide à partir de la collection de diapositives de la présentation source ainsi que
>          // Diapositive maîtresse
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Obtenir les diapositives maîtres de la présentation destination
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Cloner la diapositive maîtresse souhaitée de la présentation source vers la collection de maîtres dans la
>          // Présentation destination
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Collection de diapositives dans la présentation destination
>          ISlideCollection slds = destPres.getSlides();
>          // Cloner la diapositive source vers la collection de diapositives de destination.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Enregistrer la présentation destination sur le disque
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive à dupliquer. |

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositive maître insérée.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie une racine de synchronisation. Lecture seule Object.

**Retour:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Un java.util.Iterator pour l'ensemble de la collection.