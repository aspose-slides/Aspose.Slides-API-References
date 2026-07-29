---
title: InkActions
second_title: Aspose.Slides för C++ API-referens
description: Representerar roten för bläckåtgärder.
type: docs
weight: 66
url: /sv/aspose.slides.ink/inkactions/
---
## InkActions klass

Representerar roten av bläckåtgärder.

```cpp
class InkActions : public Aspose::Slides::GraphicalObject,
                   public Aspose::Slides::Ink::IInkActions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Lägger till en ny platshållare om det saknas och sätter platshållarens egenskaper till en specificerad. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Returnerar den alternativa texten som är kopplad till en form. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Returnerar titeln på den alternativa texten som är kopplad till en form. Läs [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Egenskapen anger hur en form renderas i svart-vit visningsläge. Läs [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Returnerar antalet anslutningspunkter på formen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Returnerar formens anpassade data. Skrivskyddad [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Returnerar [EffectFormat](../../aspose.slides/effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en form. Observera: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Skrivskyddad [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Returnerar [FillFormat](../../aspose.slides/fillformat/)-objektet som innehåller fyllningsformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har fyllningsegenskaper. Skrivskyddad [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Returnerar formramens egenskaper. Läs [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Returnerar formens lås. Skrivskyddad [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Hämtar formens höjd, mätt i punkter. Läs **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Bestämmer om formen är dold. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Returnerar hyperlänkhanteraren. Skrivskyddad [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Returnerar hyperlänken som definierats för musöverlappning. Läs [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Hämtar alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Bestämmer om formen är grupperad. Skrivskyddad **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Bestämmer om formen är TextHolder_PPT. Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Returnerar [LineFormat](../../aspose.slides/lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har linjeegenskaper. Skrivskyddad [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Returnerar namnet på en form. Måste vara icke-null. Använd en tom sträng om så behövs. Läs [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Returnerar en bild-omfattande unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken del av dokumentet som helst. Skrivskyddad **uint32_t**. Se även [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Returnerar föräldra[GroupShape](../../aspose.slides/groupshape/)-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Skrivskyddad [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Returnerar den föräldrapresentation som en bild tillhör. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Returnerar den råa formramens egenskaper. Läs [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Returnerar antalet grader som den specificerade formen är roterad kring z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Returnerar föräldrabilden för en form. Skrivskyddad [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Returnerar [ThreeDFormat](../../aspose.slides/threedformat/)-objektet som innehåller 3D-effekt-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Skrivskyddad [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omas tilldelas av användaren eller programmässigt får det inte behandlas som en beständig unik nyckel. Skrivskyddad **uint32_t**. Se även [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Hämtar formens bredd, mätt i punkter. Läs **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Hämtar x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Hämtar y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Returnerar formens position i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen är ärvd från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Gör det möjligt att hasha anpassade objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Returnerar formens miniatyr. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) miniatyrgräns-typ används som standard. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Returnerar formens miniatyr. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typnamnet för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Hämtar formens visuella gränser beräknade från dess renderade innehåll. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakarobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Anger att denna form inte är en platshållare. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Ställer in den alternativa texten som är kopplad till en form. Skriv [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ställer in titeln på den alternativa texten som är kopplad till en form. Skriv [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Egenskapen anger hur en form ska renderas i svart-vit visningsläge. Skriv [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Ställer in formramens egenskaper. Skriv [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Ställer in formens höjd, mätt i punkter. Skriv **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Bestämmer om formen är dold. Skriv **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Ställer in hyperlänken som definierats för musklick. Skriv [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Ställer in hyperlänken som definierats för musöverlappning. Skriv [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Ställer in alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Ställer in namnet på en form. Måste vara icke-null. Använd en tom sträng om så behövs. Skriv [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Ställer in den råa formramens egenskaper. Skriv [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Ställer in antalet grader som den specificerade formen är roterad kring z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation. Skriv **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Ställer in formens bredd, mätt i punkter. Skriv **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Ställer in x-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Ställer in y-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställ in n:te mallargument som en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde på den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Borde inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-bevakarobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Sparar innehållet av [Shape](../../aspose.slides/shape/) som SVG-fil. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Sparar innehållet av [Shape](../../aspose.slides/shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [GraphicalObject](../../aspose.slides/graphicalobject/)
* Klass [IInkActions](../iinkactions/)
* Namnrymd [Aspose::Slides::Ink](../)
* Bibliotek [Aspose.Slides](../../)