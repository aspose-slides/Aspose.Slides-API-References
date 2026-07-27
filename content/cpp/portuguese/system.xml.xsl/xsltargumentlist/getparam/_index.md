---
title: GetParam()
second_title: Referência da API Aspose.Slides for C++
description: Retorna o parâmetro associado ao nome qualificado do namespace.
type: docs
weight: 14
url: /pt/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) método

Retorna o parâmetro associado ao nome qualificado do namespace.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome do parâmetro. [XsltArgumentList](../) não verifica se o nome passado é um nome local válido; entretanto, o nome não pode ser **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | O URI do namespace associado ao parâmetro. |

### Valor de Retorno

O objeto de parâmetro ou **nullptr** se nenhum for encontrado.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)