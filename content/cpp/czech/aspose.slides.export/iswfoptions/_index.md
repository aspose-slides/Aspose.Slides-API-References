---
title: ISwfOptions
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu SWF.
type: docs
weight: 469
url: /cs/aspose.slides.export/iswfoptions/
---
## ISwfOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, ačkoliv podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, ačkoliv podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní účely. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Určuje, zda má být generovaný SWF dokument komprimován nebo ne. Výchozí hodnota je **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Vrací písmo použité v případě, že není nalezeno zdrojové písmo. Čte [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Povoluje/zakazuje kontextové menu. Výchozí hodnota je true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Vrací vizuální styl gradientu. Čte [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Určuje kvalitu JPEG obrázků. \n\n Výchozí hodnota je 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. \n\n Obrázek by měl být PNG o rozměrech 32x64 pixelů, jinak může být logo zobrazeno nesprávně. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Získává plnou adresu hypertextového odkazu pro logo. Má účinek pouze pokud je zadán [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Reprezentuje zpětné volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Zobrazí/skryje spodní panel. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Zobrazí/skryje tlačítko na celou obrazovku. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Určuje, zda má generovaný dokument zahrnovat skryté snímky nebo ne. Výchozí hodnota je **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Zobrazí/skryje levý panel. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Určuje, zda má být kolem stránek zobrazena ohraničení. Výchozí hodnota je true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Zobrazí/skryje krokovač stránek. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Zobrazí/skryje sekci vyhledávání. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Zobrazí/skryje celý horní panel. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čte **bool**. Výchozí hodnota je **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Získává režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). Tato vlastnost nepodporuje přiřazení objektů typu **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)**. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Spustí s otevřeným levým panelem. Lze přepsat pomocí flashvars. Výchozí hodnota je false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Určuje, zda má generovaný SWF dokument zahrnovat integrovaný prohlížeč dokumentů nebo ne. Výchozí hodnota je **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Vrací objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat, nebo bude přerušen. Čte [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílené počítadlo referencí o zadanou hodnotu. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Určuje, zda má být generovaný SWF dokument komprimován nebo ne. Výchozí hodnota je **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Nastavuje písmo použité v případě, že není nalezeno zdrojové písmo. Zapíše [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Povoluje/zakazuje kontextové menu. Výchozí hodnota je true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Nastavuje vizuální styl gradientu. Zapíše [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Určuje kvalitu JPEG obrázků. \n\n Výchozí hodnota je 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obrázek, který bude zobrazen jako logo v pravém horním rohu prohlížeče. \n\n Obrázek by měl být PNG o rozměrech 32x64 pixelů, jinak může být logo zobrazeno nesprávně. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Nastavuje plnou adresu hypertextového odkazu pro logo. Má účinek pouze pokud je zadán [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Reprezentuje zpětné volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Zobrazí/skryje spodní panel. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Zobrazí/skryje tlačítko na celou obrazovku. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Určuje, zda má generovaný dokument zahrnovat skryté snímky nebo ne. Výchozí hodnota je **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Zobrazí/skryje levý panel. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Určuje, zda má být kolem stránek zobrazena ohraničení. Výchozí hodnota je true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Zobrazí/skryje krokovač stránek. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Zobrazí/skryje sekci vyhledávání. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Zobrazí/skryje celý horní panel. Lze přepsat pomocí flashvars. Výchozí hodnota je true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Zapíše **bool**. Výchozí hodnota je **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). Tato vlastnost nepodporuje přiřazení objektů typu **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)**. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Spustí s otevřeným levým panelem. Lze přepsat pomocí flashvars. Výchozí hodnota je false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Určuje, zda má generovaný SWF dokument zahrnovat integrovaný prohlížeč dokumentů nebo ne. Výchozí hodnota je **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat, nebo bude přerušen. Zapíše [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílené počítadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílené počítadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počítadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počítadlo referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [ISaveOptions](../isaveoptions/)
* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)