---
title: ParseExact()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata in oggetto DateTimeOffset utilizzando il formato specificato, il provider di formato e lo stile di formattazione.
type: docs
weight: 716
url: /it/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodo

Converte la stringa specificata in oggetto [DateTimeOffset](../) utilizzando il formato specificato, il provider di formato e lo stile di formattazione.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |
| format | const [String](../../string/)\& | Stringa di formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Stili di formattazione di data e ora. |

### Valore restituito

[DateTimeOffset](../) che è equivalente all'**input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodo

Converte la stringa specificata in oggetto [DateTimeOffset](../) utilizzando i formati specificati, il provider di formato e lo stile di formattazione.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) di stringhe di formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Stili di formattazione di data e ora. |

### Valore restituito

[DateTimeOffset](../) che è equivalente all'**input**.

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [DateTimeOffset](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)