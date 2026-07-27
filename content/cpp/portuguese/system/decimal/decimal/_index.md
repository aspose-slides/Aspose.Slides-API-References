---
title: Decimal()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma instância que representa 0.
type: docs
weight: 1
url: /pt/system/decimal/decimal/
---
## Decimal::Decimal() construtor


Constrói uma instância que representa 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::int8_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::int8_t | Valor inteiro de 8 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(std::int16_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::int16_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::int16_t | Valor inteiro de 16 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(std::int32_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::int32_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::int32_t | Valor inteiro de 32 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(std::int64_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::int64_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::int64_t | Valor inteiro de 64 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(std::uint8_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::uint8_t | Valor inteiro sem sinal de 8 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(std::uint16_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::uint16_t | Valor inteiro sem sinal de 16 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(std::uint32_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::uint32_t | Valor inteiro sem sinal de 32 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(std::uint64_t) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | std::uint64_t | Valor inteiro sem sinal de 64 bits a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(float) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(float f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| f | **float** | O valor de ponto flutuante de precisão simples a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(double) construtor


Constrói uma instância que representa o valor especificado.

```cpp
System::Decimal::Decimal(double d)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | **double** | O valor de ponto flutuante de precisão dupla a ser representado pelo objeto [Decimal](../) que está sendo construído |

## Decimal::Decimal(const std::string\&) construtor


Constrói uma instância que representa um valor cuja representação em cadeia de caracteres é especificada como uma instância da classe std::string.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) construtor


Constrói um objeto [Decimal](../) a partir dos componentes especificados.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lo | **int32_t** | Os 32 bits menos significativos do valor |
| mid | **int32_t** | Os 32 bits intermediários do valor |
| hi | **int32_t** | Os 32 bits mais significativos do valor |
| isNegative | **bool** | Indica se o valor é negativo |
| scale | **uint8_t** | Uma potência de 10 variando de 0 a 28 |

## Decimal::Decimal(const Decimal\&) construtor


Constrói uma instância da classe [Decimal](../) que representa o mesmo número do objeto [Decimal](../) especificado.

```cpp
System::Decimal::Decimal(const Decimal &d)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | const [Decimal](../)\& | Um objeto [Decimal](../) do qual copiar o valor |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) construtor


Constrói uma instância da classe [Decimal](../) a partir de um array inteiro que contém uma representação binária.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | Um array inteiro contendo uma representação binária. |

## Decimal::Decimal(std::nullptr_t) construtor


Sempre lança ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) construtor


Constrói uma instância da classe [Decimal](../) que representa o valor especificado.

```cpp
System::Decimal::Decimal(const number_type &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | Uma referência constante ao valor a ser representado pelo objeto que está sendo construído |

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Classe [Decimal](../)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)