---
title: SslStream
second_title: Référence de l'API Aspose.Slides pour C++
description: Un flux qui utilise le protocole SSL pour authentifier le serveur et, éventuellement, le client.
type: docs
weight: 14
url: /fr/system.net.security/sslstream/
---
## SslStream classe


Un flux qui utilise le protocole SSL pour authentifier le serveur et éventuellement le client.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Authentifie le côté client de la connexion. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Authentifie le côté client de la connexion. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initie une opération de lecture asynchrone. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initie une opération de lecture asynchrone. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initie une opération d'écriture asynchrone. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initie une opération d'écriture asynchrone. |
| void [Close](./close/)() override | Ferme le flux. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Copie les octets vers le flux spécifié. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Copie les octets vers le flux spécifié, en utilisant la taille de tampon spécifiée. |
| void [Dispose](./dispose/)(**bool**) override | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux. |
| void [Dispose](../../system.io/stream/dispose/)() override | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Attend que l'opération de lecture asynchrone spécifiée se termine. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Attend que l'opération de lecture asynchrone spécifiée se termine. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Termine une opération d'écriture asynchrone. Attend que l'opération d'écriture asynchrone spécifiée se termine. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Termine une opération d'écriture asynchrone. Attend que l'opération d'écriture asynchrone spécifiée se termine. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| void [Flush](./flush/)() override | Efface les tampons de ce flux et écrit toutes les données tamponnées dans le stockage sous-jacent. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Efface de manière asynchrone tous les tampons de ce flux, force l'écriture de toutes les données tamponnées dans le périphérique sous-jacent et surveille les demandes d'annulation. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Efface de manière asynchrone tous les tampons de ce flux, force l'écriture de toutes les données tamponnées dans le périphérique sous-jacent et surveille les demandes d'annulation. |
| **bool** [get_CanRead](./get_canread/)() const override | Détermine si le flux est lisible. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Détermine si le flux prend en charge la recherche. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Obtient une valeur qui détermine si le flux actuel peut expirer. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Détermine si le flux est inscriptible. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Renvoie une valeur indiquant si la liste de révocation des certificats est vérifiée pendant le processus de validation du certificat. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Renvoie l'algorithme de chiffrement. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Renvoie la force de l'algorithme de chiffrement utilisé. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Renvoie l'algorithme de hachage. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Renvoie la force de l'algorithme de hachage utilisé. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Renvoie une valeur indiquant si l'authentification est réussie. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Renvoie une valeur indiquant si les données envoyées via ce flux sont chiffrées. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Renvoie une valeur indiquant si un serveur et un client sont authentifiés. |
| **bool** [get_IsServer](./get_isserver/)() const override | Renvoie une valeur indiquant si le côté local de la connexion est le serveur. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Renvoie une valeur indiquant si les données envoyées via ce flux sont signées. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Renvoie la force de l'algorithme d'échange de clés utilisé. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Renvoie le flux utilisé par les instances actuelles de la classe pour l'envoi et la réception de données. |
| **int64_t** [get_Length](./get_length/)() const override | Renvoie la longueur du flux en octets. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Renvoie le certificat utilisé pour authentifier le point de terminaison local. |
| **int64_t** [get_Position](./get_position/)() const override | Renvoie la position actuelle du flux. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Obtient une valeur, en millisecondes, qui détermine la durée pendant laquelle le flux tentera de lire avant d'expirer. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Renvoie le certificat utilisé pour authentifier le point de terminaison distant. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Renvoie le protocole SSL. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Obtient une valeur, en millisecondes, qui détermine la durée pendant laquelle le flux tentera d'écrire avant d'expirer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'assignation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lit le nombre spécifié d'octets du flux et les écrit dans le tableau d'octets spécifié. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lit le nombre spécifié d'octets du flux et les écrit dans la tranche d'octets spécifiée. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lit de façon asynchrone une séquence d'octets du flux actuel, avance la position dans le flux du nombre d'octets lus et surveille les demandes d'annulation. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lit de façon asynchrone une séquence d'octets du flux actuel, avance la position dans le flux du nombre d'octets lus et surveille les demandes d'annulation. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Lit un seul octet du flux et renvoie une valeur entière 32 bits équivalente à la valeur de l'octet lu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Définit la position du flux représenté par l'objet actuel. |
| void [set_Position](./set_position/)(**int64_t**) override | Définit la position du flux. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Définit une valeur qui détermine si le flux actuel peut expirer. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Définit une valeur qui détermine si le flux actuel peut expirer. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Définit une valeur, en millisecondes, qui détermine la durée pendant laquelle le flux tentera de lire avant d'expirer. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Définit une valeur, en millisecondes, qui détermine la durée pendant laquelle le flux tentera de lire avant d'expirer. |
| void [SetLength](./setlength/)(**int64_t**) override | Définit la longueur du flux représenté par l'objet actuel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définir le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Construit une nouvelle instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Construit une nouvelle instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Construit une nouvelle instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Construit une nouvelle instance. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Construit une nouvelle instance. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Écrit le tableau d'octets spécifié dans le flux. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Écrit la sous-portion spécifiée d'octets du tableau d'octets spécifié dans le flux. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Écrit le tableau d'octets spécifié dans le flux. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Écrit la sous-portion spécifiée d'octets du tableau d'octets spécifié dans le flux. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Écrit la sous-portion spécifiée d'octets du tableau d'octets spécifié dans le flux. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Écrit la sous-portion spécifiée d'octets de la tranche d'octets spécifiée dans le flux. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Écrit de façon asynchrone une séquence d'octets dans le flux actuel, avance la position actuelle dans ce flux du nombre d'octets écrits et surveille les demandes d'annulation. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Écrit de façon asynchrone une séquence d'octets dans le flux actuel, avance la position actuelle dans ce flux du nombre d'octets écrits et surveille les demandes d'annulation. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Écrit la valeur entière non signée de 8 bits spécifiée dans le flux. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Champs

| Champ | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Un flux sans stockage sous-jacent. |

## Alias de type

| Alias de type | Description |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Type de AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Type de pointeur vers l'implémentation. |

## Voir aussi

* Classe [AuthenticatedStream](../authenticatedstream/)
* Espace de noms [System::Net::Security](../)
* Bibliothèque [Aspose.Slides](../../)