---
title: ReadLines()
second_title: Référence API Aspose.Slides pour C++
description: Lit le contenu du fichier texte spécifié ligne par ligne en utilisant le codage de caractères spécifié et renvoie une collection énumérable de chaînes, chacune représentant une seule ligne du contenu du fichier.
type: docs
weight: 326
url: /fr/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) méthode

Lit le contenu du fichier texte spécifié ligne par ligne en utilisant le codage de caractères spécifié et renvoie une collection énumérable de chaînes, chacune représentant une seule ligne du contenu du fichier.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier à lire |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage de caractères à utiliser |

### Return Value

Une collection énumérable de chaînes représentant le contenu du fichier spécifié

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)