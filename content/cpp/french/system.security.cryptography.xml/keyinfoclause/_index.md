---
title: KeyInfoClause
second_title: Référence API Aspose.Slides pour C++
description: "Toutes les implémentations des sous-éléments KeyInfo doivent hériter de cette classe abstraite. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 40
url: /fr/system.security.cryptography.xml/keyinfoclause/
---
## KeyInfoClause classe

Toutes les implémentations des sous-elements [KeyInfo](../keyinfo/) doivent hériter de cette classe abstraite. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions comme argument.

```cpp
class KeyInfoClause : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la semantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison de nombres a virgule flottante a la C#-style où deux NaNs sont consideres comme egaux bien que, selon IEC 60559:1989, NaN ne soit egal a aucune valeur, incluant NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison de nombres a virgule flottante a la C#-style où deux NaNs sont consideres comme egaux bien que, selon IEC 60559:1989, NaN ne soit egal a aucune valeur, incluant NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | A des fins internes uniquement. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la methode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalises. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet represente une instance du type décrit par targetType. Analogue de l'operateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implemente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la methode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalises. |
|  [Object](../../system/object/object/)() | Cree l'objet. Initialise toutes les structures de donnees internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il se contente d'initialiser un nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie rien, en fait, il se contente d'initialiser un nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de string et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaines. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees de la valeur specifiee. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definit le n ieme argument de modele comme un pointeur faible (plutot que partage). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incremente le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et retourne le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la methode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalises en chaine. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implemente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implemente le deverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Security::Cryptography::Xml](../)
* Bibliothèque [Aspose.Slides](../../)