---
title: SslStream
second_title: Aspose.Slides voor C++ API-referentie
description: Een stream die het SSL-protocol gebruikt om de server te authenticeren en optioneel de client.
type: docs
weight: 14
url: /nl/system.net.security/sslstream/
---
## SslStream klasse

Een stream die het SSL-protocol gebruikt om de server te authenticeren en optioneel de client.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Authenticeert de clientkant van de verbinding. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Authenticeert de clientkant van de verbinding. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initieert een asynchrone leesbewerking. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initieert een asynchrone leesbewerking. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initieert een asynchrone schrijfbewerking. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initieert een asynchrone schrijfbewerking. |
| void [Close](./close/)() override | Sluit de stream. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopieert bytes naar de opgegeven stream. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopieert bytes naar de opgegeven stream, met de opgegeven buffergrootte. |
| void [Dispose](./dispose/)(**bool**) override | Vrijgeeft alle resources die door het huidige object worden gebruikt en sluit de stream. |
| void [Dispose](../../system.io/stream/dispose/)() override | Vrijgeeft alle resources die door het huidige object worden gebruikt en sluit de stream. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Wacht totdat de opgegeven asynchrone leesbewerking is voltooid. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Wacht totdat de opgegeven asynchrone leesbewerking is voltooid. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Beëindigt een asynchrone schrijfbewerking. Wacht totdat de opgegeven asynchrone schrijfbewerking is voltooid. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Beëindigt een asynchrone schrijfbewerking. Wacht totdat de opgegeven asynchrone schrijfbewerking is voltooid. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert floating-point vergelijking in C#-stijl waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert floating-point vergelijking in C#-stijl waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [Flush](./flush/)() override | Leegt de buffers van deze stream en schrijft alle gebufferde gegevens naar de onderliggende opslag. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Wis asynchroon alle buffers voor deze stream, veroorzaakt dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Wis asynchroon alle buffers voor deze stream, veroorzaakt dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en bewaakt annuleringsverzoeken. |
| **bool** [get_CanRead](./get_canread/)() const override | Bepaalt of de stream leesbaar is. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Bepaalt of de stream zoeken ondersteunt. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Haalt een waarde op die bepaalt of de huidige stream een time-out kan hebben. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Bepaalt of de stream beschrijfbaar is. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Retourneert een waarde die aangeeft of de certificaat-revocatielijst wordt gecontroleerd tijdens het certificaatvalidatieproces. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Retourneert het versleutelingsalgoritme. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Retourneert de sterkte van het gebruikte versleutelingsalgoritme. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Retourneert het hash-algoritme. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Retourneert de sterkte van het gebruikte hash-algoritme. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Retourneert een waarde die aangeeft of authenticatie succesvol is geslaagd. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Retourneert een waarde die aangeeft of de met deze stream verzonden gegevens versleuteld zijn. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Retourneert een waarde die aangeeft of een server en een client geauthenticeerd zijn. |
| **bool** [get_IsServer](./get_isserver/)() const override | Retourneert een waarde die aangeeft of de lokale kant van de verbinding de server is. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Retourneert een waarde die aangeeft of de met deze stream verzonden gegevens ondertekend zijn. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Retourneert de sterkte van het gebruikte sleuteluitwisselingsalgoritme. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Retourneert de stream die wordt gebruikt door de huidige klasse-instanties voor het verzenden en ontvangen van gegevens. |
| **int64_t** [get_Length](./get_length/)() const override | Retourneert de lengte van de stream in bytes. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Retourneert het certificaat dat wordt gebruikt om het lokale eindpunt te authenticeren. |
| **int64_t** [get_Position](./get_position/)() const override | Retourneert de huidige positie van de stream. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Retourneert het certificaat dat wordt gebruikt om het externe eindpunt te authenticeren. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Retourneert het SSL-protocol. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Haalt een waarde op, in milliseconden, die bepaalt hoe lang de stream zal proberen te schrijven voordat er een time-out optreedt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-array. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Leest het opgegeven aantal bytes uit de stream en schrijft ze naar de opgegeven byte-span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Leest asynchroon een reeks bytes uit de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Leest asynchroon een reeks bytes uit de huidige stream, verplaatst de positie in de stream met het aantal gelezen bytes, en bewaakt annuleringsverzoeken. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Leest één byte van de stream en retourneert een 32-bit geheel getal dat gelijk is aan de waarde van de gelezen byte. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie-waarde-type-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Stelt de positie van de stream in die wordt vertegenwoordigd door het huidige object. |
| void [set_Position](./set_position/)(**int64_t**) override | Stelt de positie van de stream in. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Stelt een waarde in die bepaalt of de huidige stream een time-out kan hebben. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Stelt een waarde in die bepaalt of de huidige stream een time-out kan hebben. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Stelt een waarde in, in milliseconden, die bepaalt hoe lang de stream zal proberen te lezen voordat er een time-out optreedt. |
| void [SetLength](./setlength/)(**int64_t**) override | Stelt de lengte van de stream in die wordt vertegenwoordigd door het huidige object. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Construeert een nieuwe instantie. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Construeert een nieuwe instantie. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Construeert een nieuwe instantie. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Construeert een nieuwe instantie. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Construeert een nieuwe instantie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Schrijft de opgegeven byte-array naar de stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Schrijft de opgegeven byte-array naar de stream. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de stream. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-span naar de stream. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Schrijft de opgegeven onondertekende 8-bit integerwaarde naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Geeft alle interne datastructuren vrij. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Een stream zonder onderliggende opslag. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Type of AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Type of pointer to the implementation. |

## Zie ook

* Klasse [AuthenticatedStream](../authenticatedstream/)
* Namespace [System::Net::Security](../)
* Bibliotheek [Aspose.Slides](../../)