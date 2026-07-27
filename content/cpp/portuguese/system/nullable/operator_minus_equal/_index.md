---
title: operator-=()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma instância da classe Nullable que representa um valor nulo.
type: docs
weight: 248
url: /pt/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) método


Retorna uma instância da classe [Nullable](../) que representa um valor nulo.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) método


Aplica [operator-=()](./) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do valor usado como valor do lado direito de [operator-=()](./) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | Uma referência constante ao valor que é usado como valor do lado direito do [operator-=()](./) aplicado ao valor representado pelo objeto atual. |

### Valor de retorno

Uma referência ao próprio objeto

## Nullable::operator-=(const Nullable\<T1\>\&) método


Aplica [operator-=()](./) ao valor representado pelo objeto atual usando o valor representado pelo objeto [Nullable](../) especificado como argumento do lado direito.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo subjacente de um objeto [Nullable](../) cujo valor representado é usado como argumento do lado direito de [operator-=()](./) |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Uma referência constante ao objeto [Nullable](../) cujo valor representado é usado como argumento do lado direito do [operator-=()](./) aplicado ao valor representado pelo objeto atual. |

### Valor de retorno

Uma referência ao próprio objeto

## Veja Também

* Classe [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)