---
title: SslStream
second_title: Aspose.Slides för C++ API-referens
description: En ström som använder SSL-protokollet för att autentisera servern och eventuellt klienten.
type: docs
weight: 14
url: /sv/system.net.security/sslstream/
---
## SslStream-klass


En ström som använder SSL-protokollet för att autentisera servern och eventuellt klienten.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Metoder

| Method | Description |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Autentiserar klient-sidan av anslutningen. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Autentiserar klient-sidan av anslutningen. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initierar en asynkron läsoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron läsoperation. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Initierar en asynkron skrivoperation. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initierar en asynkron skrivoperation. |
| void [Close](./close/)() override | Stänger strömmen. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopierar byte till den angivna strömmen. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopierar byte till den angivna strömmen med angiven buffertstorlek. |
| void [Dispose](./dispose/)(**bool**) override | Frigir alla resurser som används av det aktuella objektet och stänger strömmen. |
| void [Dispose](../../system.io/stream/dispose/)() override | Frigir alla resurser som används av det aktuella objektet och stänger strömmen. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Väntar tills den angivna asynkrona läsoperationen är klar. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Väntar tills den angivna asynkrona läsoperationen är klar. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen är klar. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Avslutar en asynkron skrivoperation. Väntar tills den angivna asynkrona skrivoperationen är klar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| void [Flush](./flush/)() override | Rensar denna ströms buffertar och skriver all buffrad data till den underliggande lagringen. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbrytningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbrytningsförfrågningar. |
| **bool** [get_CanRead](./get_canread/)() const override | Bestämmer om strömmen är läsbar. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Bestämmer om strömmen stöder sökning. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Hämtar ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Bestämmer om strömmen är skrivbar. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Returnerar ett värde som indikerar om certifikatåterkallningslistan kontrolleras under certifikatvalideringsprocessen. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Returnerar krypteringsalgoritmen. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Returnerar styrkan för den använda krypteringsalgoritmen. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Returnerar hash-algoritmen. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Returnerar styrkan för den använda hash-algoritmen. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Returnerar ett värde som indikerar om autentiseringen har passerat framgångsrikt. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Returnerar ett värde som indikerar om data som skickas med denna ström är krypterad. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Returnerar ett värde som indikerar om en server och en klient är autentiserade. |
| **bool** [get_IsServer](./get_isserver/)() const override | Returnerar ett värde som indikerar om den lokala sidan av anslutningen är servern. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Returnerar ett värde som indikerar om data som skickas med denna ström är signerad. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Returnerar styrkan för den använda nyckelutbytesalgoritmen. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Returnerar strömmen som används av de aktuella klassinstanserna för att skicka och ta emot data. |
| **int64_t** [get_Length](./get_length/)() const override | Returnerar strömmens längd i byte. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Returnerar certifikatet som används för att autentisera den lokala slutpunkten. |
| **int64_t** [get_Position](./get_position/)() const override | Returnerar den aktuella positionen i strömmen. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka läsa innan den får en tidsgräns. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Returnerar certifikatet som används för att autentisera fjärrslutpunkten. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Returnerar SSL-protokollet. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Hämtar ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka skriva innan den får en tidsgräns. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentryobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Konstrukterar en ny instans. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Läser det angivna antalet byte från strömmen och skriver dem till det angivna byte-spanet. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Läser asynkront en sekvens av byte från den aktuella strömmen, flyttar positionen i strömmen med antalet lästa byte och övervakar avbrytningsförfrågningar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Läser asynkront en sekvens av byte från den aktuella strömmen, flyttar positionen i strömmen med antalet lästa byte och övervakar avbrytningsförfrågningar. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Läser en enda byte från strömmen och returnerar ett 32-bitars heltalsvärde som motsvarar värdet på den lästa byten. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenräknare med det angivna värdet. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| void [set_Position](./set_position/)(**int64_t**) override | Ställer in strömmens position. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Ställer in ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Ställer in ett värde som bestämmer om den aktuella strömmen kan tidsgränsas. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Ställer in ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka läsa innan den får en tidsgräns. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Ställer in ett värde i millisekunder som bestämmer hur länge strömmen kommer att försöka läsa innan den får en tidsgräns. |
| void [SetLength](./setlength/)(**int64_t**) override | Ställer in längden på den ström som representeras av det aktuella objektet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för en delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referenräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Konstrukterar en ny instans. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Konstrukterar en ny instans. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Konstrukterar en ny instans. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Konstrukterar en ny instans. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Konstrukterar en ny instans. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentryobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Skriver den angivna byte-arrayen till strömmen. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Skriver den angivna byte-arrayen till strömmen. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Skriver det angivna delintervallet av byte från den angivna byte-arrayen till strömmen. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Skriver det angivna delintervallet av byte från det angivna byte-spanet till strömmen. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Skriver asynkront en sekvens av byte till den aktuella strömmen, flyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbrytningsförfrågningar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Skriver asynkront en sekvens av byte till den aktuella strömmen, flyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbrytningsförfrågningar. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Skriver det angivna osignerade 8-bitars heltalsvärdet till strömmen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | En ström utan underliggande lagring. |

## Typdefinitioner

| Typedef | Description |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Typ av AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Typ av pekare till implementationen. |

## Se även

* Klass [AuthenticatedStream](../authenticatedstream/)
* Namnrymd [System::Net::Security](../)
* Bibliotek [Aspose.Slides](../../)