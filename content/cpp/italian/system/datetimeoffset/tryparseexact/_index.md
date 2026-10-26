---
title: TryParseExact()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca di convertire la stringa specificata in un oggetto DateTimeOffset utilizzando i formati specificati, il provider di formato e lo stile di formattazione.
type: docs
weight: 742
url: /it/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metodo

Cerca di convertire la stringa specificata in un oggetto [DateTimeOffset](../) utilizzando i formati specificati, il provider di formattazione e lo stile di formattazione.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Array di stringhe di formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Stili di formattazione di data e ora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) che è equivalente a **input**. |

### Valore restituito

true se **input** è stato convertito con successo, altrimenti - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metodo

Cerca di convertire la stringa specificata in un oggetto [DateTimeOffset](../) utilizzando il formato specificato, il provider di formattazione e lo stile di formattazione.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |
| format | const [String](../../string/)\& | Stringa di formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Stili di formattazione di data e ora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) che è equivalente a **input**. |

### Valore restituito

true se **input** è stato convertito con successo, altrimenti - false.

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)