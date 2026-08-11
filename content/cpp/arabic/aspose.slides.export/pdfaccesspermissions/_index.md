---
title: PdfAccessPermissions
second_title: مرجع API Aspose.Slides للـ C++
description: يتضمن مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند بوصول المستخدم.
type: docs
weight: 989
url: /ar/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions تعداد

Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.

```cpp
enum class PdfAccessPermissions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | يحدد أن المستخدم لا يمتلك أذونات وصول. |
| PrintDocument | 4 | يحدد ما إذا كان يمكن للمستخدم طباعة المستند (ربما ليس بأعلى مستوى جودة، اعتمادًا على ما إذا كانت البتة [PdfAccessPermissions::HighQualityPrint](./) محددة أيضًا). |
| ModifyContent | 8 | يحدد ما إذا كان يمكن للمستخدم تعديل محتويات المستند عبر عمليات غير تلك التي تتحكم فيها البتات [PdfAccessPermissions::AddOrModifyFields](./)، [PdfAccessPermissions::FillExistingFields](./)، [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | يحدد ما إذا كان يمكن للمستخدم نسخ أو استخراج النص والرسومات من المستند بطرق غير تلك التي تتحكم فيها البتة [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | يحدد ما إذا كان يمكن للمستخدم إضافة أو تعديل التعليقات النصية، تعبئة حقول النماذج التفاعلية، وإذا كانت البتة [PdfAccessPermissions::ModifyContent](./) محددة أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| FillExistingFields | 256 | يحدد ما إذا كان يمكن للمستخدم تعبئة حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كانت البتة [PdfAccessPermissions::AddOrModifyFields](./) غير مفعلة. |
| ExtractTextAndGraphics | 512 | يحدد ما إذا كان يمكن للمستخدم استخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى. |
| AssembleDocument | 1024 | يحدد ما إذا كان يمكن للمستخدم تجميع المستند (إدراج، تدوير، أو حذف صفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كانت البتة [PdfAccessPermissions::ModifyContent](./) غير مفعلة. |
| HighQualityPrint | 2048 | يحدد ما إذا كان يمكن للمستخدم طباعة المستند إلى تمثيل يمكن منه إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما تكون هذه البتة غير مفعلة (وتكون البتة [PdfAccessPermissions::PrintDocument](./) مفعلة)، فإن الطباعة تقتصر على تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة. |

## انظر أيضًا

* النطاق [Aspose::Slides::Export](../)
* المكتبة [Aspose.Slides](../../)