---
title: get_Encoding()
second_title: مرجع Aspose.Slides للـ C++
description: تُرجع مستوى الترميز لمستند XML.
type: docs
weight: 14
url: /ar/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() طريقة

تُعيد مستوى الترميز لمستند XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### قيمة الإرجاع

اسم ترميز الحرف الصحيح.

## ملاحظات

أكثر أسماء ترميز الأحرف المدعومة شائعًا في XML هي التالية:

| الفئة | أسماء الترميز |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

هذه القيمة اختيارية. إذا لم يتم تعيين قيمة، تُعيد هذه الطريقة [String::Empty](../../../system/string/empty/). إذا لم يتضمن السمة الترميزية، يُفترض ترميز UTF-8 عند كتابة المستند أو حفظه.

## انظر أيضًا

* الصنف [String](../../../system/string/)
* الصنف [XmlDeclaration](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)