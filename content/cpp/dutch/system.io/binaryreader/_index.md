---
title: BinaryReader
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een lezer voor die primitieve gegevenstypen leest als binaire gegevens in een specifieke codering. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met de operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 92
url: /nl/system.io/binaryreader/
---
## BinaryReader klasse

Stelt een lezer voor die primitieve gegevenstypen leest als binaire gegevens in een bepaalde codering. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met de operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven.

```cpp
class BinaryReader : public System::IDisposable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construeert een instantie van de [BinaryReader](./) klasse die gegevens leest van de opgegeven stream met UTF-8-codering. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Construeert een instantie van de [BinaryReader](./) klasse die gegevens leest van de opgegeven stream met de opgegeven codering. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Construeert een instantie van de [BinaryReader](./) klasse die gegevens leest van de opgegeven stream met de opgegeven codering. |
| virtual void [Close](./close/)() | Sluit het huidige [BinaryReader](./) object en de onderliggende invoerstroom. |
| void [Dispose](./dispose/)() override | Bevrijdt alle bronnen die door het huidige object worden gebruikt en sluit de onderliggende stream. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommap vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommap vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Retourneert de invoerstroom. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschrijft door targetType. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert slechts een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| virtual int [PeekChar](./peekchar/)() | Leest één teken van de invoerstroom zonder de leescursor van de stream te verplaatsen. |
| virtual int [Read](./read/)() | Leest één teken van de invoerstroom. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Leest het opgegeven aantal bytes van de invoerstroom en schrijft ze naar de opgegeven byte-array. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Leest het opgegeven aantal tekens van de invoerstroom, converteert ze naar UTF-16-codering en schrijft de resulterende UTF-16-tekens naar de opgegeven tekenarray beginnend op de opgegeven positie. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Leest één byte van de invoerstroom en retourneert de bool-representatie. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Leest één byte van de invoerstroom. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Leest het opgegeven aantal bytes van de invoerstroom. |
| virtual char_t [ReadChar](./readchar/)() | Leest één teken van de invoerstroom. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Leest het opgegeven aantal tekens van de invoerstroom en retourneert ze in UTF-16-codering. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NIET GEREALISEERD. |
| virtual **double** [ReadDouble](./readdouble/)() | Leest 8 bytes van de invoerstroom en retourneert ze als een double-precisie zwevend-komma-waarde. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Leest 2 bytes van de invoerstroom en retourneert ze als een 16-bit geheel getal. |
| virtual int [ReadInt32](./readint32/)() | Leest 4 bytes van de invoerstroom en retourneert ze als een 32-bit geheel getal. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Leest 8 bytes van de invoerstroom en retourneert ze als een 64-bit geheel getal. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Leest één byte van de invoerstroom en retourneert het als een ondertekend 8-bit geheel getal. |
| virtual **float** [ReadSingle](./readsingle/)() | Leest 4 bytes van de invoerstroom en retourneert ze als een enkele-precisie zwevend-komma-waarde. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Leest een string van de huidige stream. De string heeft een prefix met de lengte, gecodeerd als een integer van zeven bits per keer. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Leest 2 bytes van de invoerstroom en retourneert ze als een ongeondertekend 16-bit geheel getal. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Leest 4 bytes van de invoerstroom en retourneert ze als een ongeondertekend 32-bit geheel getal. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Leest 8 bytes van de invoerstream en retourneert ze als een ongeondertekend 64-bit geheel getal. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentieteller en retourneert deze. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock() statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Bevrijdt alle interne datastructuren. |

## Zie ook

* Klasse [IDisposable](../../system/idisposable/)
* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)