---
title: StreamReader
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Představuje čtečku, která čte znaky z bytového proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním tvrzení. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 378
url: /cs/system.io/streamreader/
---
## StreamReader třída

Představuje čtečku, která čte znaky z bytového proudu. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo chybám tvrzení. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class StreamReader : public System::IO::TextReader
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Close](./close/)() override | Uzavře aktuální a podkladové proudy. |
| virtual void [Dispose](./dispose/)(**bool**) | Uvolní všechny prostředky použité aktuálním objektem a uzavře podkladový proud. |
| void [Dispose](./dispose/)() override | Uvolní všechny prostředky použité aktuálním objektem a uzavře podkladový proud. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typů hodnot ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Vrací sdílený ukazatel na objekt, který představuje podkladový proud. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Vrací aktuálně používané kódování. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Vrací hodnotu, která indikuje, zda byl dosažen konec proudu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počitadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání výrazu C# lock(). Volajte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| int [Peek](./peek/)() override | Čte jeden znak z proudu bez změny čtecího kurzoru proudu. |
| int [Read](./read/)() override | Čte jeden znak z proudu. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Čte z proudu zadaný počet znaků, převádí je do kódování UTF-16 a zapisuje výsledné znaky UTF-16 do zadaného pole znaků počínaje zadanou pozicí. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Čte maximální zadaný počet znaků z aktuálního textového čtečky a zapisuje data do bufferu, počínaje zadaným indexem. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Čte znaky z proudu až do konce aktuální řádky. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Čte znaky z proudu až do konce proudu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ string a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'th šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného podkladového proudu pomocí kódování UTF-8 a bufferu s výchozí velikostí 1024 bajtů. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného podkladového proudu pomocí kódování UTF-8 a bufferu s výchozí velikostí 1024 bajtů. Parametr určuje, zda má být povoleno rozpoznávání byte order mark. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu s výchozí velikostí 1024 bajtů. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu s výchozí velikostí 1024 bajtů. Parametr určuje, zda má být povoleno rozpoznávání byte order mark. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu specifikované velikosti. Parametr určuje, zda má být povoleno rozpoznávání byte order mark. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného souboru pomocí kódování UTF-8 a bufferu s výchozí velikostí 4096 bajtů. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného souboru pomocí kódování UTF-8 a bufferu s výchozí velikostí 4096 bajtů. Parametr určuje, zda má být povoleno rozpoznávání byte order mark. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného souboru pomocí zadaného kódování a bufferu s výchozí velikostí 4096 bajtů. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného podkladového proudu pomocí zadaného kódování a bufferu s výchozí velikostí 4096 bajtů. Parametr určuje, zda má být povoleno rozpoznávání byte order mark. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Vytvoří instanci objektu [StreamReader](./), který čte znaky ze zadaného souboru pomocí zadaného kódování a bufferu specifikované velikosti. Parametr určuje, zda má být povoleno rozpoznávání byte order mark. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání výrazu C# lock(). Volajte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
|  [~StreamReader](./~streamreader/)() | Destruktor. |
## Viz také

* Třída [TextReader](../textreader/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)