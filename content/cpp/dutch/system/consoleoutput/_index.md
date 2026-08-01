---
title: ConsoleOutput
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt de standaarduitvoerstream. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 209
url: /nl/system/consoleoutput/
---
## ConsoleOutput klasse

Geeft de standaard uitvoerstream weer. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../makeobject/) functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wikkel deze klasse altijd in een [System::SmartPtr](../smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Sluit de stream en geeft verkregen bronnen vrij. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Geeft alle resources die door het huidige object worden gebruikt vrij en sluit de onderliggende stream. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Leegt de inhoud van de buffer naar de onderliggende stream. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Geeft altijd ASCII-codering terug. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Retourneert het momenteel gebruikte [IFormatProvider](../iformatprovider/)-object. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Retourneert het momenteel gebruikte [IFormatProvider](../iformatprovider/)-object. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Retourneert een regeleinde-tekenreeks. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Retourneert een regeleinde-tekenreeks. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../object/gettype/)-aanroep. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van de C# 'is' operator. |
| void [Lock](../object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../lockcontext/) bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toekenningsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Stelt een regeleinde-tekenreeks in. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus om te schakelen. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analoge van de C# [Object.ToString()](../object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert de C# typeof([System.Object](../object/)) constructie. |
| void [Unlock](../object/unlock/)() | Implementeert het unlocken van het C# lock()-statement. Roep direct aan of gebruik het [LockContext](../lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Write](./write/)(**bool**) override | Schrijft de tekenreeksrepresentatie van de opgegeven bool-waarde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Schrijft de tekenreeksrepresentatie van het opgegeven object naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(char_t) override | Schrijft de opgegeven tekenwaarde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)([Decimal](../decimal/)) override | Schrijft de tekenreeksrepresentatie van de [Decimal](../decimal/)-waarde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(**double**) override | Schrijft de tekenreeksrepresentatie van een double-precisie zwevendekommagetal naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(**int32_t**) override | Schrijft de tekenreeksrepresentatie van een 32-bit geheel getal naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(**int64_t**) override | Schrijft de tekenreeksrepresentatie van een 64-bit geheel getal naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(**float**) override | Schrijft de tekenreeksrepresentatie van een single-precisie zwevendekommagetal naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(const [String](../string/)\&) override | Schrijft het opgegeven string-object naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(**uint32_t**) override | Schrijft de tekenreeksrepresentatie van een 32-bit unsigned geheel getal naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(**uint64_t**) override | Schrijft de tekenreeksrepresentatie van een 64-bit unsigned geheel getal naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Schrijft de tekenreeksrepresentatie van de opgegeven tekenarray naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schrijft de tekenreeksrepresentatie van een reeks waarden van de opgegeven tekenarray naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(const char_t *) override | Schrijft de opgegeven c-string naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Schrijft de tekenreeksrepresentatie van het opgegeven [TypeInfo](../typeinfo/)-object naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Schrijft de tekenreeksrepresentatie van de opgegeven 32-bit geheel getalwaarde naar de stream. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat naar de stream. |
| void [WriteLine](./writeline/)() override | Schrijft het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Schrijft de tekenreeksrepresentatie van het opgegeven object gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(**bool**) override | Schrijft de tekenreeksrepresentatie van de opgegeven bool-waarde gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(char_t) override | Schrijft de opgegeven tekenwaarde gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Schrijft de tekenreeksrepresentatie van de [Decimal](../decimal/)-waarde gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(**double**) override | Schrijft de tekenreeksrepresentatie van een double-precisie zwevendekommagetal gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(int) override | Schrijft de tekenreeksrepresentatie van een 32-bit geheel getal gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(**int64_t**) override | Schrijft de tekenreeksrepresentatie van een 64-bit geheel getal gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(**float**) override | Schrijft de tekenreeksrepresentatie van een single-precisie zwevendekommagetal gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Schrijft het opgegeven string-object gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Schrijft de tekenreeksrepresentatie van een 32-bit unsigned geheel getal gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Schrijft de tekenreeksrepresentatie van een 64-bit unsigned geheel getal gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Schrijft de tekenreeksrepresentatie van de opgegeven tekenarray gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schrijft de tekenreeksrepresentatie van een reeks waarden van de opgegeven tekenarray gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(const char_t *) override | Schrijft de opgegeven c-string gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Schrijft de tekenreeksrepresentatie van het opgegeven [TypeInfo](../typeinfo/)-object gevolgd door het huidige regeleinde naar de uitvoerstream die door het huidige object wordt vertegenwoordigd. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat gevolgd door de regeleinde-tekens naar de stream. |
| virtual  [~Object](../object/~object/)() | Vernietigt het object. Bevrijdt alle interne datastructuren. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destructeur. |

## Zie ook

* Klasse [TextWriter](../../system.io/textwriter/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)