---
title: IPAddress
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente l'adresse IP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 326
url: /fr/system.net/ipaddress/
---
## IPAddress classe


Représente l'adresse IP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class IPAddress : public System::Object
```

## Méthodes

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaNs sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaNs sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | Renvoie la famille d'adresses. |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | Renvoie une valeur indiquant si l'adresse est une adresse IPv4 et est mappée à une adresse IPv6. |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | Renvoie une valeur indiquant si l'adresse est une adresse IPv6 link-local. |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | Renvoie une valeur indiquant si l'adresse est une adresse IPv6 multicast globale. |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | Renvoie une valeur indiquant si l'adresse est une adresse IPv6 site-local. |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | Renvoie une valeur indiquant si l'adresse est une adresse IPv6 Teredo. |
| **int64_t** [get_ScopeId](./get_scopeid/)() | Obtient l'identifiant de portée de l'adresse IPv6. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | Renvoie un tableau d'octets de l'adresse IP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | Renvoie un pointeur vers l'implémentation. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | Convertit l'ordre des octets hôte spécifié en l'ordre des octets réseau correspondant. |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | Convertit l'ordre des octets hôte spécifié en l'ordre des octets réseau correspondant. |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | Convertit l'ordre des octets hôte spécifié en l'ordre des octets réseau correspondant. |
|  [IPAddress](./ipaddress/)(**int64_t**) | Construit une nouvelle instance. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | Construit une nouvelle instance. |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Construit une nouvelle instance. |
|  [IPAddress](./ipaddress/)() | Construit une nouvelle instance. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | Renvoie une valeur indiquant si l'adresse spécifiée est une adresse de boucle. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | Mappe l'adresse vers l'adresse IPv4. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | Mappe l'adresse vers l'adresse IPv6. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | Convertit l'ordre des octets réseau spécifié en l'ordre des octets hôte correspondant. |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | Convertit l'ordre des octets réseau spécifié en l'ordre des octets hôte correspondant. |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | Convertit l'ordre des octets réseau spécifié en l'ordre des octets hôte correspondant. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | Convertit une chaîne passée en une instance de la classe [IPAddress](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | Définit l'identifiant de portée de l'adresse IPv6. |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | Définit un pointeur vers l'implémentation. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | Tente de convertir une chaîne passée en une instance de la classe [IPAddress](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Champs

| Field | Description |
| --- | --- |
| static [Any](./any/) | L'adresse IPv4 qui indique si le serveur doit écouter toutes les interfaces réseau. |
| static [Broadcast](./broadcast/) | L'adresse de diffusion IPv4. |
| static [IPv6Any](./ipv6any/) | L'adresse IPv6 qui indique si le serveur doit écouter toutes les interfaces réseau. |
| static [IPv6Loopback](./ipv6loopback/) | L'adresse de boucle IPv6. |
| static [IPv6None](./ipv6none/) | L'adresse IPv6 qui indique si le serveur ne doit écouter aucune interface réseau. |
| static [Loopback](./loopback/) | L'adresse de boucle IPv4. |
| static [None](./none/) | L'adresse IPv4 qui indique si le serveur ne doit écouter aucune interface réseau. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | Un pointeur vers le type d'implémentation. |

## See Also

* Classe [Object](../../system/object/)
* Espace de noms [System::Net](../)
* Bibliothèque [Aspose.Slides](../../)