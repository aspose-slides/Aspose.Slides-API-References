---
title: CustomXmlPartCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci vlastních xml částí.
type: docs
url: /cs/com.aspose.slides/customxmlpartcollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Reprezentuje kolekci vlastních xml částí.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadaném indexu. |
| [size()](#size--) | Vrací počet vlastních xml částí v kolekci. |
| [add(String xmlString)](#add-java.lang.String-) | Přidá novou vlastní xml část. |
| [add(byte[] xmlData)](#add-byte---) | Přidá novou vlastní xml část. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Přidá novou vlastní xml část. |
| [removeAt(int index)](#removeAt-int-) | Odstraní vlastní xml část na zadaném indexu. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [clear()](#clear--) | Odstraní všechny položky z kolekce. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu určující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Vrací prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být získán. |

**Vrací:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Prvek na zadaném indexu.
### size() {#size--}
```
public final int size()
```

Vrací počet vlastních xml částí v kolekci. Pouze pro čtení int.

**Vrací:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Přidá novou vlastní xml část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlString | java.lang.String | Xml řetězec nové části, která má být přidána. |

**Vrací:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Vytvořená vlastní xml část.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Přidá novou vlastní xml část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlData | byte[] | Xml data nové části, která má být přidána. |

**Vrací:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Vytvořená vlastní xml část.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Přidá novou vlastní xml část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream s xml daty nové části, která má být přidána. |

**Vrací:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Vytvořená vlastní xml část.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní vlastní xml část na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Odstraní první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Vlastní xml část, která má být odstraněna. |

**Vrací:**
boolean - true pokud byl prvek úspěšně odstraněn; jinak false.
### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny položky z kolekce.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole, do kterého se má kopírovat. |
| index | int | Index, od kterého začne kopírování. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu určující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - IGenericEnumerator, který může být použit k iteraci kolekcí.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - java.util.Iterator pro celou kolekci.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject