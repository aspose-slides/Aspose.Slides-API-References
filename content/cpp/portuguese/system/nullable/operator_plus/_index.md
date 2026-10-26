---
title: operator+()
second_title: Referência da API Aspose.Slides for C++
description: Retorna uma instância construída por padrão da classe Nullable<T>.
type: docs
weight: 209
url: /pt/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const método

Retorna uma instância construída por padrão da classe Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const método

Soma valores anuláveis e não anuláveis.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do operando à direita. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const T1\& | valor a ser adicionado. |

### Valor de retorno

Resultado da soma.

## Nullable::operator+(const Nullable\<T1\>\&) const método

Soma valores anuláveis.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do operando à direita. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | valor a ser adicionado. |

### Valor de retorno

Resultado da soma.

## Veja também

* Classe [Nullable](../)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)