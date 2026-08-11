---
title: ReadChars()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بقراءة محتويات النص لعنصر إلى مخزن أحرف. تم تصميم هذه الطريقة لقراءة تدفقات نصية مدمجة كبيرة عن طريق استدعائها بشكل متتابع.
type: docs
weight: 755
url: /ar/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) طريقة

يقوم بقراءة محتويات النص لعنصر إلى مخزن أحرف. تم تصميم هذه الطريقة لقراءة تدفقات نصية مدمجة كبيرة عن طريق استدعائها بشكل متتابع.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### معاملات

| معلمة | نوع | وصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | المصفوفة من الأحرف التي تعمل كـ buffer الذي تُكتب إليه محتويات النص. |
| index | **int32_t** | الموضع داخل **buffer** حيث يمكن للطريقة بدء كتابة محتويات النص. |
| count | **int32_t** | عدد الأحرف التي سيتم كتابتها في **buffer**. |

### قيمة الإرجاع

عدد الأحرف المقروءة. يمكن أن يكون 0 إذا لم يكن القارئ موقعًا على عنصر أو إذا لم يعد هناك محتوى نصي لإرجاعه في السياق الحالي.

## راجع أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlTextReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)