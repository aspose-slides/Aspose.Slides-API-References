---
title: CaptionsCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une collection de sous-titres fermés.
type: docs
url: /fr/com.aspose.slides/captionscollection/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)  
```
public final class CaptionsCollection implements ICaptionsCollection
```

Représente une collection de sous-titres fermés.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie les sous-titres fermés à l'index spécifié. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Ajoute des sous-titres fermés WebVTT à la fin de la collection. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Ajoute des sous-titres fermés WebVTT à la fin de la collection depuis un flux. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Supprime les sous-titres fermés spécifiés de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime les sous-titres fermés à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les sous-titres fermés de la collection. |
| [getCount()](#getCount--) | Renvoie le nombre d'éléments dans la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |

### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Renvoie les sous-titres fermés à l'index spécifié. Lecture seule [ICaptions](../../com.aspose.slides/icaptions).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[ICaptions](../../com.aspose.slides/icaptions)

### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Ajoute des sous-titres fermés WebVTT à la fin de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| label | java.lang.String | L'étiquette des sous-titres fermés. |
| filePath | java.lang.String | Le chemin vers le fichier WebVTT. |

**Renvoie:**
[ICaptions](../../com.aspose.slides/icaptions) - L'instance [ICaptions](../../com.aspose.slides/icaptions) ajoutée.

### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Ajoute des sous-titres fermés WebVTT à la fin de la collection depuis un flux.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| label | java.lang.String | L'étiquette des sous-titres fermés. |
| stream | java.io.InputStream | Le flux d'entrée contenant des données au format WebVTT. |

**Renvoie:**
[ICaptions](../../com.aspose.slides/icaptions) - L'instance [ICaptions](../../com.aspose.slides/icaptions) ajoutée.

### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Supprime les sous-titres fermés spécifiés de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Les sous-titres fermés à supprimer. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime les sous-titres fermés à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index des sous-titres fermés à supprimer. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les sous-titres fermés de la collection.

### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre d'éléments dans la collection. Lecture seule int.

**Renvoie:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Un  System.Collections.Generic.IEnumerator1  qui peut être utilisé pour parcourir la collection.