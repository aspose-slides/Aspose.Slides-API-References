---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada para o equivalente DateTimeOffset.
type: docs
weight: 703
url: /pt/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) método


Converte a string especificada para o equivalente [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a ser convertido. |

### Valor de Retorno

[DateTimeOffset](../) que é equivalente ao **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) método


Converte a string especificada para o objeto [DateTimeOffset](../) usando o provedor de formato especificado e o estilo de formatação.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a ser convertido. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formatação de data e hora. |

### Valor de Retorno

[DateTimeOffset](../) que é equivalente ao **input**.

## Veja Também

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTimeOffset](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)