---
title: CustomXmlPartCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Az egyéni XML részek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/customxmlpartcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Az egyéni XML részek gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Az adott indexű elemet adja vissza. |
| [size()](#size--) | Visszatér a gyűjteményben lévő egyéni XML részek számával. |
| [add(String xmlString)](#add-java.lang.String-) | Új egyéni XML részt ad hozzá. |
| [add(byte[] xmlData)](#add-byte---) | Új egyéni XML részt ad hozzá. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Új egyéni XML részt ad hozzá. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az egyéni XML részt a megadott indexnél. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Eltávolítja a gyűjteményben egy adott objektum első előfordulását. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Másolás a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztonság). |
| [getSyncRoot()](#getSyncRoot--) | Visszatér egy szinkronizációs gyökérrel. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Az adott indexű elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem lekéréséhez szükséges nullától kezdődő index. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Az adott indexű elem.
### size() {#size--}
```
public final int size()
```

Visszatér a gyűjteményben lévő egyéni XML részek számával. Csak olvasható int.

**Visszatérési érték:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Új egyéni XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlString | java.lang.String | Az új részhez hozzáadandó xml karakterlánc. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott egyéni XML rész.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Új egyéni XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlData | byte[] | Az új részhez hozzáadandó xml adat. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott egyéni XML rész.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Új egyéni XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputStream | java.io.InputStream | Az xml adatokkal ellátott inputStream, amelyet a hozzáadandó részhez használunk. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott egyéni XML rész.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja az egyéni XML részt a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nullától kezdődő indexe. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Eltávolítja a gyűjteményben egy adott objektum első előfordulását.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Az eltávolítandó egyéni XML rész. |

**Visszatérési érték:**
boolean - true, ha az elem sikeresen eltávolításra került; egyébként false.
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja a gyűjtemény összes elemét.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Másolás a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | A másolandó tömb. |
| index | int | Az index, ahonnan a másolás kezdődik. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztonság). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszatér egy szinkronizációs gyökérrel. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Visszatér egy enumerátorral, amely bejárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator, amely a gyűjteményt bejárja.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Egy java.util.Iterator a teljes gyűjteményhez.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject