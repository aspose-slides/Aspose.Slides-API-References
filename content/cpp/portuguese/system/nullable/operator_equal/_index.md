---
title: operator=()
second_title: Referência da API Aspose.Slides para C++
description: Atribui um null ao objeto atual.
type: docs
weight: 14
url: /pt/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) método

Atribui um null ao objeto atual.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Valor de Retorno

Um objeto [Nullable](../) que representa um valor nulo.

## Nullable::operator=(const T1\&) método

Substitui o valor atualmente representado pelo objeto pelo especificado.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| O | tipo do novo valor a ser representado pelo objeto atual |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const T1\& | O novo valor a ser representado pelo objeto atual |

### Valor de Retorno

Uma referência ao próprio objeto

## Nullable::operator=(const Nullable\<T1\>\&) método

Substitui o valor atualmente representado pelo objeto pelo especificado.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| O | tipo do novo valor a ser representado pelo objeto atual |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | O novo valor a ser representado pelo objeto atual |

### Valor de Retorno

Uma referência ao próprio objeto

## Veja Também

* Classe [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)