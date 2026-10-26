---
title: CacheControlHeaderValue
second_title: Aspose.Slides pro C++ - referenční příručka API
description: "Representuje hodnotu hlavičky 'Cache-Control'. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy netvořte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel pro předání jako argument funkcím."
type: docs
weight: 14
url: /cs/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue třída


Represents a value of the 'Cache-Control' header. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Constructs a new instance. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Vrací kolekci tokenů cache-extension. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Získává maximální věk v sekundách, který určuje dobu, po kterou klient přijme odpověď. |
| **bool** [get_MaxStale](./get_maxstale/)() | Získává hodnotu, která určuje, zda klient přijme prošlé odpovědi. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Získává hodnotu v sekundách, která určuje dobu, po kterou klient přijme prošlé odpovědi. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Získává hodnotu, která určuje dobu čerstvosti. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Získává hodnotu, která určuje, zda server vyžaduje revalidaci položky cache, když se stane zastaralou. |
| **bool** [get_NoCache](./get_nocache/)() | Získává hodnotu, která určuje, zda klient přijme cachovanou odpověď. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Získává kolekci názvů polí v direktivě 'no-cache' v hlavičce 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Získává hodnotu, která určuje, zda cache nesmí ukládat žádnou část HTTP požadavku nebo odpovědi. |
| **bool** [get_NoTransform](./get_notransform/)() | Získává hodnotu, která určuje, že cache nebo proxy nesmí měnit žádnou část těla entity. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Získává hodnotu, která určuje, že klient musí používat pouze cachované položky. |
| **bool** [get_Private](./get_private/)() | Získává hodnotu, která určuje, že HTTP odpověď nebo její část je určena pro jednoho uživatele a nesmí být cachována sdílenou cache. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Získává kolekci názvů polí v direktivě 'private' v hlavičce 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Získává hodnotu, která určuje, zda server vyžaduje revalidaci položky cache, když se stane zastaralou pro sdílené cache uživatelských agentů. |
| **bool** [get_Public](./get_public/)() | Získává hodnotu, která určuje, že může být HTTP odpověď cachována libovolnou cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Získává sdílenou maximální věkovou hodnotu v sekundách, která přepisuje direktivu 'max-age' v hlavičce 'Cache-Control' nebo hlavičku 'Expires' pro sdílenou cache. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Převádí předaný řetězec od zadaného indexu na instanci třídy [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí přidruženou k objektu. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Převádí předaný řetězec na instanci třídy [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Nastavuje maximální věkovou hodnotu v sekundách, která určuje dobu, po kterou klient přijme odpověď. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Nastavuje hodnotu, která určuje, zda klient přijme prošlé odpovědi. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Nastavuje hodnotu v sekundách, která určuje dobu, po kterou klient přijme prošlé odpovědi. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Nastavuje hodnotu, která určuje dobu čerstvosti. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Nastavuje hodnotu, která určuje, zda server vyžaduje revalidaci položky cache, když se stane zastaralou. |
| void [set_NoCache](./set_nocache/)(**bool**) | Nastavuje hodnotu, která určuje, zda klient přijme cachovanou odpověď. |
| void [set_NoStore](./set_nostore/)(**bool**) | Nastavuje hodnotu, která určuje, že cache nesmí ukládat žádnou část HTTP požadavku nebo odpovědi. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Nastavuje hodnotu, která určuje, že cache nebo proxy nesmí měnit žádnou část těla entity. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Nastavuje hodnotu, která určuje, že klient musí používat pouze cachované položky. |
| void [set_Private](./set_private/)(**bool**) | Nastavuje hodnotu, která určuje, že HTTP odpověď nebo její část je určena pro jednoho uživatele a nesmí být cachována sdílenou cache. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Nastavuje hodnotu, která určuje, že server vyžaduje revalidaci položky cache, když se stane zastaralou pro sdílené cache uživatelských agentů. |
| void [set_Public](./set_public/)(**bool**) | Nastavuje hodnotu, která určuje, že může být HTTP odpověď cachována libovolnou cache. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Nastavuje sdílenou maximální věkovou hodnotu v sekundách, která přepisuje direktivu 'max-age' v hlavičce 'Cache-Control' nebo hlavičku 'Expires' pro sdílenou cache. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převádět vlastní objekty na řetězec. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Pokouší se převést předaný řetězec na instanci třídy [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny interní datové struktury. |
## Viz také

* Třída [ICloneable](../../system/icloneable/)
* Jmenný prostor [System::Net::Http::Headers](../)
* Knihovna [Aspose.Slides](../../)