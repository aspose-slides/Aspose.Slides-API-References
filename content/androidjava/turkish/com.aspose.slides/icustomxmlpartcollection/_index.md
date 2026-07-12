---
title: ICustomXmlPartCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Özel xml bölümlerinin koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icustomxmlpartcollection/
---
**Tüm Gerçekleştirilen Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Özel xml bölümlerinin koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi döndürür. |
| [add(byte[] xmlData)](#add-byte---) | Yeni bir özel xml bölümü ekler. |
| [add(String xmlString)](#add-java.lang.String-) | Yeni bir özel xml bölümü ekler. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Yeni bir özel xml bölümü ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki özel xml bölümünü kaldırır. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Belirtilen indeksteki öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak elemanın sıfır tabanlı indeksi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Belirtilen indeksteki öğe.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Yeni bir özel xml bölümü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlData | byte[] | Eklenecek yeni bölümün xml verisi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml bölümü.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Yeni bir özel xml bölümü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlString | java.lang.String | Eklenecek yeni bölümün xml dizesi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml bölümü.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Yeni bir özel xml bölümü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | java.io.InputStream | Eklenecek yeni bölümün xml verisine sahip inputStream. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml bölümü.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksteki özel xml bölümünü kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak elemanın sıfır tabanlı indeksi. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Kaldırılacak özel xml bölümü. |

**Döndürür:**
boolean - öğe başarılı bir şekilde kaldırıldıysa true; aksi takdirde false.
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.