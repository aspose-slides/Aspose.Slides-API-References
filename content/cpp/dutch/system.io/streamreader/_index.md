---
title: StreamReader
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een lezer voor die tekens leest van een byte-stream. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit tot runtime-fouten en/of assertiefouten leidt. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 378
url: /nl/system.io/streamreader/
---
## StreamReader klasse


Stelt een lezer voor die tekens leest van een byte-stream. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit tot runtime-fouten en/of assertiefouten leidt. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class StreamReader : public System::IO::TextReader
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Close](./close/)() override | Sluit de huidige en onderliggende streams. |
| virtual void [Dispose](./dispose/)(**bool**) | Verwijdert alle bronnen die door het huidige object worden gebruikt en sluit de onderliggende stream. |
| void [Dispose](./dispose/)() override | Verwijdert alle bronnen die door het huidige object worden gebruikt en sluit de onderliggende stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagelijk vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Retourneert een shared pointer naar een object dat de onderliggende stream vertegenwoordigt. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Retourneert de momenteel gebruikte codering. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Retourneert een waarde die aangeeft of het einde van de stream is bereikt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type dat door targetType wordt beschreven, vertegenwoordigt. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| int [Peek](./peek/)() override | Leest een enkel teken uit de stream zonder de leescursor van de stream te wijzigen. |
| int [Read](./read/)() override | Leest een enkel teken uit de stream. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Leest het opgegeven aantal tekens uit de stream, zet ze om naar UTF-16-codering en schrijft de resulterende UTF-16-tekens naar de opgegeven tekenarray beginnend op de opgegeven positie. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Leest het opgegeven maximale aantal tekens van de huidige tekstlezer en schrijft de gegevens naar een buffer, beginnend op de opgegeven index. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Leest tekens uit de stream tot het einde van de huidige regel. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Leest tekens uit de stream tot het einde van de stream. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiedata van een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een weak pointer (in plaats van shared). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van de gespecificeerde onderliggende stream met UTF-8-codering en een buffer met standaardgrootte van 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van de gespecificeerde onderliggende stream met UTF-8-codering en een buffer met standaardgrootte van 1024 bytes. Een parameter geeft aan of byte-order-mark-detectie moet worden ingeschakeld. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van de gespecificeerde onderliggende stream met de opgegeven codering en een buffer met standaardgrootte van 1024 bytes. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van de gespecificeerde onderliggende stream met de opgegeven codering en een buffer met standaardgrootte van 1024 bytes. Een parameter geeft aan of byte-order-mark-detectie moet worden ingeschakeld. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van de gespecificeerde onderliggende stream met de opgegeven codering en een buffer van de opgegeven grootte. Een parameter geeft aan of byte-order-mark-detectie moet worden ingeschakeld. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van het gespecificeerde bestand met UTF-8-codering en een buffer met standaardgrootte van 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van het gespecificeerde bestand met UTF-8-codering en een buffer met standaardgrootte van 4096 bytes. Een parameter geeft aan of byte-order-mark-detectie moet worden ingeschakeld. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van het gespecificeerde bestand met de opgegeven codering en een buffer met standaardgrootte van 4096 bytes. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van de gespecificeerde onderliggende stream met de opgegeven codering en een buffer met standaardgrootte van 4096 bytes. Een parameter geeft aan of byte-order-mark-detectie moet worden ingeschakeld. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Construeert een instantie van [StreamReader](./)-object dat tekens leest van het gespecificeerde bestand met de opgegeven codering en een buffer van de opgegeven grootte. Een parameter geeft aan of byte-order-mark-detectie moet worden ingeschakeld. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |
|  [~StreamReader](./~streamreader/)() | Destructeur. |
## Zie ook

* Klasse [TextReader](../textreader/)
* Namespace [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)