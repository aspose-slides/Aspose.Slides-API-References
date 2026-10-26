---
title: SetAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen adla özelliğin değerini ayarlar.
type: docs
weight: 222
url: /tr/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) metot


Belirtilen adla özelliğin değerini ayarlar.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Oluşturulacak veya değiştirilecek özelliğin adı. Bu, nitelikli bir addır. Ad içinde iki nokta üstüste (:) varsa, önek ve yerel ad bileşenlerine ayrılır. |
| value | [String](../../../system/string/) | Özellik için ayarlanacak değer. |

## XmlElement::SetAttribute(String, String, String) metot


Belirtilen yerel ad ve ad alanı URI'sine sahip özelliğin değerini ayarlar.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Özelliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özelliğin ad alanı URI'si. |
| value | [String](../../../system/string/) | Özellik için ayarlanacak değer. |

### Dönüş Değeri

Özellik değeri.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlElement](../)
* AdAlanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)