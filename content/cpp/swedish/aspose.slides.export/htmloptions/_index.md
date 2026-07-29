---
title: HtmlOptions
second_title: Aspose.Slides för C++ API-referens
description: Representerar alternativ för HTML-export.
type: docs
weight: 118
url: /sv/aspose.slides.export/htmloptions/
---
## HtmlOptions klass

Representerar alternativ för HTML-export.

```cpp
class HtmlOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IHtmlOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av referenstyp i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av värdetyp i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returnerar teckensnitt som används om källteckensnittet inte hittas. Läser [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Ett booleskt flagg indikerar om de beskurna delarna förblir en del av dokumentet. Om true tas de beskurna delarna bort, om false kommer de att serialiseras i dokumentet (vilket eventuellt kan leda till en större fil) |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Hämtar ett värde som indikerar om text renderas utan ligaturer. När den sätts till **true** kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är egenskapen satt till **false**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Returnerar den visuella stilen för gradienten. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() override | Returnerar HTML-mall. Läs [IHtmlFormatter](../ihtmlformatter/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Tillhandahåller alternativ som styr utseendet på [Ink](../../aspose.slides.ink/)-objekt i exporterade dokument. Skrivskyddad [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Returnerar ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Läs **uint8_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Representerar bildens komprimeringsnivå |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs **bool**. Standardvärdet är **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() override | Returnerar bildformatalternativ för bilder. Läs [ISlideImageFormat](../islideimageformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Hämtar läget i vilket bilder placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() override | True för att utesluta bredd- och höjdattribut från svg-behållaren – det gör layouten responsiv. False – annars. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Returnerar eller sätter ett objekt som mottar varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
|  [HtmlOptions](./htmloptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Skapar ett nytt [HtmlOptions](./)-objekt som specificerar återuppringning. |
|  [HtmlOptions](./htmloptions/)() | Skapar ett nytt [HtmlOptions](./)-objekt för att spara i en enda HTML-fil. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delat referensräknare med angivet värde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ställer in teckensnitt som används om källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Ett booleskt flagg indikerar om de beskurna delarna förblir en del av dokumentet. Om true tas de beskurna delarna bort, om false kommer de att serialiseras i dokumentet (vilket eventuellt kan leda till en större fil) |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Ställer in ett värde som indikerar om text renderas utan att använda ligaturer. När den sätts till **true** kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är egenskapen satt till **false**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ställer in den visuella stilen för gradienten. Skriver [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) override | Ställer in HTML-mall. Skriver [IHtmlFormatter](../ihtmlformatter/). |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Ställer in ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Skriver **uint8_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Representerar bildens komprimeringsnivå |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Skriver **bool**. Standardvärdet är **false**. |
| void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) override | Ställer in bildformatalternativ för bilder. Skriver [ISlideImageFormat](../islideimageformat/). |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Ställer in läget i vilket bilder placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) override | True för att utesluta bredd- och höjdattribut från svg-behållaren – det gör layouten responsiv. False – annars. Skriver **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returnerar eller sätter ett objekt som mottar varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. Skriver [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'th mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar det aktuella värdet av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [SaveOptions](../saveoptions/)
* Klass [IHtmlOptions](../ihtmloptions/)
* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)