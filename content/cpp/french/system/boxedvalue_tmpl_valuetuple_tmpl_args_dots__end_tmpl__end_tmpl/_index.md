---
title: BoxedValue< ValueTuple< Args... > >
second_title: Référence API Aspose.Slides pour C++
description: Version encapsulée du tuple de valeurs.
type: docs
weight: 118
url: /fr/system/boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/
---
## BoxedValue< ValueTuple< Args... > > classe


Version encapsulée du tuple de valeurs.

```cpp
template<typename...>class BoxedValue< ValueTuple< Args... > > : public System::Runtime::CompilerServices::ITuple
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| name | Types des éléments du tuple Args. |
## Méthodes

| Méthode | Description |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const [ValueT](../valuetuple/)\&) | Construit un objet [BoxedValue](../boxedvalue/) qui représente la valeur spécifiée encapsulée. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Détermine l'égalité des valeurs encapsulées représentées par les objets courant et spécifié. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| int [GetHashCode](./gethashcode/)() const override | Renvoie un code de hachage pour l'objet courant. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Obtient le type réel de l'objet. |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | Renvoie l'élément à la position index. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| **bool** [is](./is/)() const | Détermine si le type de la valeur encapsulée représentée par l'objet courant est **V**. |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Définit le n-ème argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Diminue et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Renvoie la représentation chaîne de caractères de la valeur encapsulée. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implémente la construction C# typeof([System.Object](../object/)). |
| const [ValueT](../valuetuple/)\& [unbox](./unbox/)() const | Déballe la valeur encapsulée. |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Diminue le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [ITuple](../../system.runtime.compilerservices/ituple/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)