---
title: Details_AggregateException
second_title: Référence API Aspose.Slides pour C++
description: Représente une exception qui contient plusieurs exceptions internes.
type: docs
weight: 300
url: /fr/system/details_aggregateexception/
---
## Details_AggregateException classe

Représente une exception qui contient plusieurs exceptions internes.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | Aplati l'exception agrégée en déroulant toutes les AggregateExceptions imbriquées en une liste à un seul niveau. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Renvoie un dictionnaire contenant des données d'exception personnalisées. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Renvoie une valeur entière de 32 bits qui est un code HRESULT associé à l'exception représentée par l'objet actuel. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Renvoie une référence à l'objet représentant l'exception interne. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | Obtient le nombre d'exceptions internes contenues dans cette exception agrégée. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | Obtient une collection en lecture seule des exceptions internes. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | Renvoie le tableau interne des exceptions internes. |
| [String](../string/) [get_Message](./get_message/)() const override | Remplace le message de base pour inclure les informations agrégées de toutes les exceptions internes. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Renvoie la chaîne contenant la trace de pile. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | Renvoie l'exception à l'origine du problème en déroulant récursivement les exceptions internes. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../object/gettype/). |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | Invoque une fonction de gestion sur chaque exception interne et relance les exceptions non gérées. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Définit le HRESULT, une valeur numérique codée attribuée à une exception spécifique. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Renvoie une représentation sous forme de chaîne de l'exception, incluant toutes les exceptions internes. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implémente la construction C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implémente la méthode [what()](../details_exception/what/) qui est appelée par la classe [ExceptionWrapper](../exceptionwrapper/). Malgré le fait que cette classe ne dérive pas de std::exception, les classes dérivées peuvent utiliser les membres protégés/privés pour implémenter leur logique. Déplacer l'implémentation de cette méthode vers le [ExceptionWrapper](../exceptionwrapper/) pourrait casser cette logique. |
| virtual  [~Object](../object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

Cette classe est généralement utilisée pour regrouper plusieurs exceptions qui se produisent simultanément, par exemple dans des scénarios de traitement parallèle ou d'exécution de tâches asynchrones. Elle permet aux utilisateurs d'examiner, d'aplatir ou de gérer sélectivement les exceptions contenues.

## Voir aussi

* Classe [Details_Exception](../details_exception/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)