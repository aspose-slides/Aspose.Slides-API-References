---
title: Create()
second_title: Referência da API Aspose.Slides para C++
description: Cria um comparador específico da cultura.
type: docs
weight: 79
url: /pt/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) método

Cria um comparador específico da cultura.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura para a qual criar o comparador. |
| ignoreCase | **bool** | Indica se o comparador deve ignorar maiúsculas e minúsculas. |

### Valor de Retorno

Ponteiro para o objeto comparador recém-criado.

## Ver também

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [StringComparer](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)