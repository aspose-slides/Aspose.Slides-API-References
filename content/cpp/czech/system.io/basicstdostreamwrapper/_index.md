---
title: BasicSTDOStreamWrapper
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Reprezentuje obal podobný System.IO.Stream pro std::basic_ostream a jeho odvozené objekty. Objektům této třídy by se mělo alokovat pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to způsobí chyby za běhu a/nebo selhání asercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 27
url: /cs/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper třída

Reprezentuje obal podobný [System.IO.Stream](../stream/) pro std::basic_ostream a jeho odvozené objekty. Objektům této třídy by se mělo alokovat pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Vytvoří novou instanci [BasicSTDOStreamWrapper](./). |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | Kopírovací konstruktor. Odstraněn. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Zahajuje asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Zahajuje asynchronní operaci zápisu. |
| virtual void [Close](../stream/close/)() | Uzavírá stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopíruje bajty do zadaného streamu. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopíruje bajty do zadaného streamu s použitím určené velikosti bufferu. |
| void [Dispose](../stream/dispose/)() override | Uvolňuje všechny zdroje použité aktuálním objektem a uzavírá stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedojde k dokončení zadané asynchronní operace čtení. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončuje asynchronní operaci zápisu. Čeká, dokud nedojde k dokončení zadané asynchronní operace zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| void [Flush](./flush/)() override | Vyčistí buffer tohoto streamu a zapíše všechna buforovaná data do podkladového úložiště. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vyčistí všechny buffery tohoto streamu, způsobí, že se všechna buforovaná data zapíší do podkladového zařízení, a sleduje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynchronně vyčistí všechny buffery tohoto streamu, způsobí, že se všechna buforovaná data zapíší do podkladového zařízení, a sleduje požadavky na zrušení. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | Určuje, zda stream podporuje čtení. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Určuje, zda stream podporuje posun. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Získá hodnotu určující, zda může současný stream časově vypršet. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Vrací délku streamu. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Vrací aktuální pozici streamu. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Získá hodnotu v milisekundách určující, jak dlouho se bude stream snažit číst, než vyprší časový limit. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Získá hodnotu v milisekundách určující, jak dlouho se bude stream snažit zapisovat, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# metody [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# příkazem lock(). Volat přímo nebo použít hlídkový objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# metody [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | Operátor přiřazení kopií. Odstraněn. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Operátor přiřazení kopií. Odstraněn. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Pokud je režim zabalení binární, čte z streamu zadaný počet bajtů, jinak čte zadaný počet znaků a převádí je na typ **uint8_t**. Výsledek čtení zapíše do zadaného pole bajtů. Nepodporováno! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte z streamu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Čte z streamu zadaný počet bajtů a zapíše je do zadaného pole bajtů. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Čte z streamu zadaný počet bajtů a zapíše je do zadaného rozsahu bajtů. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a sleduje požadavky na zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a sleduje požadavky na zrušení. |
| int [ReadByte](./readbyte/)() override | Pokud je režim zabalení binární, přečte jeden bajt z úložiště posledního dekódovaného znaku, jinak přečte jeden znak ze streamu a převede jej na typ **uint8_t**. Nepodporováno! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle odkazu. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle odkazu. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | Informace RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Nastaví pozici streamu reprezentovaného aktuálním objektem. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Nastaví pozici streamu. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Nastaví hodnotu určující, zda může současný stream časově vypršet. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Nastaví hodnotu v milisekundách určující, jak dlouho se bude stream snažit číst, než vyprší časový limit. |
| void [SetLength](./setlength/)(**int64_t**) override | Nastaví délku streamu reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopírovací konstruktor. Odstraněn. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# metody [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání C# výrazu lock(). Zavolejte přímo nebo použijte hlídkový objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Pokud je režim zabalení binární, zapíše do streamu zadaný podrozsah bajtů ze zadaného pole bajtů, jinak převádí zadaný podrozsah bajtů ze zadaného pole bajtů na typ char_type a poté zapíše výsledek do streamu. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do streamu. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do streamu. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše zadaný podrozsah bajtů ze zadaného rozsahu bajtů do streamu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapíše sekvenci bajtů do aktuálního streamu, posune aktuální pozici v tomto streamu o počet zapsaných bajtů a sleduje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapíše sekvenci bajtů do aktuálního streamu, posune aktuální pozici v tomto streamu o počet zapsaných bajtů a sleduje požadavky na zrušení. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Pokud je režim zabalení binární, zapíše do streamu zadanou nezápornou 8-bitovou hodnotu, jinak ji převede na typ char_type a poté zapíše výsledek do streamu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Null](../stream/null/) | Stream bez podkladového úložiště. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Viz také

* Třída [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)