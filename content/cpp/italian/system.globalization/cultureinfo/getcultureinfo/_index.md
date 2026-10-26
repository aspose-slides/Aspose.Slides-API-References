---
title: GetCultureInfo()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene la cultura per nome. Identico a CreateSpecificCulture.
type: docs
weight: 586
url: /it/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) metodo

Ottiene la cultura per nome. Stessa di CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome cultura predefinito o nome di un oggetto cultura esistente. |

### Valore restituito

Oggetto cultura appena creato.

## CultureInfo::GetCultureInfo(const String\&, const String\&) metodo

Ottiene la cultura per nome.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome della cultura. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Nome della cultura usato per gli oggetti [TextInfo](../../textinfo/) e [CompareInfo](../../compareinfo/). |

### Valore restituito

Oggetto cultura.

## CultureInfo::GetCultureInfo(int32_t) metodo

Ottiene la cultura per ID.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| culture | **int32_t** | Identificatore della cultura. |

### Valore restituito

Oggetto cultura appena creato.

## Vedi anche

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Classe [String](../../../system/string/)
* Classe [CultureInfo](../)
* Spazio dei nomi [System::Globalization](../../)
* Libreria [Aspose.Slides](../../../)