---
title: RemoveParam()
second_title: Aspose.Slides için C++ API Referansı
description: XsltArgumentList'ten parametreyi kaldırır.
type: docs
weight: 66
url: /tr/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) yöntemi


Parametreyi [XsltArgumentList](../)'den kaldırır.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kaldırılacak parametrenin adı. [XsltArgumentList](../) aktarılmış adın geçerli bir yerel ad olup olmadığını kontrol etmez; ancak ad **nullptr** olamaz. |
| namespaceUri | const [String](../../../system/string/)\& | Kaldırılacak parametrenin ad alanı URI'si. |

### Dönüş Değeri

Parametre nesnesi veya bulunamadıysa **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [String](../../../system/string/)
* Sınıf [XsltArgumentList](../)
* Ad alanı [System::Xml::Xsl](../../)
* Kütüphane [Aspose.Slides](../../../)