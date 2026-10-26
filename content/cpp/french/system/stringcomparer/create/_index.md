---
title: Create()
second_title: Référence de l'API Aspose.Slides for C++
description: Crée un comparateur spécifique à la culture.
type: docs
weight: 79
url: /fr/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) méthode

Crée un comparateur spécifique à la culture.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture pour laquelle créer le comparateur. |
| ignoreCase | **bool** | Indique si le comparateur doit ignorer la casse. |

### Valeur de retour

Pointeur vers l'objet comparateur nouvellement créé.

## Voir aussi

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [StringComparer](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)