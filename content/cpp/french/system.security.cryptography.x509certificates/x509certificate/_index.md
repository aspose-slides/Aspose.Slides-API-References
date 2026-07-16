---
title: X509Certificate
second_title: Référence API Aspose.Slides pour C++
description: "Certificat X.509 v.3. Les certificats chiffrés ne sont pas pris en charge. Seul le drapeau X509KeyStorageFlags::DefaultKeySet est pris en charge. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en argument."
type: docs
weight: 27
url: /fr/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate classe

Certificat X.509 v.3. Les certificats chiffrés ne sont pas pris en charge. Seul le drapeau [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) est pris en charge. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | Crée un certificat à partir du fichier PKCS7 spécifié. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | Crée un certificat à partir du fichier signé spécifié. |
| void [Dispose](./dispose/)() override | Ne fait rien. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compare deux certificats. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | Exporte l'objet actuel vers un tableau d'octets en utilisant le format spécifié. NOT IMPLEMENTED. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Exporte l'objet actuel vers un tableau d'octets en utilisant le format spécifié. NOT IMPLEMENTED. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Exporte l'objet actuel vers un tableau d'octets en utilisant le format spécifié. NOT IMPLEMENTED. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pour usage interne uniquement. |
| IntPtr [get_Handle](./get_handle/)() const | Obtient un handle vers le contexte de certificat Microsoft Cryptographic API. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | Obtient le nom de l'autorité de certification qui a délivré le certificat X.509v3. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | Obtient le nom distinctif du sujet du certificat. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | Obtient le hachage de l'objet actuel sous forme de tableau d'octets. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Obtient le hachage de l'objet actuel sous forme de tableau d'octets. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | Obtient le hachage [SHA1](../../system.security.cryptography/sha1/) de l'objet actuel sous forme de chaîne hexadécimale. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Obtient le hachage [SHA1](../../system.security.cryptography/sha1/) de l'objet actuel sous forme de chaîne hexadécimale. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | Obtient la date de prise d'effet du certificat actuel. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | Obtient la date d'expiration du certificat actuel. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | Obtient le nom du format du certificat. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Obtient le code de hachage du certificat. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | Obtient le nom de l'autorité de certification qui a délivré le certificat actuel. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | Obtient les informations de clé du certificat actuel sous forme de chaîne. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Obtient les informations de clé du certificat actuel sous forme de tableau d'octets. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Obtient les informations de clé du certificat actuel sous forme de chaîne hexadécimale. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | Obtient le nom du principal pour lequel le certificat actuel a été émis. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | Obtient la clé publique du certificat sous forme de tableau d'octets. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | Obtient la clé publique du certificat sous forme de chaîne hexadécimale. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | Obtient les données brutes du certificat sous forme de tableau d'octets. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | Obtient les données brutes du certificat sous forme de chaîne hexadécimale. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | Obtient le numéro de série du certificat sous forme de tableau d'octets. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | Obtient le numéro de série du certificat sous forme de chaîne hexadécimale. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importe les informations du fichier de certificat spécifié. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importe les informations du fichier de certificat spécifié. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importe les informations des données de certificat spécifiées. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importe les informations des données de certificat spécifiées. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | Importe les informations du fichier de certificat spécifié. NOT IMPLEMENTED. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Importe les informations des données de certificat spécifiées. NOT IMPLEMENTED. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement le nouvel objet et autorise la construction copie des sous-classes. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [Reset](./reset/)() | Réinitialise l'état du certificat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | Renvoie les informations du certificat au format texte. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Renvoie les informations du certificat au format texte. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructeur. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Type pointeur. |

## Voir aussi

* Classe [Object](../../system/object/)
* Classe [IDisposable](../../system/idisposable/)
* Espace de noms [System::Security::Cryptography::X509Certificates](../)
* Bibliothèque [Aspose.Slides](../../)