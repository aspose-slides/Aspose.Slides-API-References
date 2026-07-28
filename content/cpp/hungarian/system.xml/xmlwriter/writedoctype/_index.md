---
title: WriteDocType()
second_title: Aspose.Slides for C++ API referencia
description: Ha egy származtatott osztályban felülírják, a megadott névvel és opcionális attribútumokkal írja ki a DOCTYPE deklarációt.
type: docs
weight: 79
url: /hu/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metódus

Ha egy származtatott osztályban felülírják, akkor a megadott névvel és opcionális attribútumokkal írja ki a DOCTYPE deklarációt.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | A DOCTYPE neve. Ennek nem lehet üresnek lennie. |
| pubid | const [String](../../../system/string/)\& | Ha nem null, akkor a PUBLIC "pubid" "sysid" szöveget is kiírja, ahol a **pubid** és **sysid** a megadott argumentumok értékével lesz helyettesítve. |
| sysid | const [String](../../../system/string/)\& | Ha **pubid** **nullptr**, és **sysid** nem null, akkor a SYSTEM "sysid" szöveget írja ki, ahol a **sysid** a jelen argumentum értékével lesz helyettesítve. |
| subset | const [String](../../../system/string/)\& | Ha nem null, akkor a [subset] szöveget írja ki, ahol a subset a jelen argumentum értékével lesz helyettesítve. |

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlWriter](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)