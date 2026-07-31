---
title: WriteDocType()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis deklarasi DOCTYPE dengan nama yang ditentukan dan atribut opsional.
type: docs
weight: 222
url: /id/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metode

Menulis deklarasi DOCTYPE dengan nama yang ditentukan dan atribut opsional.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama DOCTYPE. Harus tidak kosong. |
| pubid | const [String](../../../system/string/)\& | Jika tidak null, juga menulis PUBLIC \"pubid\" \"sysid\" di mana **pubid** dan **sysid** digantikan dengan nilai argumen yang diberikan. |
| sysid | const [String](../../../system/string/)\& | Jika **pubid** null dan **sysid** tidak null, menulis SYSTEM \"sysid\" di mana **sysid** digantikan dengan nilai argumen ini. |
| subset | const [String](../../../system/string/)\& | Jika tidak null, menulis [subset] di mana subset digantikan dengan nilai argumen ini. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlTextWriter](../)
* Ruang nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)