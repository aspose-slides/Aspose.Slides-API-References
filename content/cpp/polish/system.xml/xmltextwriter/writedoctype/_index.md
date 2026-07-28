---
title: WriteDocType()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zapisuje deklarację DOCTYPE z określoną nazwą i opcjonalnymi atrybutami.
type: docs
weight: 222
url: /pl/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metoda

Zapisuje deklarację DOCTYPE z określoną nazwą i opcjonalnymi atrybutami.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa DOCTYPE. Musi być niepusta. |
| pubid | const [String](../../../system/string/)\& | Jeśli nie jest null, zapisuje także PUBLIC "pubid" "sysid", gdzie **pubid** i **sysid** są zastępowane wartościami podanych argumentów. |
| sysid | const [String](../../../system/string/)\& | Jeśli **pubid** jest null i **sysid** nie jest null, zapisuje SYSTEM "sysid", gdzie **sysid** jest zastępowane wartością tego argumentu. |
| subset | const [String](../../../system/string/)\& | Jeśli nie jest null, zapisuje [subset], gdzie subset jest zastępowany wartością tego argumentu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)