---
title: IVbaModuleCollection
second_title: Aspose.Slides for Java API Referansı
description: VBA Projesi modüllerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ivbamodulecollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

VBA Projesi modüllerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki öğeyi alır. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA Projesine yeni bir boş modül ekler. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Koleksiyondan belirli bir nesnenin ilk görünümünü kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Belirtilen indeksdeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


VBA Projesine yeni bir boş modül ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Modülün adı |

**Döndürür:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Eklenen modül.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Koleksiyondan belirli bir nesnenin ilk görünümünü kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Koleksiyondan kaldırılacak modül. |