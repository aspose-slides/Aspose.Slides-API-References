---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Prova a convertire la stringa specificata in un oggetto DateTimeOffset.
type: docs
weight: 729
url: /it/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) metodo

Prova a convertire la stringa specificata in oggetto [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) che è equivalente al **input**. |

### Valore restituito

true se l'**input** è stato convertito correttamente, altrimenti - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metodo

Prova a convertire la stringa specificata in oggetto [DateTimeOffset](../) utilizzando il provider di formato e lo stile di formattazione specificati.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Stili di formattazione di data e ora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) che è equivalente al **input**. |

### Valore restituito

true se l'**input** è stato convertito correttamente, altrimenti - false.

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)