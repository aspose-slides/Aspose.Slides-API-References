---
title: TryParseExact()
second_title: Référence de l'API Aspose.Slides pour C++
description: Essaie de convertir la chaîne spécifiée en objet DateTimeOffset en utilisant les formats spécifiés, le fournisseur de format et le style de formatage.
type: docs
weight: 742
url: /fr/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Tente de convertir la chaîne spécifiée en objet [DateTimeOffset](../) en utilisant les formats spécifiés, le fournisseur de format et le style de formatage.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Tableaux de chaînes de format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styles de formatage de date et d'heure. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) qui est équivalent à l'**input**. |

### Valeur de retour

true si l'**input** a été converti avec succès, sinon - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Tente de convertir la chaîne spécifiée en objet [DateTimeOffset](../) en utilisant le format spécifié, le fournisseur de format et le style de formatage.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |
| format | const [String](../../string/)\& | Chaîne de format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styles de formatage de date et d'heure. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) qui est équivalent à l'**input**. |

### Valeur de retour

true si l'**input** a été converti avec succès, sinon - false.

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)