---
title: SwfOptions
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i Swf-format.
type: docs
weight: 742
url: /sv/aspose.slides.export/swfoptions/
---
## SwfOptions klass


Tillhandahåller alternativ som styr hur en presentation sparas i Swf-format.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **bool** [get_Compressed](./get_compressed/)() override | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returnerar typsnittet som används om källtypsnittet inte hittas. Läser [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Aktivera/inaktivera snabbmenyn. Standard är true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Returnerar den visuella stilen för gradienten. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Anger kvaliteten på JPEG-bilder. Standard är 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Bild som kommer att visas som logotyp i det övre högra hörnet av visaren. Bilden ska vara en 32x64 pixlar PNG-bild, annars kan logotypen visas felaktigt. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Hämtar den fullständiga hyperlänkadressen för en logotyp. Har bara effekt om en [set_LogoImageBytes()](./set_logoimagebytes/) har angetts. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Visa/dölj bottenpanel. Kan åsidosättas i flashvars. Standard är true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Visa/dölj vänsterpanel. Kan åsidosättas i flashvars. Standard är true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Anger om ram runt sidor ska visas. Standard är true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Visa/dölj hela toppanelen. Kan åsidosättas i flashvars. Standard är true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Läs **bool**. Standardvärdet är **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Hämtar läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). Denna egenskap stödjer inte tilldelning av objekt av typ [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standard är false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Returnerar eller sätter ett objekt som tar emot varningar och avgör om laddningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ som beskrivs av targetType. Analog till C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypsobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Anger om det genererade SWF-dokumentet ska komprimeras eller inte. Standard är **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ställer in typsnitt som används om källtypsnittet inte hittas. Skriver [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Aktivera/inaktivera snabbmenyn. Standard är true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ställer in den visuella stilen för gradienten. Skriver [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Anger kvaliteten på JPEG-bilder. Standard är 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Bild som kommer att visas som logotyp i det övre högra hörnet av visaren. Bilden ska vara en 32x64 pixlar PNG-bild, annars kan logotypen visas felaktigt. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Ställer in den fullständiga hyperlänkadressen för en logotyp. Har bara effekt om en [set_LogoImageBytes()](./set_logoimagebytes/) har angetts. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Visa/dölj bottenpanel. Kan åsidosättas i flashvars. Standard är true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Visa/dölj helskärmsknapp. Kan åsidosättas i flashvars. Standard är true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Visa/dölj vänsterpanel. Kan åsidosättas i flashvars. Standard är true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Anger om ram runt sidor ska visas. Standard är true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Visa/dölj sidstegare. Kan åsidosättas i flashvars. Standard är true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Visa/dölj söksektion. Kan åsidosättas i flashvars. Standard är true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Visa/dölj hela toppanelen. Kan åsidosättas i flashvars. Standard är true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Skriv **bool**. Standardvärdet är **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Ställer in läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). Denna egenskap stödjer inte tilldelning av objekt av typ [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Starta med öppnad vänsterpanel. Kan åsidosättas i flashvars. Standard är false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Anger om det genererade SWF-dokumentet ska inkludera den integrerade dokumentvisaren eller inte. Standard är **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returnerar eller sätter ett objekt som tar emot varningar och avgör om laddningsprocessen ska fortsätta eller avbrytas. Skriv [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [SwfOptions](./swfoptions/)() | Standardkonstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/)) konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar


Följande exempel visar hur man konverterar PowerPoint till SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Se även

* Klass [SaveOptions](../saveoptions/)
* Klass [ISwfOptions](../iswfoptions/)
* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)