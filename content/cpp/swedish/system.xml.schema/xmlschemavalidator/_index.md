---
title: XmlSchemaValidator
second_title: Aspose.Slides för C++ API-referens
description: Representerar en XML Schema Definition Language (XSD) schema valideringsmotor. Klassen XmlSchemaValidator kan inte ärvas.
type: docs
weight: 937
url: /sv/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator klass


Representerar en XML [Schema](../) Definition Language (XSD) [Schema](../) valideringsmotor. Klassen [XmlSchemaValidator](./) kan inte ärvas.

```cpp
class XmlSchemaValidator : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Lägger till ett XML [Schema](../) Definition Language (XSD)-schema till mängden scheman som används för validering. |
| void [EndValidation](./endvalidation/)() | Avslutar valideringen och kontrollerar identitetsrestriktioner för hela XML-dokumentet. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil jämförelse av dubbelprecision där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | Returnerar radnummerinformationen för den XML-nod som valideras. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | Returnerar käll-URI för den XML-nod som valideras. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | Returnerar objektet som skickas som avsändarobjekt för ett valideringsevent. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | Returnerar de förväntade attributen för det aktuella elementets sammanhang. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | Returnerar de förväntade particlarna i det aktuella elementets sammanhang. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | Validerar identitetsrestriktioner på standardattributen och fyller den specificerade Listan med [XmlSchemaAttribute](../xmlschemaattribute/)-objekt för alla attribut med standardvärden som ännu inte har validerats med [XmlSchemaValidator::ValidateAttribute](./validateattribute/)-metoden i elementets sammanhang. |
| void [Initialize](./initialize/)() | Initierar tillståndet för objektet [XmlSchemaValidator](./). |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Initierar tillståndet för objektet [XmlSchemaValidator](./) med den specificerade [XmlSchemaObject](../xmlschemaobject/) för partiell validering. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning av C# lock()-sats. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktorer i underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktorer i underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypsobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | Sätter radnummerinformationen för den XML-nod som valideras. |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | Sätter käll-URI för den XML-nod som valideras. |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Sätter objektet som skickas som avsändarobjekt för ett valideringsevent. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Sätter [XmlResolver](../../system.xml/xmlresolver/)-objektet som används för att lösa **xs:import**- och **xs:include**-element samt **xsi:schemaLocation**- och **xsi:noNamespaceSchemaLocation**-attribut. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n:te mallargumentet till en weak-pekare (istället för shared). Tillåter att byta pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Hoppar över validering av det aktuella elementets innehåll och förbereder [XmlSchemaValidator](./)-objektet att validera innehåll i den överordnade elementets sammanhang. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning av C# lock()-sats (upplåsning). Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Validerar attributnamnet, namnrymdens URI och värdet i det aktuella elementets sammanhang. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Validerar attributnamnet, namnrymdens URI och värdet i det aktuella elementets sammanhang. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Validerar elementet i det aktuella sammanhanget. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Validerar elementet i det aktuella sammanhanget med de specificerade attributvärdena **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** och **xsi:NoNamespaceSchemaLocation**. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Verifierar om elementets textinnehåll är giltigt enligt dess datatyp för element med enkelt innehåll, och verifierar om innehållet i det aktuella elementet är komplett för element med komplext innehåll. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Verifierar om den angivna elementets textinnehåll är giltigt enligt dess datatyp. |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Verifierar om alla obligatoriska attribut i elementets sammanhang finns och förbereder [XmlSchemaValidator](./)-objektet för att validera elementets barninnehåll. |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | Validerar om den specificerade text **string** är tillåten i det aktuella elementets sammanhang, och samlar texten för validering om elementet har enkelt innehåll. |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | Validerar om texten som returneras av den angivna XmlValueGetter-objektet är tillåten i det aktuella elementets sammanhang, och samlar texten för validering om elementet har enkelt innehåll. |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | Validerar om mellanslaget i den specificerade **string** är tillåtet i det aktuella elementets sammanhang, och samlar mellanslag för validering om elementet har enkelt innehåll. |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | Validerar om mellanslaget som returneras av det angivna XmlValueGetter-objektet är tillåtet i det aktuella elementets sammanhang, och samlar mellanslag för validering om elementet har enkelt innehåll. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | Initierar en ny instans av [XmlSchemaValidator](./)-klassen. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Anmärkningar

Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendesfel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd den pekaren för att skicka den till funktioner som argument. 

## Se också

* Klass [Object](../../system/object/)
* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)