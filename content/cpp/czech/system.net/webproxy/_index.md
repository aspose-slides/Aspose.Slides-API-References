---
title: WebProxy
second_title: "Aspose.Slides pro C++ API Reference"
description: "Representuje http web-proxy server. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám při běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 495
url: /cs/system.net/webproxy/
---
## WebProxy třída

Representuje http web-proxy server. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám během běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání objektu funkcím jako argument.

```cpp
class WebProxy : public System::Net::IWebProxy
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | Získá adresu aktuálního proxy serveru. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_BypassList](./get_bypasslist/)() | Získá seznam adres, které nevyužívají proxy server. |
| **bool** [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | Získá hodnotu, která uvádí, zda má být proxy server používán pro lokální adresy. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | Získá přihlašovací údaje, které jsou odesílány proxy serveru pro autentizaci. |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | Získá hodnotu, která uvádí, zda mají být výchozí přihlašovací údaje odesílány s požadavky. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebProxy](./)\> [GetDefaultProxy](./getdefaultproxy/)() | Vrací proxy, které používá nedynamické nastavení Internet Exploreru. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [GetProxy](./getproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Vrací proxy URI pro webový požadavek. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| virtual **bool** [IsBypassed](./isbypassed/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Kontroluje, zda proxy server není používán pro specifikované URI. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# příkazu lock(). Voláte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje veškeré interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_Address](./set_address/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Nastaví adresu aktuálního proxy serveru. |
| void [set_BypassList](./set_bypasslist/)([System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Nastaví seznam adres, které nevyužívají proxy server. |
| void [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(**bool**) | Nastaví hodnotu, která uvádí, zda má být proxy server používán pro lokální adresy. |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Nastaví přihlašovací údaje, které jsou odesílány proxy serveru pro autentizaci. |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | Nastaví hodnotu, která uvádí, zda mají být výchozí přihlašovací údaje odesílány s požadavky. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý typový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# příkazu lock(). Voláte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [WebProxy](./webproxy/)() | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **int32_t**) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([String](../../system/string/)) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | Vytvoří novou instanci. |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | Vytvoří novou instanci. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní veškeré interní datové struktury. |

## Viz také

* Třída [IWebProxy](../iwebproxy/)
* Jmenný prostor [System::Net](../)
* Knihovna [Aspose.Slides](../../)