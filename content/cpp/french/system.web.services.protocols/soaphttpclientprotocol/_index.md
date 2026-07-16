---
title: SoapHttpClientProtocol
second_title: Référence de l'API Aspose.Slides pour C++
description: "Les services de proxy client doivent hériter de cette classe lorsque le SOAP est utilisé. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 118
url: /fr/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol classe


Les services de proxy client doivent hériter de cette classe lorsque le SOAP est utilisé. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Annule la requête. |
| virtual void [CheckForCookies](../httpwebclientprotocol/checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Ajoute les cookies de la requête spécifiée au conteneur interne de cookies. |
| void [Discover](./discover/)() | Lie l'instance actuelle au service XML [Web](../../system.web/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante double de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **bool** [get_AllowAutoRedirect](../httpwebclientprotocol/get_allowautoredirect/)() | Renvoie une valeur indiquant si le client suit les redirections du serveur. |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](../httpwebclientprotocol/get_clientcertificates/)() | Renvoie la collection des certificats du client. |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | Renvoie le nom du groupe de connexion. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](../httpwebclientprotocol/get_cookiecontainer/)() | Renvoie un conteneur utilisé pour stocker les cookies. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | Renvoie les informations d'authentification. |
| **bool** [get_EnableDecompression](../httpwebclientprotocol/get_enabledecompression/)() | Renvoie une valeur indiquant si la décompression est activée. |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | Renvoie une valeur indiquant si la pré-authentification est activée. |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](../httpwebclientprotocol/get_proxy/)() | Renvoie les informations du proxy. |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | Renvoie l'encodage utilisé pour les requêtes du client. |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | Renvoie la version SOAP. |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | Renvoie la durée d'attente avant l'expiration de la requête. |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/get_unsafeauthenticatedconnectionsharing/)() | Renvoie une valeur indiquant si le partage de connexion est activé lorsque le client utilise l'authentification NTLM. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | Renvoie l'URI du service XML [Web](../../system.web/). |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | Renvoie l'URL du service XML [Web](../../system.web/). |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | Renvoie une valeur indiquant si la propriété 'Credential' est égale à la propriété 'DefaultCredentials'. |
| [String](../../system/string/) [get_UserAgent](../httpwebclientprotocol/get_useragent/)() | Renvoie la valeur de l'en-tête 'User-Agent'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Renvoie la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Renvoie le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| void [InitializeSerializers](./initializeserializers/)(const [System::TypeInfo](../../system/typeinfo/)\&, [System::SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerImplementation](../../system.xml.serialization/xmlserializerimplementation/)\>, [String](../../system/string/)) | Initialise les champs internes. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en fait rien, il initialise simplement le nouvel objet et permet de copier les sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie en fait rien, il initialise simplement le nouvel objet et permet de copier les sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Décrémente le compteur de références partagées du nombre spécifié. |
| void [set_AllowAutoRedirect](../httpwebclientprotocol/set_allowautoredirect/)(**bool**) | Définit une valeur indiquant si le client suit les redirections du serveur. |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | Définit le nom du groupe de connexion. |
| void [set_CookieContainer](../httpwebclientprotocol/set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | Définit un conteneur utilisé pour stocker les cookies. |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | Définit les informations d'authentification. |
| void [set_EnableDecompression](../httpwebclientprotocol/set_enabledecompression/)(**bool**) | Définit une valeur indiquant si la décompression est activée. |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | Définit une valeur indiquant si la pré-authentification est activée. |
| void [set_Proxy](../httpwebclientprotocol/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | Définit les informations du proxy. |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Définit l'encodage utilisé pour les requêtes du client. |
| void [set_SoapVersion](./set_soapversion/)([SoapProtocolVersion](../soapprotocolversion/)) | Définit la version SOAP. |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | Définit la durée d'attente avant l'expiration de la requête. |
| void [set_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/set_unsafeauthenticatedconnectionsharing/)(**bool**) | Définit une valeur indiquant si le partage de connexion est activé lorsque le client utilise l'authentification NTLM. |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Définit l'URI du service XML [Web](../../system.web/). |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | Définit l'URL du service XML [Web](../../system.web/). |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | Définit une valeur indiquant si la propriété 'Credential' est égale à la propriété 'DefaultCredentials'. |
| void [set_UserAgent](../httpwebclientprotocol/set_useragent/)([String](../../system/string/)) | Définit la valeur de l'en-tête 'User-Agent'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Renvoie la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | Construit une nouvelle instance. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| void [UnregisterMapping](../httpwebclientprotocol/unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [HttpWebClientProtocol](../httpwebclientprotocol/)
* Espace de noms [System::Web::Services::Protocols](../)
* Bibliothèque [Aspose.Slides](../../)