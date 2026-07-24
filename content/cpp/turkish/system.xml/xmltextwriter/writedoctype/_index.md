---
title: WriteDocType()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE bildirimini yazar.
type: docs
weight: 222
url: /tr/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) yöntemi

Belirtilen ad ve isteğe bağlı özniteliklerle DOCTYPE bildirimini yazar.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | DOCTYPE'un adı. Boş olmaması gerekir. |
| pubid | const [String](../../../system/string/)\& | null değilse, PUBLIC "pubid" "sysid" yazar; burada **pubid** ve **sysid**, verilen argümanların değeriyle değiştirilir. |
| sysid | const [String](../../../system/string/)\& | **pubid** null ve **sysid** null değilse, SYSTEM "sysid" yazar; burada **sysid**, bu argümanın değeriyle değiştirilir. |
| subset | const [String](../../../system/string/)\& | null değilse, [subset] yazar; burada subset, bu argümanın değeriyle değiştirilir. |

## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlTextWriter](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)