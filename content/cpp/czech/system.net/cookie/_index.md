---
title: Cookie
second_title: Aspose.Slides pro C++ – reference API
description: "Representuje HTTP cookie. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject() . Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání do funkcí jako argument."
type: docs
weight: 1
url: /cs/system.net/cookie/
---
## Cookie třída


Reprezentuje HTTP cookie. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class Cookie : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Vytvoří kopii aktuální instance. |
|  [Cookie](./cookie/)() | Vytvoří novou instanci. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Vytvoří novou instanci. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Vytvoří novou instanci. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Vytvoří novou instanci. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Získá hodnotu atributu 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Získá hodnotu atributu 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Získá hodnotu atributu 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Získá hodnotu atributu 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Získá hodnotu, která určuje, zda je doména implicitní. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Vrací klíč domény. |
| **bool** [get_Expired](./get_expired/)() | Získá hodnotu, která určuje, zda cookie vypršela. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Získá hodnotu atributu 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Získá hodnotu atributu 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Získá název cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Získá hodnotu atributu 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Vrací hodnotu, která určuje, zda je specifikace cookie 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Získá hodnotu atributu 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Vrací kolekci hodnot atributu 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Získá hodnotu atributu 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Vrací čas, kdy byla cookie vytvořena. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Získá hodnotu cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Získá specifikaci cookie. |
| **int32_t** [get_Version](./get_version/)() const | Získá hodnotu atributu '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Tuto metodu volají jiné metody k nastavení názvu metody. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Volat přímo nebo použít objekt střeže [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu value s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Speciální verze [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Speciální verze [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Nastaví hodnotu atributu 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Nastaví hodnotu atributu 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Nastaví hodnotu atributu 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Nastaví hodnotu atributu 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Nastaví hodnotu, která určuje, zda je doména implicitní. |
| void [set_Expired](./set_expired/)(**bool**) | Nastaví hodnotu, která určuje, zda cookie vypršela. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Nastaví hodnotu atributu 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Nastaví hodnotu atributu 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Nastaví název cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Nastaví hodnotu atributu 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Nastaví hodnotu atributu 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Nastaví hodnotu atributu 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Nastaví hodnotu cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Nastaví specifikaci cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Nastaví hodnotu atributu '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serializuje aktuální instanci do řetězcové reprezentace. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Volat přímo nebo použít objekt střeže [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Ověřuje a nastavuje výchozí hodnoty atributů. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Pole

| Pole | Popis |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Název atributu 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Název atributu 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Název atributu 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Název atributu 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Oddělovač používaný k oddělení názvu a hodnoty atributu. |
| static [ExpiresAttributeName](./expiresattributename/) | Název atributu 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Název atributu 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Název atributu 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Maximální podporovaná verze. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Řetězcová reprezentace maximální podporované verze. |
| static [PathAttributeName](./pathattributename/) | Název atributu 'Path'. |
| static [PortAttributeName](./portattributename/) | Název atributu 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Pole obsahující oddělovače hodnot atributu 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Symbol používaný k ohraničení částí atributu. |
| static [ReservedToName](./reservedtoname/) | Hodnota vyhrazena pro název cookie. |
| static [ReservedToValue](./reservedtovalue/) | Hodnota vyhrazena pro hodnotu cookie. |
| static [SecureAttributeName](./secureattributename/) | Název atributu 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Oddělovač atributů. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Prefix názvů speciálních atributů. |
| static [VersionAttributeName](./versionattributename/) | Název atributu '[Version](../../system/version/)'. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Net](../)
* Knihovna [Aspose.Slides](../../)