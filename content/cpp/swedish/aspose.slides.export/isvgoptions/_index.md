---
title: ISVGOptions
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett SVG-alternativ.
type: docs
weight: 404
url: /sv/aspose.slides.export/isvgoptions/
---
## ISVGOptions klass


Representerar ett SVG-alternativ.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metod | Beskrivning
| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypens objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypens objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Returnerar teckensnitt som används om källteckensnittet inte hittas. Läser [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | En boolesk flagga indikerar om de beskurna delarna förblir som en del av dokumentet. Om sann så tas de beskurna delarna bort, om falsk kommer de att serialiseras i dokumentet (vilket eventuellt kan leda till en större fil) Läs **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Bestämmer om 3D-text är inaktiverad i SVG. Läs **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Hämtar ett värde som indikerar om text renderas utan ligaturer. När satt till **true** kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Inaktiverar uppdelning av FromCornerX- och FromCenter-gradienter. Läs **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 saknar förmåga att definiera inskärningar för markörer. [Aspose.Slides](../../aspose.slides/) SVG-skrivmotorn har en lösning på det problemet: den beskär slutet av linjen med pil, så linjen överlappar inte markörer. Detta alternativ stänger av sådant beteende. Läs **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Bestämmer ett sätt att hantera externt laddade teckensnitt. Läs [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Returnerar den visuella stilen för gradienten. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Tillhandahåller alternativ som styr utseendet på [Ink](../../aspose.slides.ink/)-objekt i exporterat dokument. Läs-endast [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Bestämmer JPEG-kodningskvalitet. Läs **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Returnerar den lägre upplösningsgränsen för metafil-rasterisering. Läs **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Representerar bildkomprimeringsnivån Läs [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Returnerar och ställer in ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. Läs [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Läs **bool**. Standardvärdet är **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Bestämmer om den angivna roteringen av formen ska utföras vid rendering eller inte. Läs **bool**. Standardvärdet är true. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Bestämmer om textramen kommer att inkluderas i ett renderingsområde eller inte. Läs **bool**. Standardvärdet är false. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Bestämmer om texten på en bildruta ska sparas som grafik. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Returnerar ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska objektets typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referens-jämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Ställer in teckensnitt som används om källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | En boolesk flagga indikerar om de beskurna delarna förblir som en del av dokumentet. Om sann så tas de beskurna delarna bort, om falsk kommer de att serialiseras i dokumentet (vilket eventuellt kan leda till en större fil) Skriv **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Bestämmer om 3D-text är inaktiverad i SVG. Skriv **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Ställer in ett värde som indikerar om text renderas utan ligaturer. När satt till **true** kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Inaktiverar uppdelning av FromCornerX- och FromCenter-gradienter. Skriv **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 saknar förmåga att definiera inskärningar för markörer. [Aspose.Slides](../../aspose.slides/) SVG-skrivmotorn har en lösning på det problemet: den beskär slutet av linjen med pil, så linjen överlappar inte markörer. Detta alternativ stänger av sådant beteende. Skriv **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Bestämmer ett sätt att hantera externt laddade teckensnitt. Skriv [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Ställer in den visuella stilen för gradienten. Skriv [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Bestämmer JPEG-kodningskvalitet. Skriv **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Ställer in den lägre upplösningsgränsen för metafil-rasterisering. Skriv **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Representerar bildkomprimeringsnivå Skriv [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Returnerar och ställer in ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. Skriv [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Skriv **bool**. Standardvärdet är **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Bestämmer om den angivna roteringen av formen ska utföras vid rendering eller inte. Skriv **bool**. Standardvärdet är true. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Bestämmer om textramen kommer att inkluderas i ett renderingsområde eller inte. Skriv **bool**. Standardvärdet är false. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Bestämmer om texten på en bildruta ska sparas som grafik. Skriv **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ställer in ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Skriv [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument som en svag pekare (snarare än delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [ISaveOptions](../isaveoptions/)
* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)