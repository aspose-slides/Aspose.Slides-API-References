---
title: LineFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het formaat van een lijn voor.
type: docs
weight: 4382
url: /nl/aspose.slides/lineformat/
---
## LineFormat klasse

Stelt het formaat van een lijn voor.

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | Bepaalt of de twee [LineFormat](./) instanties gelijk zijn. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagelijken vergelijk waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagelijken vergelijk waarbij twee NaN-waarden als gelijk worden beschouwd, zelfs al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | Retourneert de uitlijning van de lijn. Lees [LineAlignment](../linealignment/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | Retourneert de lengte van de pijlpunt aan het begin van een lijn. Lees [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | Retourneert de stijl van de pijlpunt aan het begin van een lijn. Lees [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | Retourneert de breedte van de pijlpunt aan het begin van een lijn. Lees [LineArrowheadWidth](../linearrowheadwidth/). |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | Retourneert de stijl van de lijnkap. Lees [LineCapStyle](../linecapstyle/). |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | Retourneert het aangepaste streeppatroon. Lees **float**[]. |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | Retourneert de streepstijl van de lijn. Lees [LineDashStyle](../linedashstyle/). |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | Retourneert de lengte van de pijlpunt aan het einde van een lijn. Lees [LineArrowheadLength](../linearrowheadlength/). |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | Retourneert de stijl van de pijlpunt aan het einde van een lijn. Lees [LineArrowheadStyle](../linearrowheadstyle/). |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | Retourneert de breedte van de pijlpunt aan het einde van een lijn. Lees [LineArrowheadWidth](../linearrowheadwidth/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | Retourneert het opvulformaat van een lijn. Alleen-lezen [ILineFillFormat](../ilinefillformat/). |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | Retourneert true als het lijnformaat niet is gedefinieerd (net gemaakt, standaard). Alleen-lezen **bool**. |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | Retourneert de verbindingsstijl van de lijnen. Lees [LineJoinStyle](../linejoinstyle/). |
| **float** [get_MiterLimit](./get_miterlimit/)() override | Retourneert de voeglimiet van een lijn. Lees **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate-object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert ouder [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | Retourneert het schetsformaat van een lijn. Alleen-lezen [ILineFillFormat](../ilinefillformat/). |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | Retourneert de lijnstijl. Lees [LineStyle](../linestyle/). |
| **double** [get_Width](./get_width/)() override | Retourneert de breedte van een lijn. Lees **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | Haalt effectieve lijnformateergegevens op met de toegepaste overerving. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hashcode. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analogie van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt het klonen van aangepaste types in staat. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copyconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt per referentie een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | Stelt de uitlijning van de lijn in. Schrijf [LineAlignment](../linealignment/). |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Stelt de lengte van de pijlpunt aan het begin van een lijn in. Schrijf [LineArrowheadLength](../linearrowheadlength/). |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Stelt de stijl van de pijlpunt aan het begin van een lijn in. Schrijf [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Stelt de breedte van de pijlpunt aan het begin van een lijn in. Schrijf [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | Stelt de stijl van de lijnkap in. Schrijf [LineCapStyle](../linecapstyle/). |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | Stelt het aangepaste streeppatroon in. Schrijf **float**[]. |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | Stelt de streepstijl van de lijn in. Schrijf [LineDashStyle](../linedashstyle/). |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | Stelt de lengte van de pijlpunt aan het einde van een lijn in. Schrijf [LineArrowheadLength](../linearrowheadlength/). |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | Stelt de stijl van de pijlpunt aan het einde van een lijn in. Schrijf [LineArrowheadStyle](../linearrowheadstyle/). |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | Stelt de breedte van de pijlpunt aan het einde van een lijn in. Schrijf [LineArrowheadWidth](../linearrowheadwidth/). |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | Stelt de verbindingsstijl van de lijnen in. Schrijf [LineJoinStyle](../linejoinstyle/). |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | Stelt de voeglimiet van een lijn in. Schrijf **float**. |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | Stelt de lijnstijl in. Schrijf [LineStyle](../linestyle/). |
| void [set_Width](./set_width/)(**double**) override | Stelt de breedte van een lijn in. Schrijf **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt het converteren van aangepaste objecten naar string in staat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [ILineFormat](../ilineformat/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)