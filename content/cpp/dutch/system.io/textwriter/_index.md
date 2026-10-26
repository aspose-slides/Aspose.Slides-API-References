---
title: TextWriter
second_title: Aspose.Slides voor C++ API-referentie
description: "Een basisklasse voor klassen die schrijvers vertegenwoordigen die reeksen tekens naar verschillende bestemmingen schrijven. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een exemplaar van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assert-fouten. Wrap deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 443
url: /nl/system.io/textwriter/
---
## TextWriter klasse


Een basisklasse voor klassen die schrijvers vertegenwoordigen die reeksen tekens naar verschillende bestemmingen schrijven. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een exemplaar van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assert-fouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class TextWriter : public System::IDisposable
```

## Methoden

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Sluit de stream en geeft verworven resources vrij. |
| void [Dispose](./dispose/)() override | Geeft alle resources die door het huidige object worden gebruikt vrij en sluit de onderliggende stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietypeobjecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetypeobjecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl drijvende-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl drijvende-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual void [Flush](./flush/)() | Leegt de inhoud van de buffer naar de onderliggende stream. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Geeft de momenteel gebruikte codering terug. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Geeft het momenteel gebruikte [IFormatProvider](../../system/iformatprovider/)-object terug. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Geeft het momenteel gebruikte [IFormatProvider](../../system/iformatprovider/)-object terug. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Geeft een regelterminator-string terug. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Geeft een regelterminator-string terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-wachtoject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creeërt een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copyconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te copy-constructeren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te copy-constructeren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Stelt een regelterminator-string in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kun je pointers in containers naar zwakke modus schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-wachtoject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schrijft de tekenreeksrepresentatie van het opgegeven object naar de stream. |
| virtual void [Write](./write/)(**bool**) | Schrijft de tekenreeksrepresentatie van de opgegeven booleaanse waarde naar de stream. |
| virtual void [Write](./write/)(char_t) | Schrijft het opgegeven teken naar de stream. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Schrijft de tekenreeksrepresentatie van het opgegeven [Decimal](../../system/decimal/)-object naar de stream. |
| virtual void [Write](./write/)(**double**) | Schrijft de tekenreeksrepresentatie van de opgegeven double-precisie drijvende-kommagetalwaarde naar de stream. |
| virtual void [Write](./write/)(int) | Schrijft de tekenreeksrepresentatie van de opgegeven 32-bit geheelalwaarde naar de stream. |
| virtual void [Write](./write/)(**int64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven 64-bit geheelalwaarde naar de stream. |
| virtual void [Write](./write/)(**float**) | Schrijft de tekenreeksrepresentatie van de opgegeven single-precisie drijvende-kommagetalwaarde naar de stream. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Schrijft de opgegeven string naar de stream. |
| virtual void [Write](./write/)(**uint32_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 32-bit geheelalwaarde naar de stream. |
| virtual void [Write](./write/)(**uint64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 64-bit geheelalwaarde naar de stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schrijft alle tekens van de opgegeven array naar de stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van UTF-16-tekens van de opgegeven tekenarray naar de stream. |
| virtual void [Write](./write/)(const char_t *) | Schrijft de opgegeven c-string naar de stream. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Schrijft de tekenreeksrepresentatie van het opgegeven [TypeInfo](../../system/typeinfo/)-object naar de stream. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat naar de stream. |
| virtual void [WriteLine](./writeline/)() | Schrijft regelterminator-tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Schrijft de tekenreeksrepresentatie van het opgegeven object gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(**bool**) | Schrijft de tekenreeksrepresentatie van de opgegeven booleaanse waarde gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(char_t) | Schrijft het opgegeven teken gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Schrijft de tekenreeksrepresentatie van het opgegeven [Decimal](../../system/decimal/)-object gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(**double**) | Schrijft de tekenreeksrepresentatie van de opgegeven double-precisie drijvende-kommagetalwaarde gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(int) | Schrijft de tekenreeksrepresentatie van de opgegeven 32-bit geheelalwaarde gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven 64-bit geheelalwaarde gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(**float**) | Schrijft de tekenreeksrepresentatie van de opgegeven single-precisie drijvende-kommagetalwaarde gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Schrijft de opgegeven string gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 32-bit geheelalwaarde gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 64-bit geheelalwaarde gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Schrijft alle tekens van de opgegeven array gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Schrijft het opgegeven subbereik van UTF-16-tekens van de opgegeven tekenarray gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Schrijft de opgegeven c-string gevolgd door de regelterminerende tekens naar de stream. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Schrijft de tekenreeksrepresentatie van het opgegeven [TypeInfo](../../system/typeinfo/)-object gevolgd door de regelterminerende tekens naar de stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat gevolgd door de regelterminerende tekens naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |
| virtual  [~TextWriter](./~textwriter/)() | Destructor. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Een alias voor een shared pointer naar deze klasse. |

## Zie ook

* Klasse [IDisposable](../../system/idisposable/)
* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)