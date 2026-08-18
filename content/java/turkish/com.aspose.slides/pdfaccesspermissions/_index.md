---
title: PdfAccessPermissions
second_title: Aspose.Slides için Java API Referansı
description: Belgenin kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verilmesi gerektiğini belirten bir dizi bayrak içerir.
type: docs
url: /tr/com.aspose.slides/pdfaccesspermissions/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Kullanıcı erişimiyle belge açıldığında hangi erişim izinlerinin verilmesi gerektiğini belirten bir dizi bayrak içerir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [None](#None) | Kullanıcının erişim izni olmadığını belirtir. |
| [PrintDocument](#PrintDocument) | Kullanıcının belgeyi yazdırıp yazdıramayacağını (muhtemelen en yüksek kalite seviyesinde olmayabilir, [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) biti de ayarlıysa buna bağlı olarak) belirtir. |
| [ModifyContent](#ModifyContent) | Kullanıcının belge içeriğini [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) bitleri tarafından kontrol edilen işlemler dışındaki işlemlerle değiştirip değiştiremeyeceğini belirtir. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Kullanıcının belgeyi [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) biti tarafından kontrol edilen işlemler dışındaki yöntemlerle metin ve grafikleri kopyalayıp/çıkarıp çıkaramayacağını belirtir. |
| [AddOrModifyFields](#AddOrModifyFields) | Kullanıcının metin ek açıklamaları ekleyip/ değiştirebileceğini, etkileşimli form alanlarını doldurabileceğini ve [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti de ayarlıysa (imza alanları dahil) etkileşimli form alanlarını oluşturup/ değiştirebileceğini belirtir. |
| [FillExistingFields](#FillExistingFields) | Kullanıcının mevcut etkileşimli form alanlarını (imza alanları dahil) [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) biti temiz olsa bile doldurup dolduramayacağını belirtir. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Kullanıcının engelli kullanıcıların erişilebilirliğini desteklemek veya başka amaçlarla metin ve grafikleri çıkarıp çıkaramayacağını belirtir. |
| [AssembleDocument](#AssembleDocument) | Kullanıcının belgeyi (sayfaları ekleyip, döndürüp, silebilir ve yer imleri ya da küçük resimler oluşturabilir) [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti temiz olsa bile birleştirip birleştiremeyeceğini belirtir. |
| [HighQualityPrint](#HighQualityPrint) | Kullanıcının PDF içeriğinin kesin bir dijital kopyası oluşturulabilecek bir temsile belgeyi yazdırıp yazdıramayacağını belirtir. |
### None {#None}
```
public static final int None
```

Kullanıcının erişim izni olmadığını belirtir.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Kullanıcının belgeyi yazdırıp yazdıramayacağını (muhtemelen en yüksek kalite seviyesinde olmayabilir, [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) biti de ayarlıysa buna bağlı olarak) belirtir.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Kullanıcının belge içeriğini [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) bitleri tarafından kontrol edilen işlemler dışındaki işlemlerle değiştirip değiştiremeyeceğini belirtir.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Kullanıcının belgeyi [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) biti tarafından kontrol edilen işlemler dışındaki yöntemlerle metin ve grafikleri kopyalayıp/çıkarıp çıkaramayacağını belirtir.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Kullanıcının metin ek açıklamaları ekleyip/ değiştirebileceğini, etkileşimli form alanlarını doldurabileceğini ve [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti de ayarlıysa (imza alanları dahil) etkileşimli form alanlarını oluşturup/ değiştirebileceğini belirtir.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Kullanıcının mevcut etkileşimli form alanlarını (imza alanları dahil) [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) biti temiz olsa bile doldurup dolduramayacağını belirtir.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Kullanıcının engelli kullanıcıların erişilebilirliğini desteklemek veya başka amaçlarla metin ve grafikleri çıkarıp çıkaramayacağını belirtir.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Kullanıcının belgeyi (sayfaları ekleyip, döndürüp, silebilir ve yer imleri ya da küçük resimler oluşturabilir) [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) biti temiz olsa bile birleştirip birleştiremeyeceğini belirtir.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Kullanıcının PDF içeriğinin kesin bir dijital kopyası oluşturulabilecek bir temsile belgeyi yazdırıp yazdıramayacağını belirtir. Bu bit temiz olduğunda (ve [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) biti ayarlıysa), yazdırma görünümün düşük seviyeli bir temsiline sınırlıdır ve kalite düşebilir.