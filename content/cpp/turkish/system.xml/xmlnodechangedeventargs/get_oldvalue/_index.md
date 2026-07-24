---
title: get_OldValue()
second_title: Aspose.Slides for C++ API Referansı
description: Düğümün orijinal değerini döndürür.
type: docs
weight: 53
url: /tr/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() yöntemi

Düğümün orijinal değerini döndürür.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```

### Dönüş Değeri

Düğümün orijinal değeri. Bu yöntem, düğüm bir öznitelik ya da metin düğümü değilse veya düğüm ekleniyorsa **nullptr** döndürür. **XmlDocument::NodeChanging** olayında çağrılırsa, **get_OldValue** başarılı bir değişiklik gerçekleşirse değiştirilecek düğümün mevcut değerini döndürür. **XmlDocument::NodeChanged** olayında çağrılırsa, **get_OldValue** değişiklik öncesindeki düğüm değerini döndürür.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNodeChangedEventArgs](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)