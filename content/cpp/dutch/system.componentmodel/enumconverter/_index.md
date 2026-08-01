---
title: EnumConverter
second_title: Aspose.Slides voor C++ API-referentie
description: "Dummy-klasse voor het gebruik van EnumConverter met vertaalde code om te compileren. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 105
url: /nl/system.componentmodel/enumconverter/
---
## EnumConverter klasse

Dummy-klasse voor het gebruik van EnumConverter met vertaalde code om te compileren. Objecten van deze klasse moeten alleen worden gealloceerd met de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, want dit zal resulteren in runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class EnumConverter : public System::ComponentModel::TypeConverter
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [CanConvertFrom](./canconvertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Controleert of typen converteerbaar zijn; niet geïmplementeerd. |
| **bool** [CanConvertTo](./canconvertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Controleert of typen converteerbaar zijn; niet geïmplementeerd. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](./convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) override | Voert de daadwerkelijke typeconversie uit; niet geïmplementeerd. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Converteert objecten. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Converteert string naar object. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../typeconverter/convertfrominvariantstring/)(const [System::String](../../system/string/)\&) | Converteert invariante string naar object. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../typeconverter/convertfrominvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Converteert invariante string naar object. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::String](../../system/string/)\&) | Converteert string naar object. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Converteert string naar object. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Converteert string naar object. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](./convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) override | Voert de daadwerkelijke typeconversie uit; niet geïmplementeerd. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](../typeconverter/convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Converteert object naar specifiek type. |
| [System::String](../../system/string/) [ConvertToInvariantString](../typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Converteert object naar invariante string. |
| [System::String](../../system/string/) [ConvertToInvariantString](../typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Converteert object naar invariante string. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Converteert object naar string. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Converteert object naar string. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Converteert object naar string. |
|  [EnumConverter](./enumconverter/)(const [System::TypeInfo](../../system/typeinfo/)\&) | RTTI-informatie. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| const [System::TypeInfo](../../system/typeinfo/)\& [get_EnumType](./get_enumtype/)() | Haalt enum-type [EnumConverter](./) op waarmee gewerkt wordt; niet geïmplementeerd. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde-type-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
|  [TypeConverter](../typeconverter/typeconverter/)() | Constructor. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [TypeConverter](../typeconverter/)
* Naamruimte [System::ComponentModel](../)
* Bibliotheek [Aspose.Slides](../../)