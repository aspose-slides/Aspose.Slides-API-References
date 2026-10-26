---
title: Legend
second_title: Aspose.Slides för C++ API-referens
description: Representerar diagrammets legendegenskaper.
type: docs
weight: 1262
url: /sv/aspose.slides.charts/legend/
---
## Legend klass

Representerar diagrammets legendegenskaper.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Anger den faktiska höjden på diagrammets element. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Anger den faktiska bredden på diagrammets element. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Anger den faktiska x-positionen (vänster) för diagrammets element i förhållande till diagrammets övre vänstra hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Anger den faktiska toppen på diagrammets element i förhållande till diagrammets övre vänstra hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Botten. Skrivskyddad **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returnerar diagrammet. Skrivskyddad [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Hämtar legendposter. Skrivskyddad [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Hämtar egenskaper för legendpost som motsvarar datapunkt i diagrammet på angivet index. För diagramtyperna: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, tas datapunkten från den första serien. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Returnerar formatet för en legend. Skrivskyddad [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Returnerar legendens höjd som en bråkdel av diagrammets höjd. Läs **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Avgör om andra diagramelement får överlappa legenden. Läs **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Anger legendens position på ett diagram. Icke-NaN-värden för egenskaperna X, Y, Width, Heigt åsidosätter denna egenskaps effekt. Läs [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Höger. Skrivskyddad **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Textformat. Skrivskyddad [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Returnerar legendens bredd som en bråkdel av diagrammets bredd. Läs **float**. |
| **float** [get_X](./get_x/)() override | Returnerar legendens x-koordinat som en bråkdel av diagrammets bredd. Läs **float**. |
| **float** [get_Y](./get_y/)() override | Returnerar legendens y-koordinat som en bråkdel av diagrammets höjd. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| void [set_Height](./set_height/)(**float**) override | Sätter legendens höjd som en bråkdel av diagrammets höjd. Skriv **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Avgör om andra diagramelement får överlappa legenden. Skriv **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Anger legendens position på ett diagram. Icke-NaN-värden för X, Y, Width, Heigt-egenskaper åsidosätter denna egenskaps effekt. Skriv [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Sätter legendens bredd som en bråkdel av diagrammets bredd. Skriv **float**. |
| void [set_X](./set_x/)(**float**) override | Sätter legendens x-koordinat som en bråkdel av diagrammets bredd. Skriv **float**. |
| void [set_Y](./set_y/)(**float**) override | Sätter legendens y-koordinat som en bråkdel av diagrammets höjd. Skriv **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Sätt den n-te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräkning. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning för C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [DomObject](../../aspose.slides/domobject/)
* Klass [ILegend](../ilegend/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)