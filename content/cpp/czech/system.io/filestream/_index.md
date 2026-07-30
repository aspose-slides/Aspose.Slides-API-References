---
title: FileStream
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Zastupuje souborový proud podporující synchronní i asynchronní operace čtení a zápisu. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy tuto třídu zabalte do ukazatele System::SmartPtr a tento ukazatel použijte při předávání jako argument funkcím."
type: docs
weight: 287
url: /cs/system.io/filestream/
---
## FileStream třída


Represents a file stream supporting synchronous and asynchronous read and write operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileStream : public System::IO::Stream
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spouští asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spouští asynchronní operaci zápisu. |
| void [Close](./close/)() override | Uzavře aktuální [FileStream](./) objekt. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopíruje bajty do určeného proudu. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopíruje bajty do určeného proudu s použitím určené velikosti bufferu. |
| void [Dispose](../stream/dispose/)() override | Uvolní veškeré prostředky použité aktuálním objektem a uzavře proud. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí zadaná asynchronní operace čtení. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončí asynchronní operaci zápisu. Čeká, dokud nedokončí zadaná asynchronní operace zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání v plovoucí řádové čárce ve stylu C#, kde jsou dva NaN považovány za rovné, přestože podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání v plovoucí řádové čárce ve stylu C#, kde jsou dva NaN považovány za rovné, přestože podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Vytvoří novou instanci třídy [FileStream](./) a inicializuje ji zadanými parametry. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | Vytvoří novou instanci třídy [FileStream](./) a inicializuje ji zadanými parametry. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | Vytvoří novou instanci třídy [FileStream](./) a inicializuje ji zadanými parametry. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | Vyčistí buffery tohoto proudu a zapíše všechna bufferovaná data do podkladového souboru. |
| void [Flush](./flush/)(**bool**) | Vyčistí buffery tohoto proudu a zapíše všechna bufferovaná data do podkladového souboru. Synonymum pro metodu [Flush()](./flush/). |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Asynchronně vyčistí všechny buffery pro tento proud, způsobí zápis všech bufferovaných dat do podkladového zařízení a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynchronně vyčistí všechny buffery pro tento proud, způsobí zápis všech bufferovaných dat do podkladového zařízení a monitoruje žádosti o zrušení. |
| **bool** [get_CanRead](./get_canread/)() const override | Určuje, zda je proud čitelný. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Určuje, zda proud podporuje hledání. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Získá hodnotu určující, zda může aktuální proud vypršet časovým limitem. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Určuje, zda je proud zapisovatelný. |
| **int64_t** [get_Length](./get_length/)() const override | Vrací délku proudu v bajtech. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Vrací název souboru zapouzdřeného aktuálním objektem [FileStream](./). |
| **int64_t** [get_Position](./get_position/)() const override | Vrací aktuální pozici proudu. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho bude proud zkoušet číst, než vyprší časový limit. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho bude proud zkoušet zapisovat, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte určený počet bajtů z proudu a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte určený počet bajtů z proudu a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Čte určený počet bajtů z proudu a zapisuje je do určeného pole bajtů. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Čte určený počet bajtů z proudu a zapisuje je do určeného rozsahu bajtů. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Asynchronně čte sekvenci bajtů z aktuálního proudu, posouvá pozici v proudu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů z aktuálního proudu, posouvá pozici v proudu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| **int32_t** [ReadByte](./readbyte/)() override | Čte jediný bajt z proudu a vrací 32-bitovou celočíselnou hodnotu odpovídající hodnotě přečteného bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Nastaví pozici proudu reprezentovaného aktuálním objektem. |
| void [set_Position](./set_position/)(**int64_t**) override | Vyprázdní proud a poté nastaví jeho pozici. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Nastaví hodnotu určující, zda může aktuální proud vypršet časovým limitem. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Nastaví hodnotu v milisekundách, která určuje, jak dlouho bude proud zkoušet číst, než vyprší časový limit. |
| void [SetLength](./setlength/)(**int64_t**) override | Nastaví délku proudu reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše určený podrozsah bajtů z určeného pole bajtů do proudu. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše určený podrozsah bajtů z určeného pole bajtů do proudu. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z určeného pole bajtů do proudu. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše určený podrozsah bajtů z určeného rozsahu bajtů do proudu. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Asynchronně zapisuje sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapisuje sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Zapisuje určenou bez znaménka 8-bitovou celočíselnou hodnotu do proudu. |
|  [~FileStream](./~filestream/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Výchozí hodnota počtu bajtů bufferovaných během operací čtení a zápisu. |
| static [Null](../stream/null/) | Proud bez podkladového úložiště. |

## Viz také

* Třída [Stream](../stream/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)