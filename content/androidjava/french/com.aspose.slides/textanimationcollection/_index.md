---
title: TextAnimationCollection
second_title: Référence API Java d'Aspose.Slides pour Android
description: Représente une collection d'animations de texte.
type: docs
url: /fr/com.aspose.slides/textanimationcollection/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Représente une collection d'animations de texte.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre d'éléments dans la collection. |
| [add()](#add--) | Ajoute une nouvelle animation de texte à la collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'élément par indice. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Renvoie tous les éléments |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


Renvoie le nombre d'éléments dans la collection. int Lecture seule.

**Renvoie:**  
int
### add() {#add--}
```
public final TextAnimation add()
```


Ajoute une nouvelle animation de texte à la collection.

**Renvoie:**  
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


Renvoie l'élément par indice.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


Renvoie tous les éléments

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) to remove. |

**Renvoie:**  
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Renvoie:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to fill. |
| index | int | Starting position in target array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). boolean Lecture seule.

**Renvoie:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie une racine de synchronisation. Object Lecture seule.

**Renvoie:**  
java.lang.Object