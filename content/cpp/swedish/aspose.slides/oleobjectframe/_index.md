---
title: OleObjectFrame
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett OLE-objekt på en bild.
type: docs
weight: 4603
url: /sv/aspose.slides/oleobjectframe/
---
## OleObjectFrame klass

Representerar ett OLE-objekt på en bild.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en specificerad. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Returnerar den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Returnerar titeln för den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Egendomen anger hur en form ska renderas i svart-vit visningsläge. Läs [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Returnerar antalet anslutningspunkter på formen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Returnerar formens anpassade data. Skrivskyddad [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Returnerar [EffectFormat](../effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en form. Observera: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | Hämtar information om OLE-inbäddade data. Läs [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | Returnerar filnamnet för det inbäddade OLE-objektet |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | Returnerar sökvägen för det inbäddade OLE-objektet |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Returnerar [FillFormat](../fillformat/)-objektet som innehåller fyllningsformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har fyllningsegenskaper. Skrivskyddad [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Returnerar formramens egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Returnerar formens lås. Skrivskyddad [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Hämtar formens höjd, mätt i punkter. Läs **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Avgör om formen är dold. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Returnerar hyperlänkshanteraren. Skrivskyddad [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Returnerar hyperlänken som definierats för muspekning. Läs [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Hämtar alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Avgör om formen är grupperad. Skrivskyddad **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | Avgör om ett objekt är synligt som ikon. Läs **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | Avgör om ett objekt är länkat till en extern fil. Skrivskyddad **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Avgör om formen är TextHolder_PPT. Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Returnerar [LineFormat](../lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som inte har linjeegenskaper. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | Returnerar hela sökvägen till en länkad fil. Kort filnamn kommer att användas. Skrivskyddad [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Returnerar hela sökvägen till en länkad fil. Långt filnamn kommer att användas. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng. Skrivskyddad [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Returnerar namnet på en form. Måste vara icke-null. Använd ett tomt strängvärde om nödvändigt. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | Returnerar namnet på ett objekt. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | Returnerar ProgID för ett objekt. Skrivskyddad [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Returnerar en unik identifierare som är specifik för en bild och förblir konstant under formens livstid och låter PowerPoint eller interop-kod referera till formen på ett pålitligt sätt från var som helst i dokumentet. Skrivskyddad **uint32_t**. Se även [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Returnerar föräldra[GroupShape](../groupshape/)-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Skrivskyddad [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Returnerar föräldrapresentationen för en bild. Skrivskyddad [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Returnerar de råa formramsegenskaperna. Läs [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Returnerar antalet grader som den angivna formen roteras runt z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Returnerar föräldrabilden för en form. Skrivskyddad [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | Returnerar OleObject-objektet för bildfyllningsegenskaper. Skrivskyddad [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | Returnerar titeln för OleObject-ikon. Läs [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Returnerar [ThreeDFormat](../threedformat/)-objektet som innehåller 3D-effektegenskaper för en form. Observera: kan returnera null för vissa typer av former som saknar 3D-egenskaper. Skrivskyddad [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programatiskt, får det inte behandlas som en bestående unik nyckel. Skrivskyddad **uint32_t**. Se även [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | Avgör om det länkade inbäddade objektet automatiskt uppdateras när presentationen öppnas eller skrivs ut. Läs **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Hämtar formens bredd, mätt i punkter. Läs **float**. |
| **float** [get_X](../shape/get_x/)() override | Hämtar x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **float** [get_Y](../shape/get_y/)() override | Hämtar y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Returnerar formens position i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen är ärvd från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Returnerar formens miniatyrbild. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatyrbildsgränstyp används som standard. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Returnerar formens miniatyrbild. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Hämtar formens visuella gräns beräknad från dess renderade innehåll. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsen för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med det angivna värdet. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definierar att denna form inte är en platshållare. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ställer in den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ställer in titeln för den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Egendomen anger hur en form ska renderas i svart-vit visningsläge. Skriv [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ställer in formramens egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ställer in formens höjd, mätt i punkter. Skriv **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Avgör om formen är dold. Skriv **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ställer in hyperlänken som definierats för musklick. Skriv [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ställer in hyperlänken som definierats för muspekning. Skriv [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ställer in alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | Avgör om ett objekt är synligt som ikon. Skriv **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Returnerar hela sökvägen till en länkad fil. Långt filnamn kommer att användas. Skriv [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ställer in namnet på en form. Måste vara icke-null. Använd ett tomt strängvärde om nödvändigt. Skriv [System::String](../../system/string/). |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | Ställer in namnet på ett objekt. Skriv [System::String](../../system/string/). |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | Returnerar ProgID för ett objekt. Skrivskyddad [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ställer in de råa formramsegenskaperna. Skriv [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ställer in antalet grader som den angivna formen roteras runt z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation. Skriv **float**. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | Ställer in titeln för OleObject-ikon. Skriv [System::String](../../system/string/). |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | Avgör om det länkade inbäddade objektet automatiskt uppdateras när presentationen öppnas eller skrivs ut. Skriv **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Ställer in formens bredd, mätt i punkter. Skriv **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ställer in x-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ställer in y-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | Ställer in information om OLE-inbäddade data. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n-te mallargumentet som en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsen för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Sparar innehållet i [Shape](../shape/) som SVG-fil. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Sparar innehållet i [Shape](../shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar

Följande exempel visar hur man får åtkomst till OLE-objekt-ramar. ```cpp
// Laddar PPTX till ett presentationsobjekt
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// Åtkomst till den första bilden
auto slide = pres->get_Slides()->idx_get(0);
// Kastar formen till OleObjectFrame
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// Läser OLE-objektet och skriver det till disk
if (oleObjectFrame != nullptr)
{
    // Hämtar inbäddade fildata
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // Hämtar inbäddad filändelse
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // Skapar en sökväg för att spara den extraherade filen
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // Sparar extraherade data
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## Se även

* Klass [GraphicalObject](../graphicalobject/)
* Klass [IOleObjectFrame](../ioleobjectframe/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)