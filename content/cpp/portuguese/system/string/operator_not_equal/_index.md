---
title: operator!=()
second_title: Referência da API Aspose.Slides for C++
description: Operador de comparação de desigualdade.
type: docs
weight: 313
url: /pt/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const método

Operador de comparação de desigualdade.

```cpp
bool System::String::operator!=(const String &str) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para comparar o atual com. |

### Valor de Retorno

false se ambas as strings forem nulas ou ambas não forem nulas e coincidirem, true caso contrário.

## String::operator!=(std::nullptr_t) const método

Verifica se a string não é nula. Aplica a mesma lógica da chamada [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### Valor de Retorno

false se a string for nula, true caso contrário.

## Veja também

* Classe [String](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)