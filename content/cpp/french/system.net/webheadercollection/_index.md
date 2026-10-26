---
title: WebHeaderCollection
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente la collection des en-têtes du protocole. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction System::MakeObject() . Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 482
url: /fr/system.net/webheadercollection/
---
## WebHeaderCollection classe


Represents the collection of the protocol headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebHeaderCollection : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Add](./add/)([String](../../system/string/), [String](../../system/string/)) | Ajoute la paire spécifiee du nom d'en-tete et de la valeur d'en-tete a la collection. |
| void [Add](./add/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Ajoute la paire spécifiee de l'en-tete et de la valeur d'en-tete a la collection. |
| void [Add](./add/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Ajoute la paire spécifiee de l'en-tete et de la valeur d'en-tete a la collection. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [AllKeys](./allkeys/)() | Renvoie une collection de noms d'en-tete stockes dans la collection. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la semantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type reference dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison en virgule flottante de style C# où deux NaN sont consideres comme egaux meme si, selon IEC 60559:1989, NaN n'est egal a aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison en virgule flottante de style C# où deux NaN sont consideres comme egaux meme si, selon IEC 60559:1989, NaN n'est egal a aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | A des fins internes uniquement. |
| **int32_t** [get_Count](./get_count/)() const | Renvoie le nombre d'elements dans la collection. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_Keys](./get_keys/)() | Renvoie une collection de noms d'en-tete stockes dans la collection. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la methode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalises. |
| [String](../../system/string/) [GetKey](./getkey/)(int) | Renvoie une cle a l'index specifie. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [GetValues](./getvalues/)([String](../../system/string/)) | Renvoie la collection des valeurs d'en-tete. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpRequestHeader](../httprequestheader/)) | Obtient la valeur d'en-tete en utilisant l'en-tete de la requete specifiee. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpResponseHeader](../httpresponseheader/)) | Obtient la valeur d'en-tete en utilisant l'en-tete de la reponse specifiee. |
| [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Obtient la valeur d'en-tete en utilisant le nom d'en-tete specifie. |
| void [idx_set](./idx_set/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Definit la valeur d'en-tete de l'en-tete specifie. |
| void [idx_set](./idx_set/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Definit la valeur d'en-tete en utilisant l'en-tete de la reponse specifiee. |
| void [idx_set](./idx_set/)([String](../../system/string/), [String](../../system/string/)) | Definit la valeur d'en-tete en utilisant le nom d'en-tete specifie. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet represente une instance du type descri par targetType. Analogue de l'operateur C# 'is'. |
| static **bool** [IsRestricted](./isrestricted/)(const [String](../../system/string/)\&) | Teste si l'en-tete HTTP specifie peut etre defini pour la requete. |
| void [Lock](../../system/object/lock/)() | Implemente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la methode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalises. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de donnees internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaine et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaines. |
| void [Remove](./remove/)([String](../../system/string/)) | Supprime l'en-tete selon le nom d'en-tete specifie. |
| void [Remove](./remove/)([HttpResponseHeader](../httpresponseheader/)) | Supprime l'en-tete de la reponse specifiee. |
| void [Remove](./remove/)([HttpRequestHeader](../httprequestheader/)) | Supprime l'en-tete de la requete specifiee. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees du nombre specifie. |
| void [Set](./set/)([String](../../system/string/), [String](../../system/string/)) | Definit la valeur de l'en-tete specifie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definit le n-ieme argument de modele comme pointeur faible (plutot que partage). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incremente le compteur de references partagees. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et renvoie le compteur de references partagees. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogue de la methode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalises en chaine. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implemente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implemente le deverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incremente le compteur de references faibles. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| [WebHeaderCollection](./webheadercollection/)() | Construit une nouvelle instance. |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Net](../)
* Bibliothèque [Aspose.Slides](../../)