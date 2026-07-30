---
title: SwfOptions
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Swf.
type: docs
weight: 742
url: /cs/aspose.slides.export/swfoptions/
---
## SwfOptions class


Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Swf.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_Compressed](./get_compressed/)() override | Určuje, zda má být vygenerovaný SWF dokument komprimován. Výchozí hodnota je **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Vrací písmo použité v případě, že zdrojové písmo není nalezeno. Čte [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Povolit/zakázat kontextové menu. Výchozí hodnota je true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Získává vizuální styl gradientu. Čte [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Určuje kvalitu JPEG obrázků. Výchozí hodnota je 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl být PNG o rozměrech 32×64 pixelů, jinak může být logo zobrazeno nesprávně. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Získává úplnou adresu hypertextového odkazu pro logo. Má efekt pouze pokud je zadáno [set_LogoImageBytes()](./set_logoimagebytes/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Zobrazit/skrýt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Zobrazit/skrýt tlačítko celé obrazovky. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Určuje, zda má vygenerovaný dokument obsahovat skryté snímky, nebo ne. Výchozí hodnota je **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Zobrazit/skrýt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Určuje, zda má být kolem stránek zobrazena ohraničující čára. Výchozí hodnota je true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Zobrazit/skrýt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Zobrazit/skrýt sekci hledání. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Zobrazit/skrýt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čte **bool**. Výchozí hodnota je **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Získává režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). Tato vlastnost nepodporuje přiřazování objektů typu [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Spustit s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Určuje, zda má vygenerovaný SWF dokument obsahovat integrovaný prohlížeč dokumentů, nebo ne. Výchozí hodnota je **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Čte [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počitadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analóg C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává aktuální typ objektu. Analóg C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analóg C# operátoru 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje C# lock() statement blocking. Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analóg C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Určuje, zda má být vygenerovaný SWF dokument komprimován. Výchozí hodnota je **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Nastavuje písmo použité v případě, že zdrojové písmo není nalezeno. Zapíše [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Povolit/zakázat kontextové menu. Výchozí hodnota je true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Nastavuje vizuální styl gradientu. Zapíše [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Určuje kvalitu JPEG obrázků. Výchozí hodnota je 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. Obrázek by měl být PNG o rozměrech 32×64 pixelů, jinak může být logo zobrazeno nesprávně. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Nastavuje úplnou adresu hypertextového odkazu pro logo. Má efekt pouze pokud je zadáno [set_LogoImageBytes()](./set_logoimagebytes/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Zobrazit/skrýt spodní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Zobrazit/skrýt tlačítko celé obrazovky. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Určuje, zda má vygenerovaný dokument obsahovat skryté snímky, nebo ne. Výchozí hodnota je **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Zobrazit/skrýt levý panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Určuje, zda má být kolem stránek zobrazena ohraničující čára. Výchozí hodnota je true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Zobrazit/skrýt krokovač stránek. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Zobrazit/skrýt sekci hledání. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Zobrazit/skrýt celý horní panel. Lze přepsat ve flashvars. Výchozí hodnota je true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Zapíše **bool**. Výchozí hodnota je **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). Tato vlastnost nepodporuje přiřazování objektů typu [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Spustit s otevřeným levým panelem. Lze přepsat ve flashvars. Výchozí hodnota je false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Určuje, zda má vygenerovaný SWF dokument obsahovat integrovaný prohlížeč dokumentů, nebo ne. Výchozí hodnota je **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Zapíše [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do režimu slabý. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Implicitní konstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analóg C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje C# typeof([System.Object](../../system/object/)) konstrukci. |
| void [Unlock](../../system/object/unlock/)() | Implementuje C# lock() statement odemykání. Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Poznámky


Následující příklad ukazuje, jak převést PowerPoint do SWF Flash. 
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

## Viz také

* Třída [SaveOptions](../saveoptions/)
* Třída [ISwfOptions](../iswfoptions/)
* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)