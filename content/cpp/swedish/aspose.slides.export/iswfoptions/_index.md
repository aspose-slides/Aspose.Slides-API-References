---
title: ISwfOptions
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i SWF-format.
type: docs
weight: 469
url: /sv/aspose.slides.export/iswfoptions/
---
## ISwfOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i SWF-format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Returnerar teckensnitt som används när källteckensnittet inte hittas. Läser [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Aktivera/inaktivera snabbmenyn. Standard är true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Returnerar den visuella stilen för gradienten. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Anger kvaliteten på JPEG-bilder. 

 Standard är 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Bild som visas som logotyp i övre högra hörnet av visaren. 

 Bilden bör vara en 32x64 pixlar PNG-bild, annars kan logotypen visas felaktigt. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Hämtar den fullständiga hyperlänksadressen för en logotyp. Har bara effekt om en [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) har angetts. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Representerar ett återuppringningsobjekt för sparande av förloppsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Visa/dölj bottenpanel. Kan åsidosättas i flashvars. Standard är true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Visa/dölj vänsterpanel. Kan åsidosättas i flashvars. Standard är true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Anger om en ram omkring sidorna ska visas. Standard är true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Visa/dölj hela översta panelen. Kan åsidosättas i flashvars. Standard är true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. Läs **bool**. Standardvärdet är **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Hämtar läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). Denna egenskap stöder inte tilldelning av objekt av typ **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standard är false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Returnerar ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknare-datastruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objekt. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av typen beskriven av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) sentinelobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Sätter teckensnitt som används när källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Aktivera/inaktivera snabbmenyn. Standard är true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Sätter den visuella stilen för gradienten. Skriv [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Anger kvaliteten på JPEG-bilder. 

 Standard är 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bild som visas som logotyp i övre högra hörnet av visaren. 

 Bilden bör vara en 32x64 pixlar PNG-bild, annars kan logotypen visas felaktigt. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Sätter den fullständiga hyperlänksadressen för en logotyp. Har bara effekt om en [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) har angetts. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Representerar ett återuppringningsobjekt för sparande av förloppsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Visa/dölj bottenpanel. Kan åsidosättas i flashvars. Standard är true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Visa/dölj vänsterpanel. Kan åsidosättas i flashvars. Standard är true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Anger om en ram omkring sidorna ska visas. Standard är true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Visa/dölj hela översta panelen. Kan åsidosättas i flashvars. Standard är true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. Skriv **bool**. Standardvärdet är **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Sätter läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). Denna egenskap stöder inte tilldelning av objekt av typ **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standard är false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Skriv [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde på delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) sentinelobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [ISaveOptions](../isaveoptions/)
* Namnutrymme [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)