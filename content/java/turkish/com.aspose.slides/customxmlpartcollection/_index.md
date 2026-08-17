---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Java API Referansı
description: Özel xml parçalarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/customxmlpartcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Özel xml parçalarının koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi döndürür. |
| [size()](#size--) | Koleksiyondaki özel xml parçalarının sayısını döndürür. |
| [add(String xmlString)](#add-java.lang.String-) | Yeni bir özel xml parçası ekler. |
| [add(byte[] xmlData)](#add-byte---) | Yeni bir özel xml parçası ekler. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Yeni bir özel xml parçası ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki özel xml parçasını kaldırır. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyonun içinde iterasyon yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Belirtilen indeksteki öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak öğenin sıfır tabanlı indeksi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Belirtilen indeksteki öğe.

### size() {#size--}
```
public final int size()
```

Koleksiyondaki özel xml parçalarının sayısını döndürür. Yalnızca okuma int.

**Döndürür:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Yeni bir özel xml parçası ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlString | java.lang.String | Eklenecek yeni parçanın xml dizesi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml parçası.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Yeni bir özel xml parçası ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlData | byte[] | Eklenecek yeni parçanın xml verisi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml parçası.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Yeni bir özel xml parçası ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | java.io.InputStream | Eklenecek yeni parçanın xml verisini içeren inputStream. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml parçası.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indeksteki özel xml parçasını kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Kaldırılacak özel xml parçası. |

**Döndürür:**
boolean - öğe başarıyla kaldırıldıysa true; aksi takdirde false.

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Kopyalanacak dizi. |
| index | int | Kopyalamaya başlanacak indeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okuma Object.

**Döndürür:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Koleksiyonun içinde iterasyon yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - An java.util.Iterator for the entire collection.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject