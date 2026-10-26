---
title: operator-()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma nova instância da classe DateTimeOffset que representa o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual.
type: docs
weight: 521
url: /pt/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const método


Retorna uma nova instância da classe [DateTimeOffset](../) que representa o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Um intervalo de tempo a ser subtraído |

### Valor de Retorno

Uma nova instância da classe [DateTimeOffset](../) que representa o valor de data e hora que é o resultado da subtração de **value** do valor representado pelo objeto atual.

## DateTimeOffset::operator-(const DateTimeOffset\&) const método


Retorna uma instância da classe [TimeSpan](../../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelo objeto atual e pelo objeto especificado.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Uma instância da classe [DateTime](../../datetime/) que marca uma extremidade do intervalo a ser calculado |

### Valor de Retorno

Uma instância da classe [TimeSpan](../../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelo objeto atual e **other**.

## Ver Também

* Classe [DateTimeOffset](../)
* Classe [TimeSpan](../../timespan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)