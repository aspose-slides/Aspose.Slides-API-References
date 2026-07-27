---
title: RemoveParam()
second_title: Aspose.Slides for C++ Referência da API
description: Remove o parâmetro da XsltArgumentList.
type: docs
weight: 66
url: /pt/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) método

Remove o parâmetro de [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome do parâmetro a ser removido. [XsltArgumentList](../) não verifica se o nome passado é um nome local válido; porém, o nome não pode ser **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | O URI do namespace do parâmetro a ser removido. |

### Valor de Retorno

O objeto do parâmetro ou **nullptr** se não for encontrado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)