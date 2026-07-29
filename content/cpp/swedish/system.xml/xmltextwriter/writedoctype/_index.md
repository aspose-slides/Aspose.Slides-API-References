---
title: WriteDocType()
second_title: Aspose.Slides för C++ API-referens
description: Skriver DOCTYPE-deklarationen med det angivna namnet och valfria attribut.
type: docs
weight: 222
url: /sv/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metod

Skriver DOCTYPE-deklarationen med det angivna namnet och valfria attribut.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på DOCTYPE. Detta får inte vara tomt. |
| pubid | const [String](../../../system/string/)\& | Om icke-null skriver den också PUBLIC "pubid" "sysid" där **pubid** och **sysid** ersätts med värdet för de givna argumenten. |
| sysid | const [String](../../../system/string/)\& | Om **pubid** är null och **sysid** är icke-null skriver den SYSTEM "sysid" där **sysid** ersätts med värdet för detta argument. |
| subset | const [String](../../../system/string/)\& | Om icke-null skriver den [subset] där subset ersätts med värdet för detta argument. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlTextWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)