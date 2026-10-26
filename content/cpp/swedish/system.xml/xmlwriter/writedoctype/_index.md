---
title: WriteDocType()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en härledd klass skriver den DOCTYPE-deklarationen med det angivna namnet och valfria attribut.
type: docs
weight: 79
url: /sv/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metod

När den åsidosätts i en härledd klass skriver den DOCTYPE-deklarationen med det angivna namnet och valfria attribut.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på DOCTYPE. Detta måste vara icke-tomt. |
| pubid | const [String](../../../system/string/)\& | Om den inte är null skriver den även PUBLIC "pubid" "sysid" där **pubid** och **sysid** ersätts med värdet på de angivna argumenten. |
| sysid | const [String](../../../system/string/)\& | Om **pubid** är **nullptr** och **sysid** inte är null skriver den SYSTEM "sysid" där **sysid** ersätts med värdet på detta argument. |
| subset | const [String](../../../system/string/)\& | Om den inte är null skriver den [subset] där subset ersätts med värdet på detta argument. |

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlWriter](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)