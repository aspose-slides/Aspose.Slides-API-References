---
title: File
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des méthodes pour manipuler des fichiers. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 261
url: /fr/system.io/file/
---
## classe File

Fournit des méthodes pour manipuler des fichiers. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.

```cpp
class File
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Ajoute les chaînes de la collection de chaînes spécifiée au fichier spécifié en utilisant le codage spécifié, en écrivant chaque chaîne sur une nouvelle ligne. Si le fichier spécifié n'existe pas, il est créé. Le fichier est fermé après l'écriture de toutes les chaînes. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Ajoute la chaîne spécifiée au fichier spécifié en utilisant le codage spécifié. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Crée un objet [StreamWriter](../streamwriter/) qui ajoute du texte au fichier spécifié en utilisant le codage UTF-8. Si le fichier spécifié n'existe pas, il est créé. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Copie le fichier spécifié vers l'emplacement spécifié. Si le fichier de destination existe déjà, un paramètre indique s'il doit être écrasé. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Crée un nouveau fichier (ou écrase celui existant) et l'ouvre en accès lecture-écriture en utilisant la taille de tampon et les options spécifiées. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Crée un nouveau fichier ou ouvre un fichier existant pour écrire du texte encodé en UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NON IMPLEMENTÉ. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Supprime le fichier ou le répertoire spécifié. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NON IMPLEMENTÉ. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Détermine si le chemin spécifié fait référence à un fichier existant. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Renvoie les attributs de l'entité spécifiée. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Renvoie la date de création de l'entité spécifiée en heure locale. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Renvoie la date de création de l'entité spécifiée en temps UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Renvoie la dernière heure d'accès de l'entité spécifiée en heure locale. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Renvoie la dernière heure d'accès de l'entité spécifiée en temps UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Renvoie la dernière heure d'écriture de l'entité spécifiée en heure locale. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Renvoie la dernière heure d'écriture de l'entité spécifiée en temps UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Déplace le fichier spécifié vers le nouvel emplacement. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Ouvre le fichier spécifié dans le mode spécifié pour la lecture et l'écriture, sans partage. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Ouvre le fichier spécifié dans le mode spécifié, avec le type d'accès et l'option de partage spécifiés. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Ouvre le fichier spécifié en lecture seule, en mode 'Open' avec un accès partagé en lecture. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Ouvre le fichier existant spécifié pour lire du texte en utilisant le codage UTF-8, sans partage. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Ouvre le fichier spécifié en écriture seule, en mode 'OpenOrCreate' sans partage. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Lit le contenu du fichier binaire spécifié dans un tableau d'octets. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lit le contenu du fichier texte spécifié ligne par ligne dans un tableau de chaînes en utilisant le codage de caractères spécifié. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lit le contenu du fichier texte spécifié dans un unique objet [String](../../system/string/) en utilisant le codage de caractères spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Lit le contenu du fichier texte spécifié ligne par ligne en utilisant le codage de caractères spécifié et renvoie une collection énumérable de chaînes, chacune représentant une ligne du contenu du fichier. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Remplace le contenu d'un fichier par un autre et crée une sauvegarde du fichier remplacé. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Définit les attributs spécifiés sur le fichier spécifié. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTÉ. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTÉ. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTÉ. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NON IMPLEMENTÉ. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la dernière heure d'écriture de l'entité spécifiée en heure locale. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Définit la dernière heure d'écriture de l'entité spécifiée en temps UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Écrase le fichier binaire spécifié et y écrit les octets spécifiés. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crée un nouveau fichier texte ou écrase celui existant et écrit toutes les chaînes de la collection énumérable de chaînes spécifiée dans le fichier, chaque chaîne sur une nouvelle ligne, en utilisant le codage spécifié. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crée un nouveau fichier texte ou écrase celui existant et écrit toutes les chaînes du tableau de chaînes spécifié dans le fichier, chaque chaîne sur une nouvelle ligne, en utilisant le codage spécifié. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Crée un nouveau fichier texte ou écrase celui existant et écrit le contenu de la chaîne spécifiée dans le fichier en utilisant le codage spécifié. |
## Champs

| Champ | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Valeur par défaut du nombre d’octets mis en mémoire tampon lors de la lecture depuis et de l'écriture vers un fichier. |
## Voir aussi

* espace de noms [System::IO](../)
* bibliothèque [Aspose.Slides](../../)