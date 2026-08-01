---
title: IConvertible
second_title: Aspose.Slides voor C++ API-referentie
description: "Definieert methoden die de waarde van het implementerende referentie- of waardetype converteren naar een Common Language Runtime-type met een equivalente waarde. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om het als argument aan functies door te geven."
type: docs
weight: 937
url: /nl/system/iconvertible/
---
## IConvertible klasse

Definieert methoden die de waarde van het implementerende referentie- of waardetype converteren naar een Common Language Runtime-type met een equivalente waarde. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Verpak deze klasse altijd in een [System::SmartPtr](../smartptr/)-pointer en gebruik die pointer om het als argument aan functies door te geven.

```cpp
class IConvertible : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-kommagetcompare waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-kommagetcompare waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/) aanroep. |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | Retourneert de typecode voor deze instantie. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie van waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe dat pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardige [Boolean](../boolean/)-waarde met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardige 8-bit uint32_teger met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig Unicode-teken met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardige [System::DateTime](../datetime/) met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig [System::Decimal](../decimal/)-nummer met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig double-precisie zwevend-kommagetal met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie.. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig 16-bit ondertekend geheel getal met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig 32-bit ondertekend geheel getal met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig 64-bit ondertekend geheel getal met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig 8-bit ondertekend geheel getal met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardig single-precisie zwevend-kommagetal met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardige [System::String](../string/) met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual [String](../string/) [ToString](./tostring/)() const | Analoge van C# [Object.ToString()](../object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een [System::Object](../object/) van het opgegeven System::Type dat een gelijkwaardige waarde heeft, met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardige 16-bit uint32_teger met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardige 32-bit uint32_teger met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | Converteert de waarde van deze instantie naar een gelijkwaardige 64-bit uint32_teger met behulp van de gespecificeerde cultuurspecifieke opmaakinformatie. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert C# typeof([System.Object](../object/)) constructie. |
| void [Unlock](../object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |
## Zie ook

* Klasse [Object](../object/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)