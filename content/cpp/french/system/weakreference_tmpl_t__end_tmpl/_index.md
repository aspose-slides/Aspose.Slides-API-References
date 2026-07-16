---
title: WeakReference< T >
second_title: Référence API Aspose.Slides pour C++
description: Représente une référence faible, qui référence un objet tout en permettant que cet objet soit supprimé.
type: docs
weight: 1483
url: /fr/system/weakreference_tmpl_t__end_tmpl/
---
## classe WeakReference< T >

Représente une référence faible, qui référence un objet tout en permettant que cet objet soit supprimé.

```cpp
template<typename T>class WeakReference< T > : public System::Object
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l'objet référencé. |

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, un NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, un NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la copie lors de la construction des sous-classes. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Vérifie si l'objet référencé n'est pas nul. |
| **bool** [operator!=](./operator_not_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Compare l'objet référencé à une autre instance de la classe WeakReference. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la copie lors de la construction des sous-classes. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vérifie si l'objet référencé est nul. |
| **bool** [operator==](./operator_equal_equal/)(const [WeakReference](./weakreference/)\<T\>\&) const | Compare l'objet référencé à une autre instance de la classe WeakReference. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [reset](./reset/)() |  |
| void [SetTarget](./settarget/)(const [SmartPtr](../smartptr/)\<T\>\&) | Définit l'objet (la cible) référencé par l'objet WeakReference actuel. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| **bool** [TryGetTarget](./trygettarget/)(const [SmartPtr](../smartptr/)\<T\>\&) const | Obtient l'objet (la cible) référencé par l'objet WeakReference actuel. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implémente la construction C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [WeakReference](./weakreference/)() | Constructeur par défaut. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Constructeur à partir de nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&) | Initialise une nouvelle instance de la classe WeakReference, en référencant l'objet spécifié. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<T\>\&, **bool**) | Initialise une nouvelle instance de la classe WeakReference, en référencant l'objet spécifié. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../object/)
* Espace de noms [System](../)
* Library [Aspose.Slides](../../)