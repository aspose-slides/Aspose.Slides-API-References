---
title: operator-()
second_title: Referência da API Aspose.Slides for C++
description: Calcula o número de dias entre dois dias da semana.
type: docs
weight: 2172
url: /pt/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) função

Calcula o número de dias entre dois dias da semana.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | O minuendo |
| b | [DayOfWeek](../dayofweek/) | O subtraendo |

### Valor de Retorno

O número de dias entre os dias da semana **a** e **b**; o valor de retorno é um número negativo se *vai* depois ****

## System::operator-(const T\&, const Decimal\&) função

Retorna uma nova instância da classe [Decimal](../decimal/) que representa um valor que é o resultado da subtração do valor representado pelo objeto [Decimal](../decimal/) especificado do valor especificado.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | const T\& | O valor do qual subtrair |
| d | const [Decimal](../decimal/)\& | O objeto [Decimal](../decimal/) que representa o valor subtraído |

### Valor de Retorno

Uma nova instância da classe [Decimal](../decimal/) que representa um valor que é o resultado da subtração do valor representado por **d** de **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) função

Desconecta todos os callbacks no delegate da mão direita do final da lista de callbacks do delegate da mão esquerda.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | O delegate do qual os callbacks serão removidos. |
| rhv | MulticastDelegate\<T\> | O delegate cujos callbacks serão removidos. |

### Valor de Retorno

Retorna um delegate que contém os callbacks do valor da mão esquerda, mas sem os callbacks do valor da mão direita.

## System::operator-(const T1\&, const Nullable\<T2\>\&) função

Subtrai valores não anuláveis e anuláveis.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do operando esquerdo. |
| T2 | Tipo do operando direito. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| some | const T1\& | Operando esquerdo. |
| other | const [Nullable](../nullable/)\<T2\>\& | Operando direito. |

### Valor de Retorno

Resultado da subtração.

## Veja Também

* Enum [DayOfWeek](../dayofweek/)
* Classe [Decimal](../decimal/)
* Classe [Nullable](../nullable/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)