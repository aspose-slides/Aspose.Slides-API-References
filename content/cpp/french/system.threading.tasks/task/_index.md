---
title: Task
second_title: Référence API Aspose.Slides pour C++
description: Représente une opération asynchrone qui peut être attendue et composée avec d'autres tâches.
type: docs
weight: 66
url: /fr/system.threading.tasks/task/
---
## Classe Task


Représente une opération asynchrone qui peut être attendue et composée avec d'autres tâches.

```cpp
class Task : public System::IDisposable
```

## Méthodes

| Method | Description |
| --- | --- |
| void [Activate](./activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Active la tâche pour l'exécution sur un planificateur. |
| void [AddCompletionAction](./addcompletionaction/)(const [Action](../../system/action/)<>\&) | Ajoute une action de continuation à exécuter lors de la terminaison. |
| void [Cancel](./cancel/)() | Marque la tâche comme annulée et termine la tâche. |
| void [Complete](./complete/)() | Marque la tâche comme terminée et termine la tâche. |
| [Runtime::CompilerServices::ConfiguredTaskAwaitable](../../system.runtime.compilerservices/configuredtaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | Configure le comportement des await sur cette tâche concernant la capture du contexte. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Crée une continuation qui s'exécute lorsque la tâche se termine. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Crée une continuation qui s'exécute lorsque la tâche se termine. |
| void [Deactivate](./deactivate/)() | Désactive la tâche pour l'exécution sur son planificateur actuel, le cas échéant. |
| void [Dispose](./dispose/)() override | Libère les ressources associées à la tâche. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence à la manière de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur à la manière de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| void [Execute](./execute/)() | Exécute la fonction de la tâche. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](./get_asyncstate/)() const | Obtient l'objet d'état défini par l'utilisateur associé à la tâche. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](./get_completedtask/)() | Obtient une tâche terminée (singleton) |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](./get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](./get_exception/)() const | Obtient l'ID de la tâche. |
| **int32_t** [get_Id](./get_id/)() const |  |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Détermine si la tâche s'est terminée suite à une annulation. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Détermine si la tâche est terminée. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Détermine si la tâche s'est terminée en raison d'une exception non gérée. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](./get_scheduler/)() const | Obtient le planificateur associé à cette tâche. |
| [TaskStatus](../taskstatus/) [get_Status](./get_status/)() const | Obtient l'état actuel de la tâche. |
| [Runtime::CompilerServices::TaskAwaiter](../../system.runtime.compilerservices/taskawaiter/) [GetAwaiter](./getawaiter/)() const | Obtient un awaiter pour cette tâche à utiliser avec Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien réellement, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien réellement, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [RunSynchronously](./runsynchronously/)() | Exécute la tâche de manière synchrone sur le fil d'exécution actuel. |
| void [RunSynchronously](./runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Exécute la tâche de manière synchrone en utilisant le planificateur spécifié. |
| void [set_Function](./set_function/)(const [FunctionT](./functiont/)\&) | Définit la fonction interne à exécuter. |
| void [set_Scheduler](./set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Définit le planificateur associé à cette tâche. |
| void [set_Status](./set_status/)([TaskStatus](../taskstatus/)) | Définit l'état de la tâche. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs vers le mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Start](./start/)() | Démarre l'exécution de la tâche en utilisant le planificateur par défaut. |
| void [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Démarre l'exécution de la tâche en utilisant le planificateur spécifié. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&) | Construit un [Task](./) avec une action à exécuter. |
|  [Task](./task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Construit un [Task](./) avec une action et un jeton d'annulation. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Construit un [Task](./) avec une action stateful et un objet d'état. |
|  [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Construit un [Task](./) avec une action stateful, un état et un jeton d'annulation. |
|  [Task](./task/)() | Constructeur interne pour créer des tâches non initialisées. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| void [Wait](./wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Attend que la tâche se termine avec prise en charge de l'annulation. |
| void [Wait](./wait/)() | Attend que la tâche se termine. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
|  [~Task](./~task/)() | Destructeur. |

## Définitions de type

| Typedef | Description |
| --- | --- |
| [FunctionT](./functiont/) | Implémentation interne. Non destiné au code utilisateur. |

## Remarques


Fournit une implémentation C++ similaire à [System.Threading.Tasks.Task](./) en .NET, prenant en charge l'annulation, les continuations et les modèles async/await.

## Voir aussi

* Classe [IDisposable](../../system/idisposable/)
* Espace de noms [System::Threading::Tasks](../)
* Bibliothèque [Aspose.Slides](../../)