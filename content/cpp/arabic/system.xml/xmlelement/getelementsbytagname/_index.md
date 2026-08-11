---
title: GetElementsByTagName()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "يرجع XmlNodeList يحتوي على قائمة بجميع العناصر التابعة التي تطابق XmlElement::get_Name المحدد."
type: docs
weight: 287
url: /ar/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) الطريقة

يرجع [XmlNodeList](../../xmlnodelist/) يحتوي على قائمة بجميع العناصر التابعة التي تطابق [XmlElement::get_Name](../get_name/) المحدد.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الوسم الاسم للمطابقة. هذا اسم مؤهل. يتم مقارنة ذلك بقيمة **get_Name** للعقدة المطابقة. النجمة (*) هي قيمة خاصة تطابق جميع الوسوم. |

### قيمة الإرجاع

[XmlNodeList](../../xmlnodelist/) يحتوي على قائمة بجميع العقد المطابقة. تكون القائمة فارغة إذا لم توجد أي عقد مطابقة.

## XmlElement::GetElementsByTagName(String, String) الطريقة

يرجع [XmlNodeList](../../xmlnodelist/) يحتوي على قائمة بجميع العناصر التابعة التي تطابق القيمتين [XmlElement::get_LocalName](../get_localname/) و [XmlElement::get_NamespaceURI](../get_namespaceuri/) المحددتين.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للمطابقة. النجمة (*) هي قيمة خاصة تطابق جميع الوسوم. |
| namespaceURI | [String](../../../system/string/) | مسار URI للمجال للمطابقة. |

### قيمة الإرجاع

[XmlNodeList](../../xmlnodelist/) يحتوي على قائمة بجميع العقد المطابقة. تكون القائمة فارغة إذا لم توجد أي عقد مطابقة.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الصنف [XmlNodeList](../../xmlnodelist/)
* الصنف [String](../../../system/string/)
* الصنف [XmlElement](../)
* المجال [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)