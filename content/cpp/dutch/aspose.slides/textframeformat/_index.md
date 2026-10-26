---
title: TextFrameFormat
second_title: Aspose.Slides voor C++ API Referentie
description: Bevat de formatTextFrameFormatting-eigenschappen van TextFrame.
type: docs
weight: 5461
url: /nl/aspose.slides/textframeformat/
---
## TextFrameFormat klasse


Contains the [TextFrame](../textframe/)'s formatTextFrameFormatting properties.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met het opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige floating-point-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige floating-point-vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Retourneert verticale ankertekst in een [TextFrame](../textframe/). Lees [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Retourneert de autofit-modus van de tekst. Lees [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Als [NullableBool::True](../nullablebool/) dan moet de tekst horizontaal in de doos worden gecentreerd. Lees [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Retourneert het aantal kolommen in het tekstgebied. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent een ongedefinieerde waarde. Lees **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Retourneert de ruimte tussen tekstkolommen in het tekstgebied (in punten). Dit mag alleen gelden wanneer er meer dan 1 kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lees **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Haalt op of de tekst plat blijft, zelfs als er een 3-D-rotatie-effect is toegepast. Lees **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Retourneert de onderste marge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Retourneert de linker marge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Retourneert de rechter marge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Retourneert de bovenste marge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate-object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert bovenliggend [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Specificeert de aangepaste rotatie die op de tekst binnen de begrenzende doos wordt toegepast. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. De vorm kan dus een rotatie hebben naast de rotatie van de tekst zelf. De uiteindelijke visuele rotatiewaarde wordt samengevat uit deze eigenschap en de vooraf gedefinieerde verticale type in TextVerticalType. Lees **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Bepaalt de tekstrichting. De uiteindelijke visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in RotationAngle. Lees [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Retourneert het [ThreeDFormat](../threedformat/)-object dat de 3D-effecteigenschappen voor een tekst vertegenwoordigt. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Haalt de tekstomslag-vorm op. Lees [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** als de tekst is gewikkeld bij de marges van [TextFrame](../textframe/). Lees [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Haalt effectieve tekstframe-opmaakgegevens op met de toegepaste overerving. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hash-code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarbewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Stelt verticale ankertekst in een [TextFrame](../textframe/) in. Schrijf [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Stelt de autofit-modus van de tekst in. Schrijf [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Als [NullableBool::True](../nullablebool/) dan moet de tekst horizontaal in de doos worden gecentreerd. Schrijf [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Stelt het aantal kolommen in het tekstgebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent een ongedefinieerde waarde. Schrijf **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Stelt de ruimte tussen tekstkolommen in het tekstgebied in (in punten). Dit mag alleen gelden wanneer er meer dan 1 kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Schrijf **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Stelt in of de tekst plat blijft, zelfs als er een 3-D-rotatie-effect is toegepast. Schrijf **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Stelt de onderste marge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Stelt de linker marge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Stelt de rechter marge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Stelt de bovenste marge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Specificeert de aangepaste rotatie die op de tekst binnen de begrenzende doos wordt toegepast. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. De vorm kan dus een rotatie hebben naast de rotatie van de tekst zelf. De uiteindelijke visuele rotatiewaarde wordt samengevat uit deze eigenschap en de vooraf gedefinieerde verticale type in TextVerticalType. Schrijf **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Bepaalt de tekstrichting. De uiteindelijke visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in RotationAngle. Schrijf [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Stelt de tekstomslag-vorm in. Schrijf [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** als de tekst is gewikkeld bij de marges van [TextFrame](../textframe/). Schrijf [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [TextFrameFormat](./textframeformat/)() | Initialiseert een nieuwe instantie van de [TextFrameFormat](./) klasse. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarbewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Bevrijdt alle interne datastructuren. |
## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [ITextFrameFormat](../itextframeformat/)
* Klasse [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)