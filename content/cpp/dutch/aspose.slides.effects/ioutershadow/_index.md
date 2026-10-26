---
title: IOuterShadow
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een Outer Shadow-effect voor.
type: docs
weight: 885
url: /nl/aspose.slides.effects/ioutershadow/
---
## IOuterShadow klasse


Stelt een Outer Shadow-effect voor.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radius, in punten. Standaardwaarde \\u2013 0 pt. Read **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Richting van de schaduw, in graden. Standaardwaarde \\u2013 0 \\u00B0 (links-naar-rechts). Read **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Afstand van de schaduw tot het object, in punten. Standaardwaarde \\u2013 0 pt. Read **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Rechthoekuitlijning. Standaardwaarde \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Read [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Geeft aan of de schaduw meedraait met de vorm. Standaardwaarde \\u2013 true. Read **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Horizontale schaalfactor, in procent van de oorspronkelijke grootte. Negatieve schaling veroorzaakt een omkering. Standaardwaarde \\u2013 100 %. Read **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Verticale schaalfactor, in procent van de oorspronkelijke grootte. Negatieve schaling veroorzaakt een omkering. Standaardwaarde \\u2013 100 %. Read **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Kleur van de schaduw. Standaardwaarde \\u2013 automatisch zwart (thema-afhankelijk). Read-only [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Horizontale scheefhoek, in graden. Standaardwaarde \\u2013 0 \\u00B0. Read **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Verticale scheefhoek, in graden. Standaardwaarde \\u2013 0 \\u00B0. Read **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Haalt de effectieve gegevens op met de toegepaste overerving. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waakhondobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment-operator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radius, in punten. Standaardwaarde \\u2013 0 pt. Write **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Richting van de schaduw, in graden. Standaardwaarde \\u2013 0 \\u00B0 (links-naar-rechts). Write **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Afstand van de schaduw tot het object, in punten. Standaardwaarde \\u2013 0 pt. Write **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Rechthoekuitlijning. Standaardwaarde \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Write [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Geeft aan of de schaduw meedraait met de vorm. Standaardwaarde \\u2013 true. Write **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Horizontale schaalfactor, in procent van de oorspronkelijke grootte. Negatieve schaling veroorzaakt een omkering. Standaardwaarde \\u2013 100 %. Write **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Verticale schaalfactor, in procent van de oorspronkelijke grootte. Negatieve schaling veroorzaakt een omkering. Standaardwaarde \\u2013 100 %. Write **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Horizontale scheefhoek, in graden. Standaardwaarde \\u2013 0 \\u00B0. Write **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Verticale scheefhoek, in graden. Standaardwaarde \\u2013 0 \\u00B0. Write **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waakhondobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne gegevensstructuren. |

## Zie ook

* Klasse [IImageTransformOperation](../iimagetransformoperation/)
* Klasse [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Bibliotheek [Aspose.Slides](../../)