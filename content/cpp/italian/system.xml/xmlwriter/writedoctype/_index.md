---
title: WriteDocType()
second_title: Aspose.Slides per C++ Riferimento API
description: Quando sovrascritto in una classe derivata, scrive la dichiarazione DOCTYPE con il nome specificato e gli attributi opzionali.
type: docs
weight: 79
url: /it/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) metodo

Quando sovrascritto in una classe derivata, scrive la dichiarazione DOCTYPE con il nome specificato e gli attributi opzionali.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome del DOCTYPE. Deve essere non vuoto. |
| pubid | const [String](../../../system/string/)\& | Se non nullo scrive anche PUBLIC "pubid" "sysid" dove **pubid** e **sysid** vengono sostituiti con il valore degli argomenti forniti. |
| sysid | const [String](../../../system/string/)\& | Se **pubid** è **nullptr** e **sysid** è non nullo scrive SYSTEM "sysid" dove **sysid** viene sostituito con il valore di questo argomento. |
| subset | const [String](../../../system/string/)\& | Se non nullo scrive [sottoinsieme] dove sottoinsieme viene sostituito con il valore di questo argomento. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)