---
title: ValidateText()
second_title: Referência da API Aspose.Slides para C++
description: Valida se a string de texto especificada é permitida no contexto do elemento atual e acumula o texto para validação se o elemento atual tem conteúdo simples.
type: docs
weight: 183
url: /pt/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) método

Valida se a **string** de texto especificada é permitida no contexto do elemento atual e acumula o texto para validação se o elemento atual tem conteúdo simples.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Um **string** de texto a validar no contexto do elemento atual. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) método

Valida se o texto retornado pelo objeto XmlValueGetter especificado é permitido no contexto do elemento atual e acumula o texto para validação se o elemento atual tem conteúdo simples.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Um callback XmlValueGetter usado para passar o valor de texto como um tipo compatível com a linguagem de Definição XML [Schema](../../) (XSD) do atributo. |

## Veja Também

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)