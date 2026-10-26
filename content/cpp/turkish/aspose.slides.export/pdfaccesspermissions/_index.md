---
title: PdfAccessPermissions
second_title: Aspose.Slides for C++ API Referansı
description: Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir.
type: docs
weight: 989
url: /tr/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir.

```cpp
enum class PdfAccessPermissions
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | 0 | Kullanıcının erişim izni olmadığını belirtir. |
| PrintDocument | 4 | Kullanıcının belgeyi yazdırıp yazdıramadığını belirtir (muhtemelen en yüksek kalite seviyesinde olmayabilir, [PdfAccessPermissions::HighQualityPrint](./) bitinin de ayarlı olup olmadığına bağlıdır). |
| ModifyContent | 8 | Kullanıcının belge içeriğini, [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./) bitleri tarafından kontrol edilen işlemler dışındaki işlemlerle değiştirip değiştiremeyeceğini belirtir. |
| CopyTextAndGraphics | 16 | Kullanıcının belge içindeki metin ve grafikleri, [PdfAccessPermissions::ExtractTextAndGraphics](./) biti tarafından kontrol edilen işlem dışında kopyalayıp çıkarıp çıkaramayacağını belirtir. |
| AddOrModifyFields | 32 | Kullanıcının metin ek açıklamaları ekleyip değiştirebileceğini, etkileşimli form alanlarını doldurabileceğini ve [PdfAccessPermissions::ModifyContent](./) biti de ayarlıysa etkileşimli form alanlarını (imza alanları dahil) oluşturup değiştirebileceğini belirtir. |
| FillExistingFields | 256 | Kullanıcının mevcut etkileşimli form alanlarını (imza alanları dahil) [PdfAccessPermissions::AddOrModifyFields](./) biti temiz olsa bile doldurabileceğini belirtir. |
| ExtractTextAndGraphics | 512 | Kullanıcının engelli kullanıcıların erişilebilirliği için veya başka amaçlarla metin ve grafikleri çıkarıp çıkaramayacağını belirtir. |
| AssembleDocument | 1024 | Kullanıcının belgeyi (sayfaları ekleme, döndürme veya silme ve yer imleri veya küçük resimler oluşturma) birleştirebileceğini, [PdfAccessPermissions::ModifyContent](./) biti temiz olsa bile belirtir. |
| HighQualityPrint | 2048 | Kullanıcının PDF içeriğinin doğru bir dijital kopyasını üretebilecek bir temsile belgeyi yazdırıp yazdırmayacağını belirtir. Bu bit temiz olduğunda (ve [PdfAccessPermissions::PrintDocument](./) biti ayarlıysa), yazdırma görünümün düşük seviyeli bir temsiline, muhtemelen düşük kalitede sınırlanır. |

## Bakınız

* AdAlanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)