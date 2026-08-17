---
title: ISensitivityLabelCollection
second_title: Aspose.Slides için Java API Referansı
description: Belgeye uygulanan duyarlılık etiketlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/isensitivitylabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Belgeye uygulanan duyarlılık etiketlerinin bir koleksiyonunu temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndeks ile duyarlılık etiketini döndürür. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Duyarlılık etiketini koleksiyonun sonuna ekler. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Bir SensitivityLabel'ı koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki duyarlılık etiketini kaldırır. |
| [clear()](#clear--) | Tüm öğeleri koleksiyondan kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm öğelerin sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


İndeks ile duyarlılık etiketini döndürür. Yalnızca okunabilir [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Duyarlılık etiketini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | java.lang.String | Duyarlılık etiketinin kimliği. |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) site tanımlayıcısı. |
| isEnabled | boolean | Duyarlılık etiketinin etkin olup olmadığını gösteren işaret. |
| methodType | int | Duyarlılık etiketi için atama yöntemi. |

**Dönüş:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


Bir SensitivityLabel'ı koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Koleksiyonun sonuna eklenecek SensitivityLabel nesnesi. |

**Dönüş:**
int - SensitivityLabel'ın eklendiği indeks.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksteki duyarlılık etiketini kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken duyarlılık etiketinin indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Tüm öğeleri koleksiyondan kaldırır.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki tüm öğelerin sayısını alır. Yalnızca okunabilir  int .

**Dönüş:**
int