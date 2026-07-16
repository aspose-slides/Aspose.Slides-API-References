---
title: DirectoryInfo
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un chemin de système de fichiers, un répertoire référencé par ce chemin et fournit des méthodes d'instance pour manipuler les répertoires. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 248
url: /fr/system.io/directoryinfo/
---
## DirectoryInfo classe

Représente un chemin de système de fichiers, un répertoire référencé par ce chemin et fournit des méthodes d'instance pour manipuler les répertoires. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Create](./create/)() | Crée un répertoire au chemin représenté par l'objet actuel. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Crée des sous-repertoires sur le chemin spécifié. |
| void [Delete](./delete/)() override | Supprime le répertoire référencé par le chemin représenté par l'objet actuel si le répertoire est vide. |
| void [Delete](./delete/)(**bool**) | Supprime le répertoire référencé par le chemin représenté par l'objet actuel. Un paramètre indique si le contenu du répertoire doit être supprimé récursivement si le répertoire n'est pas vide. |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Construit une instance de la classe [DirectoryInfo](./) sur le chemin spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Renvoie une collection énumérable contenant tous les répertoires situés dans le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Recherche les répertoires qui satisfont les critères de recherche spécifiés dans le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les répertoires qui satisfont les critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Renvoie une collection énumérable contenant tous les fichiers situés dans le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Recherche les fichiers qui satisfont les critères de recherche spécifiés dans le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers qui satisfont les critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Renvoie une collection énumérable contenant tous les fichiers et répertoires situés dans le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Recherche les fichiers et répertoires qui satisfont les critères de recherche spécifiés dans le répertoire représenté par l'objet actuel. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers et répertoires qui satisfont les critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if\<![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Ne fait rien. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Renvoie les attributs de l'entité représentée par l'objet actuel. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Renvoie la date de création de l'entité représentée par l'objet actuel en heure locale. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Renvoie la date de création de l'entité représentée par l'objet actuel en temps UTC. |
| **bool** [get_Exists](./get_exists/)() override | Détermine si le chemin représenté par l'objet actuel fait référence à un répertoire existant. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Renvoie l'extension du fichier représenté par l'objet actuel. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Renvoie le nom complet (y compris le chemin) de l'entité représentée par l'objet actuel. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Renvoie la dernière heure d'accès de l'entité représentée par l'objet actuel en heure locale. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Renvoie la dernière heure d'accès de l'entité représentée par l'objet actuel en temps UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Renvoie la dernière heure d'écriture de l'entité représentée par l'objet actuel en heure locale. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Renvoie la dernière heure d'écriture de l'entité représentée par l'objet actuel en temps UTC. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Renvoie le nom de l'entité référencée par le chemin représenté par l'objet actuel. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Renvoie un pointeur partagé vers l'objet [DirectoryInfo](./) qui représente un chemin référant au répertoire parent du répertoire représenté par l'objet actuel. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Renvoie un pointeur partagé vers l'objet [DirectoryInfo](./) qui représente un chemin référant au répertoire racine du répertoire représenté par l'objet actuel. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Renvoie un tableau contenant des pointeurs partagés vers les objets [DirectoryInfo](./) représentant tous les répertoires situés dans le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Recherche les répertoires qui satisfont les critères de recherche spécifiés dans le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les répertoires qui satisfont les critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Renvoie un tableau contenant des pointeurs partagés vers les objets [FileInfo](../fileinfo/) représentant tous les répertoires situés dans le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Recherche les fichiers qui satisfont les critères de recherche spécifiés dans le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers qui satisfont les critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Renvoie un tableau contenant des pointeurs partagés vers les objets [FileSystemInfo](../filesysteminfo/) représentant tous les fichiers et répertoires situés dans le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Recherche les fichiers et répertoires qui satisfont les critères de recherche spécifiés dans le répertoire représenté par l'objet actuel. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Recherche les fichiers et répertoires qui satisfont les critères de recherche spécifiés soit dans le répertoire représenté par l'objet actuel, soit dans l'ensemble de l'arborescence de répertoires dont la racine est le répertoire représenté par l'objet actuel. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Déplace le répertoire représenté par l'objet actuel et tout son contenu vers l'emplacement spécifié. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| void [Refresh](../filesysteminfo/refresh/)() | Actualise l'état de l'objet actuel. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Définit les attributs spécifiés sur l'entité représentée par l'objet actuel. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Définit la date de création de l'entité représentée par l'objet actuel en heure locale. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Définit la date de création de l'entité représentée par l'objet actuel en temps UTC. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'accès de l'entité représentée par l'objet actuel en heure locale. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'accès de l'entité représentée par l'objet actuel en temps UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'écriture de l'entité représentée par l'objet actuel en heure locale. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Définit la dernière heure d'écriture de l'entité représentée par l'objet actuel en temps UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Renvoie une chaîne contenant le chemin représenté par l'objet actuel. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [FileSystemInfo](../filesysteminfo/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)