---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Belgeye uygulanan duyarlılık etiketlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/sensitivitylabelcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Belgeye uygulanan duyarlılık etiketlerinin bir koleksiyonunu temsil eder.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndekse göre duyarlılık etiketini döndürür. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Koleksiyonun sonuna duyarlılık etiketini ekler. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Koleksiyona bir SensitivityLabel ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki duyarlılık etiketini kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [getCount()](#getCount--) | Koleksiyondaki öğe sayısını döndürür. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

İndekse göre duyarlılık etiketini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Koleksiyonun sonuna duyarlılık etiketini ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| id | java.lang.String | Duyarlılık etiketinin kimliği. |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) site tanımlayıcısı. |
| isEnabled | boolean | Etiketin etkin olup olmadığını belirten bayrak. |
| methodType | int | Duyarlılık etiketi için atama yöntemi. |

**Döndürür:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

Koleksiyona bir SensitivityLabel ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Koleksiyonun sonuna eklenecek SensitivityLabel nesnesi. |

**Döndürür:**
int - SensitivityLabel'ın eklendiği indeks.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen indeksdeki duyarlılık etiketini kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken duyarlılık etiketinin indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir System.Collections.Generic.IEnumerator1.
### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki öğe sayısını döndürür. Read-only  int .

**Döndürür:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |
