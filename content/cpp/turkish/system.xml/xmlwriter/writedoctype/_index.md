---
title: WriteDocType()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE bildirimini yazar.
type: docs
weight: 79
url: /tr/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String&, const String&, const String&, const String&) metodu


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE bildirimini yazar.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | DOCTYPEnin adı. Bu boş olmamalıdır. |
| pubid | const [String](../../../system/string/)& | Eğer null değilse ayrıca PUBLIC \"pubid\" \"sysid\" yazar; burada **pubid** ve **sysid**, verilen argümanların değeriyle değiştirilir. |
| sysid | const [String](../../../system/string/)& | Eğer **pubid** **nullptr** ise ve **sysid** null değilse SYSTEM \"sysid\" yazar; burada **sysid**, bu argümanın değeriyle değiştirilir. |
| subset | const [String](../../../system/string/)& | Eğer null değilse [subset] yazar; burada subset, bu argümanın değeriyle değiştirilir. |

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlWriter](../)
* İsim Uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)