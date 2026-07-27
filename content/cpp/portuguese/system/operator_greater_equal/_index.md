---
title: operator>=()
second_title: Aspose.Slides para C++ Referência da API
description: 
type: docs
weight: 2133
url: /pt/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) função




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) função




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) função


Sempre retorna false.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) função


Determina se o valor especificado é maior ou igual ao valor representado pelo objeto [Nullable](../nullable/) especificado ao aplicar [operator>=()](./) a esses valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do primeiro valor comparando |
| T2 | O tipo subjacente do objeto [Nullable](../nullable/) que representa o segundo valor comparando |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| some | const T1\& | Uma referência constante ao valor que será usado como o primeiro comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Uma referência constante ao objeto [Nullable](../nullable/) cujo valor representado será usado como o segundo comparando |

### Valor de Retorno

True se o primeiro comparando for maior ou igual ao segundo comparando, caso contrário - false

## System::operator>=(std::nullptr_t, TimeSpan) função




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## Veja Também

* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Nullable](../nullable/)
* Classe [TimeSpan](../timespan/)
* Estrutura [IsNullable](../isnullable/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)