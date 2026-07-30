---
title: XmlParserContext
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Poskytuje všechny kontextové informace požadované XmlReaderem pro analýzu XML fragmentu.
type: docs
weight: 391
url: /cs/system.xml/xmlparsercontext/
---
## XmlParserContext třída

Poskytuje veškeré kontextové informace požadované [XmlReader](../xmlreader/) pro analýzu XML fragmentu.

```cpp
class XmlParserContext : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu v C# stylu. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu v C# stylu. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C# pro typ double, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Vrací základní URI. |
| [String](../../system/string/) [get_DocTypeName](./get_doctypename/)() | Vrací název deklarace typu dokumentu. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Vrací typ kódování. |
| [String](../../system/string/) [get_InternalSubset](./get_internalsubset/)() | Vrací vnitřní podmnožinu DTD. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\> [get_NamespaceManager](./get_namespacemanager/)() | Vrací [XmlNamespaceManager](../xmlnamespacemanager/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Vrací [XmlNameTable](../xmlnametable/) používaný k atomizaci řetězců. Další informace o atomizovaných řetězcích naleznete v [XmlNameTable](../xmlnametable/). |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | Vrací veřejný identifikátor. |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | Vrací systémový identifikátor. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Vrací aktuální rozsah **xml:lang**. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Vrací aktuální rozsah **xml:space**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Přiřazovací operátor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_BaseURI](./set_baseuri/)(const [String](../../system/string/)\&) | Nastavuje základní URI. |
| void [set_DocTypeName](./set_doctypename/)(const [String](../../system/string/)\&) | Nastavuje název deklarace typu dokumentu. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Nastavuje typ kódování. |
| void [set_InternalSubset](./set_internalsubset/)(const [String](../../system/string/)\&) | Nastavuje vnitřní podmnožinu DTD. |
| void [set_NamespaceManager](./set_namespacemanager/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | Nastavuje [XmlNamespaceManager](../xmlnamespacemanager/). |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Nastavuje [XmlNameTable](../xmlnametable/) používaný k atomizaci řetězců. Další informace o atomizovaných řetězcích naleznete v [XmlNameTable](../xmlnametable/). |
| void [set_PublicId](./set_publicid/)(const [String](../../system/string/)\&) | Nastavuje veřejný identifikátor. |
| void [set_SystemId](./set_systemid/)(const [String](../../system/string/)\&) | Nastavuje systémový identifikátor. |
| void [set_XmlLang](./set_xmllang/)(const [String](../../system/string/)\&) | Nastavuje aktuální rozsah **xml:lang**. |
| void [set_XmlSpace](./set_xmlspace/)([System::Xml::XmlSpace](../xmlspace/)) | Nastavuje aktuální rozsah **xml:space**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | Inicializuje novou instanci třídy [XmlParserContext](./) s uvedenými hodnotami [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang** a **xml:space**. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Inicializuje novou instanci třídy [XmlParserContext](./) s uvedenými [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space** a kódováním. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | Inicializuje novou instanci třídy [XmlParserContext](./) s uvedenými [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), základním URI, **xml:lang**, **xml:space** a hodnotami typu dokumentu. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Inicializuje novou instanci třídy [XmlParserContext](./) s uvedenými [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), základním URI, **xml:lang**, **xml:space**, kódováním a hodnotami typu dokumentu. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Poznámky

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a používejte tento ukazatel k předávání jako argument funkcím. 

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)