---
title: XmlWriterSettings
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje sadu funkcí, které mají být podporovány na objektu XmlWriter vytvořeném metodou XmlWriter::Create."
type: docs
weight: 586
url: /cs/system.xml/xmlwritersettings/
---
## XmlWriterSettings třída

Určuje sadu funkcí, které mají být podporovány na objektu [XmlWriter](../xmlwriter/) vytvořeném metodou [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Vytvoří kopii instance [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Vrací hodnotu, která určuje, zda XML writer má kontrolovat, že všechny znaky v dokumentu odpovídají sekci "2.2 Characters" W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Vrací hodnotu, která určuje, zda [XmlWriter](../xmlwriter/) má také zavřít podkladový stream nebo TextWriter, když je zavolána metoda [XmlWriter::Close](../xmlwriter/close/). |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Vrací úroveň shody, kterou XML writer kontroluje ve výstupu XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Vrací hodnotu, která udává, zda [XmlWriter](../xmlwriter/) neescapuje atributy URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Vrací typ kódování textu, které se má použít. |
| **bool** [get_Indent](./get_indent/)() | Vrací hodnotu, která udává, zda odsazovat elementy. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Vrací řetězec znaků, který se použije při odsazování. Toto nastavení se použije, když je hodnota [XmlWriterSettings::set_Indent](./set_indent/) nastavena na **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Vrací hodnotu, která určuje, zda [XmlWriter](../xmlwriter/) má při zápisu XML obsahu odstraňovat duplicitní deklarace jmenných prostorů. Výchozí chování je, že writer vypisuje všechny deklarace jmenných prostorů, které jsou přítomny v resolveru jmenných prostorů writeru. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Vrací řetězec znaků, který se použije pro zalomení řádku. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Vrací hodnotu, která určuje, zda normalizovat zalomení řádků ve výstupu. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Vrací hodnotu, která určuje, zda zapisovat atributy na nový řádek. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Vrací hodnotu, která určuje, zda vynechat XML deklaraci. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Vrací metodu použité k serializaci výstupu [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Vrací hodnotu, která určuje, zda [XmlWriter](../xmlwriter/) přidá ukončovací tagy ke všem neuzavřeným elementům, když je volána metoda [XmlWriter::Close](../xmlwriter/close/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [Reset](./reset/)() | Resetuje členy třídy nastavení na výchozí hodnoty. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Nastaví hodnotu, která určuje, zda XML writer má kontrolovat, že všechny znaky v dokumentu odpovídají sekci "2.2 Characters" W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Nastaví hodnotu, která určuje, zda [XmlWriter](../xmlwriter/) má také zavřít podkladový stream nebo TextWriter, když je volána metoda [XmlWriter::Close](../xmlwriter/close/). |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Nastaví úroveň shody, kterou XML writer kontroluje ve výstupu XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Nastaví hodnotu, která určuje, zda [XmlWriter](../xmlwriter/) neescapuje atributy URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Nastaví typ kódování textu, který se má použít. |
| void [set_Indent](./set_indent/)(**bool**) | Nastaví hodnotu, která určuje, zda odsazovat elementy. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Nastaví řetězec znaků, který se použije při odsazování. Toto nastavení se použije, když je hodnota [XmlWriterSettings::set_Indent](./set_indent/) nastavena na **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Nastaví hodnotu, která určuje, zda [XmlWriter](../xmlwriter/) má při zápisu XML obsahu odstraňovat duplicitní deklarace jmenných prostorů. Výchozí chování je, že writer vypisuje všechny deklarace jmenných prostorů, které jsou přítomny v resolveru jmenných prostorů writeru. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Nastaví řetězec znaků, který se použije pro zalomení řádku. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Nastaví hodnotu, která určuje, zda normalizovat zalomení řádků ve výstupu. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Nastaví hodnotu, která určuje, zda zapisovat atributy na nový řádek. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Nastaví hodnotu, která určuje, zda vynechat XML deklaraci. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Nastaví hodnotu, která určuje, zda [XmlWriter](../xmlwriter/) přidá ukončovací tagy ke všem neuzavřeným elementům, když je volána metoda [XmlWriter::Close](../xmlwriter/close/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Inicializuje novou instanci třídy [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolní všechny interní datové struktury. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Poznámky

Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením asercí. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel při předávání do funkcí jako argument. 

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)