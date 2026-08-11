---
title: Compile()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتجميع نموذج XML SchemaObject Model (SOM) إلى معلومات المخطط للتحقق. يُستخدم للتحقق من البنية النحوية والدلالية لنموذج SOM المُنشأ برمجياً. يتم إجراء فحص التحقق الدلالي أثناء التجميع.
type: docs
weight: 352
url: /ar/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) طريقة

يقوم بتجميع نموذج XML [Schema](../../)[Object](../../../system/object/) (SOM) إلى معلومات المخطط للتحقق. يُستخدم للتحقق من البنية النحوية والدلالية لنموذج SOM المُنشأ برمجياً. يتم إجراء فحص التحقق الدلالي أثناء التجميع.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | معالج حدث التحقق الذي يتلقى معلومات حول أخطاء التحقق من XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) طريقة

يقوم بتجميع نموذج XML [Schema](../../)[Object](../../../system/object/) (SOM) إلى معلومات المخطط للتحقق. يُستخدم للتحقق من البنية النحوية والدلالية لنموذج SOM المُنشأ برمجياً. يتم إجراء فحص التحقق الدلالي أثناء التجميع.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | معالج حدث التحقق الذي يتلقى معلومات حول أخطاء التحقق من XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | الـ[XmlResolver](../../../system.xml/xmlresolver/) المستخدمة لحل النطاقات المشار إليها في عناصر **include** و **import**. |

## انظر أيضًا

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [XmlSchema](../)
* فئة [XmlResolver](../../../system.xml/xmlresolver/)
* نطاق [System::Xml::Schema](../../)
* مكتبة [Aspose.Slides](../../../)