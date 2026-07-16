---
title: TypeInfo
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un type particulier et fournit des informations à son sujet.
type: docs
weight: 1353
url: /fr/system/typeinfo/
---
## TypeInfo classe

Représente un type particulier et fournit des informations à son sujet.

```cpp
class TypeInfo
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Ajoute l'attribut spécifié à la liste des attributs du type. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Définit le constructeur par défaut pour le type T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Définit le constructeur par défaut à l'aide du functor qui crée l'instance de classe. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Ajoute le membre spécifié à la liste des membres du type. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Fournit une structure [TypeInfo](./) unique pour le type **BoxedValue** afin d'être partagée par plusieurs classes Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NON IMPLEMENTÉ. Retourne un pointeur vers l'assembly dans lequel le type représenté par l'objet actuel est déclaré. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NON IMPLEMENTÉ. Retourne le nom complet incluant le nom de l'assembly du type représenté par l'objet actuel. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Retourne le descripteur du type de base. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Obtient une valeur indiquant si l'objet Type actuel possède des paramètres de type qui n'ont pas été remplacés par des types spécifiques. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Obtient la liste des membres portant le nom spécifié. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Retourne le nom complet (sans le nom de l'assembly) du type représenté par l'objet actuel. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Obtient un tableau des arguments de type génériques pour ce type. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Obtient une valeur indiquant si le Type est abstrait et doit être remplacé. |
| **bool** [get_IsArray](./get_isarray/)() const | Obtient une valeur indiquant si le type est un tableau. |
| **bool** [get_IsClass](./get_isclass/)() const | Obtient une valeur indiquant si le Type est une classe ou un délégué; c'est-à-dire, ni un type valeur ni une interface. |
| **bool** [get_IsEnum](./get_isenum/)() const | Obtient une valeur indiquant si le Type actuel représente une énumération. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Obtient une valeur indiquant si le Type actuel représente une définition de type générique, à partir de laquelle d'autres types génériques peuvent être construits. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Obtient une valeur indiquant si le Type est une interface; c'est-à-dire, ni une classe ni un type valeur. |
| **bool** [get_IsSealed](./get_issealed/)() const | Obtient une valeur indiquant si le Type est déclaré scellé. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Obtient une valeur indiquant si le Type est un type valeur. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Obtient une valeur indiquant si le Type peut être accédé par du code extérieur à l'assembly. |
| [String](../string/) [get_Name](./get_name/)() const | Retourne le nom du type représenté par l'objet actuel. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Obtient l'espace de noms du Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Recherche un constructeur d'instance public dont les paramètres correspondent aux types du tableau spécifié. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Recherche les constructeurs définis pour le Type actuel, en utilisant les BindingFlags spécifiés. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Retourne tous les constructeurs publics définis pour le Type actuel. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Recherche l'attribut personnalisé appliqué ayant le type spécifié et appliqué au type représenté par l'objet actuel. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Retourne un tableau contenant les objets représentant tous les attributs personnalisés appliqués au type. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Retourne un tableau contenant les objets représentant les attributs spécifiques appliqués au type. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NON IMPLEMENTÉ. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Recherche le champ spécifié, en utilisant les contraintes de liaison spécifiées. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Recherche les champs définis pour le Type actuel, en utilisant les contraintes de liaison spécifiées. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Obtient un tableau des arguments de type génériques pour ce type. |
| int [GetHashCode](./gethashcode/)() const | Retourne un code de hachage associé à cette instance. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Obtient toutes les interfaces implémentées ou héritées par le Type actuel. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Obtient la liste des membres portant le nom spécifié. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Obtient la méthode portant le nom spécifié. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Retourne toutes les propriétés publiques du Type actuel. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Recherche les propriétés du Type actuel, en utilisant les contraintes de liaison spécifiées. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Obtient le descripteur du type de paramètre de modèle. |
| **uint32_t** [Hash](./hash/)() const | Retourne une valeur de hachage associée au type représenté par l'objet actuel. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Détermine si une instance d'un type spécifié peut être assignée à une variable du type actuel. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NON IMPLEMENTÉ. Indique si un ou plusieurs attributs du type spécifié ou de ses types dérivés sont appliqués à ce membre. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Détermine si l'objet spécifié est une instance du type actuel. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Détermine si le type représenté par l'objet actuel est une sous-classe de la classe spécifiée. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Détermine si le type actuel et l'objet [TypeInfo](./) spécifié ne sont pas égaux. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Détermine si l'objet [TypeInfo](./) actuel n'est pas un objet nul, c'est-à-dire qu'il représente un type. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Détermine si le type actuel et l'objet [TypeInfo](./) spécifié sont égaux. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Détermine si l'objet [TypeInfo](./) actuel est un objet nul, c'est-à-dire qu'il ne représente aucun type. |
| void [reset](./reset/)() | Définit [TypeInfo](./) à null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Définit une valeur indiquant si le Type est un type valeur. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Définit le descripteur du type de base. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Définit le descripteur du type de paramètre de modèle. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Calcule le hachage pour la chaîne spécifiée. |
| [String](../string/) [ToString](./tostring/)() const | Retourne une chaîne contenant le nom du type représenté par l'objet actuel. |
| static const [TypeInfo](./)\& [Type](./type/)() | Retourne un objet [TypeInfo](./) qui représente la classe [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Constructeur par défaut (aucun type n'est défini). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Constructeur d'objet nul (aucun type n'est défini). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Constructeur. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Constructeur. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Constructeur. |

## Champs

| Champ | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | Constante représentant une liste vide de [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Constante représentant une liste vide de [TypeInfo](./). |

## Typedefs

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Pointeur de fonction pour construire le type. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)