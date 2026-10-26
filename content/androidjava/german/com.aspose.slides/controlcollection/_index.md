---
title: ControlCollection
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Eine Sammlung von ActiveX-Steuerelementen.
type: docs
url: /de/com.aspose.slides/controlcollection/
---
**Vererbung:**  
java.lang.Object

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject  
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Eine Sammlung von ActiveX-Steuerelementen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Objekte in der Sammlung zurück. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Erstellt ein neues Steuerelement und fügt es der Sammlung hinzu. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Entfernt ein ActiveX-Steuerelement aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein an einer angegebenen Position gespeichertes ActiveX-Steuerelement aus der Sammlung. |
| [clear()](#clear--) | Entfernt alle Steuerelemente aus der Sammlung. |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Steuerelement an der angegebenen Position zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert die gesamte Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisations-Root zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Objekte in der Sammlung zurück. Nur-Lese int.

**Rückgabe:**  
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Erstellt ein neues Steuerelement und fügt es der Sammlung hinzu.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| controlType | int | Typ des hinzuzufügenden Steuerelements. |
| x | float | Die X-Koordinate für die linke Seite des Rahmens des Shapes. |
| y | float | Die Y-Koordinate für die obere Seite des Rahmens des Shapes. |
| width | float | Die Breite des Rahmens des Shapes. |
| height | float | Die Höhe des Rahmens des Shapes. |

**Rückgabe:**  
[IControl](../../com.aspose.slides/icontrol) - Erstelltes Steuerelement.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Entfernt ein ActiveX-Steuerelement aus der Sammlung.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Ein zu entfernendes Steuerelement. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt ein an einer angegebenen Position gespeichertes ActiveX-Steuerelement aus der Sammlung.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu entfernenden Steuerelements. |
### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Steuerelemente aus der Sammlung.
### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Gibt ein Steuerelement an der angegebenen Position zurück.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Steuerelements. |

**Rückgabe:**  
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert die gesamte Sammlung in das angegebene Array.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray |
| index | int | Index im Zielarray. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur-Lese boolean.

**Rückgabe:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Synchronisations-Root zurück. Nur-Lese Object.

**Rückgabe:**  
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabe:**  
com.aspose.slides.IDOMObject