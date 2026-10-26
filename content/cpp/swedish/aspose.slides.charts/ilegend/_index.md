---
title: ILegend
second_title: Aspose.Slides för C++ API-referens
description: Representerar diagrammets legendegenskaper.
type: docs
weight: 1080
url: /sv/aspose.slides.charts/ilegend/
---
## ILegend klass

Representerar diagrammets legendegenskaper.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Anger den faktiska höjden för diagrammets element. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) innan för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Anger den faktiska bredden för diagrammets element. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) innan för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Anger den faktiska x-positionen (vänster) för diagrammets element relativt diagrammets övre vänstra hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) innan för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Anger den faktiska toppen för diagrammets element relativt diagrammets övre vänstra hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) innan för att få faktiska värden. Läs **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Hämtar toppen för diagrammets element som en bråkdel av diagrammets höjd. Skrivskyddad **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Skrivskyddad [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Hämtar legendposter. Skrivskyddad [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Hämtar egenskaper för legendposten som motsvarar datapunkten i diagrammet vid det angivna indexet. För diagramtyperna: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, tas datapunkten från den första serien. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Returnerar formatet för en legend. Skrivskyddad [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Anger diagrammets elements höjd som en bråkdel av diagrammets höjd. Läs **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Avgör om andra diagrammets element får överlappa legend. Läs **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Anger legendens position på ett diagram. Icke-NaN-värden för X, Y, Width, Heigt åsidosätter effekten av denna egenskap. Läs [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Hämtar diagrammets elements högra sida som en bråkdel av diagrammets bredd. Skrivskyddad **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar grundsliden. Skrivskyddad [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returnerar diagrammets textformat. Skrivskyddad [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Anger diagrammets elements bredd som en bråkdel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Anger diagrammets elements x-position (vänster) som en bråkdel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Anger diagrammets elements topp som en bråkdel av diagrammets höjd. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör copy-konstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör copy-konstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr per referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Anger diagrammets elements höjd som en bråkdel av diagrammets höjd. Skriv **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Avgör om andra diagrammets element får överlappa legend. Skriv **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Anger legendens position på ett diagram. Icke-NaN-värden för X, Y, Width, Heigt-egenskaperna åsidosätter effekten av denna egenskap. Skriv [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Anger diagrammets elements bredd som en bråkdel av diagrammets bredd. Skriv **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Anger diagrammets elements x-position (vänster) som en bråkdel av diagrammets bredd. Skriv **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Anger diagrammets elements topp som en bråkdel av diagrammets höjd. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning för C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [ILayoutable](../ilayoutable/)
* Klass [IFormattedTextContainer](../iformattedtextcontainer/)
* Klass [IActualLayout](../iactuallayout/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)