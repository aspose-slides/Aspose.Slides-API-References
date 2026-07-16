---
title: ReadAllText()
second_title: Référence API Aspose.Slides pour C++
description: Lit le contenu du fichier texte spécifié dans un objet String unique en utilisant le codage de caractères spécifié.
type: docs
weight: 313
url: /fr/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) méthode

Lit le contenu du fichier texte spécifié dans un unique objet [String](../../../system/string/) en utilisant le codage de caractères spécifié.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier à lire |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage de caractères à utiliser |

### Valeur de retour

Une chaîne contenant le contenu du fichier spécifié

## Voir aussi

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)