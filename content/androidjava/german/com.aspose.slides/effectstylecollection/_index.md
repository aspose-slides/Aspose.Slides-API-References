---
title: EffectStyleCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von Effektstilen dar.
type: docs
url: /de/com.aspose.slides/effectstylecollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

Stellt eine Sammlung von Effektstilen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Element an der angegebenen Position zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [size()](#size--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```


Gibt ein Element an der angegebenen Position zurück. Nur lesbar [EffectStyle](../../com.aspose.slides/effectstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position des Elements. |

**Rückgabe:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - Element an der angegebenen Position.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Ein java.util.Iterator für die gesamte Sammlung.
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Elemente in der Sammlung zurück. Nur lesbar int, Nur lesbar int.

**Rückgabe:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur lesbar boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt die Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabe:**
java.lang.Object