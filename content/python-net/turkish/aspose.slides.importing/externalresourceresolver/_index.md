---
title: ExternalResourceResolver class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver sınıfı

Html ve Svg belgelerinin içe aktarımı sırasında dış kaynakları çözmek için kullanılan geri çağırma sınıfı. Bu çözücü kullanılırsa, istemci tarafından sağlanan HTML veya SVG dosyası, sunucu yazılımının yerel veya ağ dosyası elde etmesine neden olabilecek bir güvenlik açığı oluşturabilir. Dikkatli kullanın. ExternalResourceResolver'ın hiç belirtilmemesi (yalnızca gömülü nesneler okunur) veya belirtilen uri'nin geçerli olup olmadığını kontrol eden bir alt sınıf oluşturulması önerilir.

ExternalResourceResolver türü aşağıdaki üyeleri ortaya çıkarır:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/tr/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Temel ve göreceli URI'lerden mutlak URI'yi çözer. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/tr/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Bir URI'yi gerçek kaynağı içeren bir nesneye eşler. |


### Ayrıca Bakınız
* modül [`aspose.slides.importing`](/slides/python-net/tr/aspose.slides.importing)
* kütüphane [`Aspose.Slides`](/slides/python-net)