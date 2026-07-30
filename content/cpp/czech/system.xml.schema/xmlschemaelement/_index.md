---
title: XmlSchemaElement
second_title: Aspose.Slides pro C++ – dokumentace API
description: Zastupuje element element z XML Schema podle specifikace World Wide Web Consortium (W3C). Tato třída je základní třídou pro všechny typy částic a slouží k popisu elementu v XML dokumentu.
type: docs
weight: 365
url: /cs/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement třída


Zastupuje **element** prvek z XML [Schema](../) podle specifikace World Wide [Web](../../system.web/) Consortium (W3C). Tato třída je základní třída pro všechny typy částic a slouží k popisu prvku v XML dokumentu.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | Vrací vlastnost **annotation**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | Vrací derivaci **Block**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Vrací post-kompilační interpretaci hodnoty **Block**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | Vrací kolekci omezení na prvku. |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | Vrací výchozí hodnotu prvku, pokud je jeho obsah jednoduchý typ nebo je obsah prvku **textOnly**. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | Vrací objekt [XmlSchemaType](../xmlschematype/) představující typ prvku na základě hodnot [XmlSchemaElement::get_SchemaType](./get_schematype/) nebo [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) prvku. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | Vrací objekt na základě [XmlSchemaElement](./) nebo [XmlSchemaElement](./) prvku, který obsahuje post-kompilační interpretaci hodnoty **ElementType**. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | Vrací hodnotu **Final**, aby indikovala, že další derivace nejsou povoleny. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | Vrací post-kompilační interpretaci hodnoty **Final**. |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | Vrací pevnou hodnotu. |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | Vrací formulář pro prvek. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Vrací řetězcové ID. |
| **bool** [get_IsAbstract](./get_isabstract/)() | Vrací informaci, zda může být prvek použit v instančním dokumentu. |
| **bool** [get_IsNillable](./get_isnillable/)() | Vrací informaci, která indikuje, zda se může v instančních datech objevit **xsi:nil**. Indikuje, zda může být prvku přiřazena explicitní hodnota nil. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | Vrací číslo řádku v souboru, na který odkazuje **schema** prvek. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | Vrací pozici řádku v souboru, na který odkazuje **schema** prvek. |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | Vrací maximální počet výskytů částice. |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | Vrací číslo jako řetězcovou hodnotu. Maximální počet výskytů částice. |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | Vrací minimální počet výskytů částice. |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | Vrací číslo jako řetězcovou hodnotu. Minimální počet výskytů částice. |
| [String](../../system/string/) [get_Name](./get_name/)() | Vrací název prvku. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Vrací XmlSerializerNamespaces k použití s tímto schématem objektu. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Vrací rodiče tohoto [XmlSchemaObject](../xmlschemaobject/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | Vrací skutečný kvalifikovaný název daného prvku. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | Vrací referenční název prvku deklarovaného v tomto schématu (nebo v jiném schématu určeném zadaným jmenným prostorem). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | Vrací typ prvku. Může to být buď komplexní typ, nebo jednoduchý typ. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | Vrací název vestavěného datového typu definovaného v tomto schématu nebo v jiném schématu určeném zadaným jmenným prostorem. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Vrací zdrojovou lokaci souboru, který načetl schéma. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | Vrací název prvku, který je tímto prvkem nahrazen. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Vrací kvalifikované atributy, které nepatří do cílového jmenného prostoru aktuálního schématu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog C# operátoru 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock() příkazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Přiřazovací operátor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenci hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počítadlo referencí o zadanou hodnotu. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | Nastavuje vlastnost **annotation**. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Nastavuje derivaci **Block**. |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | Nastavuje výchozí hodnotu prvku, pokud je jeho obsah jednoduchý typ nebo je obsah prvku **textOnly**. |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Nastavuje hodnotu **Final**, aby indikovala, že další derivace nejsou povoleny. |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | Nastavuje pevnou hodnotu. |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | Nastavuje formulář pro prvek. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Nastavuje řetězcové ID. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | Nastavuje informaci, zda může být prvek použit v instančním dokumentu. |
| void [set_IsNillable](./set_isnillable/)(**bool**) | Nastavuje informaci, která indikuje, zda se může v instančních datech objevit **xsi:nil**. Indikuje, zda může být prvku přiřazena explicitní hodnota nil. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | Nastavuje číslo řádku v souboru, na který odkazuje **schema** prvek. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | Nastavuje pozici řádku v souboru, na který odkazuje **schema** prvek. |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | Nastavuje maximální počet výskytů částice. |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | Nastavuje číslo jako řetězcovou hodnotu. Maximální počet výskytů částice. |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | Nastavuje minimální počet výskytů částice. |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | Nastavuje číslo jako řetězcovou hodnotu. Minimální počet výskytů částice. |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | Nastavuje název prvku. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Nastavuje XmlSerializerNamespaces k použití s tímto schématem objektu. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Nastavuje rodiče tohoto [XmlSchemaObject](../xmlschemaobject/). |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Nastavuje referenční název prvku deklarovaného v tomto schématu (nebo v jiném schématu určeném zadaným jmenným prostorem). |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | Nastavuje typ prvku. Může to být buď komplexní typ, nebo jednoduchý typ. |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Nastavuje název vestavěného datového typu definovaného v tomto schématu nebo v jiném schématu určeném zadaným jmenným prostorem. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Nastavuje zdrojovou lokaci souboru, který načetl schéma. |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Nastavuje název prvku, který je tímto prvkem nahrazen. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Nastavuje kvalifikované atributy, které nepatří do cílového jmenného prostoru aktuálního schématu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech na slabý režim. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí podle C# lock() příkazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [XmlSchemaElement](./xmlschemaelement/)() | Inicializuje novou instanci třídy [XmlSchemaElement](./). |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | Inicializuje novou instanci třídy [XmlSchemaObject](../xmlschemaobject/). |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | Inicializuje novou instanci třídy [XmlSchemaParticle](../xmlschemaparticle/). |
| virtual  [~Object](../../system/object/~object/)() | Uvolňuje objekt. Uvolňuje všechny vnitřní datové struktury. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [Ptr](./ptr/) | Alias pro sdílený ukazatel na instanci této třídy. |

## Poznámky



Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy obalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání funkcím jako argument. 

## Viz také

* Třída [XmlSchemaParticle](../xmlschemaparticle/)
* Jmenný prostor [System::Xml::Schema](../)
* Knihovna [Aspose.Slides](../../)