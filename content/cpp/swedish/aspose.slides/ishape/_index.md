---
title: IShape
second_title: Aspose.Slides för C++ API-referens
description: Representerar en form på en bild.
type: docs
weight: 3641
url: /sv/aspose.slides/ishape/
---
## IShape klass

Representerar en form på en bild.

```cpp
class IShape : public virtual Aspose::Slides::ISlideComponent,
               public Aspose::Slides::IHyperlinkContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en specificerad. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C# stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C# stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() | Returnerar den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() | Returnerar titeln för den alternativa texten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() | Egendom specificerar hur en form ska renderas i svart-vitt läge. Läs [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() | Returnerar antalet anslutningspunkter på formen. Endast läsning **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | Returnerar formens anpassade data. Endast läsning [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Returnerar [EffectFormat](../effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en form. Endast läsning [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Returnerar [FillFormat](../fillformat/)-objektet som innehåller fyllningsformaterings-egenskaper för en form. Endast läsning [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() | Returnerar formens ram-egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](./get_height/)() | Hämtar formens höjd, mätt i punkter. Läs **float**. |
| virtual **bool** [get_Hidden](./get_hidden/)() | Avgör om formen är dold. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returnerar hyperlänken som är definierad för musklick. Läs [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks manager Endast läsning [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returnerar hyperlänken som är definierad för musöver. Läs [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](./get_isdecorative/)() | Hämtar alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| virtual **bool** [get_IsGrouped](./get_isgrouped/)() | Avgör om formen är grupperad. Endast läsning **bool**. |
| virtual **bool** [get_IsTextHolder](./get_istextholder/)() | Avgör om formen är TextHolder. Endast läsning **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Returnerar [LineFormat](../lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Endast läsning [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | Returnerar namnet på en form. Läs [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() | Returnerar ett bild-specifikt unikt identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod pålitligt referera till formen var som helst i dokumentet. Endast läsning **uint32_t**. Se även [IShape::get_UniqueId](./get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() | Returnerar överordnad [GroupShape](../groupshape/)-objekt om formen är grupperad. Annars returneras null. Endast läsning [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() | Returnerar platshållaren för en form. Endast läsning [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Endast läsning [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() | Returnerar de råa ram-egenskaperna för en form. Läs [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](./get_rotation/)() | Returnerar antalet grader som den specificerade formen är roterad runt z-axeln. Ett positivt värde betyder medurs rotation; ett negativt värde betyder moturs rotation. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() | Returnerar formens lås. Endast läsning [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returnerar basbilden. Endast läsning [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Returnerar [ThreeDFormat](../threedformat/)-objektet som innehåller linjeformaterings-egenskaper för en form. Endast läsning [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](./get_uniqueid/)() | Returnerar ett internt, presentation-specifikt identifierare avsedd för tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte betraktas som en bestående unik nyckel. Endast läsning **uint32_t**. Se även [IShape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| virtual **float** [get_Width](./get_width/)() | Hämtar formens bredd, mätt i punkter. Läs **float**. |
| virtual **float** [get_X](./get_x/)() | Hämtar x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual **float** [get_Y](./get_y/)() | Hämtar y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual **int32_t** [get_ZOrderPosition](./get_zorderposition/)() | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läsning **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](./)\> [GetBasePlaceholder](./getbaseplaceholder/)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknings-datastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | Returnerar formens miniatyrbild. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatyrbildens gränstyper används som standard. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returnerar formens miniatyrbild. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ som beskrivs av targetType. Analog till C# 'is' operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar inte någonting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar inte någonting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referens-jämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med specificerat värde. |
| virtual void [RemovePlaceholder](./removeplaceholder/)() | Definierar att denna form inte är en platshållare. |
| virtual void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) | Sätter den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) | Sätter titeln för den alternativa texten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Egendom specificerar hur en form ska renderas i svart-vitt läge. Skriv [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sätter formens ram-egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](./set_height/)(**float**) | Sätter formens höjd, mätt i punkter. Skriv **float**. |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | Anger om formen är dold. Skriv **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken som är definierad för musklick. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken som är definierad för musöver. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](./set_isdecorative/)(**bool**) | Sätter 'Mark as decorative'-alternativet Läs/skriv **bool**. |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | Sätter namnet på en form. Skriv [System::String](../../system/string/). |
| virtual void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sätter de råa ram-egenskaperna för en form. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](./set_rotation/)(**float**) | Sätter antalet grader som den specificerade formen är roterad runt z-axeln. Ett positivt värde betyder medurs rotation; ett negativt värde betyder moturs rotation. Skriv **float**. |
| virtual void [set_Width](./set_width/)(**float**) | Sätter formens bredd, mätt i punkter. Skriv **float**. |
| virtual void [set_X](./set_x/)(**float**) | Sätter x-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [set_Y](./set_y/)(**float**) | Sätter y-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument som en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräkning. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/)) konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sparar innehållet av [Shape](../shape/) som SVG-fil. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Sparar innehållet av [Shape](../shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Se även

* Klass [ISlideComponent](../islidecomponent/)
* Klass [IHyperlinkContainer](../ihyperlinkcontainer/)
* Namnutrymme [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)