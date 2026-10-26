---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Atomiza a string especificada e a adiciona ao NameTable.
type: docs
weight: 14
url: /pt/system.xml/nametable/add/
---
## NameTable::Add(const String\&) método

Atomiza a string especificada e a adiciona ao [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | A string a ser adicionada. |

### Valor de Retorno

A string atomizada ou a string existente se já existir no [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método

Atomiza a string especificada e a adiciona ao [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | O array de caracteres contendo a string a ser adicionada. |
| start | **int32_t** | O índice baseado em zero no array que especifica o primeiro caractere da string. |
| len | **int32_t** | O número de caracteres na string. |

### Valor de Retorno

A string atomizada ou a string existente se já existir no [NameTable](../). Se **len** for zero, [String::Empty](../../../system/string/empty/) será retornado.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)