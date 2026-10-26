---
title: Object
second_title: Référence de l'API Aspose.Slides pour C++
description: Classe de base qui permet d'utiliser les méthodes disponibles pour la classe System.Object en C#. Toutes les classes non triviales utilisées avec l'environnement traduit doivent en hériter.
type: docs
weight: 1119
url: /fr/system/object/
---
## Classe d'objet

Classe de base qui permet d'utiliser les méthodes disponibles pour la classe [System.Object](./) en C#. Toutes les classes non triviales utilisées avec l'environnement traduit doivent en hériter.

```cpp
class Object
```

## Méthodes

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](./gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](./lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](./memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](./object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](./object/)([Object](./) const\&) | Constructeur de copie. Ne copie rien en réalité, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Opérateur d'affectation. Ne copie rien en réalité, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](./referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](./referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](./sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analogue de la méthode C# [Object.ToString()](./tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implémente le construct C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](./~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Définitions de type

| Typedef | Description |
| --- | --- |
| [ptr](./ptr/) | Alias du type de pointeur intelligent. |

## Remarques

En plus des méthodes disponibles dans la classe C# [System.Object](./), il permet également la prise en charge de certains concepts spécifiques à l'environnement de code traduit. Cela inclut le comptage de références utilisé par les classes de pointeurs intelligents ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) et d'autres services liés à la gestion de la mémoire, au débogage, etc.

Chaque [Object](./) possède deux compteurs de référence : le compteur de références partagées et le compteur de références faibles. Le compteur de références faibles est toujours stocké dans une structure de données détachée plutôt que dans le [Object](./) lui--même, ce qui permet aux pointeurs faibles de survivre à l'objet référencé. Le compteur de références intelligentes est stocké soit dans l'objet lui-même, soit dans la même structure détachée, selon l'état de la macro ENABLE_EXTERNAL_REFCOUNT. Par défaut, il est activé dans les builds de débogage et désactivé dans les builds de diffusion. Si le compteur de pointeur intelligent est stocké dans l'objet lui-même, la structure détachée n’est créée que si des pointeurs faibles vers l'objet existent. Sinon, elle est créée en même temps que l'objet.

Tous les pointeurs intelligents utilisent ces deux compteurs de référence et contribuent au même groupe de possession unique.

Si une sous-classe [Object](./) est créée sur la pile, aucun pointeur intelligent ne doit y être créé, sinon il y a un problème de suppression de la pile.

Ce type peut être alloué soit sur la pile en tant que type valeur, soit sur le tas à l'aide de la fonction [System::MakeObject()](../makeobject/). Une fois l'objet alloué, ne mélangez jamais ces deux cas d'utilisation : posséder des pointeurs [SmartPtr](../smartptr/) vers des objets alloués sur la pile est strictement interdit. 

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)