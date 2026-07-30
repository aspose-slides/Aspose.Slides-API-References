---
title: ResultValueTask
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje hybridní typ podobný úkolu, který může zabalit buď přímou výslednou hodnotu, nebo objekt ResultTask<T>.
type: docs
weight: 53
url: /cs/system.threading.tasks/resultvaluetask/
---
## ResultValueTask třída


Reprezentuje hybridní typ podobný úkolu, který může zabalit buď přímou výslednou hodnotu, nebo objekt ResultTask<T>.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```


### Šablonové parametry

| Parametr | Popis |
| --- | --- |
| T | Typ výsledku produkovaného úkolem. |
## Metody

| Metoda | Popis |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | Převádí tento [ResultValueTask](./) na sdílený ukazatel na ResultTask<T>. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Konfiguruje awaiter pro tento úkol. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | Určuje, zda tato instance se rovná jiné instanci [ResultValueTask](./). |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Určuje, zda tato instance se rovná jinému objektu. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Určuje, zda jsou aktuální a zadané objekty stejné. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, ačkoliv podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, ačkoliv podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Vrací hodnotu, která udává, zda úkol byl dokončen kvůli zrušení. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Vrací hodnotu, která udává, zda úkol byl dokončen. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Vrací hodnotu, která udává, zda úkol byl úspěšně dokončen. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Vrací hodnotu, která udává, zda úkol byl dokončen kvůli neodchycené výjimce. |
| T [get_Result](./get_result/)() | Vrací výsledek dokončeného úkolu. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Vrací awaiter pro tento úkol, aby podporoval await výrazy. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Vrací datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Vrací skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Volá se přímo nebo pomocí objektu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nezkopíruje, pouze inicializuje nový objekt a umožňuje kopírování při konstrukci podtříd. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | Operátor nerovnosti pro [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nezkopíruje, pouze inicializuje nový objekt a umožňuje kopírování při konstrukci podtříd. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | Operátor rovnosti pro [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
|  [ResultValueTask](./resultvaluetask/)() | Vytvoří prázdný, neinicializovaný [ResultValueTask](./). |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | Vytvoří dokončený [ResultValueTask](./) se zadaným výsledkem. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | Vytvoří [ResultValueTask](./) ze sdíleného ukazatele na ResultTask<T>. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínač ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Vrací aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí příkazu C# lock(). Volá se přímo nebo pomocí objektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Poznámky


[ResultValueTask](./) kombinuje výhody [ValueTask](../valuetask/) (snížené alokace pro synchronní výsledky) se schopností zabalit existující objekty ResultTask<T>. Poskytuje awaitable rozhraní a různé metody pro kontrolu stavu úkolu. 
## Viz také

* Třída [IEquatable](../../system/iequatable/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)