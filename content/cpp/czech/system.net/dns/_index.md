---
title: Dns
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Poskytuje metody pro práci s DNS.
type: docs
weight: 105
url: /cs/system.net/dns/
---
## Dns třída

Poskytuje metody pro práci s DNS.

```cpp
class Dns : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostAddresses](./begingethostaddresses/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Spouští asynchronní operaci pro vytvoření nové instance IPHostEntry-class pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostByName](./begingethostbyname/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Spouští asynchronní operaci pro vytvoření nové instance IPHostEntry-class pomocí zadaného názvu hostitele. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Spouští asynchronní operaci pro vytvoření nové instance IPHostEntry-class pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetHostEntry](./begingethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Spouští asynchronní operaci pro vytvoření nové instance IPHostEntry-class pomocí zadané IP adresy. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginResolve](./beginresolve/)([String](../../system/string/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Spouští asynchronní operaci pro vytvoření nové instance IPHostEntry-class pomocí zadaného názvu hostitele. |
|  [Dns](./dns/)() | Smazaný výchozí konstruktor. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [EndGetHostAddresses](./endgethostaddresses/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí zadaná asynchronní operace vytvoření nové instance IPHostEntry-class. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostByName](./endgethostbyname/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí zadaná asynchronní operace vytvoření nové instance IPHostEntry-class. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndGetHostEntry](./endgethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí zadaná asynchronní operace vytvoření nové instance IPHostEntry-class. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [EndResolve](./endresolve/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Čeká, dokud nedokončí zadaná asynchronní operace vytvoření nové instance IPHostEntry-class. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty podle sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače související s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování uživatelských objektů. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>\> [GetHostAddresses](./gethostaddresses/)([String](../../system/string/)) | Vrací kolekci IP adres zadaného názvu hostitele nebo IP adresy. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([String](../../system/string/)) | Vytvoří novou instanci IPHostEntry-class pomocí zadaného řetězcového zápisu IP adresy. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByAddress](./gethostbyaddress/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Vytvoří novou instanci IPHostEntry-class pomocí zadané IP adresy. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostByName](./gethostbyname/)([String](../../system/string/)) | Vytvoří novou instanci IPHostEntry-class pomocí zadaného názvu hostitele. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([String](../../system/string/)) | Vytvoří novou instanci IPHostEntry-class pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [GetHostEntry](./gethostentry/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../ipaddress/)\>) | Vytvoří novou instanci IPHostEntry-class pomocí zadané IP adresy. |
| static [String](../../system/string/) [GetHostName](./gethostname/)() | Vrací název hostitele místního počítače. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává hodnotový typ objektu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený referenční čítač o zadanou hodnotu. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPHostEntry](../iphostentry/)\> [Resolve](./resolve/)([String](../../system/string/)) | Vytvoří novou instanci IPHostEntry-class pomocí zadaného názvu hostitele. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako weak ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do režimu weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokování pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje weak referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje weak referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Net](../)
* Knihovna [Aspose.Slides](../../)