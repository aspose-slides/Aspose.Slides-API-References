---
title: SslStream
second_title: Aspose.Slides pro C++ - reference API
description: Datový tok, který používá protokol SSL k autentizaci serveru a volitelně klienta.
type: docs
weight: 14
url: /cs/system.net.security/sslstream/
---
## SslStream třída

Datový tok, který používá protokol SSL k autentizaci serveru a volitelně klienta.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Autentizuje klientskou stranu připojení. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Autentizuje klientskou stranu připojení. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Spouští asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spouští asynchronní operaci čtení. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Spouští asynchronní operaci zápisu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spouští asynchronní operaci zápisu. |
| void [Close](./close/)() override | Uzavře datový tok. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopíruje bajty do určeného datového toku. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopíruje bajty do určeného datového toku s použitím určené velikosti bufferu. |
| void [Dispose](./dispose/)(**bool**) override | Uvolní všechny prostředky použité aktuálním objektem a uzavře datový tok. |
| void [Dispose](../../system.io/stream/dispose/)() override | Uvolní všechny prostředky použité aktuálním objektem a uzavře datový tok. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Čeká, dokud zadaná asynchronní operace čtení nedokončí. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud zadaná asynchronní operace čtení nedokončí. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Ukončí asynchronní operaci zápisu. Čeká, dokud zadaná asynchronní operace zápisu nedokončí. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončí asynchronní operaci zápisu. Čeká, dokud zadaná asynchronní operace zápisu nedokončí. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| void [Flush](./flush/)() override | Vymaže vyrovnávací paměti tohoto datového toku a zapíše všechna vyrovnaná data do podkladového úložiště. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vymaže všechny vyrovnávací paměti tohoto datového toku, způsobí zápis všech vyrovnaných dat do podkladového zařízení a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Asynchronně vymaže všechny vyrovnávací paměti tohoto datového toku, způsobí zápis všech vyrovnaných dat do podkladového zařízení a monitoruje požadavky na zrušení. |
| **bool** [get_CanRead](./get_canread/)() const override | Určuje, zda je datový tok čitelný. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Určuje, zda datový tok podporuje posouvání. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Získá hodnotu určující, zda může aktuální datový tok časově vypršet. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Určuje, zda je datový tok zapisovatelný. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Vrací hodnotu, která udává, zda je během procesu ověřování certifikátu kontrolován seznam odvolaných certifikátů. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Vrací šifrovací algoritmus. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Vrací sílu použitého šifrovacího algoritmu. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Vrací hash algoritmus. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Vrací sílu použitého hash algoritmu. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Vrací hodnotu, která udává, zda byla autentizace úspěšně provedena. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Vrací hodnotu, která udává, zda jsou data odeslaná pomocí tohoto datového toku šifrována. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Vrací hodnotu, která udává, zda jsou server a klient autentizováni. |
| **bool** [get_IsServer](./get_isserver/)() const override | Vrací hodnotu, která udává, zda je lokální strana připojení serverem. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Vrací hodnotu, která udává, zda jsou data odeslaná pomocí tohoto datového toku podepsána. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Vrací sílu použitého algoritmu výměny klíčů. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Vrací datový tok, který je používán aktuálními instancemi třídy pro odesílání a přijímání dat. |
| **int64_t** [get_Length](./get_length/)() const override | Vrací délku datového toku v bajtech. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Vrací certifikát používaný k autentizaci lokálního koncového bodu. |
| **int64_t** [get_Position](./get_position/)() const override | Vrací aktuální pozici datového toku. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Získá hodnotu v milisekundách, která určuje, jak dlouho se datový tok bude snažit číst, než vyprší časový limit. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Vrací certifikát používaný k autentizaci vzdáleného koncového bodu. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Vrací protokol SSL. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Získá hodnotu v milisekundách, která určuje, jak dlouho se datový tok bude snažit zapisovat, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# metody [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje uzamčení pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# metody [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte určený počet bajtů z datového toku a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte určený počet bajtů z datového toku a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Čte určený počet bajtů z datového toku a zapisuje je do určeného pole bajtů. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Čte určený počet bajtů z datového toku a zapisuje je do určeného rozsahu bajtů (byte span). |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně čte sekvenci bajtů z aktuálního datového toku, posune pozici v proudu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů z aktuálního datového toku, posune pozici v proudu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Přečte jeden bajt z datového toku a vrátí 32-bitové celočíselné hodnoty odpovídající hodnotě přečteného bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Nastaví pozici datového toku reprezentovaného aktuálním objektem. |
| void [set_Position](./set_position/)(**int64_t**) override | Nastaví pozici datového toku. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Nastaví hodnotu, která určuje, zda může aktuální datový tok časově vypršet. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Nastaví hodnotu, která určuje, zda může aktuální datový tok časově vypršet. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Nastaví hodnotu v milisekundách, která určuje, jak dlouho se datový tok bude snažit číst, než vyprší časový limit. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Nastaví hodnotu v milisekundách, která určuje, jak dlouho se datový tok bude snažit číst, než vyprší časový limit. |
| void [SetLength](./setlength/)(**int64_t**) override | Nastaví délku datového toku reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Vytvoří novou instanci. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Vytvoří novou instanci. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Vytvoří novou instanci. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Vytvoří novou instanci. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Vytvoří novou instanci. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# metody [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Zapíše určené pole bajtů do datového toku. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše určený podrozsah bajtů z určeného pole bajtů do datového toku. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Zapíše určené pole bajtů do datového toku. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše určený podrozsah bajtů z určeného pole bajtů do datového toku. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z určeného pole bajtů do datového toku. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše určený podrozsah bajtů z určeného rozsahu bajtů (byte span) do datového toku. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapíše sekvenci bajtů do aktuálního datového toku, posune aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapíše sekvenci bajtů do aktuálního datového toku, posune aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Zapíše určenou nezápornou 8-bitovou celočíselnou hodnotu do datového toku. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Datový tok bez podkladového úložiště. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Typ AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Typ ukazatele na implementaci. |

## Viz také

* Třída [AuthenticatedStream](../authenticatedstream/)
* Jmenný prostor [System::Net::Security](../)
* Knihovna [Aspose.Slides](../../)