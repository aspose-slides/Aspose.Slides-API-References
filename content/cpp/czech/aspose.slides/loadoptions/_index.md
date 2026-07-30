---
title: LoadOptions
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Umožňuje zadat další možnosti (např. formát nebo výchozí písmo) při načítání prezentace.
type: docs
weight: 4395
url: /cs/aspose.slides/loadoptions/
---
## LoadOptions třída

Allows to specify additional options (such as format or default font) when loading a presentation.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | Representuje možnosti, které lze použít k řízení chování při práci s Binary Large Objects (BLOBs), například používání dočasných souborů nebo maximálního počtu bajtů BLOBs v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | Vrací asijské písmo použité v případě, že výchozí písmo není nalezeno. Přečtěte si [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | Vrací běžné písmo použité v případě, že výchozí písmo není nalezeno. Přečtěte si [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | Vrací symbolické písmo použité v případě, že výchozí písmo není nalezeno. Přečtěte si [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | Vrací výchozí jazyk pro text prezentace. Přečtěte si [System::String](../../system/string/). |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | Určuje, zda [Aspose.Slides](../) při načítání prezentace smaže všechny vložené binární objekty. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | Určuje zdroje externích písem, která mají být použita v prezentaci. Tato písma jsou během celého životního cyklu prezentace k dispozici a nejsou sdílena s jinými prezentacemi |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | Token pro sledování požadavků na přerušení. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | Vrací formát prezentace k načtení. Přečtěte si [Slides::LoadFormat](../loadformat/). |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota true znamená, že z šifrovaného souboru prezentace musí být načteny pouze vlastnosti dokumentu a heslo má být ignorováno. Hodnota false znamená, že celá šifrovaná prezentace musí být načtena s použitím správného hesla. Pokud není prezentace šifrovaná, pak je hodnota vlastnosti vždy ignorována. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné a hodnota vlastnosti je true, pak vlastnosti dokumentu nelze načíst a bude vyvolána výjimka. Přečtěte si **bool**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Získá heslo. Přečtěte si [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | Vrací rozhraní zpětného volání, které spravuje načítání externích zdrojů. Přečtěte si [IResourceLoadingCallback](../iresourceloadingcallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | Získá možnosti pro tabulky. Například tyto možnosti ovlivňují výpočet vzorců pro grafy. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | Vrací objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Přečtěte si [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla reference spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analoga volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analoga operátoru C# 'is'. |
|  [LoadOptions](./loadoptions/)() | Vytvoří nové výchozí možnosti načítání. |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | Vytvoří nové možnosti načítání. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o uvedenou hodnotu. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | Representuje možnosti, které lze použít k řízení chování při práci s Binary Large Objects (BLOBs), například používání dočasných souborů nebo maximálního počtu bajtů BLOBs v paměti. Tyto možnosti jsou určeny k nastavení nejlepšího poměru výkonu a spotřeby paměti pro konkrétní prostředí nebo požadavky. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | Nastaví asijské písmo použité v případě, že výchozí písmo není nalezeno. Zapište [System::String](../../system/string/). |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | Nastaví běžné písmo použité v případě, že výchozí písmo není nalezeno. Zapište [System::String](../../system/string/). |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | Nastaví symbolické písmo použité v případě, že výchozí písmo není nalezeno. Zapište [System::String](../../system/string/). |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | Nastaví výchozí jazyk pro text prezentace. Zapište [System::String](../../system/string/). |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | Určuje, zda [Aspose.Slides](../) při načítání prezentace smaže všechny vložené binární objekty. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | Určuje zdroje externích písem, která mají být použita v prezentaci. Tato písma jsou během celého životního cyklu prezentace k dispozici a nejsou sdílena s jinými prezentacemi |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | Token pro sledování požadavků na přerušení. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | Nastaví formát prezentace k načtení. Zapište [Slides::LoadFormat](../loadformat/). |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem. Hodnota true znamená, že z šifrovaného souboru prezentace musí být načteny pouze vlastnosti dokumentu a heslo má být ignorováno. Hodnota false znamená, že celá šifrovaná prezentace musí být načtena s použitím správného hesla. Pokud není prezentace šifrovaná, pak je hodnota vlastnosti vždy ignorována. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné a hodnota vlastnosti je true, pak vlastnosti dokumentu nelze načíst a bude vyvolána výjimka. Zapište **bool**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Nastaví heslo. Zapište [System::String](../../system/string/). |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | Nastaví rozhraní zpětného volání, které spravuje načítání externích zdrojů. Zapište [IResourceLoadingCallback](../iresourceloadingcallback/). |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | Získá možnosti pro tabulky. Například tyto možnosti ovlivňují výpočet vzorců pro grafy. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Nastaví objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Zapište [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [ILoadOptions](../iloadoptions/)
* Obor názvů [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)