---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o atributo com o índice especificado.
type: docs
weight: 1
url: /pt/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) método

Retorna o atributo com o índice especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. |

### Valor de retorno

O atributo no índice especificado.

## XmlAttributeCollection::idx_get(const String\&) método

Retorna o atributo com o nome especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | O nome qualificado do atributo. |

### Valor de retorno

O atributo com o nome especificado. Se o atributo não existir, este método retorna **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) método

Retorna o atributo com o nome local e o Uniform Resource Identifier (URI) do namespace especificados.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |
| namespaceURI | const [String](../../../system/string/)\& | O URI do namespace do atributo. |

### Valor de retorno

O atributo com o nome local e o URI do namespace especificados. Se o atributo não existir, este método retorna **nullptr**.

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlAttribute](../../xmlattribute/)
* Classe [XmlAttributeCollection](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)