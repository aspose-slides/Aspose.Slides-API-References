---
title: WriteDocType()
second_title: Aspose.Slides pro C++ – reference API
description: Zapisuje deklaraci DOCTYPE se zadaným názvem a volitelnými atributy.
type: docs
weight: 222
url: /cs/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metoda

Zapisuje deklaraci DOCTYPE se zadaným názvem a volitelnými atributy.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název DOCTYPE. Musí být neprázdný. |
| pubid | const [String](../../../system/string/)\& | Pokud není null, také zapíše PUBLIC \"pubid\" \"sysid\", kde **pubid** a **sysid** jsou nahrazeny hodnotou zadaných argumentů. |
| sysid | const [String](../../../system/string/)\& | Pokud je **pubid** null a **sysid** není null, zapíše SYSTEM \"sysid\", kde **sysid** je nahrazen hodnotou tohoto argumentu. |
| subset | const [String](../../../system/string/)\& | Pokud není null, zapíše [subset], kde subset je nahrazen hodnotou tohoto argumentu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlTextWriter](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)