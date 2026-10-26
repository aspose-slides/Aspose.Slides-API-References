---
title: IBehaviorPropertyCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili properti timing untuk perilaku efek.
type: docs
url: /id/com.aspose.slides/ibehaviorpropertycollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Mewakili properti timing untuk perilaku efek.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Menambahkan properti baru ke koleksi. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Menentukan indeks item tertentu berdasarkan nilai properti dalam List. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Menyisipkan properti baru (dengan nilai properti yang ditentukan) ke koleksi pada indeks yang ditentukan. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Menghapus properti yang ditentukan dari koleksi. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Menambahkan properti baru ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti yang akan ditambahkan. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Menentukan indeks item tertentu berdasarkan nilai properti dalam List.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | nilai properti |

**Mengembalikan:**
int - Indeks properti dengan nilai yang ditentukan
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Menyisipkan properti baru (dengan nilai properti yang ditentukan) ke koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tempat properti baru harus disisipkan. |
| propertyValue | java.lang.String | Nilai properti yang akan ditambahkan. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Menghapus properti yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti yang akan dihapus. |

**Mengembalikan:**
boolean - True jika properti berhasil dihapus
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | Nilai properti untuk mencari di [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika propertyValue ditemukan di [IGenericCollection](../../com.aspose.slides/igenericcollection); jika tidak, false.