---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, atomiza a string especificada e a adiciona ao XmlNameTable.
type: docs
weight: 14
url: /pt/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método


Quando sobrescrito em uma classe derivada, atomiza a string especificada e a adiciona ao [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | O array de caracteres contendo o nome a ser adicionado. |
| offset | **int32_t** | Índice baseado em zero no array que especifica o primeiro caractere do nome. |
| length | **int32_t** | O número de caracteres no nome. |

### Valor de Retorno

A nova string atomizada ou a já existente, se já existir. Se o comprimento for zero, [String::Empty](../../../system/string/empty/) é retornado.

## XmlNameTable::Add(const String\&) método


Quando sobrescrito em uma classe derivada, atomiza a string especificada e a adiciona ao [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | O nome a ser adicionado. |

### Valor de Retorno

A nova string atomizada ou a já existente, se já existir.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)