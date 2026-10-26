---
title: WriteDocType()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, zapisuje deklarację DOCTYPE z określoną nazwą i opcjonalnymi atrybutami.
type: docs
weight: 79
url: /pl/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String&, const String&, const String&, const String&) metoda

Gdy zostanie przesłonięta w klasie pochodnej, zapisuje deklarację DOCTYPE z określoną nazwą i opcjonalnymi atrybutami.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | Nazwa DOCTYPE. Musi być niepusta. |
| pubid | const [String](../../../system/string/)& | Jeśli nie jest null, zapisuje także PUBLIC "pubid" "sysid", gdzie **pubid** i **sysid** są zastępowane wartością podanych argumentów. |
| sysid | const [String](../../../system/string/)& | Jeśli **pubid** jest **nullptr** i **sysid** nie jest null, zapisuje SYSTEM "sysid", gdzie **sysid** jest zastępowany wartością tego argumentu. |
| subset | const [String](../../../system/string/)& | Jeśli nie jest null, zapisuje [podzbiór], gdzie subset jest zastępowany wartością tego argumentu. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)