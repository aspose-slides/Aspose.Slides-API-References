---
title: MakeRelative()
second_title: Aspose.Slides için C++ API Referansı
description: İki Uri örneği arasındaki farkı belirler.
type: docs
weight: 365
url: /tr/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) metod


Determines the difference between two [Uri](../) instances.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Mevcut URI ile karşılaştırılacak URI |

### Dönüş Değeri

Eğer mevcut nesne ve **toUri** tarafından temsil edilen URI'lerin ana bilgisayar adı ve şeması aynıysa, bu metod mevcut URI örneğine eklendiğinde **toUri**'yi üreten, göreceli bir [Uri](../) temsil eden bir [String](../../string/) döndürür. Ana bilgisayar adı veya şema farklıysa, bu metod **uri** parametresini temsil eden bir [String](../../string/) döndürür.

## Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Uri](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)