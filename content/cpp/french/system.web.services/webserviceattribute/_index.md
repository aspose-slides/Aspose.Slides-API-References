---
title: WebServiceAttribute
second_title: Référence API Aspose.Slides pour C++
description: "Ajoute des informations supplémentaires au service Web XML. Les objets de cette classe ne doivent être alloués qu'avec la fonction System::MakeObject() . Ne créez jamais d'instance de ce type sur la pile ou avec l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 27
url: /fr/system.web.services/webserviceattribute/
---
## WebServiceAttribute classe

Adds additional information to the XML [Web](../../system.web/) service. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebServiceAttribute : public System::Attribute
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la semantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type reference dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison de nombres a virgule flottante de style C# ou deux NaN sont consideres comme egaux bien que, selon IEC 60559:1989, NaN ne soit egal a aucune valeur, incluant NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison de nombres a virgule flottante de style C# ou deux NaN sont consideres comme egaux bien que, selon IEC 60559:1989, NaN ne soit egal a aucune valeur, incluant NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | A des fins internes uniquement. |
| [String](../../system/string/) [get_Description](./get_description/)() | Obtient un message contenant la description du service XML [Web](../../system.web/). |
| [String](../../system/string/) [get_Name](./get_name/)() | Obtient le nom du service XML [Web](../../system.web/). |
| [String](../../system/string/) [get_Namespace](./get_namespace/)() | Obtient l'espace de noms par defaut a utiliser pour le service XML [Web](../../system.web/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Renvoie un attribut personnalise d'un type specifie applique au type specifie. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Renvoie tous les attributs personnalises appliques au type specifie. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la methode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalises. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet represente une instance du type decrit par targetType. Analogue de l'operateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en oeuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la methode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalises. |
|  [Object](../../system/object/object/)() | Cree l'objet. Initialise toutes les structures de donnees internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en realite, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie rien, en realite, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaine et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaines. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees de la valeur specifiee. |
| void [set_Description](./set_description/)([String](../../system/string/)) | Definit un message contenant la description du service XML [Web](../../system.web/). |
| void [set_Name](./set_name/)([String](../../system/string/)) | Definit le nom du service XML [Web](../../system.web/). |
| void [set_Namespace](./set_namespace/)([String](../../system/string/)) | Definit l'espace de noms par defaut a utiliser pour le service XML [Web](../../system.web/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definit le n-th argument de modele comme un pointeur faible (plutot que partage). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incremente le compteur de references partagees. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et renvoie le compteur de references partagees. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la methode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalises en chaine. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en oeuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en oeuvre le deverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incremente le compteur de references faibles. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
|  [WebServiceAttribute](./webserviceattribute/)() | Construit une nouvelle instance. |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |

## Champs

| Champ | Description |
| --- | --- |
| static [DefaultNamespace](./defaultnamespace/) | La valeur par defaut de la propriete 'Namespace'. |

## Voir aussi

* Classe [Attribute](../../system/attribute/)
* Espace de noms [System::Web::Services](../)
* Bibliotheque [Aspose.Slides](../../)