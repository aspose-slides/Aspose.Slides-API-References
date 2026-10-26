---
title: IControlPropertiesCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Koleksi kontrol ActiveX.
type: docs
url: /id/com.aspose.slides/icontrolpropertiescollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Koleksi kontrol ActiveX.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCount()](#getCount--) | Mengembalikan sejumlah properti dalam koleksi. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Menambahkan properti ke koleksi. |
| [remove(String name)](#remove-java.lang.String-) | Menghapus properti dengan nama tertentu. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Mengembalikan atau mengatur properti. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Mengembalikan atau mengatur properti. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Mengembalikan sejumlah properti dalam koleksi. |
| [clear()](#clear--) | Menghapus semua properti. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Mengembalikan sejumlah properti dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Menambahkan properti ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti. |
| value | java.lang.String | Nilai properti. |
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Menghapus properti dengan nama tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti yang akan dihapus. |
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```

Mengembalikan atau mengatur properti.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti. |
| value | java.lang.String |  |
### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Mengembalikan sejumlah properti dalam koleksi. Baca-saja [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Mengembalikan:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua properti.