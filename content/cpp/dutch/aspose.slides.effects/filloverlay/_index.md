---
title: FillOverlay
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een Fill Overlay-effect voor. Een fill overlay kan worden gebruikt om een extra vulling voor een object te specificeren en de twee vullingen samen te mengen.
type: docs
weight: 183
url: /nl/aspose.slides.effects/filloverlay/
---
## FillOverlay klasse

Stelt een Fill Overlay-effect voor. Een Fill Overlay kan worden gebruikt om een extra vulling voor een object op te geven en de twee vullingen samen te voegen.

```cpp
class FillOverlay : public Aspose::Slides::Effects::ImageTransformOperation,
                    public Aspose::Slides::Effects::IFillOverlay,
                    public Aspose::Slides::Effects::IVisualEffect
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bepaalt of de opgegeven [FillOverlay](./) gelijk is aan de huidige [FillOverlay](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [FillBlendMode](../../aspose.slides/fillblendmode/) [get_Blend](./get_blend/)() override | FillBlendMode. Lezen [FillBlendMode](../../aspose.slides/fillblendmode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Fill format. Alleen-lezen [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate-object. Alleen-lezen [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Retourneert bovenliggend [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die bij het object hoort. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlayEffectiveData](../ifilloverlayeffectivedata/)\> [GetEffective](./geteffective/)() override | Haalt effectieve Fill Overlay-effectgegevens op met de geërfde eigenschappen toegepast. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Dient als hash-functie voor een bepaald type. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement locken. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste typen in staat. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiërende constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| void [set_Blend](./set_blend/)([FillBlendMode](../../aspose.slides/fillblendmode/)) override | FillBlendMode. Schrijf [FillBlendMode](../../aspose.slides/fillblendmode/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n-de sjabloonparameter in als een zwakke pointer (in plaats van gedeeld). Stelt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendelen. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ImageTransformOperation](../imagetransformoperation/)
* Klasse [IFillOverlay](../ifilloverlay/)
* Klasse [IVisualEffect](../ivisualeffect/)
* Naamruimte [Aspose::Slides::Effects](../)
* Bibliotheek [Aspose.Slides](../../)