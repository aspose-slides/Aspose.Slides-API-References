---
title: get_NewValue()
second_title: Aspose.Slides for C++ API Referansı
description: Düğümün yeni değerini döndürür.
type: docs
weight: 66
url: /tr/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() yöntemi


Düğümün yeni değeri.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### Dönüş Değeri

Düğümün yeni değeri. Bu yöntem, düğüm ne bir öznitelik ne de bir metin düğümü ise veya düğüm kaldırılıyorsa **nullptr** döndürür. **XmlDocument::NodeChanging** olayında çağrıldığında, **get_NewValue** değişiklik başarılıysa düğümün değerini döndürür. **XmlDocument::NodeChanged** olayında çağrıldığında, **get_NewValue** düğümün mevcut değerini döndürür.

## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNodeChangedEventArgs](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)