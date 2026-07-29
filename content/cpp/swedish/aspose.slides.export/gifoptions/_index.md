---
title: GifOptions
second_title: Aspose.Slides för C++ API-referens
description: Representerar GIF-exportalternativ.
type: docs
weight: 53
url: /sv/aspose.slides.export/gifoptions/
---
## GifOptions klass

Representerar GIF-exportalternativ.

```cpp
class GifOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IGifOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| **int32_t** [get_DefaultDelay](./get_defaultdelay/)() override | Hämtar standardfördröjningstid [ms]. Detta värde kommer att användas om [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/)-metoden inte anropades. Standardvärdet är 1000. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returnerar typsnitt som används om källtypsnittet inte hittas. Läser [System::String](../../system/string/). |
| **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() override | Bestämmer om dolda bilder ska exporteras. Standardvärdet är false. |
| [System::Drawing::Size](../../system.drawing/size/) [get_FrameSize](./get_framesize/)() override | Hämtar ramstorlek. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Returnerar gradientens visuella stil. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Läs **bool**. Standardvärdet är **false**. |
| **int32_t** [get_TransitionFps](./get_transitionfps/)() override | Hämtar övergångens FPS [bilder/sek] Standardvärdet är 25. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Returnerar eller ställer in ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
|  [GifOptions](./gifoptions/)() | Initierar en ny instans av [GifOptions](./)-klassen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultDelay](./set_defaultdelay/)(**int32_t**) override | Ställer in standardfördröjningstid [ms]. Detta värde kommer att användas om [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/)-metoden inte anropades. Standardvärdet är 1000. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ställer in typsnitt som används om källtypsnittet inte hittas. Skriver [System::String](../../system/string/). |
| void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) override | Bestämmer om dolda bilder ska exporteras. Standardvärdet är false. |
| void [set_FrameSize](./set_framesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Ställer in ramstorlek. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ställer in gradientens visuella stil. Skriver [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över vid sparande av presentationen. Skriver **bool**. Standardvärdet är **false**. |
| void [set_TransitionFps](./set_transitionfps/)(**int32_t**) override | Ställer in övergångens FPS [bilder/sek] Standardvärdet är 25. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returnerar eller ställer in ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Skriver [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer n'th mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar

Följande exempel visar hur man konverterar presentationer till animerad GIF med anpassade inställningar.
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto gifOptions = System::MakeObject<GifOptions>();

gifOptions->set_FrameSize(System::Drawing::Size(960, 720)); // storleken på den resulterande GIF-filen
gifOptions->set_DefaultDelay(2000); // hur länge varje bild visas tills den byts till nästa
gifOptions->set_TransitionFps(35); // öka FPS för bättre övergångsanimeringskvalitet

pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Se även

* Klass [SaveOptions](../saveoptions/)
* Klass [IGifOptions](../igifoptions/)
* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)