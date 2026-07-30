---
title: XmlReaderSettings
second_title: Aspose.Slides pro C++ API Reference
description: "Specifikuje sadu funkcí, které jsou podporovány na objektu XmlReader vytvořeném metodou XmlReader::Create."
type: docs
weight: 443
url: /cs/system.xml/xmlreadersettings/
---
## XmlReaderSettings třída


Specifies a set of features to support on the [XmlReader](../xmlreader/) object created by the [XmlReader::Create](../xmlreader/create/) method.

```cpp
class XmlReaderSettings : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Vytvoří kopii instance [XmlReaderSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Vrací hodnotu, která určuje, zda provádět kontrolu znaků. |
| **bool** [get_CloseInput](./get_closeinput/)() | Vrací hodnotu, která určuje, zda má být podkladový stream nebo TextReader uzavřen po uzavření čtečky. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Vrací úroveň shody, které bude [XmlReader](../xmlreader/) vyhovovat. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Vrací hodnotu, která určuje zpracování DTD. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Vrací hodnotu, která určuje, zda ignorovat komentáře. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Vrací hodnotu, která určuje, zda ignorovat instrukce zpracování. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Vrací hodnotu, která určuje, zda ignorovat nevýznamné bílé znaky. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Vrací offset čísla řádku objektu [XmlReader](../xmlreader/). |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Vrací offset pozice řádku objektu [XmlReader](../xmlreader/). |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Vrací hodnotu udávající maximální povolený počet znaků v dokumentu, který vznikne rozbalením entit. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Vrací hodnotu udávající maximální povolený počet znaků v XML dokumentu. Hodnota nula (0) znamená, že neexistuje žádný limit velikosti XML dokumentu. Nenulová hodnota určuje maximální velikost v znacích. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Vrací [XmlNameTable](../xmlnametable/) používaný pro atomizovaná porovnání řetězců. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Vrací hodnotu, která určuje, zda zakázat zpracování definice typu dokumentu (DTD). |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Vrací XmlSchemaSet, který se použije při provádění validace schématu. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Vrací hodnotu udávající nastavení validace schématu. Toto nastavení se vztahuje na objekty [XmlReader](../xmlreader/), které validují schémata (hodnota [XmlReaderSettings::get_ValidationType](./get_validationtype/) je [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Vrací hodnotu, která určuje, zda [XmlReader](../xmlreader/) provede validaci nebo přiřazení typu při čtení. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počitadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt typu hodnota s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počitadlo referencí o zadanou hodnotu. |
| void [Reset](./reset/)() | Resetuje členy třídy nastavení na jejich výchozí hodnoty. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Nastavuje hodnotu určující, zda provádět kontrolu znaků. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Nastavuje hodnotu určující, zda má být podkladový stream nebo TextReader uzavřen po uzavření čtečky. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Nastavuje úroveň shody, které bude [XmlReader](../xmlreader/) vyhovovat. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Nastavuje hodnotu určující zpracování DTD. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Nastavuje hodnotu určující, zda ignorovat komentáře. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Nastavuje hodnotu určující, zda ignorovat instrukce zpracování. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Nastavuje hodnotu určující, zda ignorovat nevýznamné bílé znaky. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Nastavuje offset čísla řádku objektu [XmlReader](../xmlreader/). |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Nastavuje offset pozice řádku objektu [XmlReader](../xmlreader/). |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Nastavuje hodnotu udávající maximální povolený počet znaků v dokumentu, který vznikne rozbalením entit. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Nastavuje hodnotu udávající maximální povolený počet znaků v XML dokumentu. Hodnota nula (0) znamená, že neexistuje žádný limit velikosti XML dokumentu. Nenulová hodnota určuje maximální velikost v znacích. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Nastavuje [XmlNameTable](../xmlnametable/) používaný pro atomizovaná porovnání řetězců. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Nastavuje hodnotu určující, zda zakázat zpracování definice typu dokumentu (DTD). |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Nastavuje XmlSchemaSet, který se použije při provádění validace schématu. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Nastavuje hodnotu udávající nastavení validace schématu. Toto nastavení se vztahuje na objekty [XmlReader](../xmlreader/), které validují schémata (hodnota [XmlReaderSettings::get_ValidationType](./get_validationtype/) je [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Nastavuje hodnotu určující, zda [XmlReader](../xmlreader/) bude provádět validaci nebo přiřazení typu při čtení. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Nastavuje [XmlResolver](../xmlresolver/) používaný pro přístup k externím dokumentům. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počitadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílené počitadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílené počitadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Přidává obslužnou funkci události, která nastane, když čtečka narazí na validační chyby. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Odstraňuje obslužnou funkci události, která nastane, když čtečka narazí na validační chyby. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počitadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počitadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Inicializuje novou instanci třídy [XmlReaderSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Poznámky

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a používejte tento ukazatel k předávání jako argument funkcím. 

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)