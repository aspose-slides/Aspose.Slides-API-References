---
title: WriteDocType()
second_title: Referência da API Aspose.Slides para C++
description: Escreve a declaração DOCTYPE com o nome especificado e atributos opcionais.
type: docs
weight: 222
url: /pt/system.xml/xmltextwriter/writedoctype/
---
## XmlTextWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) método

Escreve a declaração DOCTYPE com o nome especificado e atributos opcionais.

```cpp
void System::Xml::XmlTextWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome do DOCTYPE. Deve ser não vazio. |
| pubid | const [String](../../../system/string/)\& | Se não for nulo, também grava PUBLIC \"pubid\" \"sysid\" onde **pubid** e **sysid** são substituídos pelo valor dos argumentos fornecidos. |
| sysid | const [String](../../../system/string/)\& | Se **pubid** for nulo e **sysid** não for nulo, grava SYSTEM \"sysid\" onde **sysid** é substituído pelo valor deste argumento. |
| subset | const [String](../../../system/string/)\& | Se não for nulo, grava [subset] onde subset é substituído pelo valor deste argumento. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)