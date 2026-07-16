---
title: ValueTask
second_title: Référence API Aspose.Slides pour C++
description: Fournit un résultat awaitable d'une opération asynchrone.
type: docs
weight: 92
url: /fr/system.threading.tasks/valuetask/
---
## ValueTask classe

Fournit un résultat awaitable d'une opération asynchrone.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [TaskPtr](../../system/taskptr/) [AsTask](./astask/)() const | Convertit cet [ValueTask](./) en un pointeur partagé vers [Task](../task/). |
| [Runtime::CompilerServices::ConfiguredValueTaskAwaitable](../../system.runtime.compilerservices/configuredvaluetaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | Configure un awaiter pour cette tâche. |
| **bool** [Equals](./equals/)([ValueTask](./)) override | Détermine si cette instance est égale à une autre instance [ValueTask](./). |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Détermine si cette instance est égale à un autre objet. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Détermine si les objets actuel et spécifié sont égaux. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres flottants de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Obtient une valeur indiquant si la tâche s’est terminée parce qu’elle a été annulée. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Obtient une valeur indiquant si la tâche est terminée. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Obtient une valeur indiquant si la tâche s’est terminée avec succès. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Obtient une valeur indiquant si la tâche s’est terminée à cause d’une exception non gérée. |
| [Runtime::CompilerServices::ValueTaskAwaiter](../../system.runtime.compilerservices/valuetaskawaiter/) [GetAwaiter](./getawaiter/)() const | Obtient un awaiter pour cette tâche afin de prendre en charge les expressions await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de référence associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage du statement C# lock(). Appelez directement ou utilisez l’objet sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, initialise simplement un nouvel objet et permet la construction de copie des sous-classes. |
| **bool** [operator!=](./operator_not_equal/)(const [ValueTask](./)\&) const | Opérateur d’inégalité pour [ValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, initialise simplement un nouvel objet et permet la construction de copie des sous-classes. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTask](./)\&) const | Opérateur d’égalité pour [ValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de référence partagé du nombre spécifié. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de référence partagé. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de référence partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de référence partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode [Object.ToString()](../../system/object/tostring/) de C#. Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage du statement C# lock(). Appelez directement ou utilisez l’objet sentry [LockContext](../../system/lockcontext/). |
|  [ValueTask](./valuetask/)() | Construit un [ValueTask](./) vide et non initialisé. |
|  [ValueTask](./valuetask/)(const [TaskPtr](../../system/taskptr/)\&) | Construit un [ValueTask](./) à partir d’un pointeur partagé vers un [Task](../task/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de référence faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de référence faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IEquatable](../../system/iequatable/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)