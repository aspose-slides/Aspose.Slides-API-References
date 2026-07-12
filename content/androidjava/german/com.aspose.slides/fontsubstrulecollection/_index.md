---
title: FontSubstRuleCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Schriftartsubstitutionen dar.
type: docs
url: /de/com.aspose.slides/fontsubstrulecollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

Stellt eine Sammlung von Schriftartsubstitutionen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | Fügt der Sammlung die neue Schriftartsubstitutionsregel hinzu. |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt das Element am angegebenen Index. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt eine Synchronisationswurzel zurück. |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesbar int.

**Rückgabewert:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


Fügt der Sammlung die neue Schriftartsubstitutionsregel hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Die zu entfernende Schriftartsubstitutionsregel aus der Sammlung. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


Ermittelt das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Ein java.util.Iterator für die gesamte Sammlung.
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


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesbar boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt eine Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabewert:**
java.lang.Object