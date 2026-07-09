---
title: SectionCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de sections.
type: docs
url: /fr/com.aspose.slides/sectioncollection/
---
**Héritage:**  
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Représente une collection de sections.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Récupère l'élément à l'index spécifié. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Ajoute une section de diapositives démarrée à partir d'une diapositive spécifique. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Ajoute une section vide à la fin de la collection. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Ajoute une section vide à la position spécifiée de la collection. |
| [size()](#size--) | Récupère le nombre d'éléments réellement contenus dans la collection. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Renvoie l'index de la section spécifiée dans la collection. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Supprime la section et les diapositives qu'elle contient. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Supprime la section. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Déplace la section et ses diapositives de la collection vers la position spécifiée. |
| [clear()](#clear--) | Supprime toutes les sections de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie l'intégralité de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un itérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l'ensemble de la collection. |

### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Récupère l'élément à l'index spécifié. Lecture seule [ISection](../../com.aspose.slides/isection).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**  
[ISection](../../com.aspose.slides/isection)

### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Ajoute une section de diapositives démarrée à partir d'une diapositive spécifique.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la section |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Première diapositive de la section |

**Retour:**  
[ISection](../../com.aspose.slides/isection) - Section ajoutée.

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Ajoute une section vide à la fin de la collection.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la section |

**Retour:**  
[ISection](../../com.aspose.slides/isection) - Section ajoutée.

### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Ajoute une section vide à la position spécifiée de la collection.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la section |
| index | int | Index de la nouvelle section. |

**Retour:**  
[ISection](../../com.aspose.slides/isection) - Section ajoutée.

### size() {#size--}
```
public final int size()
```

Récupère le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Retour:**  
int

### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Renvoie l'index de la section spécifiée dans la collection.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section à rechercher. |

**Retour:**  
int - Index d'une section ou -1 si la section ne provient pas de cette collection.

### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Supprime la section et les diapositives qu'elle contient.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La section à supprimer de la collection. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Supprime la section. Les diapositives contenues dans la section seront fusionnées avec la section précédente.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La section à supprimer de la collection. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Déplace la section et ses diapositives de la collection vers la position spécifiée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section à déplacer. |
| index | int | Index cible. |

### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les sections de la collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie l'intégralité de la collection dans le tableau spécifié.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible |
| index | int | Index dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule booléen.

**Retour:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie la racine de synchronisation. Lecture seule Object.

**Retour:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Renvoie un itérateur qui parcourt la collection.

**Retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Renvoie un itérateur Java pour l'ensemble de la collection.

**Retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un java.util.Iterator pour l'ensemble de la collection.