---
title: EmbeddingLevel
second_title: Aspose.Slides için C++ API Referansı
description: Yazı tipinin gömülmesi için lisans haklarını temsil eder.
type: docs
weight: 5786
url: /tr/aspose.slides/embeddingleet/
---
## EmbeddingLevel enum

Yazı tipinin gömülmesi için lisans haklarını temsil eder.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) bu ayarla, uygulama tarafından uzak sisteme gömülüp kalıcı olarak kurulabileceğini gösterir. Uzak sistemin kullanıcısı, yazı tipinin orijinal satın alıcısı gibi aynı hakları, yükümlülükleri ve lisansları elde eder ve aynı son kullanıcı lisans sözleşmesine, telif hakkına, tasarım patentesine ve/veya ticari markaya tabidir. |
| Restricted | 2 | [Fonts](../fonts/) yalnızca bu bit ayarlı olanlar, yasal sahibinden izin alınmadan hiçbir şekilde değiştirilmemeli, gömülmemeli veya değiştirilememelidir. |
| PreviewPrint | 4 | Bu bit ayarlıysa, yazı tipi gömülebilir ve geçici olarak uzak sisteme yüklenebilir. Preview & Print yazı tiplerini içeren belgeler \"yalnızca okuma;\" belgeye herhangi bir düzenleme uygulanamaz. |
| Editable | 8 | Bu bit ayarlıysa, yazı tipi gömülebilir ancak yalnızca diğer sistemlerde geçici olarak kurulabilir. Preview & Print yazı tiplerinin aksine, Editable yazı tiplerini içeren belgeler okuma amaçlı açılabilir, düzenlemeye izin verilir ve değişiklikler kaydedilebilir. |
| NoSubsetting | 256 | Bu bit ayarlıysa, yazı tipi gömülmeden önce alt küme oluşturulamaz. Bit 0-3 ve 9'da belirtilen diğer gömme kısıtlamaları da geçerlidir. |
| BitmapOnly | 512 | Bu bit ayarlıysa, sadece yazı tipinde bulunan bitmapler gömülebilir. Kontur verileri gömülemez. Yazı tipinde bitmap bulunmuyorsa, yazı tipi gömülemez olarak kabul edilir ve gömme hizmetleri başarısız olur. |

## Ayrıca Bakınız

* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)