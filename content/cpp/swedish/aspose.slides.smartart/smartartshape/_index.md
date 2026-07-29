---
title: SmartArtShape
second_title: Aspose.Slides för C++ API-referens
description: Representerar SmartArt-figur
type: docs
weight: 105
url: /sv/aspose.slides.smartart/smartartshape/
---
## SmartArtShape klass

Representerar [SmartArt](../smartart/) figur

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en angiven. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | Skapar och returnerar en array av figurens element. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | Returnerar en figurs justeringsvärde på angivet index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | Returnerar en samling av figurens justeringsvärden. Skrivskyddad [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Returnerar den alternativa texten som är kopplad till en figur. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Returnerar titeln på den alternativa texten som är kopplad till en figur. Läs [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Egenskapen anger hur en figur renderas i svart-vitt läge.. Läs [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Returnerar antalet anslutningsställen på figuren. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Returnerar figurens anpassade data. Skrivskyddad [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Returnerar [EffectFormat](../../aspose.slides/effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en figur. Observera: kan returnera null för vissa figurtyper som inte har effektegenskaper. Skrivskyddad [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Returnerar [FillFormat](../../aspose.slides/fillformat/)-objektet som innehåller fyllningsformaterings-egenskaper för en figur. Observera: kan returnera null för vissa figurtyper som inte har fyllningsegenskaper. Skrivskyddad [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Returnerar figurens ram-egenskaper. Läs [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Hämtar figurens höjd, mätt i punkter. Läs **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Avgör om figuren är dold. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Returnerar hyperlänks-hanteraren. Skrivskyddad [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Returnerar hyperlänken som definierats för mus över. Läs [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Hämtar alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Avgör om figuren är grupperad. Skrivskyddad **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Avgör om figuren är TextHolder_PPT. Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Returnerar [LineFormat](../../aspose.slides/lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en figur. Observera: kan returnera null för vissa figurtyper som inte har linjeegenskaper. Skrivskyddad [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Returnerar namnet på en figur. Får inte vara null. Använd tom sträng om nödvändigt. Läs [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Returnerar en bild-omfattande unik identifierare som förblir konstant under figurens livstid och låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till figuren från vilken del av dokumentet som helst. Skrivskyddad **uint32_t**. Se även [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Returnerar förälder-[GroupShape](../../aspose.slides/groupshape/)-objektet om figuren är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Returnerar platshållaren för en figur. Returnerar null om figuren saknar platshållare. Skrivskyddad [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Returnerar föräldrapresentationen för en bild. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Returnerar de råa ram-egenskaperna för figuren. Läs [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Returnerar antalet grader som den angivna figuren roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Returnerar figurens lås. Skrivskyddad [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | Returnerar figurens stilobjekt. Skrivskyddad [IShapeStyle](../../aspose.slides/ishapestyle/). |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | Returnerar geometrins förinställda typ. Observera: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Läs [Slides::ShapeType](../../aspose.slides/shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Returnerar föräldrabilden för en figur. Skrivskyddad [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | Returnerar texten för [SmartArt](../smartart/)-figuren. Skrivskyddad [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Returnerar [ThreeDFormat](../../aspose.slides/threedformat/)-objektet som innehåller 3D-effektegenskaper för en figur. Observera: kan returnera null för vissa figurtyper som inte har 3D-egenskaper. Skrivskyddad [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte betraktas som en beständig unik nyckel. Skrivskyddad **uint32_t**. Se även [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Hämtar figurens bredd, mätt i punkter. Läs **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Hämtar x-koordinaten för figurens övre-vänstra hörn, mätt i punkter. Läs **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Hämtar y-koordinaten för figurens övre-vänstra hörn, mätt i punkter. Läs **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Returnerar figurens position i z-ordningen. Shapes[0] returnerar figuren längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar figuren längst fram i z-ordningen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Returnerar en grundläggande platshållarfigur (figur från layouten och/eller huvudsidan som den aktuella figuren ärvs från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | Returnerar en kopia av vägen för geometrifiguren. Koordinaterna är relativa till figurens övre-vänstra hörn. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Returnerar figurens miniatyrbild. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) miniatyrbildens gränstyps används som standard. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Returnerar figurens miniatyrbild. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Hämtar figurens visuella gränser beräknade från dess renderade innehåll. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satset för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet av sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet av strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Anger att denna figur inte är en platshållare. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Sätter den alternativa texten som är kopplad till en figur. Skriv [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Sätter titeln på den alternativa texten som är kopplad till en figur. Skriv [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Egenskapen anger hur en figur renderas i svart-vitt läge.. Skriv [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Sätter figurens ram-egenskaper. Skriv [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Sätter figurens höjd, mätt i punkter. Skriv **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Avgör om figuren är dold. Skriv **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Sätter hyperlänken som definierats för musklick. Skriv [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Sätter hyperlänken som definierats för mus över. Skriv [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Sätter alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Sätter namnet på en figur. Får inte vara null. Använd tom sträng om nödvändigt. Skriv [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Sätter de råa ram-egenskaperna för figuren. Skriv [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Sätter antalet grader som den angivna figuren roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skriv **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | Sätter geometrins förinställda typ. Observera: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Skriv [Slides::ShapeType](../../aspose.slides/shapetype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Sätter figurens bredd, mätt i punkter. Skriv **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Sätter x-koordinaten för figurens övre-vänstra hörn, mätt i punkter. Skriv **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Sätter y-koordinaten för figurens övre-vänstra hörn, mätt i punkter. Skriv **float**. |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | Uppdaterar figurens geometri från [IGeometryPath](../../aspose.slides/igeometrypath/)-objektet. Koordinater måste vara relativa till figurens övre-vänstra hörn. Ändrar figurens typ ([ShapeType](../../aspose.slides/shapetype/)) till [ShapeType::Custom](../../aspose.slides/shapetype/). |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | Uppdaterar figurens geometri från en array av [IGeometryPath](../../aspose.slides/igeometrypath/). Koordinater måste vara relativa till figurens övre-vänstra hörn. Ändrar figurens typ ([ShapeType](../../aspose.slides/shapetype/)) till [ShapeType::Custom](../../aspose.slides/shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satset för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vakt-objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Sparar innehållet av [Shape](../../aspose.slides/shape/) som SVG-fil. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Sparar innehållet av [Shape](../../aspose.slides/shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [GeometryShape](../../aspose.slides/geometryshape/)
* Klass [ISmartArtShape](../ismartartshape/)
* Namnrymd [Aspose::Slides::SmartArt](../)
* Bibliotek [Aspose.Slides](../../)