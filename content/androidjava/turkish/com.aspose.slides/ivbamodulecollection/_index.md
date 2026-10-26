---
title: IVbaModuleCollection
second_title: Aspose.Slides for Android via Java API Referansı
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
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | VBA Projesine yeni boş bir modül ekler. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

Belirtilen dizindeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

VBA Projesine yeni boş bir modül ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Modülün adı |

**Dönüş Değeri:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Eklenen modül.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Koleksiyondan kaldırılacak modül. |