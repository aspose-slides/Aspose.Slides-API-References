---
title: XmlSchemaContentProcessing
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُوفر معلومات حول وضع التحقق من استبدالات عناصر any و anyAttribute.
type: docs
weight: 976
url: /ar/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

يوفر معلومات حول وضع التحقق من **any** و **anyAttribute** لاستبدالات العناصر.

```cpp
enum class XmlSchemaContentProcessing
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | عناصر المستند غير مُتحقَّق منها. |
| Skip | 1 | يجب أن تتكون عناصر المستند من XML صالح ولا يتم التحقق منها بواسطة المخطط. |
| Lax | 2 | إذا وُجد المخطط المرتبط، فسيتم التحقق من عناصر المستند. لن تُطرح أي أخطاء خلاف ذلك. |
| Strict | 3 | يجب على معالج المخطط العثور على مخطط مرتبط بالفضاء الاسمي المشار إليه لتتحقق من عناصر المستند. |

## راجع أيضاً

* نطاق [System::Xml::Schema](../)
* مكتبة [Aspose.Slides](../../)