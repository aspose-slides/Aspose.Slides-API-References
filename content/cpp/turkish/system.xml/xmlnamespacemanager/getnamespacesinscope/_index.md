---
title: GetNamespacesInScope()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli kapsamda bulunan ad alanlarını numaralandırmak için kullanılabilecek, önek anahtarına göre ad alanı adlarını içeren bir koleksiyon döndürür.
type: docs
weight: 105
url: /tr/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) yöntemi

Geçerli kapsamda bulunan ad alanlarını numaralandırmak için kullanılabilecek, önek anahtarına göre ad alanı adlarını içeren bir koleksiyon döndürür.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Döndürülecek ad alanı düğümlerinin türünü belirten bir enum değeri. |

### Dönüş Değeri

Geçerli kapsamda bulunan ad alanı ve önek çiftlerinden oluşan bir koleksiyon.

## Ayrıca Bakınız

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IDictionary](../../../system.collections.generic/idictionary/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNamespaceManager](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)