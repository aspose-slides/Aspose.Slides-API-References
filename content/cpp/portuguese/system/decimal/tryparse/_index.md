---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada contendo a representação textual de um número para o valor Decimal equivalente.
type: docs
weight: 482
url: /pt/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) método

Converte a string especificada contendo a representação textual de um número para o valor [Decimal](../) equivalente.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| result | [Decimal](../)\& | A referência a uma variável [Decimal](../) onde o resultado da conversão é colocado |

### Valor de Retorno

Verdadeiro se a conversão for bem-sucedida, caso contrário - falso

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) método

Converte a string especificada contendo a representação textual de um número para o valor [Decimal](../) equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual de um número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string |
| result | [Decimal](../)\& | Um argumento de saída; contém o resultado da conversão |

### Valor de Retorno

Verdadeiro se a conversão for bem-sucedida, caso contrário - falso

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Decimal](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)