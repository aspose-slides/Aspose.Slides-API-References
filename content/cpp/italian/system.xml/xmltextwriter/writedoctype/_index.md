---
title: WriteDocType()
second_title: Aspose.Slides per C++ API Reference
description: Scrive la dichiarazione DOCTYPE con il nome specificato e gli attributi opzionali.
type: docs
weight: 222
url: /it/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String&, const String&, const String&, const String&) metodo

Scrive la dichiarazione DOCTYPE con il nome specificato e gli attributi opzionali.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome del DOCTYPE. Deve essere non vuoto. |
| pubid | const [String](../../../system/string/)\& | Se non è nullo scrive anche PUBLIC "pubid" "sysid" dove **pubid** e **sysid** vengono sostituiti con il valore degli argomenti forniti. |
| sysid | const [String](../../../system/string/)\& | Se **pubid** è nullo e **sysid** non è nullo scrive SYSTEM "sysid" dove **sysid** viene sostituito con il valore di questo argomento. |
| subset | const [String](../../../system/string/)\& | Se non è nullo scrive [subset] dove subset viene sostituito con il valore di questo argomento. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)