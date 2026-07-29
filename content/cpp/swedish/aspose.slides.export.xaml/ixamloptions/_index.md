---
title: IXamlOptions
second_title: Aspose.Slides för C++ API-referens
description: Alternativ som styr hur ett XAML-dokument sparas.
type: docs
weight: 1
url: /sv/aspose.slides.export.xaml/ixamloptions/
---
## IXamlOptions klass

Alternativ som styr hur ett XAML-dokument sparas.

```cpp
class IXamlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av referenstyp i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../../aspose.slides.export/isaveoptions/get_defaultregularfont/)() | Returnerar teckensnittet som används om källteckensnittet inte hittas. Läs [System::String](../../system/string/). |
| virtual **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() | Avgör om dolda bilder ska exporteras. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../../aspose.slides.export/isaveoptions/get_gradientstyle/)() | Returnerar gradientens visuella stil. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\> [get_OutputSaver](./get_outputsaver/)() | Representerar en implementation av IOutputSaver-gränssnittet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../../aspose.slides.export/isaveoptions/get_progresscallback/)() | Representerar ett återuppringningsobjekt för att spara förloppsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/get_skipjavascriptlinks/)() | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Läs **bool**. Standardvärdet är **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../../aspose.slides.export/isaveoptions/get_warningcallback/)() | Returnerar ett objekt som mottar varningar och avgör om inläsningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenstaggsdatastrukturen som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C#-metoden [Object.GetHashCode()](../../system/object/gethashcode/). Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C#-anropet [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C#-metoden [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Möjliggör kloning av egna typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetypobjekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenstaggsräknare med angivet värde. |
| virtual void [set_DefaultRegularFont](../../aspose.slides.export/isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Ställer in teckensnittet som används om källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| virtual void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) | Avgör om dolda bilder ska exporteras. |
| virtual void [set_GradientStyle](../../aspose.slides.export/isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Ställer in gradientens visuella stil. Skriver [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_OutputSaver](./set_outputsaver/)([System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\>) | Representerar en implementation av IOutputSaver-gränssnittet. |
| virtual void [set_ProgressCallback](../../aspose.slides.export/isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Representerar ett återuppringningsobjekt för att spara förloppsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/set_skipjavascriptlinks/)(**bool**) | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Skriv **bool**. Standardvärdet är **false**. |
| virtual void [set_WarningCallback](../../aspose.slides.export/isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ställer in ett objekt som mottar varningar och avgör om inläsningsprocessen ska fortsätta eller avbrytas. Skriv [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n:te mallargumentet som en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referenstaggsräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenstaggsräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenstaggsräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenstaggsräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenstaggsräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```


## Se också

* Klass [ISaveOptions](../../aspose.slides.export/isaveoptions/)
* Namnrymd [Aspose::Slides::Export::Xaml](../)
* Bibliotek [Aspose.Slides](../../)