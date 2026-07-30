---
title: CryptoStream
second_title: Aspose.Slides pro C++ API Reference
description: "Implementace streamu, která obaluje existující stream pomocí kryptografické funkce. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu ukazatelem System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 53
url: /cs/system.security.cryptography/cryptostream/
---
## CryptoStream třída

Implementace streamu, která obaluje existující stream pomocí kryptografické funkce. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class CryptoStream : public System::IO::Stream
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Inicializuje asynchronní operaci zápisu. |
| void [Close](./close/)() override | Uzavře spojení. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Kopíruje bajty do určeného streamu. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Kopíruje bajty do určeného streamu s použitím určené velikosti bufferu. |
|  [CryptoStream](./cryptostream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\>\&, [CryptoStreamMode](../cryptostreammode/)) | Konstruktor. |
| void [Dispose](../../system.io/stream/dispose/)() override | Uvolní všechny prostředky používané aktuálním objektem a uzavře stream. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí určená asynchronní operace čtení. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončuje asynchronní operaci zápisu. Čeká, dokud nedokončí určená asynchronní operace zápisu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| void [Flush](./flush/)() override | Vyprázdní buffer do obaleného streamu. Nedělá nic, protože transformovací algoritmus může stále čekat na další data. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vymaže všechny buffery pro tento stream, způsobí, že veškerá bufferovaná data budou zapsána do podkladového zařízení, a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Asynchronně vymaže všechny buffery pro tento stream, způsobí, že veškerá bufferovaná data budou zapsána do podkladového zařízení, a monitoruje požadavky na zrušení. |
| void [FlushFinalBlock](./flushfinalblock/)() | Zapíše data, která jsou stále v bufferu, do streamu. |
| **bool** [get_CanRead](./get_canread/)() const override | Kontroluje, zda je stream čitelný. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Kontroluje, zda je stream přeskakovateľný. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Získá hodnotu, která určuje, zda může aktuální stream vypršet časovým limitem. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Kontroluje, zda je stream zapisovatelný. |
| **int64_t** [get_Length](./get_length/)() const override | Získá délku streamu. Není podporováno. |
| **int64_t** [get_Position](./get_position/)() const override | Získá aktuální pozici ve streamu. Není podporováno. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream pokusí číst, než vyprší časový limit. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream pokusí zapisovat, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# výrazu lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte data ze streamu. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Čte data ze streamu. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Čte zadaný počet bajtů ze streamu a zapisuje je do zadaného pole bajtů. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Čte zadaný počet bajtů ze streamu a zapisuje je do zadaného rozsahu bajtů. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a monitoruje požadavky na zrušení. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Čte jediný bajt ze streamu a vrací 32-bitovou celočíselnou hodnotu ekvivalentní hodnotě přečteného bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Posouvá pozici ve streamu. Není podporováno. |
| void [set_Position](./set_position/)(**int64_t**) override | Posouvá pozici ve streamu. Není podporováno. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Nastavuje hodnotu, která určuje, zda může aktuální stream vypršet časovým limitem. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Nastavuje hodnotu v milisekundách, která určuje, jak dlouho se stream pokusí číst, než vyprší časový limit. |
| void [SetLength](./setlength/)(**int64_t**) override | Posouvá velikost streamu. Není podporováno. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše data do streamu. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Zapíše data do streamu. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do streamu. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše zadaný podrozsah bajtů ze zadaného rozsahu bajtů do streamu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapisuje sekvenci bajtů do aktuálního streamu, posouvá aktuální pozici ve streamu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapisuje sekvenci bajtů do aktuálního streamu, posouvá aktuální pozici ve streamu o počet zapsaných bajtů a monitoruje požadavky na zrušení. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Zapíše zadanou nezápornou 8bitovou celočíselnou hodnotu do streamu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Stream bez podkladového úložiště. |

## Viz také

* Třída [Stream](../../system.io/stream/)
* Jmenný prostor [System::Security::Cryptography](../)
* Knihovna [Aspose.Slides](../../)