---
title: TimeSpan()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um objeto TimeSpan que representa um intervalo de tempo zero.
type: docs
weight: 1
url: /pt/system/timespan/timespan/
---
## TimeSpan::TimeSpan() construtor


Constrói um objeto [TimeSpan](../) que representa um intervalo de tempo zero.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) construtor


Constrói uma instância da classe [TimeSpan](../) que representa o intervalo de tempo especificado.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ticks | **int64_t** | O intervalo de tempo a ser representado pela instância que está sendo construída, expresso como o número de intervalos de 100 nanossegundos. |

## TimeSpan::TimeSpan(int, int, int) construtor


Constrói uma instância da classe [TimeSpan](../) que representa o intervalo de tempo que é igual à soma do número especificado de horas, minutos e segundos.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hours | int | O número de horas na componente de horas do intervalo de tempo a ser representado pela instância que está sendo construída |
| minutes | int | O número de minutos na componente de minutos do intervalo de tempo a ser representado pela instância que está sendo construída |
| seconds | int | O número de segundos na componente de segundos do intervalo de tempo a ser representado pela instância que está sendo construída |

## TimeSpan::TimeSpan(int, int, int, int, int) construtor


Constrói uma instância da classe [TimeSpan](../) que representa o intervalo de tempo que é igual à soma do número especificado de horas, minutos, segundos e milissegundos.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| days | int | O número de dias na componente de dias do intervalo de tempo a ser representado pela instância que está sendo construída |
| hours | int | O número de horas na componente de horas do intervalo de tempo a ser representado pela instância que está sendo construída |
| minutes | int | O número de minutos na componente de minutos do intervalo de tempo a ser representado pela instância que está sendo construída |
| seconds | int | O número de segundos na componente de segundos do intervalo de tempo a ser representado pela instância que está sendo construída |
| milliseconds | int | O número de milissegundos na componente de milissegundos do intervalo de tempo a ser representado pela instância que está sendo construída |

## TimeSpan::TimeSpan(const TimeSpan\&) construtor


Constrói um objeto [TimeSpan](../) que representa o intervalo de tempo igual ao intervalo de tempo representado pelo objeto [TimeSpan](../) especificado.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Veja Também

* Classe [TimeSpan](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)