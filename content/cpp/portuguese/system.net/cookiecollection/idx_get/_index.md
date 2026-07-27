---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um cookie da coleção de cookies no índice especificado.
type: docs
weight: 40
url: /pt/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) método

Retorna um cookie da coleção de cookies no índice especificado.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice de um cookie que deve ser retornado. |

### Valor de Retorno

Um cookie no índice especificado.

## CookieCollection::idx_get(String) método

Retorna um cookie da coleção de cookies pelo nome especificado.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome de um cookie que deve ser retornado. |

### Valor de Retorno

Um cookie da coleção de cookies pelo nome especificado quando encontrado; caso contrário, nullptr.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [Cookie](../../cookie/)
* classe [CookieCollection](../)
* classe [String](../../../system/string/)
* espaço de nomes [System::Net](../../)
* biblioteca [Aspose.Slides](../../../)