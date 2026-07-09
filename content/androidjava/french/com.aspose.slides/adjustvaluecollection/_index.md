---
title: AdjustValueCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une collection d'ajustements de formes.
type: docs
url: /fr/com.aspose.slides/adjustvaluecollection/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Représente une collection d'ajustements de forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre d'ajustements. |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'ajustement par indice. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |
| [iterator()](#iterator--) | Renvoie un itérateur pour l'ensemble de la collection. |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'ajustements. int en lecture seule.

**Renvoie:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

Renvoie l'ajustement par indice.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | indice de l'ajustement. |

**Renvoie:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Indice de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). boolean en lecture seule.

**Renvoie:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie la racine de synchronisation. Object en lecture seule.

**Renvoie:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

Renvoie un itérateur pour l'ensemble de la collection.

**Renvoie:**
com.aspose.ms.System.Collections.IEnumerator