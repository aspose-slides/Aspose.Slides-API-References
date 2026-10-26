---
title: ControlPropertiesCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Koleksi properti AcitveX.
type: docs
url: /id/com.aspose.slides/controlpropertiescollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Koleksi properti AcitveX.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Menambahkan properti ke koleksi. |
| [remove(String name)](#remove-java.lang.String-) | Menghapus properti dengan nama yang ditentukan. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Mengembalikan atau mengatur properti. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Mengembalikan atau mengatur properti. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Mengembalikan koleksi nama properti. |
| [clear()](#clear--) | Menghapus semua properti. |
| [getCount()](#getCount--) | Mengembalikan jumlah properti dalam koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator Java untuk seluruh koleksi. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Menambahkan properti ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti. |
| value | java.lang.String | Nilai properti. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Menghapus properti dengan nama yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti yang akan dihapus. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Mengembalikan atau mengatur properti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti. |

**Mengembalikan:**
java.lang.String - Properti.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Mengembalikan atau mengatur properti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Mengembalikan koleksi nama properti. Hanya-baca [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Mengembalikan:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua properti.

### getCount() {#getCount--}
```
public final int getCount()
```

Mengembalikan jumlah properti dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Sebuah java.util.Iterator untuk seluruh koleksi.