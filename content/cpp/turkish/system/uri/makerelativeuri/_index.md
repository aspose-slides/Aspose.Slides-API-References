---
title: MakeRelativeUri()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli ve belirtilen Uri nesneleri tarafından temsil edilen URI'lar arasındaki farkı belirler.
type: docs
weight: 352
url: /tr/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) yöntemi

Mevcut ve belirtilen [Uri](../) nesneleri tarafından temsil edilen URI'lar arasındaki farkı belirler.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Karşılaştırılan değer |

### Dönüş Değeri

Mevcut nesne ve **toUri** tarafından temsil edilen URI'ların ana bilgisayar adı ve şeması aynıysa, bu yöntem göreli bir [Uri](../) döndürür; bu, mevcut URI örneğine eklendiğinde **toUri** elde edilir. Ana bilgisayar adı veya şema farklıysa, bu yöntem **uri** parametresini temsil eden bir [Uri](../) nesnesi döndürür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Uri](../)
* Ad alanı [System](../../)
* Library [Aspose.Slides](../../../)