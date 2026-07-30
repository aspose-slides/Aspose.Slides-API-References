---
title: STDIOStreamWrapperBase
second_title: Aspose.Slides pro C++ API Reference
description: "Representuje základní třídu pro obaly podobné System.IO.Stream. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání funkcím jako argument."
type: docs
weight: 352
url: /cs/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase třída


Representuje základní třídu pro [System.IO.Stream](../stream/)-like obaly. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to může vést k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání funkcím jako argument.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Metody

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spustí asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spustí asynchronní operaci zápisu. |
| virtual void [Close](../stream/close/)() | Uzavře stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopíruje bajty do určeného streamu. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopíruje bajty do určeného streamu s použitím zadané velikosti vyrovnávací paměti. |
| void [Dispose](../stream/dispose/)() override | Uvolní všechny zdroje používané aktuálním objektem a uzavře stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, až dokončí zadanou asynchronní operaci čtení. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončí asynchronní operaci zápisu. Čeká, až dokončí zadanou asynchronní operaci zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje C#-styl porovnání floating point, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje C#-styl porovnání floating point, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual void [Flush](../stream/flush/)() | Vyprázdní vyrovnávací paměti tohoto streamu a zapíše všechna bufferovaná data do podkladového úložiště. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vyprázdní všechny vyrovnávací paměti tohoto streamu, způsobí zápis všech bufferovaných dat do podkladového zařízení a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynchronně vyprázdní všechny vyrovnávací paměti tohoto streamu, způsobí zápis všech bufferovaných dat do podkladového zařízení a monitoruje požadavky na zrušení. |
| **bool** [get_CanRead](./get_canread/)() const override | Určuje, zda stream podporuje čtení. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Určuje, zda stream podporuje posun. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Získá hodnotu určující, zda může aktuální stream vypršet časový limit. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Určuje, zda stream podporuje zápis. |
| **int64_t** [get_Length](./get_length/)() const override | Vrací délku streamu. |
| **int64_t** [get_Position](./get_position/)() const override | Vrací aktuální pozici streamu. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit číst, než vyprší časový limit. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit zapisovat, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače přidruženou k objektu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# výrazu lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožní kopírování podtříd. |
| [STDIOStreamWrapperBase](./)\& [operator=](./operator_equal/)(const [STDIOStreamWrapperBase](./)\&) | Operátor přiřazení kopií. Smazáno. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožní kopírování podtříd. |
| virtual **int32_t** [Read](../stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Přečte z streamu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| virtual **int32_t** [Read](../stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Přečte z streamu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Přečte z streamu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Přečte z streamu zadaný počet bajtů a zapíše je do zadaného byte span. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně přečte sekvenci bajtů z aktuálního streamu, posune pozici ve streamu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně přečte sekvenci bajtů z aktuálního streamu, posune pozici ve streamu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| virtual int [ReadByte](../stream/readbyte/)() | Přečte jeden bajt ze streamu a vrátí 32bitovou celočíselnou hodnotu odpovídající hodnotě přečteného bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/)) | Informace RTTI. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Nastaví pozici streamu reprezentovaného aktuálním objektem. |
| void [set_Position](./set_position/)(**int64_t**) override | Nastaví pozici streamu. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Nastaví hodnotu určující, zda může aktuální stream vypršet časový limit. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Nastaví hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit číst, než vyprší časový limit. |
| virtual void [SetLength](../stream/setlength/)(**int64_t**) | Nastaví délku streamu reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech na slabý režim. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](./)\&) | Kopírovací konstruktor. Smazáno. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# výrazu lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [Write](../stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z daného pole bajtů do streamu. |
| virtual void [Write](../stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z daného pole bajtů do streamu. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z daného pole bajtů do streamu. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše určený podrozsah bajtů ze zadaného byte span do streamu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapíše sekvenci bajtů do aktuálního streamu, posune aktuální pozici v tomto streamu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapíše sekvenci bajtů do aktuálního streamu, posune aktuální pozici v tomto streamu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Zapíše zadanou neznačenou 8-bitovou celočíselnou hodnotu do streamu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Pole

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | Stream bez podkladového úložiště. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Viz také

* Třída [Stream](../stream/)
* jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)