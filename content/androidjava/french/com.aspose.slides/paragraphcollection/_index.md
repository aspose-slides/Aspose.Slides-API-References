---
title: ParagraphCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une collection de paragraphes.
type: docs
url: /fr/com.aspose.slides/paragraphcollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Représente une collection de paragraphes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [isReadOnly()](#isReadOnly--) | Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Ajoute un Paragraph à la fin de la collection. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Ajoute le contenu d'un ParagraphCollection à la fin de la collection. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Détermine l'index d'un élément spécifique dans la List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Insère un Paragraph dans la collection à l'index spécifié. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Insère le contenu d'un ParagraphCollection dans la collection à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un tableau, en commençant à un index de tableau particulier. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'une collection de paragraphes. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'une collection de paragraphes. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Ajoute du texte à partir d'une chaîne HTML spécifiée à la collection. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Ajoute du texte à partir d'une chaîne HTML spécifiée à la collection. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Convertit les paragraphes spécifiés en HTML et le renvoie sous forme d'objet String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule.

**Renvoie :**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule. booléen en lecture seule.

**Renvoie :**
boolean - true si le [IGenericCollection](../../com.aspose.slides/igenericcollection) est en lecture seule ; sinon, false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Ajoute un Paragraph à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Le Paragraph à ajouter à la fin de la collection. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Ajoute le contenu d'un ParagraphCollection à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Le ParagraphCollection à ajouter à la fin de la collection. |

**Renvoie :**
int - L'index auquel le Paragraph a été ajouté ou -1 s'il n'y a rien à ajouter.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Détermine l'index d'un élément spécifique dans la List.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | L'objet à localiser dans la List. |

**Renvoie :**
int - L'index de l'item s'il est trouvé dans la liste ; sinon, -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Insère un Paragraph dans la collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où le Paragraph doit être inséré. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Le Paragraph à insérer. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Insère le contenu d'un ParagraphCollection dans la collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où les paragraphes doivent être insérés. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Les paragraphes à insérer. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments de la collection.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Détermine si le [IGenericCollection](../../com.aspose.slides/igenericcollection) contient une valeur spécifique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | L'objet à localiser dans le [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**
boolean - true si l'item est trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Copie les éléments du [IGenericCollection](../../com.aspose.slides/igenericcollection) dans un tableau, en commençant à un index de tableau particulier.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Le tableau unidimensionnel qui est la destination des éléments copiés depuis [IGenericCollection](../../com.aspose.slides/igenericcollection). Le tableau doit être indexé à partir de zéro. |
| arrayIndex | int | L'index basé sur zéro dans le tableau où la copie commence. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Supprime la première occurrence d'un objet spécifique du [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | L'objet à supprimer du [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Renvoie :**
boolean - true si l'item a été supprimé avec succès du [IGenericCollection](../../com.aspose.slides/igenericcollection) ; sinon, false. Cette méthode renvoie également false si l'item n'est pas trouvé dans le [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Un java.util.Iterator pour l'ensemble de la collection.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parente d'une collection de paragraphes. [BaseSlide](../../com.aspose.slides/baseslide) en lecture seule.

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente d'une collection de paragraphes. [IPresentation](../../com.aspose.slides/ipresentation) en lecture seule.

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Ajoute du texte à partir d'une chaîne HTML spécifiée à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Ajoute du texte à partir d'une chaîne HTML spécifiée à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objet de rappel du résolveur qui résout les URI et récupère les objets référencés. |
| uri | java.lang.String | URI pour l'ajout du document HTML. Utilisé pour la résolution des liens relatifs.

--------------------

Spécifier un résolveur peut potentiellement introduire une vulnérabilité. Utilisez avec précaution. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Convertit les paragraphes spécifiés en HTML et le renvoie sous forme d'objet String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | Index du premier paragraphe |
| paragraphsCount | int | Nombre de paragraphes |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Options de conversion [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Renvoie :**
java.lang.String - HTML généré.