---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بقراءة العنصر وفك ترميز محتوى BinHex.
type: docs
weight: 482
url: /ar/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) طريقة


يقوم بقراءة العنصر وفك ترميز محتوى BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن المؤقت الذي سيتم نسخ النص الناتج إليه. لا يمكن أن تكون هذه القيمة **nullptr**. |
| index | **int32_t** | الإزاحة داخل المخزن المؤقت حيث يبدأ نسخ النتيجة. |
| count | **int32_t** | الحد الأقصى لعدد البايتات التي سيتم نسخها إلى المخزن المؤقت. عدد البايتات الفعلي المنسوخة يُعاد من هذه الطريقة. |

### قيمة الإرجاع

عدد البايتات المكتوبة إلى المخزن المؤقت.

## أنظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [XmlNodeReader](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)