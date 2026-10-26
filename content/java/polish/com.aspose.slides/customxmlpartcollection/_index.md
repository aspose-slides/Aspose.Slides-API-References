---
title: CustomXmlPartCollection
second_title: Aspose.Slides dla Java - dokumentacja API
description: Reprezentuje kolekcję niestandardowych części XML.
type: docs
url: /pl/com.aspose.slides/customxmlpartcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Reprezentuje kolekcję niestandardowych części XML.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca element pod wskazanym indeksem. |
| [size()](#size--) | Zwraca liczbę niestandardowych części XML w kolekcji. |
| [add(String xmlString)](#add-java.lang.String-) | Dodaje nową niestandardową część XML. |
| [add(byte[] xmlData)](#add-byte---) | Dodaje nową niestandardową część XML. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Dodaje nową niestandardową część XML. |
| [removeAt(int index)](#removeAt-int-) | Usuwa niestandardową część XML pod określonym indeksem. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Zwraca element pod wskazanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do pobrania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Element pod wskazanym indeksem.

### size() {#size--}
```
public final int size()
```

Zwraca liczbę niestandardowych części XML w kolekcji. tylko do odczytu int.

**Zwraca:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Dodaje nową niestandardową część XML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlString | java.lang.String | Łańcuch XML nowej części do dodania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Utworzona niestandardowa część XML.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Dodaje nową niestandardową część XML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlData | byte[] | Dane XML nowej części do dodania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Utworzona niestandardowa część XML.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Dodaje nową niestandardową część XML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| inputStream | java.io.InputStream | Strumień wejściowy z danymi XML nowej części do dodania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Utworzona niestandardowa część XML.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa niestandardową część XML pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Niestandardowa część XML do usunięcia. |

**Zwraca:**
boolean - true jeśli element został pomyślnie usunięty; w przeciwnym razie false.

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie elementy z kolekcji.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica, do której kopiować. |
| index | int | Indeks, od którego rozpocząć kopiowanie. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). tylko do odczytu boolean.

**Zwraca:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. tylko do odczytu Object.

**Zwraca:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Enumerator IGenericEnumerator, który można użyć do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - java.util.Iterator dla całej kolekcji.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject