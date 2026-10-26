---
title: OpenText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ouvre le fichier existant spécifié pour lire du texte en utilisant le codage UTF-8 sans partage.
type: docs
weight: 261
url: /fr/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) méthode


Ouvre le fichier existant spécifié pour lire du texte en utilisant le codage UTF-8 sans partage.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier à ouvrir |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Le codage de caractères à utiliser |

### Valeur de retour

Un pointeur partagé vers un objet [StreamWriter](../../streamwriter/) associé au fichier ouvert

## Voir aussi

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [String](../../../system/string/)
* Classe [File](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)