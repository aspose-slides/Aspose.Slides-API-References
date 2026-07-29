---
title: IZoomFrame
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett Slide Zoom-objekt i en bild.
type: docs
weight: 4252
url: /sv/aspose.slides/izoomframe/
---
## IZoomFrame klass

Representerar ett [Slide](../slide/) Zoom-objekt på en bild.

```cpp
class IZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en angiven. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om de enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om de enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Returnerar den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Returnerar titeln för den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Egendom specificerar hur en form ska renderas i svart-vit visningsläge.. Läs [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Returnerar antalet anslutningspunkter på formen. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Returnerar formens anpassade data. Skrivskyddad [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Returnerar [EffectFormat](../effectformat/)-objektet som innehåller pixel-effekter som tillämpas på en form. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Returnerar [FillFormat](../fillformat/)-objektet som innehåller fyllningsformateringsegenskaper för en form. Skrivskyddad [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Returnerar formens ram-egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Returnerar formens lås. Skrivskyddad [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Hämtar formens höjd, mätt i punkter. Läs **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Avgör om formen är dold. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlänks-hanterare. Skrivskyddad [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returnerar hyperlänken som definierats för muspekning. Läs [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Hämtar bildtypen för ett zoom-objekt. Läs [ZoomImageType](../zoomimagetype/). Standardvärde: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Hämtar alternativet 'Markera som dekorativ'. Läs/skriv **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Avgör om formen är grupperad. Skrivskyddad **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Avgör om formen är TextHolder. Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Returnerar [LineFormat](../lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Skrivskyddad [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Returnerar namn på en form. Läs [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Returnerar en unikt identifierare inom en bild som förblir konstant under formens livstid och låter PowerPoint eller interop-kod referera till formen på ett tillförlitligt sätt från vilken plats som helst i dokumentet. Skrivskyddad **uint32_t**. Se även [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Returnerar förälder-[GroupShape](../groupshape/)-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Returnerar platshållaren för en form. Skrivskyddad [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Returnerar de råa ram-egenskaperna för formen. Läs [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Hämtar navigeringsbeteendet i bildspel. Läs **bool**. Standardvärde: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Returnerar antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Hämtar värdet som specificerar om Zoom ska använda bakgrunden för destinationsbilden. Läs **bool**. Standardvärde: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returnerar grund-bilden. Skrivskyddad [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | Hämtar bildobjektet som [Slide](../slide/) Zoom-objekt länkar till. Läs [ISlide](../islide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Returnerar [ThreeDFormat](../threedformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Skrivskyddad [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Hämtar varaktigheten för övergången mellan Zoom och bild. Läs **float**. Standardvärde: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Returnerar en intern, presentations-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan återtilldelas av användaren eller programmässigt, får det inte behandlas som en beständig unik nyckel. Skrivskyddad **uint32_t**. Se även [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Hämtar formens bredd, mätt i punkter. Läs **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Hämtar x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Hämtar y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Hämtar bild för zoom-objektet. Läs [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen är ärvd från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Returnerar formens miniatyrbild. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/)-typ för miniatyrbildsgränser används som standard. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returnerar formens miniatyrbild. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-instruktion för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr genom referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med det angivna värdet. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definierar att denna form inte är en platshållare. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Sätter den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Sätter titeln för den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Egendom specificerar hur en form ska renderas i svart-vit visningsläge.. Skriv [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sätter formens ram-egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Sätter formens höjd, mätt i punkter. Skriv **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Ställer in om formen är dold. Skriv **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken som definierats för musklick. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken som definierats för muspekning. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Sätter bildtypen för ett zoom-objekt. Skriv [ZoomImageType](../zoomimagetype/). Standardvärde: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Ställer in alternativet 'Markera som dekorativ'. Läs/skriv **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Sätter namnet på en form. Skriv [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sätter de råa ram-egenskaperna för formen. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Sätter navigeringsbeteendet i bildspel. Skriv **bool**. Standardvärde: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Sätter antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skriv **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Sätter värdet som specificerar om Zoom ska använda bakgrunden för destinationsbilden. Skriv **bool**. Standardvärde: true |
| virtual void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Sätter bildobjektet som [Slide](../slide/) Zoom-objekt länkar till. Skriv [ISlide](../islide/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Sätter varaktigheten för övergången mellan Zoom och bild. Skriv **float**. Standardvärde: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Sätter formens bredd, mätt i punkter. Skriv **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Sätter x-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Sätter y-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Sätter bild för zoom-objektet. Skriv [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n-:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-instruktion för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sparar innehållet i [Shape](../shape/) som SVG-fil. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Sparar innehållet i [Shape](../shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IZoomObject](../izoomobject/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)