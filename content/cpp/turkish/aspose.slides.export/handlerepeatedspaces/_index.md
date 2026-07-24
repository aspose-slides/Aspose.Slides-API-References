---
title: HandleRepeatedSpaces
second_title: Aspose.Slides için C++ API Referansı
description: Markdown dışa aktarma sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirler.
type: docs
weight: 937
url: /tr/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Yinelenen normal boşluk karakterlerinin Markdown dışa aktarımı sırasında nasıl işleneceğini belirtir.

```cpp
enum class HandleRepeatedSpaces
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Tüm boşluklar, herhangi bir değişiklik yapılmadan normal boşluk karakteri olarak korunur. Herhangi bir dönüşüm uygulanmaz ve birden fazla ardışık boşluk olduğu gibi dışa aktarılır. |
| AlternateSpacesToNbsp | 1 | İki veya daha fazla ardışık normal boşluk dizisini, normal boşluk karakterleri ile bölünmüş boşluk olmayan ara karakterleri (**&nbsp;**) dönüşümlü olarak değiştirir. İlk boşluk her zaman normal boşluk olarak korunur. |
| MultipleSpacesToNbsp | 2 | İki veya daha fazla ardışık normal boşluk dizisini, ilk boşluğu normal bir boşluk karakteri olarak koruyarak ve sonraki tüm boşlukları boşluk olmayan ara karakterleri (**&nbsp;**) ile değiştirerek dönüştürür. |

## Ayrıca Bakınız

* Ad alanı [Aspose::Slides::Export](../)
* Kitaplık [Aspose.Slides](../../)