---
title: ISVGOptions
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje možnosti SVG.
type: docs
weight: 404
url: /cs/aspose.slides.export/isvgoptions/
---
## ISVGOptions třída


Reprezentuje možnosti SVG.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Vrací písmo použité v případě, že zdrojové písmo není nalezeno. Čte [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Booleanový příznak udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny; pokud je false, budou serializovány v dokumentu (což může vést k většímu souboru). Read **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Určuje, zda je 3D text v SVG zakázán. Read **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Získává hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastavena na **true**, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Zakazuje dělení gradientů FromCornerX a FromCenter. Read **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 postrádá možnost definovat odsazení pro značky. [Aspose.Slides](../../aspose.slides/) SVG engine pro zápis má obcházení tohoto problému: ořezává konec čáry s šipkou, takže čára nepřekrývá značky. Toto nastavení vypíná takové chování. Read **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Určuje způsob zacházení s externě načtenými fonty. Read [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Vrací vizuální styl gradientu. Read [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Poskytuje možnosti, které řídí vzhled objektů [Ink](../../aspose.slides.ink/) v exportovaném dokumentu. Read-only [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Určuje kvalitu JPEG kódování. Read **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Vrací limit nižší rozlišení pro rasterizaci metafile. Read **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Reprezentuje úroveň komprese obrázků. Read [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Reprezentuje zpětné volání pro ukládání průběhových aktualizací v procentech. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. Read [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Určuje, zda přeskočit hypertextové odkazy s voláním JavaScriptu při ukládání prezentace. Read **bool**. Výchozí hodnota je **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Určuje, zda provést zadanou rotaci tvaru při vykreslování nebo ne. Read **bool**. Výchozí hodnota je true. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Určuje, zda bude textový rámec zahrnut v oblasti vykreslování nebo ne. Read **bool**. Výchozí hodnota je false. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Určuje, zda bude text na snímku uložen jako grafika. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Vrací objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen. Read [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Volá se přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Nastavuje písmo použité v případě, že zdrojové písmo není nalezeno. Zapíše [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Booleanový příznak udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny; pokud je false, budou serializovány v dokumentu (což může vést k většímu souboru). Write **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Určuje, zda je 3D text v SVG zakázán. Write **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Nastavuje hodnotu určující, zda je text vykreslován bez použití ligatur. Když je nastavena na **true**, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Zakazuje dělení gradientů FromCornerX a FromCenter. Write **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 postrádá možnost definovat odsazení pro značky. [Aspose.Slides](../../aspose.slides/) SVG engine pro zápis má obcházení tohoto problému: ořezává konec čáry s šipkou, takže čára nepřekrývá značky. Toto nastavení vypíná takové chování. Write **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Určuje způsob zacházení s externě načtenými fonty. Write [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Nastavuje vizuální styl gradientu. Write [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Určuje kvalitu JPEG kódování. Write **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Nastavuje limit nižšího rozlišení pro rasterizaci metafile. Write **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Reprezentuje úroveň komprese obrázků. Write [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Reprezentuje zpětné volání pro ukládání průběhových aktualizací v procentech. See [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Vrací a nastavuje rozhraní zpětného volání, které umožňuje uživateli řídit konverzi tvaru. Write [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Určuje, zda přeskočit hypertextové odkazy s voláním JavaScriptu při ukládání prezentace. Write **bool**. The default value is **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Určuje, zda provést zadanou rotaci tvaru při vykreslování nebo ne. Write **bool**. Default value is true. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Určuje, zda bude textový rámec zahrnut v oblasti vykreslování nebo ne. Write **bool**. Default value is false. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Určuje, zda bude text na snímku uložen jako grafika. Write **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Nastavuje objekt, který přijímá varování a rozhoduje, zda proces načítání bude pokračovat nebo bude přerušen. Write [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock() příkazu. Volá se přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [ISaveOptions](../isaveoptions/)
* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)