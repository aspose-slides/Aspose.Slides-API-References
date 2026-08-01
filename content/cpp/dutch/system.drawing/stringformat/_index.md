---
title: StringFormat
second_title: Aspose.Slides voor C++ API-referentie
description: "Omvat informatie over tekstindeling, weergavemanipulaties en OpenType-functies. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 313
url: /nl/system.drawing/stringformat/
---
## StringFormat klasse


Omsluit tekstindelingsinformatie, weergavemanipulaties en OpenType-functies. Objecten van deze klasse mogen alleen worden toegewezen met behulp van [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Verpak deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument door te geven aan functies.

```cpp
class StringFormat : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [Clone](./clone/)() | Retourneert een exacte kopie van het huidige object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl floating point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl floating point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [StringAlignment](../stringalignment/) [get_Alignment](./get_alignment/)() const | Retourneert een waarde die de horizontale uitlijning van de tekenreeks aangeeft. |
| **int32_t** [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Retourneert een waarde die de taal aangeeft die wordt gebruikt wanneer lokale cijfers worden vervangen door westerse cijfers. |
| [StringDigitSubstitute](../stringdigitsubstitute/) [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Retourneert de methode voor cijfervervanging. |
| [StringFormatFlags](../stringformatflags/) [get_FormatFlags](./get_formatflags/)() const | Retourneert een bitwise combinatie van StringFormatFlags die het door het huidige object gerepresenteerde tekenreeksformaat specificeert. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericDefault](./get_genericdefault/)() | Retourneert een [StringFormat](./) object dat een generiek standaardformaat vertegenwoordigt. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericTypographic](./get_generictypographic/)() | Retourneert een [StringFormat](./) object dat een generiek typografisch formaat vertegenwoordigt. |
| [Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/) [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Retourneert de waarde die aangeeft hoe het sneltoetsvoorvoegsel wordt weergegeven. |
| [StringAlignment](../stringalignment/) [get_LineAlignment](./get_linealignment/)() const | Retourneert een waarde die de verticale uitlijning van de tekenreeks aangeeft. |
| [StringTrimming](../stringtrimming/) [get_Trimming](./get_trimming/)() const | Retourneert een waarde die aangeeft hoe de tekenreeks wordt getrimd. |
| int [GetCharacterRangesCount](./getcharacterrangescount/)() const | Haalt de grootte op van de [CharacterRange](../characterrange/) array. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashing van aangepaste objecten mogelijk. |
| [ArrayPtr](../../system/arrayptr/)\<**float**\> [GetTabStops](./gettabstops/)(**float**\&) const | Retourneert de tabstops voor het huidige [StringFormat](./) object. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type op van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep rechtstreeks aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copyconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde-type-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van tekenreeks en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van tekenreeksen. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Alignment](./set_alignment/)([StringAlignment](../stringalignment/)) | Stelt de horizontale uitlijning van de tekenreeks in. |
| void [set_FormatFlags](./set_formatflags/)([StringFormatFlags](../stringformatflags/)) | Stelt de tekenreeksformaatvlaggen in. |
| void [set_HotkeyPrefix](./set_hotkeyprefix/)([Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/)) | Stelt de waarde in die aangeeft hoe het sneltoetsvoorvoegsel moet worden weergegeven. |
| void [set_LineAlignment](./set_linealignment/)([StringAlignment](../stringalignment/)) | Stelt de verticale uitlijning van de tekenreeks in. |
| void [set_Trimming](./set_trimming/)([StringTrimming](../stringtrimming/)) | Stelt een waarde in die aangeeft hoe de tekenreeks wordt getrimd. |
| void [SetDigitSubstitution](./setdigitsubstitution/)(**int32_t**, [StringDigitSubstitute](../stringdigitsubstitute/)) | Stelt de taal en methode voor cijfervervanging in. |
| void [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const [ArrayPtr](../../system/arrayptr/)\<[CharacterRange](../characterrange/)\>\&) | Stelt een array van [CharacterRange](../characterrange/) objecten in die de tekenbereikreeksen vertegenwoordigen die gemeten worden door een aanroep van de MeasureCharacterRanges() methode. |
| void [SetTabStops](./settabstops/)(**float**, const [ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Stelt de tabstops in voor het huidige [StringFormat](./) object. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat het wisselen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde op van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [StringFormat](./stringformat/)() | Construeert een nieuw exemplaar van [StringFormat](./) klasse. |
|  [StringFormat](./stringformat/)([StringFormatFlags](../stringformatflags/), **int32_t**) | Construeert een nieuw exemplaar van [StringFormat](./) klasse met de opgegeven formaatvlaggen en taal. |
|  [StringFormat](./stringformat/)(const [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\>\&) | Copyconstructor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar tekenreeks mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep rechtstreeks aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)