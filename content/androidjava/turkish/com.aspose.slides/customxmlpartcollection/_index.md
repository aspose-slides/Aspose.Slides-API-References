---
title: CustomXmlPartCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Özel XML bölümlerinin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/customxmlpartcollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Özel XML bölümlerinin koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi döndürür. |
| [size()](#size--) | Koleksiyondaki özel XML bölümlerinin sayısını döndürür. |
| [add(String xmlString)](#add-java.lang.String-) | Yeni özel XML bölümü ekler. |
| [add(byte[] xmlData)](#add-byte---) | Yeni özel XML bölümü ekler. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Yeni özel XML bölümü ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki özel XML bölümünü kaldırır. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir sayıcı döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir Java yineleyicisi döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Belirtilen dizindeki öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak öğenin sıfır tabanlı indeksi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Belirtilen dizindeki öğe.

### size() {#size--}
```
public final int size()
```

Koleksiyondaki özel XML bölümlerinin sayısını döndürür. Salt-okunur int.

**Döndürür:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Yeni özel XML bölümü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlString | java.lang.String | Eklenecek yeni bölümün XML dizesi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel XML bölümü.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Yeni özel XML bölümü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlData | byte[] | Eklenecek yeni bölümün XML verisi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel XML bölümü.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Yeni özel XML bölümü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | java.io.InputStream | Eklenecek yeni bölümün XML verilerini içeren inputStream. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel XML bölümü.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen dizindeki özel XML bölümünü kaldırır.

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
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Kaldırılacak özel XML bölümü. |

**Döndürür:**
boolean - true ise öğe başarıyla kaldırıldı; aksi takdirde false.

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
| index | int | Kopyalamanın başlayacağı indeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Koleksiyon içinde yineleme yapan bir sayıcı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Tüm koleksiyon için bir Java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Tüm koleksiyon için bir java.util.Iterator.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject