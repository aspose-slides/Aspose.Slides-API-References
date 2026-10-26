---
title: BehaviorPropertyCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili properti timing untuk perilaku efek.
type: docs
url: /id/com.aspose.slides/behaviorpropertycollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Mewakili properti timing untuk perilaku efek.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Returns the number of properties stored in the collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Adds a new property to the collection. |
| [add(String propertyValue)](#add-java.lang.String-) | Adds a new property to the collection. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Determines the index of a specific item in the List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determines the index of a specific item by property value in the List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Inserts a new property to the collection at the specified index. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserts a new property (with the specified property value) to the collection at the specified index. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Removes specified property from the collection. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Removes specified property from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes property at the specified index. |
| [clear()](#clear--) | Removes all properties from the collection. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [get_Item(int index)](#get-Item-int-) | Returns a property at the specified index. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Sets a property at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```

Returns the number of properties stored in the collection. int baca-saja.

**Mengembalikan:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. boolean baca-saja.

**Mengembalikan:**
boolean - true jika [IGenericCollection](../../com.aspose.slides/igenericcollection) bersifat baca-saja; jika tidak, false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Menambahkan properti baru ke koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Properti yang akan ditambahkan. |
### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Menambahkan properti baru ke koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti yang akan ditambahkan. |
### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Menentukan indeks item tertentu dalam List.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Objek yang akan dicari dalam List. |

**Mengembalikan:**
int - Indeks item jika ditemukan dalam list; jika tidak, -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Menentukan indeks item tertentu berdasarkan nilai properti dalam List.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | nilai properti |

**Mengembalikan:**
int - Indeks properti dengan nilai yang ditentukan
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Menyisipkan properti baru ke koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tempat properti baru akan disisipkan. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Properti yang akan ditambahkan. |
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Menyisipkan properti baru (dengan nilai properti yang ditentukan) ke koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tempat properti baru akan disisipkan. |
| propertyValue | java.lang.String | Nilai properti yang akan ditambahkan. |
### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke sebuah Array, mulai pada indeks Array tertentu.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Array satu dimensi yang menjadi tujuan elemen yang disalin dari [IGenericCollection](../../com.aspose.slides/igenericcollection). Array harus menggunakan pengindeksan berbasis nol. |
| arrayIndex | int | Indeks berbasis nol dalam array tempat penyalinan dimulai. |
### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Menghapus properti yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Properti yang akan dihapus. |

**Mengembalikan:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Menghapus properti yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti yang akan dihapus. |

**Mengembalikan:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus properti pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks properti yang harus dihapus. |
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua properti dari koleksi.
### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Properti yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika propertyValue ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Mengembalikan properti pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks properti yang akan dikembalikan. |

**Mengembalikan:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Properti perilaku animasi.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Menetapkan properti pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int | Indeks properti yang akan dikembalikan. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Mengembalikan:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |
### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |
### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Mengembalikan:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |
### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Mengembalikan:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - java.util.Iterator untuk seluruh koleksi.