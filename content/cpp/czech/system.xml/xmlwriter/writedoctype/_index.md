---
title: WriteDocType()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Když je přepsána v odvozené třídě, zapíše deklaraci DOCTYPE se zadaným názvem a volitelnými atributy.
type: docs
weight: 79
url: /cs/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metoda


Když je přepsána v odvozené třídě, zapíše deklaraci DOCTYPE se zadaným názvem a volitelnými atributy.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název DOCTYPE. Musí být neprázdný. |
| pubid | const [String](../../../system/string/)\& | Pokud není null, také zapíše PUBLIC \"pubid\" \"sysid\", kde **pubid** a **sysid** jsou nahrazeny hodnotami zadaných argumentů. |
| sysid | const [String](../../../system/string/)\& | Pokud je **pubid** **nullptr** a **sysid** není null, zapíše SYSTEM \"sysid\", kde **sysid** je nahrazen hodnotou tohoto argumentu. |
| subset | const [String](../../../system/string/)\& | Pokud není null, zapíše [subset], kde subset je nahrazen hodnotou tohoto argumentu. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlWriter](../)
* Obor názvů [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)