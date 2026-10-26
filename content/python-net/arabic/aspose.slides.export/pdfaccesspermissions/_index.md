---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/pdfaccesspermissions/
---
## تعداد PdfAccessPermissions

يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول ينبغي منحها عندما يتم فتح المستند باستخدام وصول المستخدم.

نوع PdfAccessPermissions يكشف عن الأعضاء التالية:

## الحقول

| الحقل | الوصف |
| :- | :- |
| NONE | يحدد أن المستخدم لا يملك أذونات وصول. |
| PRINT_DOCUMENT | يحدد ما إذا كان يجوز للمستخدم طباعة المستند (ربما ليس بأعلى مستوى جودة، اعتمادًا على<br/> ما إذا كانت العلامة [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) مفعلة również). |
| MODIFY_CONTENT | يحدد ما إذا كان يجوز للمستخدم تعديل محتوى المستند بعمليات غير تلك التي تتحكم فيها<br/> العلامات [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS)، [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS)، [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | يحدد ما إذا كان يجوز للمستخدم نسخ أو استخراج النص والرسومات من المستند بعمليات<br/> غير تلك التي تتحكم فيها العلامة [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | يحدد ما إذا كان يجوز للمستخدم إضافة أو تعديل التعليقات النصية، تعبئة حقول النماذج التفاعلية، وإذا كانت العلامة<br/> [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) مفعلة أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| FILL_EXISTING_FIELDS | يحدد ما إذا كان يجوز للمستخدم تعبئة حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كانت العلامة<br/> [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) غير مفعلة. |
| EXTRACT_TEXT_AND_GRAPHICS | يحدد ما إذا كان يجوز للمستخدم استخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة<br/> أو لأغراض أخرى. |
| ASSEMBLE_DOCUMENT | يحدد ما إذا كان يجوز للمستخدم تجميع المستند (إدراج، تدوير، أو حذف صفحات وإنشاء إشارات مرجعية أو<br/> صور مصغرة)، حتى إذا كانت العلامة [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) غير مفعلة. |
| HIGH_QUALITY_PRINT | يحدد ما إذا كان يجوز للمستخدم طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة<br/> لمحتوى PDF. عندما تكون هذه العلامة غير مفعلة (والعلامة [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/ar/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) مفعلة)،<br/> تكون الطباعة مقتصرة على تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة. |

### انظر أيضًا
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)