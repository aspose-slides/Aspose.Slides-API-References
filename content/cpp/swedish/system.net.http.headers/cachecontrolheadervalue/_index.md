---
title: CacheControlHeaderValue
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett värde för 'Cache-Control'-huvudet. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 14
url: /sv/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue klass


Representerar ett värde för 'Cache-Control'-huvudet. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Skapar en ny instans. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Returnerar samlingen av cache-extension-token. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Hämtar maxåldersvärdet i sekunder som bestämmer en tidsperiod då klienten accepterar ett svar. |
| **bool** [get_MaxStale](./get_maxstale/)() | Hämtar värdet som bestämmer om klienten accepterar utgångna svar. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Hämtar värdet i sekunder som bestämmer tidsperioden då klienten accepterar utgångna svar. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Hämtar värdet som bestämmer färskhetens livslängd. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Hämtar värdet som bestämmer om servern kräver revalidering av en cachepost när den blir föråldrad. |
| **bool** [get_NoCache](./get_nocache/)() | Hämtar värdet som bestämmer om klienten accepterar ett cachat svar. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Hämtar samlingen av fältnamn i 'no-cache'-direktivet i 'Cache-Control'-huvudet. |
| **bool** [get_NoStore](./get_nostore/)() | Hämtar värdet som bestämmer om en cache inte får lagra någon del av en HTTP-begäran eller -svar. |
| **bool** [get_NoTransform](./get_notransform/)() | Hämtar värdet som bestämmer om en cache eller proxy inte får ändra någon del av entity-kroppen. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Hämtar värdet som bestämmer om klienten bara får använda cachade poster. |
| **bool** [get_Private](./get_private/)() | Hämtar värdet som bestämmer om HTTP-svarsmeddelandet eller dess del är avsedd för en enskild användare och inte får cachas av en delad cache. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Hämtar samlingen av fältnamn i 'private'-direktivet i 'Cache-Control'-huvudet. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Hämtar värdet som bestämmer om servern kräver revalidering av en cachepost när den blir föråldrad för delade användaragentscacher. |
| **bool** [get_Public](./get_public/)() | Hämtar värdet som bestämmer om ett HTTP-svar kan cachas av någon cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Hämtar det delade maxåldersvärdet i sekunder som åsidosätter 'max-age'-direktivet i 'Cache-Control'-huvudet eller 'Expires'-huvudet för en delad cache. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Konverterar en given sträng från det angivna indexet till en instans av [CacheControlHeaderValue](./)-klassen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning av C# lock()-satser. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Konverterar en given sträng till en instans av [CacheControlHeaderValue](./)-klassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sätter maxåldersvärdet i sekunder som bestämmer en tidsperiod då klienten accepterar ett svar. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Sätter värdet som bestämmer om klienten accepterar utgångna svar. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sätter värdet i sekunder som bestämmer tidsperioden då klienten accepterar utgångna svar. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sätter värdet som bestämmer färskhetens livslängd. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Sätter värdet som bestämmer om servern kräver revalidering av en cachepost när den blir föråldrad. |
| void [set_NoCache](./set_nocache/)(**bool**) | Sätter värdet som bestämmer om klienten accepterar ett cachat svar. |
| void [set_NoStore](./set_nostore/)(**bool**) | Sätter värdet som bestämmer om en cache inte får lagra någon del av en HTTP-begäran eller -svar. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Sätter värdet som bestämmer om en cache eller proxy inte får ändra någon del av entity-kroppen. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Sätter värdet som bestämmer om klienten bara får använda cachade poster. |
| void [set_Private](./set_private/)(**bool**) | Sätter värdet som bestämmer om HTTP-svarsmeddelandet eller dess del är avsedd för en enskild användare och inte får cachas av en delad cache. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Sätter värdet som bestämmer om servern kräver revalidering av en cachepost när den blir föråldrad för delade användaragentscacher. |
| void [set_Public](./set_public/)(**bool**) | Sätter värdet som bestämmer om ett HTTP-svar kan cachas av någon cache. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Sätter det delade maxåldersvärdet i sekunder som åsidosätter 'max-age'-direktivet i 'Cache-Control'-huvudet eller 'Expires'-huvudet för en delad cache. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te template-argumentet till en weak-pekare (istället för shared). Tillåter byte av pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Försöker konvertera en given sträng till en instans av [CacheControlHeaderValue](./)-klassen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning av C# lock()-satser. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [ICloneable](../../system/icloneable/)
* Namnrymd [System::Net::Http::Headers](../)
* Bibliotek [Aspose.Slides](../../)