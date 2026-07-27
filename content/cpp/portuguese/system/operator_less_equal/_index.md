---
title: operator<=()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 2107
url: /pt/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) função




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) função




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) função


Sempre retorna false.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) função


Determina se o valor especificado é menor ou igual ao valor representado pelo objeto [Nullable](../nullable/) especificado, aplicando [operator<=()](./) a esses valores.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | O tipo do primeiro valor comparado |
| T2 | O tipo subjacente do objeto [Nullable](../nullable/) que representa o segundo valor comparado |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| some | const T1\& | Uma referência constante ao valor que será usado como o primeiro comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Uma referência constante ao objeto [Nullable](../nullable/) cujo valor representado será usado como o segundo comparando |

### Valor de retorno

True se o primeiro comparando for menor ou igual ao segundo comparando, caso contrário - false

## System::operator<=(std::nullptr_t, TimeSpan) função




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## Ver também

* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Nullable](../nullable/)
* Classe [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)