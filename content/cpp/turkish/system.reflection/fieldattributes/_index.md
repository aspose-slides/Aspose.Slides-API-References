---
title: FieldAttributes
second_title: Aspose.Slides için C++ API Referansı
description: Yansıtılmış alan öznitelikleri.
type: docs
weight: 170
url: /tr/system.reflection/fieldattributes/
---
## FieldAttributes enum

Yansıtılmış alan öznitelikleri.

```cpp
enum class FieldAttributes
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| FieldAccessMask | 7 | Üye erişim maskesi. Bu maskeyi erişilebilirlik bilgilerini almak için kullanın. |
| PrivateScope | 0 | Referans alınamayan üyeler. |
| Private | 1 | Özel üyeler. |
| FamANDAssem | 2 | Özel ve derleme kapsamlı üyeler. |
| Assembly | 3 | Derleme kapsamlı üyeler. |
| Family | 4 | Tip ve alt tipler tarafından erişilebilir üyeler. |
| FamORAssem | 5 | Tip, alt tipler ve derleme tarafından erişilebilir üyeler. |
| Public | 6 | Herkes tarafından erişilebilir üyeler. |
| Static | 16 | Örnek üyelere karşıt olarak statik üyeler. |
| InitOnly | 32 | Sadece başlatılabilen, ancak değiştirilemeyen sabit üyeler. |
| Literal | 64 | Derleme zamanında sabit olan üyeler. |
| NotSerialized | 128 | Serileştirilmemiş üyeler. |
| SpecialName | 512 | Aşağıdaki adlardan birine sahip özel alan. |
| PinvokeImpl | 8192 | Ara yüz aktarılmış uygulama. |
| ReservedMask | 38144 | Yalnızca çalışma zamanında kullanım için ayrılmış bayraklar. |
| RTSpecialName | 1024 | Çalışma zamanı isim kodlamasını kontrol etmelidir. |
| HasFieldMarshal | 4096 | Marshaling bilgisi mevcuttur. |
| HasDefault | 32768 | Varsayılan değer mevcuttur. |
| HasFieldRVA | 256 | RVA mevcuttur. |

## Ayrıca Bakınız

* AdAlanı [System::Reflection](../)
* Kütüphane [Aspose.Slides](../../)