---
title: Create()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un comparatore specifico per la cultura.
type: docs
weight: 79
url: /it/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) metodo


Crea un comparatore specifico per la cultura.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura per cui creare il comparatore. |
| ignoreCase | **bool** | Indica se il comparatore deve ignorare maiuscole/minuscole. |

### Valore di ritorno

Puntatore al nuovo oggetto comparatore creato.

## Vedi anche

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [StringComparer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)