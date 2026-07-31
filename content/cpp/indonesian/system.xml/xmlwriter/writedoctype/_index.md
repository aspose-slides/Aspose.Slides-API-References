---
title: WriteDocType()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat ditimpa di kelas turunan, menulis deklarasi DOCTYPE dengan nama yang ditentukan dan atribut opsional.
type: docs
weight: 79
url: /id/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metode

Saat ditimpa di kelas turunan, menulis deklarasi DOCTYPE dengan nama yang ditentukan dan atribut opsional.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama DOCTYPE. Ini harus tidak kosong. |
| pubid | const [String](../../../system/string/)\& | Jika tidak null, juga menulis PUBLIC \"pubid\" \"sysid\" di mana **pubid** dan **sysid** digantikan dengan nilai argumen yang diberikan. |
| sysid | const [String](../../../system/string/)\& | Jika **pubid** adalah **nullptr** dan **sysid** tidak null, maka menulis SYSTEM \"sysid\" di mana **sysid** digantikan dengan nilai argumen ini. |
| subset | const [String](../../../system/string/)\& | Jika tidak null, menulis [subset] di mana subset digantikan dengan nilai argumen ini. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlWriter](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)