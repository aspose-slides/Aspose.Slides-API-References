---
title: WriteDocType()
second_title: Aspose.Slides C++ API hivatkozás
description: Kiírja a DOCTYPE deklarációt a megadott névvel és opcionális attribútumokkal.
type: docs
weight: 222
url: /hu/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) módszer

Kiírja a DOCTYPE deklarációt a megadott névvel és opcionális attribútumokkal.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A DOCTYPE neve. Ennek nem lehet üres. |
| pubid | const [String](../../../system/string/)\& | Ha nem null, akkor a PUBLIC \"pubid\" \"sysid\" kifejezést is kiírja, ahol a **pubid** és **sysid** helyére az adott argumentumok értéke kerül. |
| sysid | const [String](../../../system/string/)\& | Ha **pubid** null, és **sysid** nem null, akkor a SYSTEM \"sysid\" kifejezést írja ki, ahol a **sysid** helyére ennek az argumentumnak az értéke kerül. |
| subset | const [String](../../../system/string/)\& | Ha nem null, akkor a [subset] részt írja ki, ahol a subset helyére az argumentum értéke kerül. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextWriter](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)