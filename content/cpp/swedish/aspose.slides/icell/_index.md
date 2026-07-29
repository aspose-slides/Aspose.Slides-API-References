---
title: ICell
second_title: Aspose.Slides för C++ API-referens
description: Representerar en cell i en tabell.
type: docs
weight: 1639
url: /sv/aspose.slides/icell/
---
## ICell klass

Representerar en cell i en tabell.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Bestämmer om en textruta är centrerad i en cell eller inte. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Returnerar [CellFormat](../cellformat/)-objektet som innehåller formateringsegenskaper för denna cell. Skrivskyddad [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Returnerar antalet rutnätskolumner i föräldertabellens tabellnät som ska sträcka sig över den aktuella cellen. Denna egenskap gör att celler kan se sammanslagna ut, eftersom de sträcker sig över vertikala gränser för andra celler i tabellen. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Hämtar den första kolumnen i cellen. Skrivskyddad [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Returnerar indexet för den första kolumnen som täcks av cellen. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Hämtar den första raden i cellen. Skrivskyddad [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Returnerar indexet för den första raden som täcks av cellen. Skrivskyddad **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Returnerar cellens höjd. Skrivskyddad **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Returnerar true om cellen är sammanslagen med någon justerad cell, false annars. Skrivskyddad **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Returnerar den nedre marginalen i en [TextFrame](../textframe/). Läs **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Returnerar den vänstra marginalen i en [TextFrame](../textframe/). Läs **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Returnerar den högra marginalen i en [TextFrame](../textframe/). Läs **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Returnerar den övre marginalen i en [TextFrame](../textframe/). Läs **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Returnerar den minsta höjden för en cell. Detta är summan av minimala höjder för alla rader som täcks av cellen. Skrivskyddad **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Returnerar avståndet från vänstra sidan av en tabell till vänstra sidan av en cell. Skrivskyddad **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Returnerar avståndet från övre sidan av en tabell till övre sidan av en cell. Skrivskyddad **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Returnerar antalet rader som en sammanslagen cell sträcker sig över. Detta används i kombination med vMerge-attributet på andra celler för att ange startcellen för en horisontell sammanslagning. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returnerar grundsliden. Skrivskyddad [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Returnerar föräldra[Table](../table/)-objektet för en cell. Skrivskyddad [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Returnerar textankringstypen. Läs [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Returnerar textramen för en cell. Skrivskyddad [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Returnerar typen av vertikal text. Läs [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Returnerar cellens bredd. Skrivskyddad **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Bestämmer om en textruta är centrerad i en cell eller inte. Skriv **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ställer in den nedre marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ställer in den vänstra marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ställer in den högra marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ställer in den övre marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Ställer in textankringstypen. Skriv [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Ställer in typen av vertikal text. Skriv [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n:te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Delar cellen i två celler efter kolumnindex. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Delar cellen efter höjd. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Delar cellen i två celler efter radindex. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Delar cellen efter bredd. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [ISlideComponent](../islidecomponent/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)