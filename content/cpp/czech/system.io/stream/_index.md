---
title: Stream
second_title: "Aspose.Slides pro C++ – referenční příručka API"
description: "Základní třída pro různé implementace streamu. Objektům této třídy by měl být alokován pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to může způsobit chyby za běhu a/nebo selhání asercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 365
url: /cs/system.io/stream/
---
## Třída Stream

Základní třída pro různé implementace streamu. Instance této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class Stream : public System::IDisposable
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spouští asynchronní operaci čtení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Spouští asynchronní operaci zápisu. |
| virtual void [Close](./close/)() | Uzavře stream. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | Zkopíruje bajty do určeného streamu. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | Zkopíruje bajty do určeného streamu s použitím určené velikosti bufferu. |
| void [Dispose](./dispose/)() override | Uvolní všechny prostředky používané aktuálním objektem a uzavře stream. |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud se neurčená asynchronní operace čtení nedokončí. |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ukončuje asynchronní operaci zápisu. Čeká, dokud se neurčená asynchronní operace zápisu nedokončí. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual void [Flush](./flush/)() | Vyčistí vyrovnávací paměti tohoto streamu a zapíše všechna data z bufferu do podkladového úložiště. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně vyčistí všechny vyrovnávací paměti pro tento stream, způsobí, že všechna data v bufferu budou zapsána do podkladového zařízení, a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | Asynchronně vyčistí všechny vyrovnávací paměti pro tento stream, způsobí, že všechna data v bufferu budou zapsána do podkladového zařízení, a monitoruje žádosti o zrušení. |
| virtual **bool** [get_CanRead](./get_canread/)() const | Určuje, zda je stream čitelný. |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | Určuje, zda stream podporuje posouvání. |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | Získá hodnotu, která určuje, zda může aktuální stream vypršet časovým limitem. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | Určuje, zda je stream zapisovatelný. |
| virtual **int64_t** [get_Length](./get_length/)() const | Vrací délku streamu v bajtech. |
| virtual **int64_t** [get_Position](./get_position/)() const | Vrací aktuální pozici streamu. |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit číst, než vyprší časový limit. |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | Získá hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit zapisovat, než vyprší časový limit. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zámek statementu C# lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Čte určený počet bajtů ze streamu a zapisuje je do určeného pole bajtů. |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Čte určený počet bajtů ze streamu a zapisuje je do určeného pole bajtů. |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Čte určený počet bajtů ze streamu a zapisuje je do určeného pole bajtů. |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Čte určený počet bajtů ze streamu a zapisuje je do určeného pole bajtů. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně čte sekvenci bajtů z aktuálního streamu, posouvá pozici ve streamu o počet přečtených bajtů a monitoruje žádosti o zrušení. |
| virtual int [ReadByte](./readbyte/)() | Čte jediný bajt ze streamu a vrací 32-bitovou celočíselnou hodnotu ekvivalentní hodnotě přečteného bajtu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počítadlo referencí o zadanou hodnotu. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | Nastaví pozici streamu reprezentovaného aktuálním objektem. |
| virtual void [set_Position](./set_position/)(**int64_t**) | Nastaví pozici streamu. |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | Nastaví hodnotu, která určuje, zda může aktuální stream vypršet časovým limitem. |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | Nastaví hodnotu v milisekundách, která určuje, jak dlouho se stream bude snažit číst, než vyprší časový limit. |
| virtual void [SetLength](./setlength/)(**int64_t**) | Nastaví délku streamu reprezentovaného aktuálním objektem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako weak ukazatel (namísto shared). Umožňuje přepínat ukazatele v kontejnerech do režimu weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje konverzi vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání statementu C# lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje weak počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje weak počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z určeného pole bajtů do streamu. |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z určeného pole bajtů do streamu. |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Zapíše určený podrozsah bajtů z určeného pole bajtů do streamu. |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Zapíše určený podrozsah bajtů z určeného byte span do streamu. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Asynchronně zapisuje sekvenci bajtů do aktuálního streamu, posouvá aktuální pozici v tomto streamu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Asynchronně zapisuje sekvenci bajtů do aktuálního streamu, posouvá aktuální pozici v tomto streamu o počet zapsaných bajtů a monitoruje žádosti o zrušení. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | Zapíše určenou neznačkovou 8-bitovou celočíselnou hodnotu do streamu. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [Null](./null/) | Stream bez podkladového úložiště. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na tuto třídu. |

## Viz také

* Třída [IDisposable](../../system/idisposable/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)