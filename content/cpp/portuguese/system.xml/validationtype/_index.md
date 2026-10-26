---
title: ValidationType
second_title: Referência da API Aspose.Slides para C++
description: Especifica o tipo de validação a ser realizado.
type: docs
weight: 729
url: /pt/system.xml/validationtype/
---
## ValidationType enum

Especifica o tipo de validação a ser realizado.

```cpp
enum class ValidationType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Nenhuma validação é realizada, e nenhum erro de validação é lançado. Esta configuração cria um analisador não validador compatível com XML 1.0. |
| Auto | 1 | Valida se informações de DTD ou esquema são encontradas. |
| DTD | 2 | Valida de acordo com o DTD. |
| XDR | 3 | Valida de acordo com esquemas XML-Data Reduced (XDR), incluindo esquemas XDR embutidos. Esquemas XDR são reconhecidos usando o prefixo de namespace **x-schema** ou o valor [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Valida de acordo com esquemas da linguagem de definição XML [Schema](../../system.xml.schema/) (XSD), incluindo esquemas XML embutidos. Esquemas XML são associados a URIs de namespace seja usando o atributo **schemaLocation** ou os **Schemas** fornecidos. |

## Veja Também

* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)