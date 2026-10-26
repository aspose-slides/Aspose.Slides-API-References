---
title: X509Extension
second_title: Aspose.Slides pro C++ API Reference
description: "Objekt rozšíření pro uchování dodatečných informací spojených s X.509 certifikátem. Instance této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením asertací. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 144
url: /cs/system.security.cryptography.x509certificates/x509extension/
---
## X509Extension třída

Extension objekt pro uchování dodatečných informací spojených s X.509 certifikátem. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání jako argumentu funkcím.

```cpp
class X509Extension : public System::Security::Cryptography::AsnEncodedData
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) | Kopírovací konstruktor. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [AsnEncodedData](../../system.security.cryptography/asnencodeddata/asnencodeddata/)(const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
| void [CopyFrom](./copyfrom/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&) override | Kopíruje data rozšíření z jiného objektu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [String](../../system/string/) [Format](../../system.security.cryptography/asnencodeddata/format/)(**bool**) const | Formátuje data ve čitelné podobě. |
| **bool** [get_Critical](./get_critical/)() const | Kontroluje, zda je rozšíření kritické. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_Oid](../../system.security.cryptography/asnencodeddata/get_oid/)() const | Získává identifikátor objektu kódovaných dat. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](../../system.security.cryptography/asnencodeddata/get_rawdata/)() const | Získává surová kódovaná data. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává aktuální typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
|  [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_Critical](./set_critical/)(**bool**) | Definuje, zda je rozšíření kritické. |
| void [set_Oid](../../system.security.cryptography/asnencodeddata/set_oid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&) | Nastavuje identifikátor objektu kódovaných dat. |
| void [set_RawData](../../system.security.cryptography/asnencodeddata/set_rawdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Nastavuje surová kódovaná data. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastavuje n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte inteligentní ukazatele nebo ThisProtector. |
|  [X509Extension](./x509extension/)(const [SharedPtr](../../system/sharedptr/)\<[AsnEncodedData](../../system.security.cryptography/asnencodeddata/)\>\&, **bool**) | Konstruktor. |
|  [X509Extension](./x509extension/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Konstruktor. |
|  [X509Extension](./x509extension/)(const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Konstruktor. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny interní datové struktury. |

## Viz také

* Třída [AsnEncodedData](../../system.security.cryptography/asnencodeddata/)
* Jmenný prostor [System::Security::Cryptography::X509Certificates](../)
* Knihovna [Aspose.Slides](../../)