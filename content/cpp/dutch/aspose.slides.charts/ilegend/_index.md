---
title: ILegend
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de legende-eigenschappen van de grafiek voor.
type: docs
weight: 1080
url: /nl/aspose.slides.charts/ilegend/
---
## ILegend klasse

Stelt de eigenschappen van de legenda van de grafiek voor.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl vergelijking van zwevende-komma-waarden waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl vergelijking van zwevende-komma-waarden waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Geeft de werkelijke hoogte van het grafiekelement op. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Leest **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Geeft de werkelijke breedte van het grafiekelement op. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Leest **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Geeft de werkelijke x-locatie (links) van het grafiekelement relatief ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Leest **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Geeft de werkelijke bovenkant van het grafiekelement relatief ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Leest **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Haalt de bovenkant van het grafiekelement op als een fractie van de hoogte van de grafiek. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Geeft de grafiek terug. Alleen-lezen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Haalt de legenda-items op. Alleen-lezen [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Haalt de eigenschappen op van het legenda-item dat overeenkomt met het datapunten in de grafiek op de opgegeven index. Bij grafiektype-s: staaf-van-taart, geëxplodeerde taart, geëxplodeerde taart 3D, taart, taart 3D, taart-van-taart, wordt het datapunten genomen uit de eerste serie. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Geeft het formaat van een legenda terug. Alleen-lezen [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Geeft de hoogte van het grafiekelement op als een fractie van de hoogte van de grafiek. Leest **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Bepaalt of andere grafiekelementen de legenda mogen overlappen. Leest **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Geeft de positie van de legenda op een grafiek op. Niet-NaN-waarden van X, Y, Width, Height-eigenschappen overschrijven het effect van deze eigenschap. Leest [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Geeft de presentatie terug. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Haalt de rechterkant van het grafiekelement op als een fractie van de breedte van de grafiek. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Geeft de basis-dia terug. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Geeft het tekstformaat van de grafiek terug. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Geeft de breedte van het grafiekelement op als een fractie van de breedte van de grafiek. Leest **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Geeft de x-locatie (links) van het grafiekelement op als een fractie van de breedte van de grafiek. Leest **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Geeft de bovenkant van het grafiekelement op als een fractie van de hoogte van de grafiek. Leest **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Stelt de hoogte van het grafiekelement in als een fractie van de hoogte van de grafiek. Schrijf **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Bepaalt of andere grafiekelementen de legenda mogen overlappen. Schrijf **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Stelt de positie van de legenda op een grafiek in. Niet-NaN-waarden van X, Y, Width, Heigt-eigenschappen overschrijven het effect van deze eigenschap. Schrijf [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Stelt de breedte van het grafiekelement in als een fractie van de breedte van de grafiek. Schrijf **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Stelt de x-locatie (links) van het grafiekelement in als een fractie van de breedte van de grafiek. Schrijf **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Stelt de bovenkant van het grafiekelement in als een fractie van de hoogte van de grafiek. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloon-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ILayoutable](../ilayoutable/)
* Klasse [IFormattedTextContainer](../iformattedtextcontainer/)
* Klasse [IActualLayout](../iactuallayout/)
* Naamruimte [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)