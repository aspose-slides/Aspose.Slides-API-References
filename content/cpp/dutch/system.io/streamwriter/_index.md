---
title: StreamWriter
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een schrijver voor die tekens naar een byte-stream schrijft. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject()-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Plaats deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 391
url: /nl/system.io/streamwriter/
---
## StreamWriter klasse


Stelt een schrijver voor die tekens naar een byte-stream schrijft. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Plaats deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Close](./close/)() override | Sluit de stream en geeft verworven bronnen vrij. |
| void [Dispose](./dispose/)() override | Geeft alle bronnen vrij die door het huidige object worden gebruikt en sluit de onderliggende stream. |
| virtual void [Dispose](./dispose/)(**bool**) | Geeft alle bronnen vrij die door het huidige object worden gebruikt en sluit de onderliggende stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [Flush](./flush/)() override | Leegt de inhoud van de buffer naar de onderliggende stream en leegt vervolgens de onderliggende stream. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Geeft een waarde terug die aangeeft of [StreamWriter](./) de gegevens naar de onderliggende stream zal leegmaken elke keer dat methode [StreamWriter::Write](./write/) wordt aangeroepen. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Geeft een shared pointer terug naar een object dat de onderliggende stream vertegenwoordigt. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Geeft de momenteel gebruikte codering terug. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Geeft het momenteel gebruikte [IFormatProvider](../../system/iformatprovider/)-object terug. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Geeft het momenteel gebruikte [IFormatProvider](../../system/iformatprovider/)-object terug. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Geeft een regel-terminator tekenreeks terug. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Geeft een regel-terminator tekenreeks terug. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakerobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopie-construeren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopie-construeren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Geeft een waarde terug die aangeeft of [StreamWriter](./) de gegevens moet leegmaken naar de onderliggende stream elke keer dat methode [StreamWriter::Write](./write/) wordt aangeroepen. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Stelt een regel-terminator tekenreeks in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van shared). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construeert een instantie van [StreamWriter](./)-object die tekens schrijft naar de opgegeven onderliggende stream met UTF-8-codering en een buffer met standaardgrootte van 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Construeert een instantie van [StreamWriter](./)-object die tekens schrijft naar de opgegeven onderliggende stream met de gespecificeerde codering en een buffer met standaardgrootte van 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Construeert een instantie van [StreamWriter](./)-object die tekens schrijft naar de opgegeven onderliggende stream met de gespecificeerde codering en een buffer van de opgegeven grootte. Een parameter specificeert of de onderliggende stream moet worden gesloten wanneer het [StreamWriter](./)-object wordt vrijgegeven. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Construeert een instantie van [StreamWriter](./)-object die tekens schrijft naar het opgegeven bestand met UTF-8-codering en een buffer met standaardgrootte van 1024 bytes. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Construeert een instantie van [StreamWriter](./)-object die tekens schrijft naar het opgegeven bestand met de gespecificeerde codering en een buffer met standaardgrootte van 1024 bytes. Een parameter specificeert of de gegevens aan het bestand moeten worden toegevoegd of dat het bestand moet worden overschreven. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Construeert een instantie van [StreamWriter](./)-object die tekens schrijft naar het opgegeven bestand met de gespecificeerde codering en buffergrootte. Een parameter specificeert of de gegevens aan het bestand moeten worden toegevoegd of dat het bestand moet worden overschreven. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakerobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [Write](./write/)(char_t) override | Schrijft het opgegeven teken naar de stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Schrijft de opgegeven string naar de stream. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Schrijft de tekenreeksrepresentatie van het opgegeven object naar de stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Schrijft alle tekens van de opgegeven array naar de stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van UTF-16-tekens van de opgegeven tekenarray naar de stream. |
| void [Write](./write/)(const char_t *) override | Schrijft de opgegeven c-string naar de stream. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Schrijft de tekenreeksrepresentatie van het opgegeven object naar de stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Schrijft de tekenreeksrepresentatie van de opgegeven booleaanse waarde naar de stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Schrijft de tekenreeksrepresentatie van het opgegeven [Decimal](../../system/decimal/)-object naar de stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Schrijft de tekenreeksrepresentatie van de opgegeven double-precisie floating point-waarde naar de stream. |
| virtual void [Write](../textwriter/write/)(int) | Schrijft de tekenreeksrepresentatie van de opgegeven 32-bit gehele getalwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven 64-bit gehele getalwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Schrijft de tekenreeksrepresentatie van de opgegeven single-precisie floating point-waarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 32-bit gehele getalwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 64-bit gehele getalwaarde naar de stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Schrijft de tekenreeksrepresentatie van het opgegeven [TypeInfo](../../system/typeinfo/)-object naar de stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat naar de stream. |
| void [WriteLine](./writeline/)() override | Schrijft regel-terminator tekens naar de stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Schrijft de opgegeven string gevolgd door de regel-terminator tekens naar de stream. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Schrijft de tekenreeksrepresentatie van het opgegeven object gevolgd door de regel-terminator tekens naar de stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Schrijft alle tekens van de opgegeven array gevolgd door de regel-terminator tekens naar de stream. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Schrijft het opgegeven subbereik van UTF-16-tekens van de opgegeven tekenarray gevolgd door de regel-terminator tekens naar de stream. |
| void [WriteLine](./writeline/)(const char_t *) override | Schrijft de opgegeven c-string gevolgd door de regel-terminator tekens naar de stream. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Schrijft de tekenreeksrepresentatie van het opgegeven object gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Schrijft de tekenreeksrepresentatie van de opgegeven booleaanse waarde gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Schrijft het opgegeven teken gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Schrijft de tekenreeksrepresentatie van het opgegeven [Decimal](../../system/decimal/)-object gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Schrijft de tekenreeksrepresentatie van de opgegeven double-precisie floating point-waarde gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Schrijft de tekenreeksrepresentatie van de opgegeven 32-bit gehele getalwaarde gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven 64-bit gehele getalwaarde gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Schrijft de tekenreeksrepresentatie van de opgegeven single-precisie floating point-waarde gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 32-bit gehele getalwaarde gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Schrijft de tekenreeksrepresentatie van de opgegeven unsigned 64-bit gehele getalwaarde gevolgd door de regel-terminator tekens naar de stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Schrijft de tekenreeksrepresentatie van het opgegeven [TypeInfo](../../system/typeinfo/)-object gevolgd door de regel-terminator tekens naar de stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Schrijft de opgegeven waarden geformatteerd volgens het opgegeven formaat gevolgd door de regel-terminator tekens naar de stream. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
|  [~StreamWriter](./~streamwriter/)() | Destructor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destructor. |
## Zie ook

* Klasse [TextWriter](../textwriter/)
* Naamruimte [System::IO](../)
* Library [Aspose.Slides](../../)