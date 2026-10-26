---
title: CustomXmlPartCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von benutzerdefinierten XML-Teilen dar.
type: docs
url: /de/com.aspose.slides/customxmlpartcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Stellt eine Sammlung von benutzerdefinierten XML-Teilen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [size()](#size--) | Gibt die Anzahl der benutzerdefinierten XML-Teile in der Sammlung zurück. |
| [add(String xmlString)](#add-java.lang.String-) | Fügt ein neues benutzerdefiniertes XML-Teil hinzu. |
| [add(byte[] xmlData)](#add-byte---) | Fügt ein neues benutzerdefiniertes XML-Teil hinzu. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Fügt ein neues benutzerdefiniertes XML-Teil hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das benutzerdefinierte XML-Teil am angegebenen Index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsgrundobjekt zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des abzurufenden Elements. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Das Element am angegebenen Index.

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der benutzerdefinierten XML-Teile in der Sammlung zurück. Nur lesbar int.

**Rückgabewert:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Fügt ein neues benutzerdefiniertes XML-Teil hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlString | java.lang.String | Der XML-String des hinzuzufügenden Teils. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Erstelltes benutzerdefiniertes XML-Teil.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Fügt ein neues benutzerdefiniertes XML-Teil hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlData | byte[] | Die XML-Daten des hinzuzufügenden Teils. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Erstelltes benutzerdefiniertes XML-Teil.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Fügt ein neues benutzerdefiniertes XML-Teil hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | java.io.InputStream | Der InputStream mit den XML-Daten des hinzuzufügenden Teils. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Erstelltes benutzerdefiniertes XML-Teil.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das benutzerdefinierte XML-Teil am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Das zu entfernende benutzerdefinierte XML-Teil. |

**Rückgabewert:**
boolean - true, wenn das Element erfolgreich entfernt wurde; andernfalls false.

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der Sammlung.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array, in das kopiert werden soll. |
| index | int | Index, ab dem kopiert wird. |

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

Gibt ein Synchronisationsgrundobjekt zurück. Nur lesbar Object.

**Rückgabewert:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - An java.util.Iterator for the entire collection.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject