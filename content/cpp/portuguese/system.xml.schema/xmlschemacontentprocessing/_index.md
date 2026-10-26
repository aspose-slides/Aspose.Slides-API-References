---
title: XmlSchemaContentProcessing
second_title: Referência da API Aspose.Slides para C++
description: Fornece informações sobre o modo de validação de substituições de elementos any e anyAttribute.
type: docs
weight: 976
url: /pt/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Fornece informações sobre o modo de validação de substituições de elementos **any** e **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Os itens do documento não são validados. |
| Skip | 1 | Os itens do documento devem consistir em XML bem formado e não são validados pelo esquema. |
| Lax | 2 | Se o esquema associado for encontrado, os itens do documento serão validados. Nenhum erro será lançado caso contrário. |
| Strict | 3 | O processador de esquema deve encontrar um esquema associado ao namespace indicado para validar os itens do documento. |

## Veja Também

* Namespace [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)