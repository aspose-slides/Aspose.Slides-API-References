---
title: ISensitivityLabelCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Belgeye uygulanan hassasiyet etiketlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/isensitivitylabelcollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Belgeye uygulanan hassasiyet etiketlerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndeksle hassasiyet etiketini döndürür. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Koleksiyonun sonuna hassasiyet etiketini ekler. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Koleksiyona bir SensitivityLabel ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki hassasiyet etiketini kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm öğelerin sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

İndeksle hassasiyet etiketini döndürür. Yalnızca okuma [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Koleksiyonun sonuna hassasiyet etiketini ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| id | java.lang.String | Hassasiyet etiketinin kimliği. |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) site tanımlayıcısı. |
| isEnabled | boolean | Etiketin etkin olup olmadığını gösteren bayrak. |
| methodType | int | Hassasiyet etiketi için atama yöntemi. |

**Dönüş Değeri:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Koleksiyona bir SensitivityLabel ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Koleksiyonun sonuna eklenecek SensitivityLabel nesnesi. |

**Dönüş Değeri:**
int - SensitivityLabel'in eklendiği indeks.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksdeki hassasiyet etiketini kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken hassasiyet etiketinin indeksi. |
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyondaki tüm öğelerin sayısını alır. Yalnızca okuma int .

**Dönüş Değeri:**
int