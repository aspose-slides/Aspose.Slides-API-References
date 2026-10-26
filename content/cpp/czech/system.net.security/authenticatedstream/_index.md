---
title: AuthenticatedStream
second_title: Aspose.Slides pro C++ – referenční příručka
description: "Obsahuje metody pro předávání přihlašovacích údajů přes proud. Objektům této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 1
url: /cs/system.net.security/authenticatedstream/
---
## AuthenticatedStream třída


Obsahuje metody pro předávání přihlašovacích údajů přes proud. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci zápisu. |
| virtual void [Close](../../system.io/stream/close/)() | Uzavře proud. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Zkopíruje bajty do určeného proudu. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Zkopíruje bajty do určeného proudu, používá určenou velikost vyrovnávací paměti. |
| void [Dispose](../../system.io/stream/dispose/)() override | Uvolní všechny prostředky používané aktuálním objektem a uzavře proud. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud se nedokončí určená asynchronní operace čtení. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončí asynchronní operaci zápisu. Čeká, dokud se nedokončí určená asynchronní operace zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual void [Flush](../../system.io/stream/flush/)() | Vyprázdní vyrovnávací paměti tohoto proudu a zapíše všechna bufferovaná data do podkladového úložiště. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vyprázdní všechny vyrovnávací paměti tohoto proudu, způsobí zápis všech bufferovaných dat do podkladového zařízení a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Asynchronně vyprázdní všechny vyrovnávací paměti tohoto proudu, způsobí zápis všech bufferovaných dat do podkladového zařízení a monitoruje požadavky na zrušení. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | Určuje, zda je proud čitelný. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | Určuje, zda proud podporuje posouvání. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Získá hodnotu, která určuje, zda může aktuální proud vypršet časovým limitem. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | Určuje, zda je proud zapisovatelný. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | Vrací hodnotu, která indikuje, zda bylo ověření úspěšně předáno. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | Vrací hodnotu, která indikuje, zda jsou data odeslaná tímto proudem šifrována. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Vrací hodnotu, která indikuje, zda jsou server a klient ověřeni. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | Vrací hodnotu, která indikuje, zda je místní strana spojení server. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | Vrací hodnotu, která indikuje, zda jsou data odeslaná tímto proudem podepsána. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Vrací proud, který je používán aktuálními instancemi třídy pro odesílání a přijímání dat. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | Vrací délku proudu v bajtech. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | Vrací aktuální pozici proudu. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se proud bude snažit číst, než vyprší časový limit. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se proud bude snažit zapisovat, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analoga volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analoga operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt hlídkáře [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Čte z proudu zadaný počet bajtů a zapisuje je do určeného pole bajtů. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Čte z proudu zadaný počet bajtů a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Čte z proudu zadaný počet bajtů a zapisuje je do určeného pole bajtů. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Čte z proudu zadaný počet bajtů a zapisuje je do určeného úseku bajtů. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně čte sekvenci bajtů z aktuálního proudu, posouvá pozici v proudu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů z aktuálního proudu, posouvá pozici v proudu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Čte jeden bajt z proudu a vrátí 32-bitovou celočíselnou hodnotu odpovídající hodnotě přečteného bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt typu hodnoty s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje čítač sdílených referencí o zadanou hodnotu. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | Nastavuje pozici proudu reprezentovaného aktuálním objektem. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | Nastavuje pozici proudu. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Nastavuje hodnotu, která určuje, zda může aktuální proud vypršet časovým limitem. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Nastavuje hodnotu v milisekundách, která určuje, jak dlouho se proud bude snažit číst, než vyprší časový limit. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | Nastavuje délku proudu reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (místo sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu čítače sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje čítač sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací čítač sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje konverzi vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt hlídkáře [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje čítač slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje čítač slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah bajtů z určeného pole bajtů do proudu. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah bajtů z určeného pole bajtů do proudu. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah bajtů z určeného pole bajtů do proudu. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše zadaný podrozsah bajtů z určeného úseku bajtů do proudu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapíše sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapíše sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Zapíše zadanou nepodepsanou 8-bitovou celočíselnou hodnotu do proudu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Proud bez podkladového úložiště. |

## Viz také

* Třída [Stream](../../system.io/stream/)
* Jmenný prostor [System::Net::Security](../)
* Knihovna [Aspose.Slides](../../)