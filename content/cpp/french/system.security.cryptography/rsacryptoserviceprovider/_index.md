---
title: RSACryptoServiceProvider
second_title: Référence API Aspose.Slides pour C++
description: "Algorithme RSA sous forme CSP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject() . Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 469
url: /fr/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider classe


[RSA](../rsa/) algorithme sous forme CSP. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Méthodes

| Method | Description |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Libère toutes les ressources. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)() | Crée une implémentation d'algorithme [RSA](../rsa/) par défaut. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [String](../../system/string/)\&) | Crée une implémentation d'algorithme [RSA](../rsa/) par défaut. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(**int32_t**) | Crée une implémentation d'algorithme [RSA](../rsa/) par défaut avec la taille de clé spécifiée. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [RSAParameters](../rsaparameters/)\&) | Crée une implémentation d'algorithme [RSA](../rsa/) par défaut avec des paramètres spécifiés. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [CreateFromXmlString](../rsa/createfromxmlstring/)(const [String](../../system/string/)\&) | Crée une implémentation d'algorithme [RSA](../rsa/) par défaut avec des paramètres encodés XML spécifiés. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Déchiffre le message. Non implémenté. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | Déchiffre les données d'entrée en utilisant le mode de remplissage spécifié. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](../rsa/decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Déchiffre la valeur en utilisant la clé privée. |
| void [Dispose](./dispose/)() override | Libère les données associées à l'objet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Chiffre le message. Non implémenté. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | Chiffre les données d'entrée en utilisant le mode de remplissage spécifié. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](../rsa/encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Chiffre la valeur en utilisant la clé privée. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, le NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, le NaN ne soit égal à aucune valeur, y compris NaN. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | Exporte le blob contenant les informations sur la clé. Non implémenté. |
| [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | Exporte les paramètres CSP. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| void [FromXmlString](../rsa/fromxmlstring/)([String](../../system/string/)) override | Initialise l'objet en utilisant des paramètres encodés XML. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Obtient un objet [CspKeyContainerInfo](../cspkeycontainerinfo/). |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Vérifie l'algorithme d'échange de clé associé à l'objet. |
| **int32_t** [get_KeySize](./get_keysize/)() override | Obtient la taille de clé utilisée par l'algorithme. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Obtient le tableau des tailles de clé autorisées. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Vérifie si la clé est persistée dans l'objet CSP. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | Vérifie si seule la clé publique est présente dans l'objet CSP. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Obtient l'algorithme de signature associé à l'objet CSP. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Vérifie si la clé persiste dans le magasin machine au lieu du magasin utilisateur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associé à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | Importe le blob contenant les informations sur la clé. Non implémenté. |
| void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) override | Importe les paramètres CSP. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | Constructeur. Utilise les paramètres par défaut. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Constructeur. Non implémenté. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [RSAParameters](../rsaparameters/)\&) | Constructeur. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**) | Constructeur. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Constructeur. Non implémenté. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Définit la taille de la clé. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | Définit si la clé est persistée dans l'objet CSP. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | Définit si la clé persiste dans le magasin machine au lieu du magasin utilisateur. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Calcule la signature de la valeur d'entrée spécifiée. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Calcule la signature de la valeur d'entrée spécifiée. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Calcule la signature de la valeur d'entrée spécifiée. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage et le remplissage spécifiés, puis signe le résultat. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Calcule la valeur de hachage du tableau de données spécifié en utilisant l'algorithme de hachage et le remplissage spécifiés, puis signe le résultat. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Calcule la valeur de hachage du flux binaire spécifié en utilisant l'algorithme de hachage et le remplissage spécifiés, puis signe le résultat. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | Calcule la signature pour la valeur de hachage spécifiée. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Calcule la signature de la valeur d'entrée spécifiée. Non implémenté. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| [String](../../system/string/) [ToXmlString](../rsa/toxmlstring/)(**bool**) override | Exporte tous les paramètres au format XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Vérifie la signature des données. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Vérifie que la signature des données spécifiées est valide. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Vérifie que la signature des données spécifiées est valide. |
| **bool** [VerifyData](../rsa/verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Vérifie que la signature du flux binaire spécifié est valide. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Vérifie la signature des données. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | Vérifie que la signature du hachage spécifié est valide. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [RSA](../rsa/)
* Classe [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)