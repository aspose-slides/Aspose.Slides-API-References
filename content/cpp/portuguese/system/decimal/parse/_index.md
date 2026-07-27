---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a representação em string de um número decimal em uma instância equivalente da classe Decimal.
type: docs
weight: 469
url: /pt/system/decimal/parse/
---
## Decimal::Parse(const String\&) método


Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um número |

### Valor de Retorno

Uma nova instância da classe [Decimal](../) representando um valor equivalente ao representado pela string especificada.

## Decimal::Parse(const String\&, Globalization::NumberStyles) método


Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](../) usando o estilo especificado.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor decimal a ser convertido |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [Decimal](../) |

### Valor de Retorno

Uma nova instância da classe [Decimal](../) representando um valor equivalente ao representado pela string especificada.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](../) usando o provedor de formato especificado.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor decimal a ser convertido |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato |

### Valor de Retorno

Uma nova instância da classe [Decimal](../) representando um valor equivalente ao representado pela string especificada.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Converte a representação em string de um número decimal em uma instância equivalente da classe [Decimal](../) usando o estilo e o provedor de formato especificados.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor decimal a ser convertido |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato |

### Valor de Retorno

Uma nova instância da classe [Decimal](../) representando um valor equivalente ao representado pela string especificada.

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* namespace [System](../../)
* Library [Aspose.Slides](../../../)