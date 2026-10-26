---
title: ValidateWhitespace()
second_title: Aspose.Slides para C++ Referência da API
description: Valida se o espaço em branco na string especificada é permitido no contexto do elemento atual e acumula o espaço em branco para validação se o elemento atual possui conteúdo simples.
type: docs
weight: 196
url: /pt/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) método

Valida se o espaço em branco na **string** especificada é permitido no contexto do elemento atual e acumula o espaço em branco para validação se o elemento atual possui conteúdo simples.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Uma **string** de espaço em branco para validar no contexto do elemento atual. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) método

Valida se o espaço em branco retornado pelo objeto XmlValueGetter especificado é permitido no contexto do elemento atual e acumula o espaço em branco para validação se o elemento atual possui conteúdo simples.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Um retorno de chamada XmlValueGetter usado para passar o valor do espaço em branco como um tipo compatível com o tipo da Linguagem de Definição de XML [Schema](../../) (XSD) do atributo. |

## Veja Também

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)