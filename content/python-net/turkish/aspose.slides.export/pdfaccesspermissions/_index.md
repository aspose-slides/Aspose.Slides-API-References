---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir.

PdfAccessPermissions türü aşağıdaki üyeleri ortaya koyar:

## Alanlar

| Field | Description |
| :- | :- |
| NONE | Kullanıcının erişim izni bulunmadığını belirtir. |
| PRINT_DOCUMENT | Kullanıcının belgeyi yazdırıp yazdıramayacağını belirtir (en yüksek kalite seviyesinde olmayabilir, <br/>[`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) bitinin de ayarlanıp ayarlanmadığına bağlıdır). |
| MODIFY_CONTENT | Kullanıcının belge içeriğini, <br/>bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) tarafından kontrol edilen işlemler dışındaki işlemlerle değiştirebileceğini belirtir. |
| COPY_TEXT_AND_GRAPHICS | Kullanıcının belge içinden metin ve grafikleri kopyalayıp/çıkarabileceğini, <br/>[`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) biti tarafından kontrol edilen işlemler dışındaki işlemlerle belirtir. |
| ADD_OR_MODIFY_FIELDS | Kullanıcının metin açıklamaları ekleyip/ değiştirebileceğini, etkileşimli form alanlarını doldurabileceğini ve, <br/>[`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) biti de ayarlıysa, etkileşimli form alanlarını (imza alanları dahil) oluşturup/ değiştirebileceğini belirtir. |
| FILL_EXISTING_FIELDS | Kullanıcının mevcut etkileşimli form alanlarını (imza alanları dahil) doldurabileceğini, <br/>bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) temiz olsa bile belirtir. |
| EXTRACT_TEXT_AND_GRAPHICS | Kullanıcının engelli kullanıcıların erişilebilirliği ya da diğer amaçlar için belge içinden metin ve grafikleri çıkarabileceğini belirtir. |
| ASSEMBLE_DOCUMENT | Kullanıcının belgeyi (sayfaları ekleyip/ döndürüp/ silerek ve yer imleri ya da küçük önizleme görselleri oluşturarak) birleştirebileceğini, <br/>[`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) biti temiz olsa bile belirtir. |
| HIGH_QUALITY_PRINT | Kullanıcının PDF içeriğinin doğru bir dijital kopyası üretilebilecek bir temsile belgeyi yazdırıp yazdıramayacağını belirtir. Bu bit temiz olduğunda (ve <br/>bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/tr/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) ayarlıysa), <br/>yazdırma görünümün düşük seviyeli bir temsiliyle sınırlıdır, muhtemelen kalite kaybı yaşanabilir. |

### İlgili
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)