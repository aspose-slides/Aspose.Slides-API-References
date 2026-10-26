---
title: GetCompareInfo()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene CompareInfo associato alla cultura specificata e utilizza i metodi di confronto di stringhe nell'assembly specificato.
type: docs
weight: 183
url: /it/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) metodo

Ottiene [CompareInfo](../) associato alla cultura specificata e utilizza i metodi di confronto di stringhe nell'assembly specificato.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| culture | int | Identificatore della cultura (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly che contiene i metodi di confronto di stringhe. |

### Valore di ritorno

[CompareInfo](../) oggetto.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) metodo

Ottiene [CompareInfo](../) associato alla cultura specificata e utilizza i metodi di confronto di stringhe nell'assembly specificato.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome della cultura. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly che contiene i metodi di confronto di stringhe. |

### Valore di ritorno

[CompareInfo](../) oggetto.

## CompareInfo::GetCompareInfo(int) metodo

Ottiene [CompareInfo](../) associato alla cultura specificata.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| culture | int | Identificatore della cultura (LCID). |

### Valore di ritorno

[CompareInfo](../) oggetto.

## CompareInfo::GetCompareInfo(const String\&) metodo

Ottiene [CompareInfo](../) associato alla cultura specificata.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nome della cultura. |

### Valore di ritorno

[CompareInfo](../) oggetto.

## Vedi anche

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Assembly](../../../system.reflection/assembly/)
* Class [CompareInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)