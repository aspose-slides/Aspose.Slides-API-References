---
title: MoveToAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Move para o atributo com o nome especificado.
type: docs
weight: 456
url: /pt/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) método

Move para o atributo com o nome especificado.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não muda.

## XmlValidatingReader::MoveToAttribute(String, String) método

Move para o atributo com o nome local e o identificador de recurso uniforme (URI) do namespace especificados.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do atributo. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do atributo. |

### Valor de Retorno

**true** se o atributo for encontrado; caso contrário, **false**. Se **false**, a posição do leitor não muda.

## XmlValidatingReader::MoveToAttribute(int32_t) método

Move para o atributo com o índice especificado.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **int32_t** | O índice do atributo. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlValidatingReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)