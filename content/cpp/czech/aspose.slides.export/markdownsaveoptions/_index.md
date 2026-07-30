---
title: MarkdownSaveOptions
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje možnosti, které řídí, jak má být prezentace uložena do markdownu.
type: docs
weight: 547
url: /cs/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions třída

Reprezentuje možnosti, které řídí, jak má být prezentace uložena do markdownu.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní použití. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Určuje základní cestu, kam bude dokument s prostředky uložen. Výchozí je aktuální adresář aplikace. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Vrací písmo použité, pokud není nalezeno zdrojové písmo. Čte [System::String](../../system/string/). |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Určuje specifikaci markdownu pro převod prezentace. Výchozí je **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Určuje specifikaci markdownu pro převod prezentace. Výchozí je **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Vrací vizuální styl gradientu. Čte [GradientStyle](../../aspose.slides/gradientstyle/). |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Určuje, jak mají být při exportu do Markdownu zpracovávány opakující se běžné mezery. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Určuje název složky pro uložení obrázků. Výchozí je **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Určuje, zda má vygenerovaný dokument mít nové řádky \r(Macintosh), \n(Unix) nebo \r\n(Windows). Výchozí je **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | Pokud je nastaven na **true**, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdownu. Výchozí je **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Určuje, zda má vygenerovaný dokument zobrazovat komentáře. Výchozí je **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky. Výchozí je **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku. Výchozí je **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Určuje, zda přeskočit hypertextové odkazy s voláním JavaScriptu při ukládání prezentace. Čte **bool**. Výchozí hodnota je **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Získá formátovací řetězec používaný pro záhlaví čísel snímků ve výstupu Markdownu. Formát musí obsahovat zástupný znak \"{0}\", který bude během exportu nahrazen indexem snímku. Příklad: \"# Slide {0}\" vytvoří \"# Slide 1\", \"# Slide 2\" atd. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Čte [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Konstruktor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Určuje základní cestu, kam bude dokument s prostředky uložen. Výchozí je aktuální adresář aplikace. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Nastavuje písmo použité, pokud není nalezeno zdrojové písmo. Zapíše [System::String](../../system/string/). |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Určuje specifikaci markdownu pro převod prezentace. Výchozí je **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Určuje specifikaci markdownu pro převod prezentace. Výchozí je **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Nastavuje vizuální styl gradientu. Zapíše [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Určuje, jak mají být při exportu do Markdownu zpracovávány opakující se běžné mezery. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Určuje název složky pro uložení obrázků. Výchozí je **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Určuje, zda má vygenerovaný dokument mít nové řádky \r(Macintosh), \n(Unix) nebo \r\n(Windows). Výchozí je **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | Pokud je nastaven na **true**, odstraňuje prázdné řádky nebo řádky obsahující pouze mezery z konečného výstupu Markdownu. Výchozí je **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Určuje, zda má vygenerovaný dokument zobrazovat komentáře. Výchozí je **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky. Výchozí je **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Určuje, zda má vygenerovaný dokument zobrazovat číslo každého snímku. Výchozí je **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Určuje, zda přeskočit hypertextové odkazy s voláním JavaScriptu při ukládání prezentace. Zapíše **bool**. Výchozí hodnota je **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Nastavuje formátovací řetězec používaný pro záhlaví čísel snímků ve výstupu Markdownu. Formát musí obsahovat zástupný znak \"{0}\", který bude během exportu nahrazen indexem snímku. Příklad: \"# Slide {0}\" vytvoří \"# Slide 1\", \"# Slide 2\" atd. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Zapíše [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Voláno pro každý obrázek, který není SVG (bitmapa nebo metafile), během exportu do Markdownu.\n Vrátí **true**, aby se použil zadaný *link*,\n nebo **false**, aby se použila výchozí logika ukládání. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Voláno pro každý SVG obrázek během exportu do Markdownu.\n Vrátí **true**, aby se použil zadaný *link*,\n nebo **false**, aby se použila výchozí logika ukládání. |

## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Viz také

* Třída [SaveOptions](../saveoptions/)
* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)