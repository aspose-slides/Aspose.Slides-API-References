---
title: AppendAllLines()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute les chaînes provenant de la collection de chaînes spécifiée au fichier spécifié en utilisant le codage spécifié, en écrivant chaque chaîne sur une nouvelle ligne. Si le fichier spécifié n'existe pas, il est créé. Le fichier est fermé après l'écriture de toutes les chaînes.
type: docs
weight: 1
url: /fr/system.io/file/appendalllines/
---
## File::AppendAllLines(const String&, const SharedPtr<Collections::Generic::IEnumerable<String>>&, const EncodingPtr&) méthode

Ajoute les chaînes provenant de la collection de chaînes spécifiée au fichier spécifié en utilisant le codage spécifié, en écrivant chaque chaîne sur une nouvelle ligne. Si le fichier spécifié n'existe pas, il est créé. Le fichier est fermé après l'écriture de toutes les chaînes.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier auquel ajouter les chaînes |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Les chaînes à écrire dans le fichier |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage des caractères à utiliser |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)