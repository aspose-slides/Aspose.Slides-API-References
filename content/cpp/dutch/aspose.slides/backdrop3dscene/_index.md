---
title: Backdrop3DScene
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert een vlak waarin effecten, zoals gloed en schaduw, worden toegepast in relatie tot de vorm waarop ze worden toegepast.
type: docs
weight: 92
url: /nl/aspose.slides/backdrop3dscene/
---
## Backdrop3DScene klasse


Definieert een vlak waarin effecten, zoals gloed en schaduw, worden toegepast ten opzichte van de vorm waarop ze worden toegepast.

```cpp
class Backdrop3DScene : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IBackdrop3DScene
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige vergelijking van zwevende komma waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige vergelijking van zwevende komma waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() override | Retourneert een punt in 3D-ruimte. Dit punt is het punt in de ruimte dat het achtergrondvlak verankert. 3D-punt wordt weergegeven door een array van 3 float-waarden die X-, Y- en Z-coördinaten definiëren. Lezen **float**[]. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() override | Retourneert een normale vector. Meer precies, dit attribuut definieert een vector die loodrecht staat op het oppervlak van het achtergrondvlak. Vector wordt weergegeven door een array van 3 float-waarden die X-, Y- en Z-coördinaten definiëren. Lezen **float**[]. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate-object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert bovenliggend [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() override | Retourneert een vector die 'up' vertegenwoordigt. Meer precies, dit attribuut definieert een vector die 'up' aangeeft ten opzichte van het oppervlak van het achtergrondvlak. Vector wordt weergegeven door een array van 3 float-waarden die X-, Y- en Z-coördinaten definiëren. Lezen **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die bij het object hoort. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hashcode. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analogie van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een value-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert gedeelde referentieteller met opgegeven waarde. |
| void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Stelt een punt in 3D-ruimte in. Dit punt is het punt in de ruimte dat het achtergrondvlak verankert. 3D-punt wordt weergegeven door een array van 3 float-waarden die X-, Y- en Z-coördinaten definiëren. Schrijf **float**[]. |
| void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Stelt een normale vector in. Meer precies, dit attribuut definieert een vector die loodrecht staat op het oppervlak van het achtergrondvlak. Vector wordt weergegeven door een array van 3 float-waarden die X-, Y- en Z-coördinaten definiëren. Schrijf **float**[]. |
| void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Stelt een vector in die 'up' vertegenwoordigt. Meer precies, dit attribuut definieert een vector die 'up' aangeeft ten opzichte van het oppervlak van het achtergrondvlak. Vector wordt weergegeven door een array van 3 float-waarden die X-, Y- en Z-coördinaten definiëren. Schrijf **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |
## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [IBackdrop3DScene](../ibackdrop3dscene/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)