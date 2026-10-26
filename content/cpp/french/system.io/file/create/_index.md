---
title: Create()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau fichier (ou écrase un fichier existant) et l'ouvre en accès lecture-écriture en utilisant la taille de tampon et les options spécifiées.
type: docs
weight: 53
url: /fr/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) method


Crée un nouveau fichier (ou écrase un fichier existant) et l’ouvre en accès lecture-écriture en utilisant la taille de tampon et les options spécifiées.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Le chemin du fichier à créer ou à écraser |
| bufferSize | **int32_t** | Le nombre d’octets mis en tampon lors de la lecture et de l’écriture du fichier |
| options | [FileOptions](../../fileoptions/) | Définit comment créer ou écraser le fichier |

### Valeur de retour

Un pointeur partagé vers l’objet [FileStream](../../filestream/) associé au fichier spécifié

## Voir aussi

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)