---
title: PdfAccessPermissions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند بصلاحيات المستخدم.
type: docs
url: /ar/com.aspose.slides/pdfaccesspermissions/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند بصلاحيات المستخدم.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [None](#None) | يحدد أن المستخدم ليس لديه أذونات وصول. |
| [PrintDocument](#PrintDocument) | يحدد ما إذا كان يمكن للمستخدم طباعة المستند (قد لا يكون بأعلى جودة، اعتمادًا على ما إذا كانت البتة [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) محددة أيضًا). |
| [ModifyContent](#ModifyContent) | يحدد ما إذا كان يمكن للمستخدم تعديل محتويات المستند بعمليات غير تلك التي تتحكم فيها البتات [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)، [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | يحدد ما إذا كان يمكن للمستخدم نسخ النص والرسومات أو استخراجها بطرق أخرى من المستند بعمليات غير تلك التي تتحكم فيها البتة [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | يحدد ما إذا كان يمكن للمستخدم إضافة أو تعديل تعليقات النص، تعبئة حقول النماذج التفاعلية، وإذا كانت البتة [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) محددة أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| [FillExistingFields](#FillExistingFields) | يحدد ما إذا كان يمكن للمستخدم تعبئة حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كانت البتة [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) غير مفعلة. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | يحدد ما إذا كان يمكن للمستخدم استخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| [AssembleDocument](#AssembleDocument) | يحدد ما إذا كان يمكن للمستخدم تجميع المستند (إدراج، تدوير، أو حذف الصفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كانت البتة [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) غير مفعلة. |
| [HighQualityPrint](#HighQualityPrint) | يحدد ما إذا كان يمكن للمستخدم طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة لمحتوى PDF. |
### None {#None}
```
public static final int None
```


يحدد أن المستخدم ليس لديه أذونات وصول.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


يحدد ما إذا كان يمكن للمستخدم طباعة المستند (قد لا يكون بأعلى جودة، اعتمادًا على ما إذا كانت البتة [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) محددة أيضًا).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


يحدد ما إذا كان يمكن للمستخدم تعديل محتويات المستند بعمليات غير تلك التي تتحكم فيها البتات [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)، [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```


يحدد ما إذا كان يمكن للمستخدم نسخ النص والرسومات أو استخراجها بطرق أخرى من المستند بعمليات غير تلك التي تتحكم فيها البتة [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```


يحدد ما إذا كان يمكن للمستخدم إضافة أو تعديل تعليقات النص، تعبئة حقول النماذج التفاعلية، وإذا كانت البتة [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) محددة أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```


يحدد ما إذا كان يمكن للمستخدم تعبئة حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كانت البتة [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) غير مفعلة.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```


يحدد ما إذا كان يمكن للمستخدم استخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


يحدد ما إذا كان يمكن للمستخدم تجميع المستند (إدراج، تدوير، أو حذف الصفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كانت البتة [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) غير مفعلة.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```


يحدد ما إذا كان يمكن للمستخدم طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة لمحتوى PDF. عندما تكون هذه البتة غير مفعلة (وتكون البتة [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) مفعلة)، يقتصر الطباعة على تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة.