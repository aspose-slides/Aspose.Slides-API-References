---
title: HttpRequestCachePolicy
second_title: Aspose.Slides för C++ API-referens
description: "HTTP-cachepolicy som uttrycker RFC2616 HTTP-cachningssemantik. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körningsfel och/eller påståendefel. Omslut alltid denna klass med en System::SmartPtr-pekare och använd den pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1
url: /sv/system.net.cache/httprequestcachepolicy/
---
## HttpRequestCachePolicy class


HTTP-cachepolicy som uttrycker RFC2616 HTTP-cachesemantik. Objekt av den här klassen får endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körningsfel och/eller påståendefel. Omslut alltid den här klassen med en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class HttpRequestCachePolicy : public System::Net::Cache::RequestCachePolicy
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [DateTime](../../system/datetime/) [get_CacheSyncDate](./get_cachesyncdate/)() const | Hämtar tiden då resurser lagrade i cachen måste valideras på nytt. |
| [DateTime](../../system/datetime/) [get_InternalCacheSyncDateUtc](./get_internalcachesyncdateutc/)() const | Hämtar tiden i UTC-format då resurser lagrade i cachen måste valideras på nytt. Endast för internt bruk. |
| [HttpRequestCacheLevel](../httprequestcachelevel/) [get_Level](./get_level/)() const | Hämtar det angivna HttpRequestCacheLevel-värdet. |
| [RequestCacheLevel](../requestcachelevel/) [get_Level](../requestcachepolicy/get_level/)() | Hämtar det angivna RequestCacheLevel-värdet. |
| [TimeSpan](../../system/timespan/) [get_MaxAge](./get_maxage/)() const | Hämtar det maximala åldersvärdet som tillåts för en resurs. |
| [TimeSpan](../../system/timespan/) [get_MaxStale](./get_maxstale/)() const | Hämtar det maximala föråldringsvärdet som är tillåtet för en resurs. |
| [TimeSpan](../../system/timespan/) [get_MinFresh](./get_minfresh/)() const | Hämtar den minsta tillåtna åldern för en resurs. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)() | Skapar en ny instans. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpRequestCacheLevel](../httprequestcachelevel/)) | Skapar en ny instans. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/)) | Skapar en ny instans. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/)) | Skapar en ny instans. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([DateTime](../../system/datetime/)) | Skapar en ny instans. |
|  [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/), [DateTime](../../system/datetime/)) | Skapar en ny instans. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-uttrycket. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetyp-objekt med nullptr med referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
|  [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)() | Skapar en ny instans. |
|  [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)([RequestCacheLevel](../requestcachelevel/)) | Skapar en ny instans med det angivna RequestCacheLevel-värdet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (i stället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde på delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-uttrycket. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [RequestCachePolicy](../requestcachepolicy/)
* Namnrymd [System::Net::Cache](../)
* Bibliotek [Aspose.Slides](../../)