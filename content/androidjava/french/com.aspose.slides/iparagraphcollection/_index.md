---
title: IParagraphCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de paragraphes.
type: docs
url: /fr/com.aspose.slides/iparagraphcollection/
---
**Toutes les interfaces implémentées**:
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Représente une collection de paragraphes.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Récupère l'élément à l'index spécifié. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Ajoute un Paragraph à la fin de la collection. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Ajoute le contenu de ParagraphCollection à la fin de la collection. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Insère un Paragraph dans la collection à l'index spécifié. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Insère le contenu de ParagraphCollection dans la collection à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Supprime la première occurrence d'un paragraphe spécifique. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Ajoute du texte à partir de la chaîne HTML spécifiée à la collection. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Ajoute du texte à partir de la chaîne HTML spécifiée à la collection. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Convertit les paragraphes spécifiés en HTML et le renvoie sous forme d'objet String. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Récupère l'élément à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IParagraph](../../com.aspose.slides/iparagraph)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre d'éléments réellement contenus dans la collection. int en lecture seule.

**Retour:**
int

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Ajoute un Paragraph à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Le Paragraph à ajouter à la fin de la collection. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Ajoute le contenu de ParagraphCollection à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Le ParagraphCollection à ajouter à la fin de la collection. |

**Retour:**
int - L'index auquel le Paragraph a été ajouté ou -1 s'il n'y a rien à ajouter.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Insère un Paragraph dans la collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où le Paragraph doit être inséré. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Le Paragraph à insérer. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Insère le contenu de ParagraphCollection dans la collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro où les paragraphes doivent être insérés. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Les paragraphes à insérer. |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les éléments de la collection.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Supprime la première occurrence d'un paragraphe spécifique.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Le paragraphe à supprimer de la collection. |

**Retour:**
boolean - true si l'élément a été supprimé avec succès ; sinon, false.

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Ajoute du texte à partir de la chaîne HTML spécifiée à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Ajoute du texte à partir de la chaîne HTML spécifiée à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objet de rappel du résolveur qui résout les URI et récupère les objets référencés. |
| uri | java.lang.String | URI pour ajouter le document HTML. Utilisé pour résoudre les liens relatifs.

Spécifier un résolveur peut potentiellement introduire une vulnérabilité. Utilisez-le avec prudence. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Convertit les paragraphes spécifiés en HTML et le renvoie sous forme d'objet String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | Index du premier paragraphe |
| paragraphsCount | int | Nombre de paragraphes |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Options de conversion [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Retour:**
java.lang.String - HTML généré.