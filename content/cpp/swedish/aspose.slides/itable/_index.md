---
title: ITable
second_title: Aspose.Slides för C++ API-referens
description: Representerar en tabell på en bild.
type: docs
weight: 4018
url: /sv/aspose.slides/itable/
---
## ITable klass


Representerar en tabell på en bild.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Returnerar den alternativa texten som är kopplad till en form. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Returnerar titeln för den alternativa texten som är kopplad till en form. Läs [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Egenskapen anger hur en form renderas i svart-vitt visningsläge. Läs [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | Returnerar en kolumn på angivet index. Endast läsning [Aspose::Slides::IColumn](../icolumn/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | Returnerar samlingen av kolumner. Endast läsning [IColumnCollection](../icolumncollection/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Returnerar antalet anslutningspunkter på formen. Endast läsning **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Returnerar formens anpassade data. Endast läsning [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Returnerar [EffectFormat](../effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en form. Endast läsning [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Returnerar [FillFormat](../fillformat/)-objektet som innehåller fyllningsformateringsegenskaper för en form. Endast läsning [IFillFormat](../ifillformat/). |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | Avgör om den första kolumnen i en tabell ska ritas med särskild formatering. Läs **bool**. |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | Avgör om den första raden i en tabell ska ritas med särskild formatering. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Returnerar formramens egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Returnerar formens lås. Endast läsning [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Hämtar formens höjd, mätt i punkter. Läs **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Avgör om formen är dold. Läs **bool**. |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | Avgör om jämna rader ska ritas med annan formatering. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlänkshanterare. Endast läsning [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returnerar hyperlänken som definierats för mus över. Läs [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Hämtar alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Avgör om formen är grupperad. Endast läsning **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Avgör om formen är TextHolder. Endast läsning **bool**. |
| virtual **bool** [get_LastCol](./get_lastcol/)() | Avgör om den sista kolumnen i en tabell ska ritas med särskild formatering. Läs **bool**. |
| virtual **bool** [get_LastRow](./get_lastrow/)() | Avgör om den sista raden i en tabell ska ritas med särskild formatering. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Returnerar [LineFormat](../lineformat/)-objektet som innehåller linjeformateringsegenskaper för en form. Endast läsning [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Returnerar namnet på en form. Läs [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Returnerar ett bild-specifikt unikt identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från var som helst i dokumentet. Endast läsning **uint32_t**. Se även [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Returnerar föräldra-[GroupShape](../groupshape/)-objektet om formen är grupperad. Annars returneras null. Endast läsning [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Returnerar platshållaren för en form. Endast läsning [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Endast läsning [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Returnerar de råa formramsegenskaperna. Läs [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Avgör om tabellen har högervänster läsordning. Läser **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Returnerar antalet grader som den specificerade formen är roterad kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | Returnerar en rad på angivet index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | Returnerar samlingen av rader. Endast läsning [IRowCollection](../irowcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Returnerar formens lås. Endast läsning [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returnerar grundbilden. Endast läsning [IBaseSlide](../ibaseslide/). |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | Hämtar eller sätter inbyggd tabellstil. Läs [TableStylePreset](../tablestylepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | Returnerar [TableFormat](../tableformat/)-objektet som innehåller formateringsegenskaper för denna tabell. Endast läsning [ITableFormat](../itableformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Returnerar [ThreeDFormat](../threedformat/)-objektet som innehåller linjeformateringsegenskaper för en form. Endast läsning [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas som en beständig unik nyckel. Endast läsning **uint32_t**. Se även [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | Avgör om jämna kolumner ska ritas med annan formatering. Läs **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Hämtar formens bredd, mätt i punkter. Läs **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Hämtar x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Hämtar y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läsning **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Returnerar en grundläggande platshållarform (form från layouten och/eller mästresliden som den aktuella formen är ärvd från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Returnerar formens miniatyrbild. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/)-formens miniatyrbildens gränstyp används som standard. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returnerar formens miniatyrbild. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Returnerar cellen på angivna kolumn- och radindex. Endast läsning [ICell](../icell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | Slår ihop angränsande celler. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Anger att denna form inte är en platshållare. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Ställer in den alternativa texten som är kopplad till en form. Skriv [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ställer in titeln för den alternativa texten som är kopplad till en form. Skriv [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Egenskapen anger hur en form renderas i svart-vitt läge. Skriv [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | Avgör om den första kolumnen i en tabell ska ritas med särskild formatering. Skriv **bool**. |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | Avgör om den första raden i en tabell ska ritas med särskild formatering. Skriv **bool**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ställer in formramens egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Ställer in formens höjd, mätt i punkter. Skriv **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Avgör om formen är dold. Skriv **bool**. |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | Avgör om jämna rader ska ritas med annan formatering. Skriv **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ställer in hyperlänken som definierats för musklick. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ställer in hyperlänken som definierats för mus över. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Ställer in alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | Avgör om den sista kolumnen i en tabell ska ritas med särskild formatering. Skriv **bool**. |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | Avgör om den sista raden i en tabell ska ritas med särskild formatering. Skriv **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Ställer in namnet på en form. Skriv [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ställer in de råa formramsegenskaperna. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | Avgör om tabellen har högervänster läsordning. Skriver **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Ställer in antalet grader som den specificerade formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skriv **float**. |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | Hämtar eller sätter inbyggd tabellstil. Skriv [TableStylePreset](../tablestylepreset/). |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | Avgör om jämna kolumner ska ritas med annan formatering. Skriv **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Ställer in formens bredd, mätt i punkter. Skriv **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Ställer in x-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Ställer in y-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te template-argument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | Ställer in definierade portionformateringsegenskaper för alla elementets portioner. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | Ställer in definierade styckeformateringsegenskaper för alla elementets stycken. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | Ställer in definierade textraframeformateringsegenskaper för alla elementets textramar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector annars. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector annars. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sparar innehållet i [Shape](../shape/) som SVG-fil. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Sparar innehållet i [Shape](../shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [IGraphicalObject](../igraphicalobject/)
* Klass [IBulkTextFormattable](../ibulktextformattable/)
* Namnrymd [Aspose::Slides](../)
* Library [Aspose.Slides](../../)