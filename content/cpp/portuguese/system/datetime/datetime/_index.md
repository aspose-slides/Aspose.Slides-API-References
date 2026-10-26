---
title: DateTime()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma instância que representa o menor valor possível de data e hora, igual a MinValue.
type: docs
weight: 1
url: /pt/system/datetime/datetime/
---
## DateTime::DateTime() construtor


Constrói uma instância que representa o menor valor possível de data e hora, igual a MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) construtor


Constrói uma instância que representa um valor de data e hora especificado como um ano, mês e dia específicos.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | O ano a ser representado pela instância que está sendo construída. |
| month | int | O mês do **year** a ser representado pela instância que está sendo construída. |
| day | int | O dia do **month** a ser representado pela instância que está sendo construída. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) construtor


Constrói uma instância que representa um valor de data e hora especificado como um ano, mês e dia específicos no calendário especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | O ano a ser representado pela instância que está sendo construída. |
| month | int | O mês do **year** a ser representado pela instância que está sendo construída. |
| day | int | O dia do **month** a ser representado pela instância que está sendo construída. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | O calendário usado para interpretar o **year**, **month** e **day** especificados. |

## DateTime::DateTime(int, int, int, int, int, int) construtor


Constrói uma instância que representa um valor de data e hora especificado como um ano, mês, dia, hora, minuto e segundo específicos.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | O ano a ser representado pela instância que está sendo construída. |
| month | int | O mês do **year** a ser representado pela instância que está sendo construída. |
| day | int | O dia do **month** a ser representado pela instância que está sendo construída. |
| hour | int | A hora do **day** a ser representado pela instância que está sendo construída. |
| minute | int | O minuto da **hour** a ser representado pela instância que está sendo construída. |
| second | int | O segundo do **minute** a ser representado pela instância que está sendo construída. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) construtor


Constrói uma instância que representa um valor de data e hora especificado como um ano, mês, dia, hora, minuto e segundo específicos.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | O ano a ser representado pela instância que está sendo construída. |
| month | int | O mês do **year** a ser representado pela instância que está sendo construída. |
| day | int | O dia do **month** a ser representado pela instância que está sendo construída. |
| hour | int | A hora do **day** a ser representado pela instância que está sendo construída. |
| minute | int | O minuto da **hour** a ser representado pela instância que está sendo construída. |
| second | int | O segundo do **minute** a ser representado pela instância que está sendo construída. |
| kind | [DateTimeKind](../../datetimekind/) | O valor que indica se os parâmetros de data e hora fornecidos especificam um horário local, horário UTC ou nenhum dos dois. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) construtor


Constrói uma instância que representa um valor de data e hora especificado como um ano, mês, dia, hora, minuto e segundo específicos no calendário especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | O ano a ser representado pela instância que está sendo construída. |
| month | int | O mês do **year** a ser representado pela instância que está sendo construída. |
| day | int | O dia do **month** a ser representado pela instância que está sendo construída. |
| hour | int | A hora do **day** a ser representado pela instância que está sendo construída. |
| minute | int | O minuto da **hour** a ser representado pela instância que está sendo construída. |
| second | int | O segundo do **minute** a ser representado pela instância que está sendo construída. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | O calendário usado para interpretar o **year**, **month** e **day** especificados. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) construtor


Constrói uma instância que representa um valor de data e hora especificado como um ano, mês, dia, hora, minuto, segundo e milissegundo específicos.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | O ano a ser representado pela instância que está sendo construída. |
| month | int | O mês do **year** a ser representado pela instância que está sendo construída. |
| day | int | O dia do **month** a ser representado pela instância que está sendo construída. |
| hour | int | A hora do **day** a ser representado pela instância que está sendo construída. |
| minute | int | O minuto da **hour** a ser representado pela instância que está sendo construída. |
| second | int | O segundo do **minute** a ser representado pela instância que está sendo construída. |
| millisecond | int | O milissegundo do **second** a ser representado pela instância que está sendo construída. |
| kind | [DateTimeKind](../../datetimekind/) | O valor que indica se os parâmetros de data e hora fornecidos especificam um horário local, horário UTC ou nenhum dos dois. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) construtor


Constrói uma instância que representa um valor de data e hora especificado como um ano, mês, dia, hora, minuto, segundo e milissegundo específicos no calendário especificado.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| year | int | O ano a ser representado pela instância que está sendo construída. |
| month | int | O mês do **year** a ser representado pela instância que está sendo construída. |
| day | int | O dia do **month** a ser representado pela instância que está sendo construída. |
| hour | int | A hora do **day** a ser representado pela instância que está sendo construída. |
| minute | int | O minuto da **hour** a ser representado pela instância que está sendo construída. |
| second | int | O segundo do **minute** a ser representado pela instância que está sendo construída. |
| millisecond | int | O milissegundo do **second** a ser representado pela instância que está sendo construída. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | O valor que indica se os parâmetros de data e hora fornecidos especificam um horário local, horário UTC ou nenhum dos dois. |
| calendar | [DateTimeKind](../../datetimekind/) | O calendário usado para interpretar o **year**, **month** e **day** especificados. |

## DateTime::DateTime(int64_t, DateTimeKind) construtor


Constrói uma instância que representa um valor de data e hora especificado como um número de ticks.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ticks | **int64_t** | O número de intervalos de 100 ns que se passaram desde 1º de janeiro de 0001 00:00:00.000 no calendário gregoriano. |
| kind | [DateTimeKind](../../datetimekind/) | O valor que indica se o parâmetro **ticks** especifica um horário local, horário UTC ou nenhum dos dois. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) construtor


Constrói uma instância que representa um valor de data e hora especificado como um número de ticks. PARA USO INTERNO.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ticks | **int64_t** | O número de intervalos de 100 ns que se passaram desde 1º de janeiro de 0001 00:00:00.000 no calendário gregoriano. |
| kind | [DateTimeKind](../../datetimekind/) | O valor que indica se o parâmetro **ticks** especifica um horário local, horário UTC ou nenhum dos dois. |
| is_ambiguous_local_dst | **bool** | Verdadeiro se a data e hora especificadas são ambíguas e podem ser mapeadas para vários horários UTC. |

## DateTime::DateTime(const DateTime\&) construtor


Constrói uma cópia de uma instância.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Uma instância da classe [DateTime](../) da qual copiar o valor de data e hora representado |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)