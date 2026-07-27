---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Tenta converter a string especificada em objeto DateTimeOffset.
type: docs
weight: 729
url: /pt/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) método


Tenta converter a string especificada em objeto [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para converter. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que é equivalente ao **input**. |

### Valor de Retorno

true se o **input** for convertido com sucesso, caso contrário - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) método


Tenta converter a string especificada em objeto [DateTimeOffset](../) usando o provedor de formato e o estilo de formatação especificados.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para converter. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formatação de data e hora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que é equivalente ao **input**. |

### Valor de Retorno

true se o **input** for convertido com sucesso, caso contrário - false.

## Veja Também

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTimeOffset](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)