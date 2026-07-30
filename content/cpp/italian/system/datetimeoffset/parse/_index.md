---
title: Parse()
second_title: Riferimento API Aspose.Slides per C++
description: Converte la stringa specificata in un equivalente DateTimeOffset.
type: docs
weight: 703
url: /it/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) metodo

Converte la stringa specificata in un equivalente [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |

### Valore di ritorno

[DateTimeOffset](../) che è equivalente all'**input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodo

Converte la stringa specificata in un oggetto [DateTimeOffset](../) utilizzando il provider di formato e lo stile di formattazione specificati.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Stili di formattazione data e ora. |

### Valore di ritorno

[DateTimeOffset](../) che è equivalente all'**input**.

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTimeOffset](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)