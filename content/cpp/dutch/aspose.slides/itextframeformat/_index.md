---
title: ITextFrameFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat de opmaakeigenschappen van TextFrame.
type: docs
weight: 4083
url: /nl/aspose.slides/itextframeformat/
---
## ITextFrameFormat klasse


Bevat de opmaak eigenschappen van [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Retourneert verticale ankertekst in een [TextFrame](../textframe/). Lees [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Retourneert de autofit-modus van de tekst. Lees [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Als [NullableBool::True](../nullablebool/) dan moet de tekst horizontaal gecentreerd worden in het vak. Lees [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Retourneert het aantal kolommen in het tekstgebied. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Lees **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Retourneert de ruimte tussen tekstkolommen in het tekstgebied (in punten). Dit is alleen van toepassing wanneer er meer dan 1 kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lees **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Retourneert of stelt in dat tekst volledig buiten de 3D-scene wordt gehouden. Lees **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Retourneert de ondermarge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Retourneert de linkermarge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Retourneert de rechtermarge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Retourneert de bovenmarge (punten) in een [TextFrame](../textframe/). Lees **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende doos. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lees **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Retourneert de stijl van de tekst. Alleen-lezen [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Bepaalt de tekstoriëntatie. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en de aangepaste hoek in de eigenschap RotationAngle. Lees [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Retourneert het [ThreeDFormat](../threedformat/)-object dat de 3D-effecteigenschappen voor een tekst weergeeft. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Haalt de tekstomslagvorm op. Lees [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** als de tekst is ingepakt bij de marges van [TextFrame](../textframe/). Lees [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die bij het object hoort. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Haalt de effectieve opmaakgegevens van het tekstkader op met de toegepaste overerving. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het vergrendelen van de C# lock()-instructie. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets; initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets; initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Stelt verticale ankertekst in een [TextFrame](../textframe/) in. Schrijf [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Stelt de autofit-modus van de tekst in. Schrijf [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Als [NullableBool::True](../nullablebool/) dan moet de tekst horizontaal gecentreerd worden in het vak. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Stelt het aantal kolommen in het tekstgebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Schrijf **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Stelt de ruimte tussen tekstkolommen in het tekstgebied (in punten) in. Dit is alleen van toepassing wanneer er meer dan 1 kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Schrijf **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Retourneert of stelt in dat tekst volledig buiten de 3D-scene wordt gehouden. Schrijf **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Stelt de ondermarge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Stelt de linkermarge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Stelt de rechtermarge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Stelt de bovenmarge (punten) in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende doos. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Schrijf **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Bepaalt de tekstoriëntatie. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en de aangepaste hoek in de eigenschap RotationAngle. Schrijf [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Stelt de tekstomslagvorm in. Schrijf [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** als de tekst is ingepakt bij de marges van [TextFrame](../textframe/). Schrijf [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-instructie. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijmaakt alle interne datastructuren. |
## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)