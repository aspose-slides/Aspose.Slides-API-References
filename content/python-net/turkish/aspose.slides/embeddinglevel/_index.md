---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/embeddinglevel/
---
## EmbeddingLevel sayımı

Yazı tipinin gömülmesi için lisans haklarını temsil eder.

EmbeddingLevel türü aşağıdaki üyeleri ortaya çıkarır:

## Alanlar

| Alan | Açıklama |
| :- | :- |
| INSTALLABLE | Bu ayara sahip yazı tipleri, bir uygulama tarafından uzaktaki sisteme gömülebilir ve kalıcı olarak kurulabilir. <br/>            Uzaktaki sistemin kullanıcısı, o yazı tipi için orijinal satın alıcı ile aynı hakları, yükümlülükleri ve lisansları elde eder, <br/>            ve orijinal satın alıcı gibi aynı son kullanıcı lisans anlaşması, telif hakkı, tasarım patenti ve/veya ticari marka'ya tabi olur. |
| RESTRICTED | Sadece bu bit ayarlı olan yazı tipleri, yasal sahibinden izin alınmadan hiçbir şekilde değiştirilmemeli, gömülmemeli veya değiş tokuş edilmemelidir. |
| PREVIEW_PRINT | Bu bit ayarlandığında, yazı tipi gömülebilir ve uzaktaki sisteme geçici olarak yüklenebilir. Preview & <br/>            Print yazı tiplerini içeren belgeler "read-only" olarak açılmalıdır; belgeye hiçbir düzenleme uygulanamaz. |
| EDITABLE | Bu bit ayarlandığında, yazı tipi gömülebilir ancak yalnızca diğer sistemlerde geçici olarak kurulabilir. Preview & <br/>            Print yazı tiplerinin aksine, Editable yazı tiplerini içeren belgeler okuma için açılabilir, düzenleme izin verilir ve değişiklikler kaydedilebilir. |
| NO_SUBSETTING | Bu bit ayarlandığında, yazı tipinin gömülmeden önce alt kümesi oluşturulamaz. Bit 0-3 ve 9'da belirtilen diğer gömme kısıtlamaları da geçerlidir. |
| BITMAP_ONLY | Bu bit ayarlandığında, sadece yazı tipinde bulunan bitmapler gömülebilir. Kontur verileri gömülemez. Eğer yazı tipinde bitmap bulunmuyorsa, <br/>            yazı tipi gömülemez olarak kabul edilir ve gömme hizmetleri başarısız olur. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)