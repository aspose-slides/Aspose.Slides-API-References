---
title: XPathExpression
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje typovanou třídu, která představuje zkompilovaný výraz XPath.
type: docs
weight: 40
url: /cs/system.xml.xpath/xpathexpression/
---
## XPathExpression třída

Poskytuje typovanou třídu, která představuje zkompilovaný výraz [XPath](../).

```cpp
class XPathExpression : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [AddSort](./addsort/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>) | Pokud je přepsána v odvozené třídě, řadí uzly vybrané výrazem [XPath](../) podle zadaného objektu IComparer. |
| virtual void [AddSort](./addsort/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [XmlSortOrder](../xmlsortorder/), [XmlCaseOrder](../xmlcaseorder/), [String](../../system/string/), [XmlDataType](../xmldatatype/)) | Pokud je přepsána v odvozené třídě, řadí uzly vybrané výrazem [XPath](../) podle poskytnutých parametrů. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Clone](./clone/)() | Pokud je přepsána v odvozené třídě, vrací klon tohoto [XPathExpression](./). |
| static [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Compile](./compile/)(const [String](../../system/string/)\&) | Zkompiluje zadaný výraz [XPath](../) a vrátí objekt [XPathExpression](./) představující výraz [XPath](../). |
| static [SharedPtr](../../system/sharedptr/)\<[XPathExpression](./)\> [Compile](./compile/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&) | Zkompiluje zadaný výraz [XPath](../) s objektem [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) určeným pro řešení jmenných prostorů a vrátí objekt [XPathExpression](./), který představuje výraz [XPath](../). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [String](../../system/string/) [get_Expression](./get_expression/)() | Pokud je přepsána v odvozené třídě, získá **string** reprezentaci [XPathExpression](./). |
| virtual [XPathResultType](../xpathresulttype/) [get_ReturnType](./get_returntype/)() | Pokud je přepsána v odvozené třídě, získá typ výsledku výrazu [XPath](../). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného pomocí targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt střežce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetContext](./setcontext/)([SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>) | Pokud je přepsána v odvozené třídě, určuje objekt [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) k použití při řešení jmenných prostorů. |
| virtual void [SetContext](./setcontext/)([SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Pokud je přepsána v odvozené třídě, určuje objekt [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) k použití při řešení jmenných prostorů. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (na rozdíl od sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt střežce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zlikviduje objekt. Uvolní všechny interní datové struktury. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Xml::XPath](../)
* Knihovna [Aspose.Slides](../../)