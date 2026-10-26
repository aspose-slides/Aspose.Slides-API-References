---
title: BasicSTDIStreamWrapper
second_title: Aspose.Slides pro C++ API Reference
description: "Představuje obal podobný System.IO.Stream pro std::basic_istream a jeho odvozené objekty. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu ukazatelem System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 14
url: /cs/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper třída

Representuje [System.IO.Stream](../stream/)-podobný obal pro std::basic_istream a jeho odvozené objekty. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo k selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání funkcím jako argument.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Metody

| Method | Description |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Vytvoří novou instanci [BasicSTDIStreamWrapper](./). |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | Kopírovací konstruktor. Smazán. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci zápisu. |
| virtual void [Close](../stream/close/)() | Zavře proud. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopíruje bajty do zadaného proudu. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopíruje bajty do zadaného proudu s použitím zadané velikosti vyrovnávací paměti. |
| void [Dispose](../stream/dispose/)() override | Uvolní všechny prostředky použité aktuálním objektem a zavře proud. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, až se dokončí zadaná asynchronní operace čtení. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončí asynchronní operaci zápisu. Čeká, až se dokončí zadaná asynchronní operace zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| void [Flush](./flush/)() override | Vyčistí vyrovnávací paměti tohoto proudu a zapíše všechna data z bufferu do podkladového úložiště. Nepodporováno! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vyprázdní všechny buffery tohoto proudu, způsobí, že se všechna data v bufferu zapíší do podkladového zařízení, a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynchronně vyprázdní všechny buffery tohoto proudu, způsobí, že se všechna data v bufferu zapíší do podkladového zařízení, a monitoruje žádosti o zrušení. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Určuje, zda proud podporuje posouvání. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Získá hodnotu, která určuje, zda může aktuální proud vypršet časovým limitem. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Určuje, zda proud podporuje zápis. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Vrací délku proudu. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Vrací aktuální pozici proudu. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho bude proud čekat na čtení, než vyprší časový limit. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho bude proud čekat na zápis, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání výrazu C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | Operátor přiřazení kopií. Smazán. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Operátor přiřazení kopií. Smazán. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Pokud je režim obalu binární, přečte ze streamu zadaný počet bajtů, jinak přečte zadaný počet znaků a převede je na typ **uint8_t**. Výsledek čtení zapíše do zadaného pole bajtů. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Přečte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Přečte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Přečte z proudu zadaný počet bajtů a zapíše je do zadaného rozsahu bajtů. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně čte sekvenci bajtů ze současného proudu, posune pozici v proudu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů ze současného proudu, posune pozici v proudu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| int [ReadByte](./readbyte/)() override | Pokud je režim obalu binární, přečte jeden bajt z úložiště posledního dekódovaného znaku, jinak přečte jeden znak z proudu a převede jej na typ **uint8_t**. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | Informace RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Nastaví pozici proudu reprezentovaného aktuálním objektem. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Nastaví pozici proudu. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Nastaví hodnotu, která určuje, zda může aktuální proud vypršet časovým limitem. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Nastaví hodnotu v milisekundách, která určuje, jak dlouho bude proud čekat na čtení, než vyprší časový limit. |
| void [SetLength](./setlength/)(**int64_t**) override | Nastaví délku proudu reprezentovaného aktuálním objektem. Nepodporováno! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopírovací konstruktor. Smazán. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokování výrazu C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Pokud je režim obalu binární, zapíše do proudu zadaný podrozsah bajtů ze zadaného pole bajtů, jinak převede zadaný podrozsah bajtů ze zadaného pole bajtů na typ char_type a pak zapíše výsledek do proudu. Nepodporováno! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do proudu. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do proudu. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše zadaný podrozsah bajtů ze zadaného rozsahu bajtů do proudu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapíše sekvenci bajtů do aktuálního proudu, posune aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapíše sekvenci bajtů do aktuálního proudu, posune aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Pokud je režim obalu binární, zapíše do proudu zadanou neoznačenou 8bitovou celočíselnou hodnotu, jinak ji převede na typ char_type a pak zapíše výsledek do proudu. Nepodporováno! |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Pole

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | Proud bez podkladového úložiště. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Viz také

* Třída [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)