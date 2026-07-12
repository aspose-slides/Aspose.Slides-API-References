---
title: PdfAccessPermissions
second_title: Aspose.Slides Android için Java API Referansı
description: Belge, kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir.
type: docs
url: /tr/com.aspose.slides/pdfaccesspermissions/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Belge, kullanıcı erişimi ile açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [None](#None) | Kullanıcının hiçbir erişim iznine sahip olmadığını belirtir. |
| [PrintDocument](#PrintDocument) | Kullanıcının belgeyi yazdırıp yazdıramayacağını belirtir (en yüksek kalite seviyesinde olmayabilir, [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) biti de ayarlıysa buna bağlıdır). |
| [ModifyContent](#ModifyContent) | Kullanıcının, [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) bitleri tarafından kontrol edilen işlem dışındaki işlemlerle belgenin içeriğini değiştirebilip değiştiremeyeceğini belirtir. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Kullanıcının, [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) bitiyle kontrol edilen işlem dışındaki işlemlerle belgeden metin ve grafik kopyalayıp çıkarıp çıkaramayacağını belirtir. |
| [AddOrModifyFields](#AddOrModifyFields) | Kullanıcının metin açıklamaları ekleyip değiştirebilip değiştiremeyeceğini, etkileşimli form alanlarını doldurup dolduramayacağını ve [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti de ayarlıysa etkileşimli form alanlarını (imza alanları dahil) oluşturup değiştirebilip değiştiremeyeceğini belirtir. |
| [FillExistingFields](#FillExistingFields) | Kullanıcının, [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) biti temiz olsa bile mevcut etkileşimli form alanlarını (imza alanları dahil) doldurup dolduramayacağını belirtir. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Kullanıcının, engelli kullanıcıların erişilebilirliğini desteklemek veya başka amaçlarla metin ve grafik çıkarıp çıkaramayacağını belirtir. |
| [AssembleDocument](#AssembleDocument) | Kullanıcının, [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti temiz olsa bile belgeyi birleştirip (sayfaları ekleyip, döndürüp veya silip, yer imleri veya küçük resimler oluşturup) yapıp yapamayacağını belirtir. |
| [HighQualityPrint](#HighQualityPrint) | Kullanıcının, PDF içeriğinin doğru bir dijital kopyasının oluşturulabileceği bir temsile belgeyi yazdırıp yazdırmayacağını belirtir. |

### None {#None}
```
public static final int None
```

Kullanıcının hiçbir erişim iznine sahip olmadığını belirtir.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Kullanıcının belgeyi yazdırıp yazdıramayacağını belirtir (en yüksek kalite seviyesinde olmayabilir, [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) biti de ayarlıysa buna bağlıdır).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Kullanıcının, [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) bitleri tarafından kontrol edilen işlem dışındaki işlemlerle belgenin içeriğini değiştirebilip değiştiremeyeceğini belirtir.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Kullanıcının, [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) bitiyle kontrol edilen işlem dışındaki işlemlerle belgeden metin ve grafik kopyalayıp çıkarıp çıkaramayacağını belirtir.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Kullanıcının metin açıklamaları ekleyip değiştirebilip değiştiremeyeceğini, etkileşimli form alanlarını doldurup dolduramayacağını ve [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti de ayarlıysa etkileşimli form alanlarını (imza alanları dahil) oluşturup değiştirebilip değiştiremeyeceğini belirtir.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Kullanıcının, [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) biti temiz olsa bile mevcut etkileşimli form alanlarını (imza alanları dahil) doldurup dolduramayacağını belirtir.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Kullanıcının, engelli kullanıcıların erişilebilirliğini desteklemek veya başka amaçlarla metin ve grafik çıkarıp çıkaramayacağını belirtir.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Kullanıcının, [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti temiz olsa bile belgeyi birleştirip (sayfaları ekleyip, döndürüp veya silip, yer imleri veya küçük resimler oluşturup) yapıp yapamayacağını belirtir.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Kullanıcının, PDF içeriğinin doğru bir dijital kopyasının oluşturulabileceği bir temsile belgeyi yazdırıp yazdırmayacağını belirtir. Bu bit temiz olduğunda (ve [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) biti ayarlı olduğunda), baskı görünümün düşük seviyeli bir temsiliyle sınırlıdır; kalite düşebilir.