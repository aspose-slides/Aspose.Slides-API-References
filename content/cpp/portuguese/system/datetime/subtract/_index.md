---
title: Subtract()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma nova instância da classe DateTime que representa o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual.
type: docs
weight: 326
url: /pt/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const método


Retorna uma nova instância da classe [DateTime](../) que representa o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Um intervalo de tempo a ser subtraído |

### Valor de Retorno

Uma nova instância da classe [DateTime](../) que representa o valor de data e hora que é o resultado da subtração de **duration** do valor representado pelo objeto atual.

## DateTime::Subtract(DateTime) const método


Retorna uma instância da classe [TimeSpan](../../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelo objeto atual e pelo objeto especificado.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [DateTime](../) | Uma instância da classe [DateTime](../) que marca uma extremidade do intervalo a ser calculado |

### Valor de Retorno

Uma instância da classe [TimeSpan](../../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelo objeto atual e **value**.

## Veja Também

* Classe [DateTime](../)
* Classe [TimeSpan](../../timespan/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)