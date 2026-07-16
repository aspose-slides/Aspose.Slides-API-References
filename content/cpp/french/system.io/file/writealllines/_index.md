---
title: WriteAllLines()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau fichier texte ou écrase le fichier existant et écrit toutes les chaînes de la collection énumérable de chaînes spécifiée dans celui-ci, chaque chaîne sur une nouvelle ligne, en utilisant le codage spécifié.
type: docs
weight: 456
url: /fr/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) méthode

Crée un nouveau fichier texte ou écrase le fichier existant et écrit toutes les chaînes de la collection énumérable de chaînes spécifiée dans celui-ci, chaque chaîne sur une nouvelle ligne, en utilisant le codage spécifié.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le fichier à créer ou à écraser |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\& | Une collection énumérable de chaînes |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage des caractères à utiliser |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) méthode

Crée un nouveau fichier texte ou écrase le fichier existant et écrit toutes les chaînes du tableau de chaînes spécifié dans celui-ci, chaque chaîne sur une nouvelle ligne, en utilisant le codage spécifié.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le fichier à créer ou à écraser |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Un tableau de chaînes |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage des caractères à utiliser |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [File](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)