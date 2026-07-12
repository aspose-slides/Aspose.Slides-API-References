---
title: IDigitalSignatureCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Bir belgeye eklenmiş dijital imzaların koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/idigitalsignaturecollection/
---
**Tüm Gerçekleştirilen Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Bir belgeye eklenmiş dijital imzaların koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndekse göre imzayı döndürür. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | İmzayı koleksiyonun sonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki imzayı kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm imzaları kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


İndekse göre imzayı döndürür.

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
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Eklemek için imza. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksteki imzayı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken imzanın indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm imzaları kaldırır.