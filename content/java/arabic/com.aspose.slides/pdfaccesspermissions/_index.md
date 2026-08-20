---
title: PdfAccessPermissions
second_title: مرجع API Aspose.Slides للغة Java
description: يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب أن تُمنح عندما يُفتح المستند بإذن المستخدم.
type: docs
url: /ar/com.aspose.slides/pdfaccesspermissions/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب أن تُمنح عندما يُفتح المستند بإذن المستخدم.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [None](#None) | يحدد أن المستخدم لا يمتلك أذونات وصول. |
| [PrintDocument](#PrintDocument) | يحدد ما إذا كان بإمكان المستخدم طباعة المستند (ربما ليس بأعلى مستوى جودة، اعتمادًا على ما إذا كان البت [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) مُحددًا أيضًا). |
| [ModifyContent](#ModifyContent) | يحدد ما إذا كان بإمكان المستخدم تعديل محتويات المستند عبر عمليات غير تلك التي يتحكم فيها البتات [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)، [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | يحدد ما إذا كان بإمكان المستخدم نسخ النص والرسومات أو استخراجها بطرق أخرى من المستند عبر عمليات غير تلك التي يتحكم فيها البت [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | يحدد ما إذا كان بإمكان المستخدم إضافة أو تعديل التعليقات النصية، تعبئة حقول النماذج التفاعلية، وإذا كان البت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) مُحددًا أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| [FillExistingFields](#FillExistingFields) | يحدد ما إذا كان بإمكان المستخدم تعبئة حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى وإن كان البت [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) غير مُحدد. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | يحدد ما إذا كان بإمكان المستخدم استخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى. |
| [AssembleDocument](#AssembleDocument) | يحدد ما إذا كان بإمكان المستخدم تجميع المستند (إدراج، تدوير، أو حذف صفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى وإن كان البت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) غير مُحدد. |
| [HighQualityPrint](#HighQualityPrint) | يحدد ما إذا كان بإمكان المستخدم طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. |
### None {#None}
```
public static final int None
```

يحدد أن المستخدم لا يمتلك أذونات وصول.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

يحدد ما إذا كان بإمكان المستخدم طباعة المستند (ربما ليس بأعلى مستوى جودة، اعتمادًا على ما إذا كان البت [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) مُحددًا أيضًا).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

يحدد ما إذا كان بإمكان المستخدم تعديل محتويات المستند عبر عمليات غير تلك التي يتحكم فيها البتات [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)، [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)، [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

يحدد ما إذا كان بإمكان المستخدم نسخ النص والرسومات أو استخراجها بطرق أخرى من المستند عبر عمليات غير تلك التي يتحكم فيها البت [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

يحدد ما إذا كان بإمكان المستخدم إضافة أو تعديل التعليقات النصية، تعبئة حقول النماذج التفاعلية، وإذا كان البت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) مُحددًا أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

يحدد ما إذا كان بإمكان المستخدم تعبئة حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى وإن كان البت [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) غير مُحدد.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

يحدد ما إذا كان بإمكان المستخدم استخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

يحدد ما إذا كان بإمكان المستخدم تجميع المستند (إدراج، تدوير، أو حذف صفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى وإن كان البت [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) غير مُحدد.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

يحدد ما إذا كان بإمكان المستخدم طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما يكون هذا البت غير مُحدد (والبت [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) مُحدد)، تكون الطباعة محدودة إلى تمثيل منخفض المستوى للمظهر، قد يكون بجودة منخفضة.