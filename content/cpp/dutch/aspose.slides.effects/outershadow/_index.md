---
title: OuterShadow
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een buitenschaduw-effect voor.
type: docs
weight: 1041
url: /nl/aspose.slides.effects/outershadow/
---
## OuterShadow klasse


Stelt een Outer Shadow effect voor.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Methoden

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bepaalt of de opgegeven [OuterShadow](./) gelijk is aan de huidige [OuterShadow](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagelijk vergelijken waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagelijk vergelijken waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius, in punten. Standaardwaarde – 0 pt. Lezen **double**. |
| **float** [get_Direction](./get_direction/)() override | Richting van de schaduw, in graden. Standaardwaarde – 0 ° (van links naar rechts). Lezen **float**. |
| **double** [get_Distance](./get_distance/)() override | Afstand van de schaduw tot het object, in punten. Standaardwaarde – 0 pt. Lezen **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Geeft de bovenliggende [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) terug. Alleen-lezen [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rechthoekuitlijning. Standaardwaarde – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Lezen [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Geeft aan of de schaduw meedraait met de vorm. Standaardwaarde – true. Lezen **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Horizontale schaalfactor, in procent van de originele grootte. Negatieve schaal veroorzaakt een draai. Standaardwaarde – 100 %. Lezen **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Verticale schaalfactor, in procent van de originele grootte. Negatieve schaal veroorzaakt een draai. Standaardwaarde – 100 %. Lezen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Kleur van de schaduw. Standaardwaarde – automatisch zwart (themagerelateerd). Alleen-lezen [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Horizontale scheefhoek, in graden. Standaardwaarde – 0 °. Lezen **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Verticale scheefhoek, in graden. Standaardwaarde – 0 °. Lezen **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versie. Alleen-lezen **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de referentieteller-datastructuur op die bij het object hoort. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Haal de effectieve Outer Shadow effect-gegevens op met de overgeërfde waarden toegepast. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Dient als een hash-functie voor een bepaald type. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt het object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te copy-constructen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toekenningsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te copy-constructen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object via referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius, in punten. Standaardwaarde – 0 pt. Schrijf **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Richting van de schaduw, in graden. Standaardwaarde – 0 ° (van links naar rechts). Schrijf **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Afstand van de schaduw tot het object, in punten. Standaardwaarde – 0 pt. Schrijf **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rechthoekuitlijning. Standaardwaarde – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Schrijf [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Geeft aan of de schaduw meedraait met de vorm. Standaardwaarde – true. Schrijf **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Horizontale schaalfactor, in procent van de originele grootte. Negatieve schaal veroorzaakt een draai. Standaardwaarde – 100 %. Schrijf **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Verticale schaalfactor, in procent van de originele grootte. Negatieve schaal veroorzaakt een draai. Standaardwaarde – 100 %. Schrijf **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Horizontale scheefhoek, in graden. Standaardwaarde – 0 °. Schrijf **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Verticale scheefhoek, in graden. Standaardwaarde – 0 °. Schrijf **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IOuterShadow](../ioutershadow/)
* Klasse [IVisualEffect](../ivisualeffect/)
* Klasse [IPVIObject](../../aspose.slides/ipviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)