---
title: ReadElementString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يقرأ عنصرًا نصيًا فقط. ومع ذلك، يُنصح باستخدام طريقة XmlReader::ReadElementContentAsString بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية."
type: docs
weight: 859
url: /ar/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() طريقة

يقرا عنصرًا نصيًا فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### قيمة الإرجاع

النص المحتوى في العنصر الذي تم قراءته. سلسلة فارغة إذا كان العنصر فارغًا.

## XmlReader::ReadElementString(String) طريقة

يتحقق من أن قيمة [XmlReader::get_Name](../get_name/) للعنصر المعثور عليه تطابق السلسلة المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم للتحقق منه. |

### قيمة الإرجاع

النص المحتوى في العنصر الذي تم قراءته. سلسلة فارغة إذا كان العنصر فارغًا.

## XmlReader::ReadElementString(String, String) طريقة

يتحقق من أن قيم [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/) للعنصر المعثور عليه تطابق السلاسل المعطاة قبل قراءة عنصر نصي فقط. ومع ذلك، يُنصح باستخدام طريقة [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) بدلاً من ذلك، لأنها توفر طريقة أكثر بساطة للتعامل مع هذه العملية.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | الاسم المحلي للتحقق منه. |
| ns | [String](../../../system/string/) | معرف URI للمجال للتحقق منه. |

### قيمة الإرجاع

النص المحتوى في العنصر الذي تم قراءته. سلسلة فارغة إذا كان العنصر فارغًا.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* المجال [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)