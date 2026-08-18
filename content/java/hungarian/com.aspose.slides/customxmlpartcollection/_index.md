---
title: CustomXmlPartCollection
second_title: Aspose.Slides Java API referenciája
description: A testreszabott XML részek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/customxmlpartcollection/
---
**Öröklés:**  
java.lang.Object

**Minden megvalósított interfész:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

A testreszabott XML részek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elemet a megadott indexnél. |
| [size()](#size--) | Visszaadja a testreszabott XML részek számát a gyűjteményben. |
| [add(String xmlString)](#add-java.lang.String-) | Új testreszabott XML részt ad hozzá. |
| [add(byte[] xmlData)](#add-byte---) | Új testreszabott XML részt ad hozzá. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Új testreszabott XML részt ad hozzá. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a testreszabott XML részt a megadott indexnél. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Másolás a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigjárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Visszaadja az elemet a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem lekéréséhez használt nulláktól induló index. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Az elem a megadott indexnél.

### size() {#size--}
```
public final int size()
```

Visszaadja a testreszabott XML részek számát a gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Új testreszabott XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlString | java.lang.String | Az új részhez hozzáadandó XML karakterlánc. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott testreszabott XML rész.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Új testreszabott XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xmlData | byte[] | Az új részhez hozzáadandó XML adatok. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott testreszabott XML rész.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Új testreszabott XML részt ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inputStream | java.io.InputStream | Az új részhez hozzáadandó XML adatokat tartalmazó InputStream. |

**Visszatérési érték:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Létrehozott testreszabott XML rész.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a testreszabott XML részt a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulláktól induló indexe. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Eltávolítja a megadott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Az eltávolítandó testreszabott XML rész. |

**Visszatérési érték:**
boolean - true ha az elem sikeresen eltávolítva; egyébként false.

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes elemet a gyűjteményből.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Másolás a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Az átmásolandó tömb. |
| index | int | A másolás kezdő indexe. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos)-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Visszaad egy enumerátort, amely végigjárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator, amelyet a gyűjtemény bejárására lehet használni.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Egy java.util.Iterator a teljes gyűjteményhez.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject