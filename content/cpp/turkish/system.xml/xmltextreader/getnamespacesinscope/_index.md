---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API Referansı
description: Şu anda kapsamda olan tüm namespace'leri içeren bir koleksiyon döndürür.
type: docs
weight: 716
url: /tr/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) yöntemi


Şu anda kapsamda olan tüm namespace'leri içeren bir koleksiyon döndürür.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Dönüş yapılacak namespace düğümlerinin türünü belirten bir XmlNamespaceScope değeri. |

### Dönüş Değeri

İçinde mevcut kapsamda olan tüm namespace'leri barındıran bir IDictionary nesnesi. Okuyucu bir öğe üzerinde konumlandırılmamışsa, boş bir sözlük (namespace yok) döndürülür.

## İlgili

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)