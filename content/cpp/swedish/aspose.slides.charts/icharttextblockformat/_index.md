---
title: IChartTextBlockFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar formateringsegenskaper för diagramtextelement.
type: docs
weight: 885
url: /sv/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat klass

Representerar formateringsegenskaper för diagramtextelement.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Returnerar vertikal förankringstext i en [TextFrame](../../aspose.slides/textframe/). Läs [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Returnerar textens autofit-läge. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Läs [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | Om [NullableBool::True](../../aspose.slides/nullablebool/) så ska texten centreras i rutan horisontellt. Läs [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Returnerar den nedre marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Läs **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Returnerar den vänstra marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Läs **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Returnerar den högra marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Läs **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Returnerar den övre marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Läs **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Anger den anpassade rotation som tillämpas på texten inom den omgivande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det betyder att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Bestämmer textorienteringen. Det resulterande värdet av visuell textrotation summeras från denna egenskap och den anpassade vinkeln i egenskapen RotationAngle. Läs [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** om texten radbryts vid [TextFrame](../../aspose.slides/textframe/)-marginalerna. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2007/2013). Läs [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Ställer in vertikal förankringstext i en [TextFrame](../../aspose.slides/textframe/). Skriv [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Ställer in textens autofit-läge. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Skriv [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | Om [NullableBool::True](../../aspose.slides/nullablebool/) så ska texten centreras horisontellt i rutan. Skriv [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ställer in den nedre marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Skriv **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ställer in den vänstra marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Skriv **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ställer in den högra marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Skriv **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ställer in den övre marginalen (punkter) i en [TextFrame](../../aspose.slides/textframe/). Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt på rendering). Skriv **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Anger den anpassade rotation som tillämpas på texten inom den omgivande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det betyder att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Skriv **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Bestämmer textorienteringen. Det resulterande värdet av visuell textrotation summeras från denna egenskap och den anpassade vinkeln i egenskapen RotationAngle. Skriv [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** om texten radbryts vid [TextFrame](../../aspose.slides/textframe/)-marginalerna. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: [DataLabel](../datalabel/) och [DataLabelFormat](../datalabelformat/) (fullt stöd i PowerPoint 2007/2013). Skriv [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)