---
title: GetCultureInfo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère la culture par son nom. Identique à CreateSpecificCulture.
type: docs
weight: 586
url: /fr/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) méthode

Récupère la culture par son nom. Identique à CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nom de culture prédéfini ou nom d’un objet culture existant. |

### Valeur de retour

Objet culture nouvellement créé.

## CultureInfo::GetCultureInfo(const String\&, const String\&) méthode

Récupère la culture par son nom.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nom de la culture. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Nom de culture utilisé pour les objets [TextInfo](../../textinfo/) et [CompareInfo](../../compareinfo/). |

### Valeur de retour

Objet culture.

## CultureInfo::GetCultureInfo(int32_t) méthode

Récupère la culture par son identifiant.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| culture | **int32_t** | Identifiant de la culture. |

### Valeur de retour

Objet culture nouvellement créé.

## Voir aussi

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Classe [String](../../../system/string/)
* Classe [CultureInfo](../)
* Espace de noms [System::Globalization](../../)
* Bibliothèque [Aspose.Slides](../../../)