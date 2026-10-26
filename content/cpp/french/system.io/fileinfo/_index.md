---
title: FileInfo
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un chemin vers un fichier et le fichier référencé par ce chemin, et fournit des méthodes pour le manipuler. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject() . Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des violations d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 274
url: /fr/system.io/fileinfo/
---
## FileInfo classe


Représente un chemin vers un fichier et le fichier référencé par ce chemin et fournit des méthodes pour le manipuler. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des violations d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Ouvre un fichier représenté par l'objet actuel en écriture de texte en utilisant l'encodage UTF-8, en mode 'Append' sans partage. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Copie le fichier représenté par l'objet actuel vers l'emplacement spécifié. Si le fichier de destination existe déjà, la copie échoue. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Copie le fichier représenté par l'objet actuel vers l'emplacement spécifié. Un paramètre indique si le fichier de destination existant doit être écrasé. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Crée un fichier à l'emplacement spécifié par le chemin représenté par l'objet actuel et l'ouvre en lecture/écriture, en mode tronquer et sans partage. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Crée un fichier à l'emplacement spécifié par le chemin représenté par l'objet actuel et l'ouvre en écriture de texte en utilisant l'encodage UTF-8 sans partage. |
| void [Decrypt](./decrypt/)() | NON IMPLEMENTÉ. |
| void [Delete](./delete/)() override | Supprime le fichier représenté par l'objet actuel. |
| void [Encrypt](./encrypt/)() | NON IMPLEMENTÉ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Construit une nouvelle instance de la classe [FileInfo](./) qui représente le fichier spécifié. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Ne fait rien. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Renvoie les attributs de l'entité représentée par l'objet actuel. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Renvoie l'heure de création de l'entité représentée par l'objet actuel en heure locale. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Renvoie l'heure de création de l'entité représentée par l'objet actuel en temps UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Renvoie un objet [DirectoryInfo](../directoryinfo/) qui représente le répertoire contenant le fichier représenté par l'objet actuel. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Renvoie le nom complet du répertoire dans lequel le fichier représenté par l'objet actuel est situé. |
| **bool** [get_Exists](./get_exists/)() override | Renvoie une valeur indiquant si le fichier existe. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Renvoie l'extension du fichier représenté par l'objet actuel. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Renvoie le nom complet (chemin inclus) de l'entité représentée par l'objet actuel. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Renvoie une valeur indiquant si l'attribut ReadOnly est défini. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Renvoie la dernière heure d'accès de l'entité représentée par l'objet actuel en heure locale. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Renvoie la dernière heure d'accès de l'entité représentée par l'objet actuel en temps UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Renvoie la dernière heure d'écriture de l'entité représentée par l'objet actuel en heure locale. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Renvoie la dernière heure d'écriture de l'entité représentée par l'objet actuel en temps UTC. |
| **int64_t** [get_Length](./get_length/)() | Renvoie la taille du fichier en octets. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Renvoie le nom du fichier. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Déplace le fichier représenté par l'objet actuel vers l'emplacement spécifié. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie réellement rien, il initialise simplement le nouvel objet et permet la construction de copies dans les sous-classes. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Ouvre le fichier représenté par l'objet actuel dans le mode spécifié pour la lecture et l'écriture, sans partage. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Ouvre le fichier représenté par l'objet actuel dans le mode spécifié, avec le type d'accès spécifié et sans partage. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Ouvre le fichier représenté par l'objet actuel dans le mode spécifié, avec le type d'accès spécifié et l'option de partage. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Ouvre un fichier représenté par l'objet actuel en lecture seule, en mode 'Open' avec accès partagé en lecture. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Ouvre le fichier existant à l'emplacement spécifié par le chemin représenté par l'objet actuel pour lire du texte en utilisant l'encodage UTF-8 sans partage. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Ouvre un fichier représenté par l'objet actuel en écriture seule, en mode 'OpenOrCreate' sans partage. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie réellement rien, il initialise simplement le nouvel objet et permet la construction de copies dans les sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| void [Refresh](../filesysteminfo/refresh/)() | Actualise l'état de l'objet actuel. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Remplace le contenu d'un fichier de destination spécifié par le fichier représenté par l'objet [FileInfo](./) actuel et crée une sauvegarde du fichier remplacé. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Remplace le contenu d'un fichier de destination spécifié par le fichier représenté par l'objet [FileInfo](./) actuel et crée une sauvegarde du fichier remplacé. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Définit les attributs spécifiés sur l'entité représentée par l'objet actuel. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Définit l'heure de création de l'entité représentée par l'objet actuel en heure locale. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Définit l'heure de création de l'entité représentée par l'objet actuel en temps UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Définit ou supprime l'attribut ReadOnly sur le fichier. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'accès de l'entité représentée par l'objet actuel en heure locale. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'accès de l'entité représentée par l'objet actuel en temps UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'écriture de l'entité représentée par l'objet actuel en heure locale. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'écriture de l'entité représentée par l'objet actuel en temps UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Renvoie un chemin représenté par l'objet actuel. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [FileSystemInfo](../filesysteminfo/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)