---
title: IBlobManagementOptions
second_title: Référence de l'API Aspose.Slides pour C++
description: Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique - c'est à dire qu'un BLOB peut être un fichier audio, vidéo ou une présentation elle-même. Un certain nombre de techniques sont utilisées pour optimiser la consommation de mémoire lors de la manipulation des BLOBs, qu'ils soient déjà stockés dans la présentation ou ajoutés ultérieurement par programme. En utilisant IBlobManagementOptions, vous pouvez modifier différents aspects du comportement concernant la gestion des BLOBs pendant la durée de vie de l'instance IPresentation.
type: docs
weight: 1535
url: /fr/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions classe


Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique - c’est-à-dire qu’un BLOB peut être un audio, une vidéo ou une présentation elle-même. Un certain nombre de techniques sont utilisées pour optimiser la consommation de mémoire lors de la manipulation des BLOBs - qu’ils soient déjà stockés dans la présentation ou ajoutés ultérieurement par programme. En utilisant [IBlobManagementOptions](./) vous pouvez modifier différents aspects du comportement concernant la gestion des BLOBs pendant le cycle de vie de l’instance [IPresentation](../ipresentation/).

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon la norme IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon la norme IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Cette propriété définit si des fichiers temporaires peuvent être créés lors de la manipulation des BLOBs, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (tels que les fichiers temporaires) sont employés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte consommation de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Cette propriété définit si une instance de la classe [Presentation](../presentation/) peut être propriétaire de la source — fichier ou flux — pendant la durée de vie de l’instance. Si l’instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors de la manipulation des BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l’instance [Presentation](../presentation/). Voici un exemple : |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire [System](../../system/) sera utilisé par défaut. Le processus d’hébergement doit disposer des autorisations nécessaires pour créer des fichiers et dossiers à cet emplacement. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien réellement, il se contente d’initialiser un nouvel objet et permet la construction par copie de sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien réellement, il se contente d’initialiser un nouvel objet et permet la construction par copie de sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Cette propriété définit si des fichiers temporaires peuvent être créés lors de la manipulation des BLOBs, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (tels que les fichiers temporaires) sont employés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte consommation de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Cette propriété définit si une instance de la classe [Presentation](../presentation/) peut être propriétaire de la source — fichier ou flux — pendant la durée de vie de l’instance. Si l’instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors de la manipulation des BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l’instance [Presentation](../presentation/). Voici un exemple : |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire [System](../../system/) sera utilisé par défaut. Le processus d’hébergement doit disposer des autorisations nécessaires pour créer des fichiers et dossiers à cet emplacement. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définir le nᵉ argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)