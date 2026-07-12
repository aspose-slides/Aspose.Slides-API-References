---
title: LineFormatCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt die Sammlung von Linienstilen dar.
type: docs
url: /de/com.aspose.slides/lineformatcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

Stellt die Sammlung von Linienstilen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisations-Root zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur-Lesen [ILineFormat](../../com.aspose.slides/ilineformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - Ein java.util.Iterator für die gesamte Sammlung.
### size() {#size--}
```
public final int size()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur-Lesen int.

**Rückgabewert:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur-Lesen boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Synchronisations-Root zurück. Nur-Lesen Object.

**Rückgabewert:**
java.lang.Object