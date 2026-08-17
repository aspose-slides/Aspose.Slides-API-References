---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides für Java API Referenz
description: Unveränderliches Objekt, das eine schreibgeschützte Sammlung effektiver Bildtransformations-Effekte darstellt.
type: docs
url: /de/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Unveränderliches Objekt, das eine schreibgeschützte Sammlung von effektiven Bildtransformations-Effekten darstellt.

--------------------

Name IImageTransformOperationCollectionEffectiveData verkürzt zu IImageTransformOCollectionEffectiveData, weil COM-Namen nicht länger als 39 Zeichen sein dürfen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Bildeffekte in einer Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element nach Index zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ, geeignet für Hash-Algorithmen und Datenstrukturen wie eine Hashtabelle. |
| [iterator()](#iterator--) | Gibt einen Aufzähler zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-safe) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Bildeffekte in einer Sammlung zurück. Nur-Lese int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


Gibt das Element anhand des Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabe:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - Das [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) Objekt.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt, das mit dem aktuellen Objekt verglichen wird. |

**Rückgabe:**
boolean - true, wenn das angegebene Objekt dem aktuellen Objekt gleich ist; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Hash-Funktion für einen bestimmten Typ, geeignet für Hash-Algorithmen und Datenstrukturen wie eine Hashtabelle.

**Rückgabe:**
int - Ein Hashcode für das aktuelle Objekt.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


Gibt einen Aufzähler zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Ein IGenericEnumerator, der verwendet werden kann, um durch die Sammlung zu iterieren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array zum Füllen. |
| index | int | Startposition im Zielarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-safe) ist. Nur-Lese boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt die Synchronisationswurzel zurück. Nur-Lese Object.

**Rückgabe:**
java.lang.Object