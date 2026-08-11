---
title: ReadBinHex()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يفكّ شيفرة BinHex ويعيد البايتات الثنائية المفكوكة.
type: docs
weight: 781
url: /ar/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يقوم بفك تشفير **BinHex** ويعيد البايتات الثنائية المفكوكة.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت التي تعمل كالمخزن الذي تُكتب فيه البايتات الثنائية المفكوكة. |
| offset | **int32_t** | الفهرس القائم على الصفر في المصفوفة الذي يحدد المكان الذي يمكن للطريقة البدء في الكتابة إليه في المخزن. |
| len | **int32_t** | عدد البايتات التي يجب كتابتها في المخزن. |

### قيمة الإرجاع

عدد البايتات المكتوبة في المخزن الخاص بك.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlTextReader](../)
* نطاق الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)