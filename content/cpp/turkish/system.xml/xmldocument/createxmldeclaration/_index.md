---
title: CreateXmlDeclaration()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değerlerle bir XmlDeclaration düğümü oluşturur.
type: docs
weight: 378
url: /tr/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) metodu

Belirtilen değerlerle bir [XmlDeclaration](../../xmldeclaration/) düğümü oluşturur.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Sürüm \"1.0\" olmalıdır. |
| encoding | const [String](../../../system/string/)\& | Kodlama özniteliğinin değeri. Bu, [XmlDocument](../)'yi bir dosyaya veya akışa kaydettiğinizde kullanılan kodlamadır; bu nedenle, [Text::Encoding](../../../system.text/encoding/) sınıfı tarafından desteklenen bir dize olarak ayarlanmalıdır, aksi takdirde \"XmlDocument::Save(String)\" başarısız olur. Eğer bu **nullptr** veya [String::Empty](../../../system/string/empty/) ise, [XmlDocument::Save](../save/) yöntemi XML bildirgesinde bir kodlama özniteliği yazmaz ve bu yüzden varsayılan kodlama, UTF-8, kullanılır. |
| standalone | const [String](../../../system/string/)\& | Değer \"yes\" ya da \"no\" olmalıdır. Eğer bu **nullptr** veya [String::Empty](../../../system/string/empty/) ise, [XmlDocument::Save](../save/) yöntemi XML bildirgesinde bir standalone özniteliği yazmaz. |

### Dönüş Değeri

Yeni [XmlDeclaration](../../xmldeclaration/) düğümü.

## Açıklamalar

Not: Eğer [XmlDocument](../) bir TextWriter ya da bir [XmlTextWriter](../../xmltextwriter/)'a kaydedilirse, bu kodlama değeri göz ardı edilir. Bunun yerine TextWriter'ın ya da [XmlTextWriter](../../xmltextwriter/)'in kodlaması kullanılır. Bu, dışa yazılan XML'nin doğru kodlamayla yeniden okunabilmesini sağlar. 

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlDeclaration](../../xmldeclaration/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlDocument](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)