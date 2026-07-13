---
title: BehaviorPropertyCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili properti waktu untuk perilaku efek.
type: docs
url: /id/com.aspose.slides/behaviorpropertycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Mewakili properti waktu untuk perilaku efek.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah properti yang disimpan dalam koleksi. |
| [isReadOnly()](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya-baca. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Menambahkan properti baru ke dalam koleksi. |
| [add(String propertyValue)](#add-java.lang.String-) | Menambahkan properti baru ke dalam koleksi. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Menentukan indeks dari item tertentu dalam List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Menentukan indeks dari item tertentu berdasarkan nilai properti dalam List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Menyisipkan properti baru ke dalam koleksi pada indeks yang ditentukan. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Menyisipkan properti baru (dengan nilai properti yang ditentukan) ke dalam koleksi pada indeks yang ditentukan. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke dalam Array, dimulai pada indeks Array tertentu. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Menghapus properti yang ditentukan dari koleksi. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Menghapus properti yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus properti pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua properti dari koleksi. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan properti pada indeks yang ditentukan. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Mengatur properti pada indeks yang ditentukan. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### size() {#size--}
```
public final int size()
```


Mengembalikan jumlah properti yang disimpan dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya-baca. Hanya-baca boolean.

**Mengembalikan:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


Menambahkan properti baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Properti yang akan ditambahkan. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


Menambahkan properti baru ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti yang akan ditambahkan. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


Menentukan indeks dari item tertentu dalam List.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Objek yang akan dicari dalam List. |

**Mengembalikan:**
int - The index of item if found in the list; otherwise, -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


Menentukan indeks dari item tertentu berdasarkan nilai properti dalam List.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | nilai properti |

**Mengembalikan:**
int - The index of the property with the specified value
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


Menyisipkan properti baru ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tempat properti baru akan disisipkan. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Properti yang akan ditambahkan. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


Menyisipkan properti baru (dengan nilai properti yang ditentukan) ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tempat properti baru akan disisipkan. |
| propertyValue | java.lang.String | Nilai properti yang akan ditambahkan. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke dalam Array, dimulai pada indeks Array tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Array satu dimensi yang menjadi tujuan elemen yang disalin dari [IGenericCollection](../../com.aspose.slides/igenericcollection). Array harus menggunakan indeks berbasis nol. |
| arrayIndex | int | Indeks berbasis nol dalam array tempat penyalinan dimulai. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


Menghapus properti yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Properti yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true if propertyValue is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


Mengembalikan properti pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks properti yang akan dikembalikan. |

**Mengembalikan:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animation behavior property.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


Mengatur properti pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks properti yang akan diatur. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - A IGenericEnumerator that can be used to iterate through the collection.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Mengembalikan:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Mengembalikan:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Parameter:**
| Parameter | Tipe | Deskripsi |
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - An java.util.Iterator for the entire collection.