---
title: MathPortion
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt een gedeelte met wiskundige context voor.
type: docs
weight: 1041
url: /nl/aspose.slides.mathtext/mathportion/
---
## MathPortion klasse


Stelt een gedeelte met wiskundige context voor.

```cpp
class MathPortion : public Aspose::Slides::Portion,
                    public Aspose::Slides::MathText::IMathPortion
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AddField](../../aspose.slides/portion/addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../../aspose.slides/ifieldtype/)\>) override | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| void [AddField](../../aspose.slides/portion/addfield/)([System::String](../../system/string/)) override | Converteert dit gedeelte naar het automatisch bijgewerkte veld. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../../aspose.slides/ifield/)\> [get_Field](../../aspose.slides/portion/get_field/)() override | Retourneert een veld van dit gedeelte. Alleen-lezen [IField](../../aspose.slides/ifield/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathParagraph](../imathparagraph/)\> [get_MathParagraph](./get_mathparagraph/)() override | Wiskundige alinea |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../../aspose.slides/iportionformat/)\> [get_PortionFormat](../../aspose.slides/portion/get_portionformat/)() override | Retourneert een opmaakobject dat expliciet ingestelde opmaak-eigenschappen van het tekstgedeelte bevat zonder erfenis toegepast. Alleen-lezen [IPortionFormat](../../aspose.slides/iportionformat/). |
| [System::String](../../system/string/) [get_Text](../../aspose.slides/portion/get_text/)() override | Haalt de platte tekst van een gedeelte op. Lees [System::String](../../system/string/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](../../aspose.slides/portion/getcoordinates/)() override | Haalt de coördinaten op van het begin van het gedeelte. De X-coördinaat van het punt vertegenwoordigt het begin van het gedeelte vanaf het eerste teken inclusief linker-side-bearing. De Y-coördinaat omvat de bovenste side-bearing. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die met het object is geassocieerd. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](../../aspose.slides/portion/getrect/)() override | Haalt de coördinaten op van de rechthoek die het gedeelte omsluit. De rechthoek omvat alle tekstregels in het gedeelte, inclusief lege. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
|  [MathPortion](./mathportion/)() | Initialiseert een nieuw exemplaar van de [MathPortion](./) klasse. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert simpelweg een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert simpelweg een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
|  [Portion](../../aspose.slides/portion/portion/)() | Initialiseert een nieuw exemplaar van de [Portion](../../aspose.slides/portion/) klasse. |
|  [Portion](../../aspose.slides/portion/portion/)([System::String](../../system/string/)) | Initialiseert een nieuw exemplaar van de [Portion](../../aspose.slides/portion/) klasse. |
|  [Portion](../../aspose.slides/portion/portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](../../aspose.slides/portion/)\>) | Initialiseert een nieuw exemplaar van de [Portion](../../aspose.slides/portion/) klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referentie-vergelijkt waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemoveField](../../aspose.slides/portion/removefield/)() override | Converteert dit veld-gedeelte naar het eenvoudige gedeelte. |
| void [set_Text](../../aspose.slides/portion/set_text/)([System::String](../../system/string/)) override | Stelt de platte tekst van een gedeelte in. Schrijf [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijgave van alle interne datastructuren. |

## Opmerkingen


Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Zie ook

* Klasse [Portion](../../aspose.slides/portion/)
* Klasse [IMathPortion](../imathportion/)
* Naamruimte [Aspose::Slides::MathText](../)
* Bibliotheek [Aspose.Slides](../../)