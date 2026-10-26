---
title: operator==()
second_title: Referência da API Aspose.Slides para C++
description: Operador de comparação de igualdade.
type: docs
weight: 300
url: /pt/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const método

Operador de comparação de igualdade.

```cpp
bool System::String::operator==(const String &str) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para comparar o atual com. |

### Valor de Retorno

true se ambas as strings forem null ou ambas não forem null e coincidir, false caso contrário.

## String::operator==(std::nullptr_t) const método

Verifica se a string é null. Aplica a mesma lógica da chamada [IsNull()](../isnull/).

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### Valor de Retorno

true se a string for null, false caso contrário.

## Veja Também

* Classe [String](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)