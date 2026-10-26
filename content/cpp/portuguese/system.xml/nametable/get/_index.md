---
title: Get()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a string atomizada com o valor especificado.
type: docs
weight: 27
url: /pt/system.xml/nametable/get/
---
## NameTable::Get(const String\&) método

Retorna a string atomizada com o valor especificado.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | O nome a ser encontrado. |

### Valor de Retorno

O objeto string atomizado ou **nullptr** se a string ainda não foi atomizada.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método

Retorna a string atomizada contendo os mesmos caracteres do intervalo especificado no array fornecido.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | O array de caracteres contendo o nome a ser encontrado. |
| start | **int32_t** | O índice baseado em zero no array que especifica o primeiro caractere do nome. |
| len | **int32_t** | O número de caracteres no nome. |

### Valor de Retorno

A string atomizada ou **nullptr** se a string ainda não foi atomizada. Se **len** for zero, [String::Empty](../../../system/string/empty/) será retornado.

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [NameTable](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)