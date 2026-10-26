---
title: Cell
second_title: Aspose.Slides för C++ API-referens
description: Representerar en cell i en tabell.
type: docs
weight: 300
url: /sv/aspose.slides/cell/
---
## Cell klass

Representerar en cell i en tabell.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Avgör om textrutan är centrerad i en cell eller inte. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Returnerar [CellFormat](../cellformat/)-objektet som innehåller formateringsegenskaper för denna cell. Läs-endast [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Returnerar antalet rutnätkolumner i den överordnade tabellens tabellrutnät som ska spännas över av den aktuella cellen. Denna egenskap gör att celler kan få utseendet av att vara sammanslagna, eftersom de sträcker sig över vertikala gränser för andra celler i tabellen. Läs-endast **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Hämtar första kolumnen i cellen. Läs-endast [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Returnerar ett index för första kolumnen som täcks av cellen. Läs-endast **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Hämtar första raden i cellen. Läs-endast [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Returnerar ett index för första raden som täcks av cellen. Läs-endast **int32_t**. |
| **double** [get_Height](./get_height/)() override | Returnerar cellens höjd. Läs-endast **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Returnerar true om cellen är sammanslagen med någon justerad cell, annars false. Läs-endast **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Returnerar den nedre marginalen i en [TextFrame](../textframe/). Läs **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Returnerar den vänstra marginalen i en [TextFrame](../textframe/). Läs **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Returnerar den högra marginalen i en [TextFrame](../textframe/). Läs **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Returnerar den övre marginalen i en [TextFrame](../textframe/). Läs **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Returnerar cellens minsta höjd. Detta är summan av minimihöjderna för alla rader som täcks av cellen. Läs-endast **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Returnerar avståndet från tabellens vänstra sida till cellens vänstra sida. Läs-endast **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Returnerar avståndet från tabellens övre sida till cellens övre sida. Läs-endast **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Returnerar cellens överordnade presentation. Läs-endast [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Returnerar antalet rader som en sammanslagen cell sträcker sig över. Detta används i kombination med vMerge-attributet på andra celler för att ange startcellen för en horisontell sammanslagning. Läs-endast **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Returnerar cellens överordnade bild. Läs-endast [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Returnerar den överordnade [Table](../table/)-objektet för en cell. Läs-endast [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Returnerar textankartypen. Läs [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Returnerar textramen för en cell. Läs-endast [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Returnerar typen av vertikal text. Läs [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Returnerar cellens bredd. Läs-endast **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Avgör om textrutan är centrerad i en cell eller inte. Skriv **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Ställer in den nedre marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Ställer in den vänstra marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Ställer in den högra marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Ställer in den övre marginalen i en [TextFrame](../textframe/). Skriv **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Ställer in textankartypen. Skriv [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Ställer in typen av vertikal text. Skriv [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (snarare än delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Delar cellen i två celler efter kolumnindex. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Delar cellen efter höjd. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Delar cellen i två celler efter radindex. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Delar cellen efter bredd. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IDOMObject](../idomobject/)
* Klass [ICell](../icell/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)