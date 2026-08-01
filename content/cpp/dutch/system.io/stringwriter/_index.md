---
title: StringWriter
second_title: Aspose.Slides voor C++ API-referentie
description: "Implementeert een TextWriter die informatie naar een string schrijft. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Plaats deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 417
url: /nl/system.io/stringwriter/
---
## StringWriter klasse


Implementeert een [TextWriter](../textwriter/) die informatie naar een string schrijft. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Plaats deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Sluit de stream en geeft verworven resources vrij. |
| void [Dispose](../textwriter/dispose/)() override | Geeft alle resources vrij die door het huidige object worden gebruikt en sluit de onderliggende stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual void [Flush](../textwriter/flush/)() | Leegt de inhoud van de buffer naar de onderliggende stream. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Retourneert de momenteel gebruikte codering. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Retourneert het momenteel gebruikte [IFormatProvider](../../system/iformatprovider/) object. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Retourneert het momenteel gebruikte [IFormatProvider](../../system/iformatprovider/) object. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Retourneert een regelafsluitings-string. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Retourneert een regelafsluitings-string. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt hashing van aangepaste objecten in staat. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Retourneert de momenteel gebruikte StringBuilder. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt klonen van aangepaste types in staat. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert enkel een nieuw object en stelt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert enkel een nieuw object en stelt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Stelt een regelafsluitings-string in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik hiervoor smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik hiervoor smart pointers of ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Construeert een nieuw exemplaar van [StringWriter](./) met de opgegeven StringBuilder en [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Construeert een nieuw exemplaar van [StringWriter](./) met de opgegeven StringBuilder en [IFormatProvider](../../system/iformatprovider/) uit de huidige cultuur. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Construeert een nieuw exemplaar van [StringWriter](./) met de opgegeven [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Construeert een nieuw exemplaar van [StringWriter](./) met [IFormatProvider](../../system/iformatprovider/) uit de huidige cultuur. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retourneert de onderliggende string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik hiervoor smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik hiervoor smart pointers of ThisProtector. |
| void [Write](./write/)(char_t) override | Schrijft het opgegeven teken naar de stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van tekens uit de opgegeven tekenarray naar de stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Schrijft de opgegeven string naar de stream. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schrijft de stringrepresentatie van het opgegeven object naar de stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Schrijft de stringrepresentatie van de opgegeven booleaanse waarde naar de stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Schrijft de stringrepresentatie van het opgegeven [Decimal](../../system/decimal/) object naar de stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Schrijft de stringrepresentatie van de opgegeven double-precisie zwevend-kommagelijk waarde naar de stream. |
| virtual void [Write](../textwriter/write/)(int) | Schrijft de stringrepresentatie van de opgegeven 32-bit integerwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Schrijft de stringrepresentatie van de opgegeven 64-bit integerwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Schrijft de stringrepresentatie van de opgegeven single-precisie zwevend-kommagelijk waarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Schrijft de stringrepresentatie van de opgegeven unsigned 32-bit integerwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Schrijft de stringrepresentatie van de opgegeven unsigned 64-bit integerwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schrijft alle tekens uit de opgegeven array naar de stream. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Schrijft de opgegeven c-string naar de stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Schrijft de stringrepresentatie van het opgegeven [TypeInfo](../../system/typeinfo/) object naar de stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)() | Schrijft regelafsluitings-tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schrijft de stringrepresentatie van het opgegeven object, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Schrijft de stringrepresentatie van de opgegeven booleaanse waarde, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Schrijft het opgegeven teken, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Schrijft de stringrepresentatie van het opgegeven [Decimal](../../system/decimal/) object, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Schrijft de stringrepresentatie van de opgegeven double-precisie zwevend-kommagelijk waarde, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Schrijft de stringrepresentatie van de opgegeven 32-bit integerwaarde, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Schrijft de stringrepresentatie van de opgegeven 64-bit integerwaarde, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Schrijft de stringrepresentatie van de opgegeven single-precisie zwevend-kommagelijk waarde, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Schrijft de opgegeven string, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Schrijft de stringrepresentatie van de opgegeven unsigned 32-bit integerwaarde, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Schrijft de stringrepresentatie van de opgegeven unsigned 64-bit integerwaarde, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schrijft alle tekens uit de opgegeven array, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van UTF-16 tekens uit de opgegeven tekenarray, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Schrijft de opgegeven c-string, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Schrijft de stringrepresentatie van het opgegeven [TypeInfo](../../system/typeinfo/) object, gevolgd door de regelafsluitings-tekens, naar de stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat, gevolgd door de regelafsluitings-tekens, naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destructor. |
## Zie ook

* Klasse [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)