---
title: operator-()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma nova instância da classe DateTime representando o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual.
type: docs
weight: 651
url: /pt/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const método


Retorna uma nova instância da classe [DateTime](../) representando o valor de data e hora que é o resultado da subtração do intervalo de tempo especificado do valor representado pelo objeto atual.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Um intervalo de tempo a ser subtraído |

### Valor de Retorno

Uma nova instância da classe [DateTime](../) representando o valor de data e hora que é o resultado da subtração de **value** do valor representado pelo objeto atual.

## DateTime::operator-(DateTime) const método


Retorna uma instância da classe [TimeSpan](../../timespan/) que representa o intervalo de tempo entre os valores de data e hora representados pelos objetos atual e especificado.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [DateTime](../) | Uma instância da classe [DateTime](../) que marca uma extremidade do intervalo a ser calculado |

### Valor de Retorno

Uma instância da classe [TimeSpan](../../timespan/) representando o intervalo de tempo entre os valores de data e hora representados pelo objeto atual e **value**.

## Veja também

* Classe [DateTime](../)
* Classe [TimeSpan](../../timespan/)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)