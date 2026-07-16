---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Tente de convertir la chaîne spécifiée en objet DateTimeOffset.
type: docs
weight: 729
url: /fr/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Essaie de convertir la chaîne spécifiée en objet [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) qui est équivalent à **input**. |

### Valeur de retour

true si le **input** a été converti avec succès, sinon - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Essaie de convertir la chaîne spécifiée en objet [DateTimeOffset](../) en utilisant le fournisseur de format spécifié et le style de formatage.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styles de formatage de date et d'heure. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) qui est équivalent à **input**. |

### Valeur de retour

true si le **input** a été converti avec succès, sinon - false.

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)