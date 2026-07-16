---
title: ReadAllLines()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit le contenu du fichier texte spécifié ligne par ligne dans un tableau de chaînes en utilisant le codage de caractères spécifié.
type: docs
weight: 300
url: /fr/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) méthode


Lit le contenu du fichier texte spécifié ligne par ligne dans un tableau de chaînes en utilisant le codage de caractères spécifié.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier à lire |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage de caractères à utiliser |

### Valeur de retour

Un tableau de chaînes dont chaque élément représente une ligne unique du fichier spécifié

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)