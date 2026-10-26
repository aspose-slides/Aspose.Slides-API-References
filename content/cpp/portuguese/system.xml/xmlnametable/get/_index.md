---
title: Get()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, obtém a cadeia atomizada contendo os mesmos caracteres do intervalo de caracteres especificado no array fornecido.
type: docs
weight: 1
url: /pt/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método


Quando sobrescrito em uma classe derivada, obtém a cadeia atomizada contendo os mesmos caracteres do intervalo de caracteres especificado no array fornecido.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | O array de caracteres contendo o nome a ser pesquisado. |
| offset | **int32_t** | O índice baseado em zero no array que especifica o primeiro caractere do nome. |
| length | **int32_t** | O número de caracteres no nome. |

### Valor de retorno

A cadeia atomizada ou **nullptr** se a cadeia ainda não foi atomizada. Se **length** for zero, [String::Empty](../../../system/string/empty/) é retornado.

## XmlNameTable::Get(const String\&) método


Quando sobrescrito em uma classe derivada, obtém a cadeia atomizada contendo o mesmo valor da cadeia especificada.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | O nome a ser pesquisado. |

### Valor de retorno

A cadeia atomizada ou **nullptr** se a cadeia ainda não foi atomizada.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)