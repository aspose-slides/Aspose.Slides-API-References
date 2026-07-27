---
title: WriteDocType()
second_title: Referência da API do Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, grava a declaração DOCTYPE com o nome especificado e atributos opcionais.
type: docs
weight: 79
url: /pt/system.xml/xmlwriter/writedoctype/
---
## XmlWriter::WriteDocType(const String\&, const String\&, const String\&, const String\&) método


Quando sobrescrito em uma classe derivada, grava a declaração DOCTYPE com o nome especificado e atributos opcionais.

```cpp
virtual void System::Xml::XmlWriter::WriteDocType(const String &name, const String &pubid, const String &sysid, const String &subset)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome do DOCTYPE. Deve ser não vazio. |
| pubid | const [String](../../../system/string/)\& | Se não for nulo, também grava PUBLIC \"pubid\" \"sysid\" onde **pubid** e **sysid** são substituídos pelo valor dos argumentos fornecidos. |
| sysid | const [String](../../../system/string/)\& | Se **pubid** for **nullptr** e **sysid** não for nulo, grava SYSTEM \"sysid\" onde **sysid** é substituído pelo valor deste argumento. |
| subset | const [String](../../../system/string/)\& | Se não for nulo, grava [subset] onde subset é substituído pelo valor deste argumento. |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)