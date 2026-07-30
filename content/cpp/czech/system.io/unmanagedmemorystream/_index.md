---
title: UnmanagedMemoryStream
second_title: Aspose.Slides pro C++ API Reference
description: "Poskytuje přístup k neřízené paměti. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject() . Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 456
url: /cs/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream třída

Poskytuje přístup k neřízené paměti. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci zápisu. |
| virtual void [Close](../stream/close/)() | Uzavře stream. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Kopíruje bajty do zadaného streamu. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Kopíruje bajty do zadaného streamu pomocí specifikované velikosti vyrovnávací paměti. |
| void [Dispose](../stream/dispose/)() override | Uvolní všechny prostředky používané aktuálním objektem a uzavře stream. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí zadanou asynchronní operaci čtení. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončuje asynchronní operaci zápisu. Čeká, dokud nedokončí zadanou asynchronní operaci zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| void [Flush](./flush/)() override | Nedělá nic. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vyprázdní všechny vyrovnávací paměti tohoto streamu, způsobí, že se všechna bufferovaná data zapíší do podkladového zařízení, a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Asynchronně vyprázdní všechny vyrovnávací paměti tohoto streamu, způsobí, že se všechna bufferovaná data zapíší do podkladového zařízení, a monitoruje žádosti o zrušení. |
| **bool** [get_CanRead](./get_canread/)() const override | Určuje, zda je stream čitelný. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Určuje, zda stream podporuje posouvání. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Získá hodnotu, která určuje, zda může aktuální stream časově vypršet. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Určuje, zda je stream zapisovatelný. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | Vrací aktuální kapacitu podkladové paměťové vyrovnávací paměti. |
| **int64_t** [get_Length](./get_length/)() const override | Vrací délku streamu v bajtech. |
| **int64_t** [get_Position](./get_position/)() const override | Vrací aktuální pozici streamu. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | NEIMPLEMENTOVÁNO. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit číst před vypršením časového limitu. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit zapisovat před vypršením časového limitu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zjistí, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() prohláška. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopírováním. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopírováním. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte zadaný počet bajtů ze streamu a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte zadaný počet bajtů ze streamu a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Čte zadaný počet bajtů ze streamu a zapisuje je do určeného pole bajtů. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Čte zadaný počet bajtů ze streamu a zapisuje je do určeného bajtového úseku. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| virtual int [ReadByte](../stream/readbyte/)() | Přečte jeden bajt ze streamu a vrátí 32-bitovou celočíselnou hodnotu odpovídající hodnotě přečteného bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený referenční čítač o zadanou hodnotu. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Nastaví pozici streamu reprezentovaného aktuálním objektem. |
| void [set_Position](./set_position/)(**int64_t**) override | Nastaví pozici streamu. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | NEIMPLEMENTOVÁNO. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Nastaví hodnotu, která určuje, zda může aktuální stream časově vypršet. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Nastaví hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit číst před vypršením časového limitu. |
| void [SetLength](./setlength/)(**int64_t**) override | NEIMPLEMENTOVÁNO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() prohláška. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | Vytvoří novou instanci [UnmanagedMemoryStream](./). |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | Vytvoří novou instanci [UnmanagedMemoryStream](./). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NEIMPLEMENTOVÁNO. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NEIMPLEMENTOVÁNO. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapisuje určený podrozsah bajtů z daného pole bajtů do streamu. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapisuje určený podrozsah bajtů z daného bajtového úseku do streamu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapisuje sekvenci bajtů do aktuálního streamu, posouvá aktuální pozici v tomto streamu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapisuje sekvenci bajtů do aktuálního streamu, posouvá aktuální pozici v tomto streamu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Zapisuje určenou neznačenou 8-bitovou celočíselnou hodnotu do streamu. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Pole

| Pole | Popis |
| --- | --- |
| static [Null](../stream/null/) | Stream bez podkladového úložiště. |
## Viz také

* Třída [Stream](../stream/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)