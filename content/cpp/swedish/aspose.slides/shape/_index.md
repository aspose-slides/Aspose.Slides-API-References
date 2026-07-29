---
title: Shape
second_title: Aspose.Slides för C++ API-referens
description: Representerar en form på en bild.
type: docs
weight: 5084
url: /sv/aspose.slides/shape/
---
## Shape klass

Representerar en form på en bild.

```cpp
class Shape : public virtual Aspose::Slides::IShape,
              public Aspose::Slides::IDOMObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en angiven. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() override | Returnerar den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() override | Returnerar titeln för den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() override | Egenskapen specificerar hur en form renderas i svart-vitt visningsläge. Läs [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() override | Returnerar antalet anslutningspunkter på formen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Returnerar formens anpassade data. Skrivskyddad [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Returnerar [EffectFormat](../effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Returnerar [FillFormat](../fillformat/)-objektet som innehåller fyllningsformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har fyllningsegenskaper. Skrivskyddad [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | Returnerar formramens egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](./get_height/)() override | Hämtar formens höjd, mätt i punkter. Läs **float**. |
| **bool** [get_Hidden](./get_hidden/)() override | Avgör om formen är dold. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Returnerar hyperlänkshanteraren. Skrivskyddad [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Returnerar hyperlänken som definierats för mus över. Läs [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](./get_isdecorative/)() override | Hämtar alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| **bool** [get_IsGrouped](./get_isgrouped/)() override | Avgör om formen är grupperad. Skrivskyddad **bool**. |
| **bool** [get_IsTextHolder](./get_istextholder/)() override | Avgör om formen är TextHolder_PPT. Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Returnerar [LineFormat](../lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linjeegenskaper. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Returnerar namnet på en form. Måste vara icke-null. Använd tom sträng om nödvändigt. Läs [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() override | Returnerar en bild-specifik unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken del av dokumentet som helst. Skrivskyddad **uint32_t**. Se även [Shape::get_UniqueId](./get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | Returnerar förälder [GroupShape](../groupshape/)-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() override | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Skrivskyddad [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Returnerar den överordnade presentationen för en bild. Skrivskyddad [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() override | Returnerar de råa formramens egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](./get_rotation/)() override | Returnerar antalet grader som den specificerade formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() override | Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Returnerar den överordnade bilden för en form. Skrivskyddad [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Returnerar [ThreeDFormat](../threedformat/)-objektet som innehåller 3D-effektegenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Skrivskyddad [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](./get_uniqueid/)() override | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan återtilldelas av användaren eller programatiskt, får det inte behandlas som en bestående unik nyckel. Skrivskyddad **uint32_t**. Se även [Shape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| **float** [get_Width](./get_width/)() override | Hämtar formens bredd, mätt i punkter. Läs **float**. |
| **float** [get_X](./get_x/)() override | Hämtar x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **float** [get_Y](./get_y/)() override | Hämtar y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **int32_t** [get_ZOrderPosition](./get_zorderposition/)() override | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](./getbaseplaceholder/)() override | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen är ärvd från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | Returnerar formens miniatyr. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) formens miniatyrgräns-typ används som standard. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Returnerar formens miniatyr. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](./getvisualbounds/)() | Hämtar formens visuella gränser beräknade från dess renderade innehåll. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens för värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [RemovePlaceholder](./removeplaceholder/)() override | Anger att denna form inte är en platshållare. |
| void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) override | Ställer in den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) override | Ställer in titeln för den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Egenskapen specificerar hur en form renderas i svart-vitt läge. Skriv [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ställer in formramens egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| void [set_Height](./set_height/)(**float**) override | Ställer in formens höjd, mätt i punkter. Skriv **float**. |
| void [set_Hidden](./set_hidden/)(**bool**) override | Avgör om formen är dold. Skriv **bool**. |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stämmer in hyperlänken som definierats för musklick. Skriv [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ställer in hyperlänken som definierats för mus över. Skriv [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](./set_isdecorative/)(**bool**) override | Ställer in alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Ställer in namnet på en form. Måste vara icke-null. Använd tom sträng om nödvändigt. Skriv [System::String](../../system/string/). |
| void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ställer in de råa formramens egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](./set_rotation/)(**float**) override | Ställer in antalet grader som den specificerade formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skriv **float**. |
| void [set_Width](./set_width/)(**float**) override | Ställer in formens bredd, mätt i punkter. Skriv **float**. |
| void [set_X](./set_x/)(**float**) override | Ställer in x-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| void [set_Y](./set_y/)(**float**) override | Ställer in y-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'th mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Sparar innehållet av [Shape](./) som SVG-fil. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Sparar innehållet av [Shape](./) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IShape](../ishape/)
* Klass [IDOMObject](../idomobject/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)