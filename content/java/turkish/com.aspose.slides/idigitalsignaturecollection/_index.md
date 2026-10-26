---
title: IDigitalSignatureCollection
second_title: Aspose.Slides için Java API Referansı
description: Bir belgeye eklenmiş dijital imzaların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/idigitalsignaturecollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Bir belgeye eklenmiş dijital imzaların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İmzayı dizine göre döndürür. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | İmzayı koleksiyonun sonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki imzayı kaldırır. |
| [clear()](#clear--) | Koleksiyondan tüm imzaları kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


İmzayı dizine göre döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


İmzayı koleksiyonun sonuna ekler.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Eklenecek imza. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen dizindeki imzayı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken imzanın dizini. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondan tüm imzaları kaldırır.