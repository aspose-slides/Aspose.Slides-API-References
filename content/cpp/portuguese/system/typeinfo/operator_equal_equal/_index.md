---
title: operator==()
second_title: Referência da API Aspose.Slides para C++
description: Determina se o objeto atual e os objetos TypeInfo especificados são iguais.
type: docs
weight: 443
url: /pt/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const método

Determina se o objeto atual e o objeto [TypeInfo](../) especificado são iguais.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | O objeto [TypeInfo](../) a ser comparado |

### Valor de Retorno

True se os hashes dos objetos forem iguais, caso contrário - false

## TypeInfo::operator==(std::nullptr_t) const método

Determina se o objeto [TypeInfo](../) atual é um objeto nulo, ou seja, não representa nenhum tipo.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Valor de Retorno

True se o objeto [TypeInfo](../) atual for um objeto nulo, caso contrário - false

## Veja Também

* Classe [TypeInfo](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)