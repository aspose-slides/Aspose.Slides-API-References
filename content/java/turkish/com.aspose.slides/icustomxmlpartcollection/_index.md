---
title: ICustomXmlPartCollection
second_title: Aspose.Slides for Java API Referansı
description: Özel xml parçalarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icustomxmlpartcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Özel xml parçalarının koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi döndürür. |
| [add(byte[] xmlData)](#add-byte---) | Yeni bir özel xml parçası ekler. |
| [add(String xmlString)](#add-java.lang.String-) | Yeni bir özel xml parçası ekler. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Yeni bir özel xml parçası ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki özel xml parçasını kaldırır. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Koleksiyondan belirli bir nesnenin ilk örneğini kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Belirtilen indeksteki öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak öğenin sıfır tabanlı indeksi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Belirtilen indeksteki öğe.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Yeni bir özel xml parçası ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlData | byte[] | Eklenecek yeni parçanın xml verisi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml parçası.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Yeni bir özel xml parçası ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlString | java.lang.String | Eklenecek yeni parçanın xml dizesi. |

**Döndürür:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Oluşturulan özel xml parçası.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
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
public abstract void removeAt(int index)
```

Belirtilen indeksteki özel xml parçasını kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Koleksiyondan belirli bir nesnenin ilk örneğini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Kaldırılacak özel xml parçası. |

**Döndürür:**
boolean - öğe başarıyla kaldırıldıysa true; aksi takdirde false.
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.