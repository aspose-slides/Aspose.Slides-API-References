---
title: TextAnimationCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Textanimationen dar.
type: docs
url: /de/com.aspose.slides/textanimationcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Stellt eine Sammlung von Textanimationen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [add()](#add--) | Fügt der Sammlung eine neue Textanimation hinzu. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element nach Index zurück. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Gibt alle Elemente zurück |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationsbasis zurück. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Elemente in der Sammlung zurück. Nur lesbarer int.

**Rückgabe:**
int
### add() {#add--}
```
public final TextAnimation add()
```


Fügt der Sammlung eine neue Textanimation hinzu.

**Rückgabe:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


Gibt das Element nach Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


Gibt alle Elemente zurück

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) to remove. |

**Rückgabe:**
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zu füllendes Array. |
| index | int | Startposition im Zielarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur lesbarer boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt die Synchronisationsbasis zurück. Nur lesbares Object.

**Rückgabe:**
java.lang.Object