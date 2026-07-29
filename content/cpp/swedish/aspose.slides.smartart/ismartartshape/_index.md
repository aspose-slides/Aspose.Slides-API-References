---
title: ISmartArtShape
second_title: Aspose.Slides för C++ API-referens
description: Representerar en form i ett SmartArt-diagram
type: docs
weight: 40
url: /sv/aspose.slides.smartart/ismartartshape/
---
## ISmartArtShape klass

Representerar en form i [SmartArt](../smartart/) diagram

```cpp
class ISmartArtShape : public virtual Aspose::Slides::IGeometryShape
```

## Metoder

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements/)() | Skapar och returnerar en array av formens element. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/igeometryshape/get_adjustment/)(**int32_t**) | Returnerar formens justeringsvärde på angivet index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/igeometryshape/get_adjustments/)() | Returnerar en samling av formens justeringsvärden. Skrivskyddad [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Returnerar den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Returnerar titeln för den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Egenskapen anger hur en form renderas i svart-vitt läge. Läs [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Returnerar antalet anslutningsställen på formen. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Returnerar formens anpassade data. Skrivskyddad [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Returnerar [EffectFormat](../../aspose.slides/effectformat/)-objektet som innehåller pixel-effekter som tillämpas på en form. Skrivskyddad [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Returnerar [FillFormat](../../aspose.slides/fillformat/)-objektet som innehåller fyllningsformaterings-egenskaper för en form. Skrivskyddad [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Returnerar formens ram-egenskaper. Läs [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Hämtar formens höjd i punkter. Läs **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Avgör om formen är dold. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Returnerar hyperlänken som är definierad för musklick. Läs [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlänks-hanterare. Skrivskyddad [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returnerar hyperlänken som är definierad för mus-över. Läs [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | Hämtar alternativet 'Mark as decorative'. Läsa/skriva **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Avgör om formen är grupperad. Skrivskyddad **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Avgör om formen är TextHolder. Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Returnerar [LineFormat](../../aspose.slides/lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Skrivskyddad [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Returnerar namnet på en form. Läs [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Returnerar ett unikt identifierare för bilden som förblir konstant under hela formens livstid och låter PowerPoint eller interop-kod referera till formen på ett pålitligt sätt. Skrivskyddad **uint32_t**. Se även [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Returnerar föräldra[GroupShape](../../aspose.slides/groupshape/)-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Returnerar platshållaren för en form. Skrivskyddad [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Returnerar de råa ram-egenskaperna för formen. Läs [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Returnerar antalet grader som den angivna formen roteras runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/igeometryshape/get_shapestyle/)() | Returnerar formens stil-objekt. Skrivskyddad [IShapeStyle](../../aspose.slides/ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](../../aspose.slides/igeometryshape/get_shapetype/)() | Returnerar geometrins förinställda typ. Obs: vid värdeändring återställs alla justeringsvärden till sina standardvärden. Läs [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar bas-bilden. Skrivskyddad [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | Returnerar texten för [SmartArt](../smartart/)-formen. Skrivskyddad [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Returnerar [ThreeDFormat](../../aspose.slides/threedformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Skrivskyddad [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Returnerar en intern, presentations-specifik identifierare avsedd för tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt får det inte behandlas som en bestående unik nyckel. Skrivskyddad **uint32_t**. Se även [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Hämtar formens bredd i punkter. Läs **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Hämtar x-koordinaten för formens övre-vänstra hörn i punkter. Läs **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Hämtar y-koordinaten för formens övre-vänstra hörn i punkter. Läs **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Returnerar formens position i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Returnerar en grundläggande platshållar-form (form från layouten och/eller huvudinlednings-bilden som den aktuella formen är ärvd från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastruktur som är associerad med objektet. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths/)() | Returnerar en kopia av geometriformens bana. Koordinater är relativa till formens vänstra övre hörn. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Returnerar formens miniatyrbild. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) miniatyrbilds-gränstyp används som standard. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Returnerar formens miniatyrbild. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objekt-typen. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-statement låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referens-jämför ett värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Anger att denna form inte är en platshållare. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Sätter den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Sätter titeln för den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Egenskapen anger hur en form renderas i svart-vitt läge. Skriv [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Sätter formens ram-egenskaper. Skriv [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Sätter formens höjd i punkter. Skriv **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Anger om formen är dold. Skriv **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Sätter hyperlänken som är definierad för musklick. Skriv [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Sätter hyperlänken som är definierad för mus-över. Skriv [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | Sätter 'Mark as decorative'-alternativet Läsa/skriva **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Sätter namnet på en form. Skriv [System::String](../../system/string/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Sätter de råa ram-egenskaperna för formen. Skriv [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Sätter antalet grader som den angivna formen roteras runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skriv **float**. |
| virtual void [set_ShapeType](../../aspose.slides/igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) | Sätter geometrins förinställda typ. Obs: vid värdeändring återställs alla justeringsvärden till sina standardvärden. Skriv [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Sätter formens bredd i punkter. Skriv **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Sätter x-koordinaten för formens övre-vänstra hörn i punkter. Skriv **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Sätter y-koordinaten för formens övre-vänstra hörn i punkter. Skriv **float**. |
| virtual void [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) | Uppdaterar formens geometri från [IGeometryPath](../../aspose.slides/igeometrypath/)-objekt. Koordinater måste vara relativa till formens vänstra övre hörn. Ändrar formens typ ([ShapeType](../../aspose.slides/shapetype/)) till [ShapeType::Custom](../../aspose.slides/shapetype/). |
| virtual void [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) | Uppdaterar formens geometri från en array av [IGeometryPath](../../aspose.slides/igeometrypath/). Koordinater måste vara relativa till formens vänstra övre hörn. Ändrar formens typ ([ShapeType](../../aspose.slides/shapetype/)) till [ShapeType::Custom](../../aspose.slides/shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'th mall-argument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-statement upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sparar innehållet i [Shape](../../aspose.slides/shape/) som SVG-fil. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Sparar innehållet i [Shape](../../aspose.slides/shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Se även

* Klass [IGeometryShape](../../aspose.slides/igeometryshape/)
* Namnrymd [Aspose::Slides::SmartArt](../)
* Bibliotek [Aspose.Slides](../../)