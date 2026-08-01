---
title: IDataLabel
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt labels van een reeks voor.
type: docs
weight: 937
url: /nl/aspose.slides.charts/idatalabel/
---
## IDataLabel klasse

Stelt labels van een reeks voor.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialiseert TextFrameForOverriding met de tekst in de parameter \"text\". Als TextFrameForOverriding al is geïnitialiseerd, wordt de tekst eenvoudigweg aangepast. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl vergelijking van zwevendekommagetallen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl vergelijking van zwevendekommagetallen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Specificeert de werkelijke hoogte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Alleen-lezen **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Specificeert de werkelijke breedte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Alleen-lezen **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Specificeert de werkelijke x-locatie (links) van het chart-element ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Alleen-lezen **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Specificeert de werkelijke bovenkant van het chart-element ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Alleen-lezen **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Haal de bovenkant van het chart-element op als een fractie van de hoogte van de chart. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retourneert de chart. Alleen-lezen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Retourneert het formaat van het data-label. Alleen-lezen [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Specificeert de hoogte van het chart-element als een fractie van de hoogte van de chart. Alleen-lezen **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False betekent dat het data-label niet zichtbaar is (en daardoor alle Show*-vlaggen (ShowValue, ...) false zijn). Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Haal het rechterdeel van het chart-element op als een fractie van de breedte van de chart. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basis-slide. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retourneert het chart-tekstformaat. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kan een rijk opgemaakt tekst bevatten. Als deze eigenschap niet null is, overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst. Automatisch gegenereerde tekst is een impliciete eigenschap van het data-label, het weergave-eenheidslabel van de waarde-as, de as-titel, de chart-titel, het label van de trendlijn. Automatisch gegenereerde tekst wordt opgemaakt met de [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/)-eigenschap. Alleen-lezen [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Haal de workbook-datacel op. Toegepast als de eigenschap IDataLabelFormat::get(set)_ShowLabelValueFromCell true is. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Specificeert de breedte van het chart-element als een fractie van de breedte van de chart. Alleen-lezen **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Specificeert de x-locatie (links) van het chart-element als een fractie van de breedte van de chart. Alleen-lezen **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Specificeert de bovenkant van het chart-element als een fractie van de hoogte van de chart. Alleen-lezen **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Retourneert de werkelijke labeltekst op basis van de [DataLabelFormat](../datalabelformat/)-instellingen of de TextFrameForOverriding.Text-waarde. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het actuele type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual void [Hide](./hide/)() | Maak het data-label verborgen door alle Show*-vlaggen (ShowValue, ...) op false te zetten. IsVisible zal daarna false zijn. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr via referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Specificeert de hoogte van het chart-element als een fractie van de hoogte van de chart. Schrijf **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Stelt de workbook-datacel in. Toegepast als de eigenschap IDataLabelFormat::get(set)_ShowLabelValueFromCell true is. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Specificeert de breedte van het chart-element als een fractie van de breedte van de chart. Schrijf **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Specificeert de x-locatie (links) van het chart-element als een fractie van de breedte van de chart. Schrijf **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Specificeert de bovenkant van het chart-element als een fractie van de hoogte van de chart. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Stelt het mogelijk om pointers in containers over te schakelen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar een string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Verwijdert object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [ILayoutable](../ilayoutable/)
* Klasse [IOverridableText](../ioverridabletext/)
* Klasse [IActualLayout](../iactuallayout/)
* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)