---
title: ParseExact()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée en objet DateTimeOffset en utilisant le format spécifié, le fournisseur de format et le style de formatage.
type: docs
weight: 716
url: /fr/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) méthode

Convertit la chaîne spécifiée en objet [DateTimeOffset](../) en utilisant le format spécifié, le fournisseur de format et le style de formatage.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |
| format | const [String](../../string/)\& | Chaîne de format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styles de formatage de date et d'heure. |

### Valeur de retour

[DateTimeOffset](../) qui est équivalent à **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) méthode

Convertit la chaîne spécifiée en objet [DateTimeOffset](../) en utilisant les formats spécifiés, le fournisseur de format et le style de formatage.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) de chaînes de format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styles de formatage de date et d'heure. |

### Valeur de retour

[DateTimeOffset](../) qui est équivalent à **input**.

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [DateTimeOffset](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)