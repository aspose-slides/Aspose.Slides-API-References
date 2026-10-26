---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen önek için ad alanı URI'sını döndürür.
type: docs
weight: 118
url: /tr/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) metot

Belirtilen önek için ad alanı URI'sını döndürür.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Çözmek istediğiniz ad alanı URI'sına sahip önek. Varsayılan ad alanıyla eşleşmek için [String::Empty](../../../system/string/empty/) gönderin. |

### Dönüş Değeri

Eşlenmiş bir ad alanı yoksa **prefix** için ad alanı URI'sı veya **nullptr** döndürülür. Döndürülen dize atomik hale getirilir. Atomik dizeler hakkında daha fazla bilgi için [XmlNameTable](../../xmlnametable/) sınıfına bakın.

## İlgili Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNamespaceManager](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)