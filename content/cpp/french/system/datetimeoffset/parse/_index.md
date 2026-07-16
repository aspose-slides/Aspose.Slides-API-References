---
title: Parse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée en équivalent DateTimeOffset.
type: docs
weight: 703
url: /fr/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) méthode

Convertit la chaîne spécifiée en équivalent [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |

### Valeur de retour

[DateTimeOffset](../) qui est équivalent à **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) méthode

Convertit la chaîne spécifiée en objet [DateTimeOffset](../) en utilisant le fournisseur de format spécifié et le style de formatage.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styles de formatage de date et d'heure. |

### Valeur de retour

[DateTimeOffset](../) qui est équivalent à **input**.

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)