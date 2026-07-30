---
title: ToString()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il GUID rappresentato dall'oggetto corrente nella sua rappresentazione stringa.
type: docs
weight: 79
url: /it/system/guid/tostring/
---
## Guid::ToString() const metodo

Converte il GUID rappresentato dall'oggetto corrente nella sua rappresentazione stringa.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const metodo

Converte il GUID rappresentato dall'oggetto corrente nella sua rappresentazione stringa usando il formato stringa specificato.

```cpp
String System::Guid::ToString(const String &format) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../string/)\& | Il formato da usare |

### Valore restituito

La rappresentazione stringa del valore GUID rappresentato dall'oggetto corrente

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metodo

Converte il GUID rappresentato dall'oggetto corrente nella sua rappresentazione stringa usando il formato stringa specificato e la cultura.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../string/)\& | Il formato da usare |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da usare |

### Valore restituito

La rappresentazione stringa del valore GUID rappresentato dall'oggetto corrente

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Guid](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)