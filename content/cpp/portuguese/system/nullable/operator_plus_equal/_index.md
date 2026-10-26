---
title: operator+=()
second_title: Aspose.Slides para C++ Referência da API
description: Redefine o objeto atual para que ele represente um valor nulo.
type: docs
weight: 235
url: /pt/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) método

Redefine o objeto atual para que ele represente um valor nulo.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Valor de Retorno

Uma cópia do próprio objeto

## Nullable::operator+=(const T1\&) método

Aplica [operator+=()](./) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do valor usado como valor do lado direito de [operator+=()](./) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Uma referência constante ao valor que é usado como valor do lado direito do [operator+=()](./) aplicado ao valor representado pelo objeto atual. |

### Valor de Retorno

Uma referência ao próprio objeto

## Nullable::operator+=(const Nullable\<T1\>\&) método

Aplica [operator+=()](./) ao valor representado pelo objeto atual usando o valor representado pelo objeto [Nullable](../) especificado como argumento do lado direito.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente de um objeto [Nullable](../) cujo valor representado é usado como argumento do lado direito de [operator+=()](./) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Uma referência constante ao objeto [Nullable](../) cujo valor representado é usado como argumento do lado direito do [operator+=()](./) aplicado ao valor representado pelo objeto atual. |

### Valor de Retorno

Uma referência ao próprio objeto

## Ver Também

* Classe [Nullable](../)
* Estrutura [IsNullable](../../isnullable/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)