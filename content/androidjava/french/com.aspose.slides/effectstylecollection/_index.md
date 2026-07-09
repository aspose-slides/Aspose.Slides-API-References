---
title: EffectStyleCollection
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente une collection de styles d'effet.
type: docs
url: /fr/com.aspose.slides/effectstylecollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

Représente une collection de styles d'effet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie un élément à la position spécifiée. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour la collection entière. |
| [size()](#size--) | Renvoie le nombre d'éléments dans la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```


Renvoie un élément à la position spécifiée. Lecture seule [EffectStyle](../../com.aspose.slides/effectstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Position de l'élément. |

**Renvoie :**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - Élément à la position spécifiée.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```


Renvoie un itérateur java pour la collection entière.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Un java.util.Iterator pour la collection entière.
### size() {#size--}
```
public final int size()
```


Renvoie le nombre d'éléments dans la collection. Lecture seule int, Lecture seule int.

**Renvoie :**
int
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


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie :**
java.lang.Object