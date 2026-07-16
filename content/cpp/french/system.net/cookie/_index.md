---
title: Cookie
second_title: Aspose.Slides pour C++ Référence API
description: "Représente un cookie HTTP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 1
url: /fr/system.net/cookie/
---
## Classe Cookie


Représente un cookie HTTP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class Cookie : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Crée une copie de l'instance actuelle. |
|  [Cookie](./cookie/)() | Construit une nouvelle instance. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Construit une nouvelle instance. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Construit une nouvelle instance. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Construit une nouvelle instance. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Obtient la valeur de l'attribut 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Obtient la valeur de l'attribut 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Obtient la valeur de l'attribut 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Obtient la valeur de l'attribut 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Obtient une valeur indiquant si le domaine est implicite. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Renvoie la clé du domaine. |
| **bool** [get_Expired](./get_expired/)() | Obtient une valeur indiquant si le cookie a expiré. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Obtient la valeur de l'attribut 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Obtient la valeur de l'attribut 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Obtient le nom du cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Obtient la valeur de l'attribut 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Renvoie une valeur indiquant si la spécification du cookie est 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Obtient la valeur de l'attribut 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Renvoie la collection des valeurs de l'attribut 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Obtient la valeur de l'attribut 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Renvoie le moment où le cookie a été créé. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Obtient la valeur du cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Obtient la spécification du cookie. |
| **int32_t** [get_Version](./get_version/)() const | Obtient la valeur de l'attribut '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Cette méthode est appelée par d'autres méthodes pour définir un nom de méthode. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de string et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Définit la valeur de l'attribut 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Définit la valeur de l'attribut 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Définit la valeur de l'attribut 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Définit la valeur de l'attribut 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Définit une valeur indiquant si le domaine est implicite. |
| void [set_Expired](./set_expired/)(**bool**) | Définit une valeur indiquant si le cookie a expiré. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Définit la valeur de l'attribut 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Définit la valeur de l'attribut 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Définit le nom du cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Définit la valeur de l'attribut 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Définit la valeur de l'attribut 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Définit la valeur de l'attribut 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Définit la valeur du cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Définit la spécification du cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Définit la valeur de l'attribut '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Débute le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Sérialise l'instance actuelle en représentation sous forme de chaîne. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Vérifie et définit les valeurs par défaut de l'attribut. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Champs

| Champ | Description |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Le nom de l'attribut 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Le nom de l'attribut 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Le nom de l'attribut 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Le nom de l'attribut 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Le séparateur utilisé pour séparer le nom et la valeur d'un attribut. |
| static [ExpiresAttributeName](./expiresattributename/) | Le nom de l'attribut 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Le nom de l'attribut 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Le nom de l'attribut 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | La version maximale prise en charge. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | La représentation sous forme de chaîne de la version maximale prise en charge. |
| static [PathAttributeName](./pathattributename/) | Le nom de l'attribut 'Path'. |
| static [PortAttributeName](./portattributename/) | Le nom de l'attribut 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Le tableau contenant les délimiteurs pour les valeurs de l'attribut 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Le symbole utilisé pour encapsuler les parties de l'attribut. |
| static [ReservedToName](./reservedtoname/) | Une valeur réservée au nom du cookie. |
| static [ReservedToValue](./reservedtovalue/) | Une valeur réservée à la valeur du cookie. |
| static [SecureAttributeName](./secureattributename/) | Le nom de l'attribut 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Le séparateur d'attribut. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Le préfixe des noms des attributs spéciaux. |
| static [VersionAttributeName](./versionattributename/) | Le nom de l'attribut '[Version](../../system/version/)'. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Net](../)
* Bibliothèque [Aspose.Slides](../../)