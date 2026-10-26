---
title: ImageCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de PPImage.
type: docs
url: /fr/com.aspose.slides/imagecollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)  
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Représente une collection de PPImage.

## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre d’images dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l’élément à l’index spécifié. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Ajoute une copie d’une image provenant d’une autre présentation. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Ajoute une image à une présentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Ajoute une image à une présentation à partir d’un flux. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Crée et ajoute une image à une présentation à partir d’un flux. |
| [addImage(byte[] buffer)](#addImage-byte---) | Ajoute une image à une présentation à partir du tampon spécifié. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Ajoute une image à une présentation à partir d’un objet Svg. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l’ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |

### size() {#size--}
```
public final int size()
```

Renvoie le nombre d’images dans la collection. Lecture seule  int .

**Renvoie :**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Obtient l’élément à l’index spécifié. Lecture seule [IPPImage](../../com.aspose.slides/ippimage).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage)

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Ajoute une copie d’une image provenant d’une autre présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Image source. |

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Ajoute une image à une présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Image à ajouter.

--------------------

Cette méthode convertit les fichiers WMF/EMF en image PNG raster avant de les insérer dans une présentation. |

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Ajoute une image à une présentation à partir d’un flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux à partir duquel ajouter l’image.

--------------------

Cette méthode peut ajouter des fichiers WMF/EMF à une présentation sans les convertir en image PNG raster. |

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Crée et ajoute une image à une présentation à partir d’un flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux à partir duquel ajouter le fichier image. |
| loadingStreamBehavior | int | Le comportement qui sera appliqué au flux. |

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage) - Image [IPPImage](../../com.aspose.slides/ippimage) ajoutée.

### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Ajoute une image à une présentation à partir du tampon spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Tampon. |

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Ajoute une image à une présentation à partir d’un objet Svg.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objet image Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Renvoie un itérateur Java pour l’ensemble de la collection.

**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Un java.util.Iterator pour l’ensemble de la collection.

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

Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). Lecture seule  boolean .

**Renvoie :**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie la racine de synchronisation. Lecture seule  Object .

**Renvoie :**  
java.lang.Object