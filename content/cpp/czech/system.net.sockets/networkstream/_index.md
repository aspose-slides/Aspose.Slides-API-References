---
title: NetworkStream
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Poskytuje podkladový proud dat pro síťový přístup. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo k selháním assercí. Vždy tuto třídu zabalte do ukazatele System::SmartPtr a tento ukazatel používejte k předávání jako argument funkcím."
type: docs
weight: 40
url: /cs/system.net.sockets/networkstream/
---
## NetworkStream třída

Provides the underlying stream of the data for the network access. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NetworkStream : public System::IO::Stream
```

## Metody

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicializuje asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci čtení. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Inicializuje asynchronní operaci zápisu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci zápisu. |
| void [Close](./close/)(int) | Uzavře aktuální instanci po uplynutí zadaného času. |
| virtual void [Close](../../system.io/stream/close/)() | Uzavře proud. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopíruje bajty do určeného proudu. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopíruje bajty do určeného proudu pomocí zadané velikosti vyrovnávací paměti. |
| void [Dispose](../../system.io/stream/dispose/)() override | Uvolní všechny prostředky používané aktuálním objektem a uzavře proud. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Čeká, dokud nedokončí zadanou asynchronní operaci čtení. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí zadanou asynchronní operaci čtení. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Ukončí asynchronní operaci zápisu. Čeká, dokud nedokončí zadanou asynchronní operaci zápisu. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončí asynchronní operaci zápisu. Čeká, dokud nedokončí zadanou asynchronní operaci zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| void [Flush](./flush/)() override | Vyčistí vyrovnávací paměť tohoto proudu a zapíše všechna data v bufferu do podkladového úložiště. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vyčistí všechny buffery pro tento proud, způsobí, že se veškerá bufferovaná data zapíšou do podkladového zařízení, a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Asynchronně vyčistí všechny buffery pro tento proud, způsobí, že se veškerá bufferovaná data zapíšou do podkladového zařízení, a monitoruje žádosti o zrušení. |
| **bool** [get_CanRead](./get_canread/)() const override | Určuje, zda lze proud číst. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Určuje, zda proud podporuje posouvání. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Získá hodnotu určující, zda může aktuální proud časově vypršet. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Určuje, zda lze do proudu zapisovat. |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | Vrací hodnotu, která indikuje, zda jsou k dispozici data ke čtení. |
| **int64_t** [get_Length](./get_length/)() const override | Vrací délku proudu v bajtech. |
| **int64_t** [get_Position](./get_position/)() const override | Vrací aktuální pozici proudu. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Získá hodnotu v milisekundách, která určuje, jak dlouho se proud bude pokoušet číst před časovým vypršením. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | Získá podkladový [Socket](../socket/). |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Získá hodnotu v milisekundách, která určuje, jak dlouho se proud bude pokoušet zapisovat před časovým vypršením. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí přidruženou k objektu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | Vytvoří novou instanci. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | Vytvoří novou instanci. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | Vytvoří novou instanci. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Načte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Načte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Načte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Načte z proudu zadaný počet bajtů a zapíše je do zadaného bytového spanu. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně načte sekvenci bajtů z aktuálního proudu, posune pozici v proudu o počet načtených bajtů a monitoruje žádosti o zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně načte sekvenci bajtů z aktuálního proudu, posune pozici v proudu o počet načtených bajtů a monitoruje žádosti o zrušení. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Načte jediný bajt z proudu a vrátí 32bitovou celočíselnou hodnotu odpovídající načtenému bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Nastaví pozici proudu reprezentovaného aktuálním objektem. |
| void [set_Position](./set_position/)(**int64_t**) override | Nastaví pozici proudu. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Nastaví hodnotu určující, zda může aktuální proud časově vypršet. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Nastaví hodnotu určující, zda může aktuální proud časově vypršet. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Nastaví hodnotu v milisekundách, která určuje, jak dlouho se proud bude pokoušet číst před časovým vypršením. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Nastaví hodnotu v milisekundách, která určuje, jak dlouho se proud bude pokoušet číst před časovým vypršením. |
| void [SetLength](./setlength/)(**int64_t**) override | Nastaví délku proudu reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do proudu. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do proudu. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do proudu. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše zadaný podrozsah bajtů ze zadaného bytového spanu do proudu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapíše sekvenci bajtů do aktuálního proudu, posune aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapíše sekvenci bajtů do aktuálního proudu, posune aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Zapíše zadanou nepodepsanou 8bitovou celočíselnou hodnotu do proudu. |
| virtual  [~NetworkStream](./~networkstream/)() | Zničí aktuální instanci. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Proud bez podkladového úložiště. |

## Viz také

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)