---
title: ChartTitle
second_title: Aspose.Slides för C++ API-referens
description: Representerar diagramrubrikens egenskaper.
type: docs
weight: 326
url: /sv/aspose.slides.charts/charttitle/
---
## ChartTitle-klass

Representerar egenskaper för diagramrubrik.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initierar TextFrameForOverriding med texten i parametern \"text\". Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Anger det faktiska höjden för diagramelementet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Anger den faktiska bredden för diagramelementet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Anger den faktiska x-positionen (vänster) för diagramelementet relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Anger den faktiska toppen för diagramelementet relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Botten. Skriva-skyddad **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returnerar föräldradiagrammet. Skriva-skyddad [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Returnerar fyllnings-, linje- och effektstilar för en titel. Skriva-skyddad [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Returnerar höjden på en titel som en bråkdel av diagrammets höjd. Läs **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Bestämmer om andra diagramelement får överlappa titel. Läs **bool**. |
| **float** [get_Right](./get_right/)() override | Höger. Skriva-skyddad **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Returnerar textformat. Skriva-skyddad [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Kan innehålla rikligt formaterad text. Om detta egenskap inte är null ersätter detta formaterade textvärde den automatiskt genererade texten. Den automatiskt genererade texten är en implicit egenskap för datalabeln, enhetsetiketten för värdeaxeln, axeltiteln, diagramtiteln, etiketten för trendlinjen. Den automatiskt genererade texten formateras med [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/)-egenskapen. Skriva-skyddad [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Returnerar bredden på en titel som en bråkdel av diagrammets bredd. Läs **float**. |
| **float** [get_X](./get_x/)() override | Returnerar x-koordinaten för en titel som en bråkdel av diagrammets bredd. Läs **float**. |
| **float** [get_Y](./get_y/)() override | Returnerar y-koordinaten för en titel som en bråkdel av diagrammets höjd. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Height](./set_height/)(**float**) override | Sätter höjden på en titel som en bråkdel av diagrammets höjd. Skriv **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Bestämmer om andra diagramelement får överlappa titel. Skriv **bool**. |
| void [set_Width](./set_width/)(**float**) override | Sätter bredden på en titel som en bråkdel av diagrammets bredd. Skriv **float**. |
| void [set_X](./set_x/)(**float**) override | Sätter x-koordinaten för en titel som en bråkdel av diagrammets bredd. Skriv **float**. |
| void [set_Y](./set_y/)(**float**) override | Sätter y-koordinaten för en titel som en bråkdel av diagrammets höjd. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en weak-pekare (snarare än shared). Tillåter att byta pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IChartTitle](../icharttitle/)
* Klass [IDOMObject](../../aspose.slides/idomobject/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)