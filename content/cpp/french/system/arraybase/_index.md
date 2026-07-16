---
title: ArrayBase
second_title: Référence de l'API Aspose.Slides pour C++
description: Le témoin pour la classe System.Array (classe de base abstraite pour tous les tableaux) peut être rempli de fonctionnalités sur demande.
type: docs
weight: 27
url: /fr/system/arraybase/
---
## classe ArrayBase

Le témoin pour la classe [System.Array](../array/) (classe de base abstraite pour tous les tableaux) peut être rempli de fonctionnalités sur demande.

```cpp
class ArrayBase : public virtual System::Object
```

## Méthodes

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante à la C# où deux NaN sont considérés égaux même si, selon la IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante à la C# où deux NaN sont considérés égaux même si, selon la IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **int32_t** [get_Length](./get_length/)() const | Renvoie un entier 32 bits qui représente le nombre total de tous les éléments dans toutes les dimensions du tableau. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../object/gethashcode/). Active le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sub-classes. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sub-classes. |
| virtual void * [raw_data_ptr](./raw_data_ptr/)() | Renvoie un pointeur vers le premier élément d’un tableau à une dimension. Pour les tableaux à plusieurs dimensions, le résultat est indéfini. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implémente la construction C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../object/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)