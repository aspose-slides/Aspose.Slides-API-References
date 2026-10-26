---
title: "System::Reflection"
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 755
url: /fr/system.reflection/
---
## Classes

| Classe | Description |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) classe décrivant l'assembly. Le support est limité car les règles diffèrent considérablement entre C# et C++. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [AssemblyName](./assemblyname/) | Définit le nom de l'assembly. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton pour enregistrer le type dans l'assembly en cours d'exécution. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Type de base pour les singletons afin d'enregistrer le type dans l'assembly en cours d'exécution. |
| [ConstructorInfo](./constructorinfo/) | Fournit l'accès aux métadonnées du constructeur. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException est levée par la méthode Module.GetTypes si l'une des classes d'un module ne peut pas être chargée. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe ReflectionTypeLoadException à la place. Ne placez jamais les instances de la classe ReflectionTypeLoadException dans [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException est levée par les méthodes invoquées via la réflexion. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe TargetInvocationException à la place. Ne placez jamais les instances de la classe TargetInvocationException dans [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Découvre les attributs d'un champ et fournit l'accès aux métadonnées du champ. |
| [MemberInfo](./memberinfo/) | Fournit des informations de réflexion sur les membres. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [MethodBase](./methodbase/) | Informations de base sur la méthode. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument. |
| [MethodInfo](./methodinfo/) | Représente les informations sur la méthode de classe. |
| [PropertyInfo](./propertyinfo/) | Représente les informations de propriété. |

## Énumérations

| Énumération | Description |
| --- | --- |
| [BindingFlags](./bindingflags/) | Définit les membres et les modes de recherche et de liaison des types. |
| [FieldAttributes](./fieldattributes/) | Attributs de champ reflétés. |
| [MemberTypes](./membertypes/) | Marque chaque type de membre. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException est levée par la méthode Module.GetTypes si l'une des classes d'un module ne peut pas être chargée. Ne placez jamais les instances de la classe ReflectionTypeLoadException dans [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException est levée par les méthodes invoquées via la réflexion. Ne placez jamais les instances de la classe TargetInvocationException dans [System::SmartPtr](../system/smartptr/). |