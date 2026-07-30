---
title: FontsManager
second_title: Aspose.Slides pro C++ API Reference
description: Spravuje fonty v celé prezentaci.
type: docs
weight: 989
url: /cs/aspose.slides/fontsmanager/
---
## FontsManager třída

Spravuje fonty v celé prezentaci.

```cpp
class FontsManager : public Aspose::Slides::IFontsManager
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [AddEmbeddedFont](./addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Přidá vložený font |
| void [AddEmbeddedFont](./addembeddedfont/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Přidá vložený font |
| virtual void [AddEmbeddedFont](../ifontsmanager/addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) | Přidá vložený font. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typů hodnot ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/)\> [get_FontFallBackRule](./get_fontfallbackrule/)(**int32_t**) override | Vrací pravidlo na zadaném indexu pro správné nahrazení pomocí funkce záložní náhrady. Pouze pro čtení [Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\> [get_FontFallBackRulesCollection](./get_fontfallbackrulescollection/)() override | Reprezentuje kolekci pravidel FontFallBack uživatele pro správu kolekcí fontů pro správné nahrazení pomocí funkce záložní náhrady. Číst [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\> [get_FontSubstRule](./get_fontsubstrule/)(**int32_t**) override | Vrací pravidlo nahrazení fontu na zadaném indexu pro použití při vykreslování. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\> [get_FontSubstRuleList](./get_fontsubstrulelist/)() override | Nahrazení fontů pro použití při vykreslování. Číst [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetEmbeddedFonts](./getembeddedfonts/)() override | Vrací fonty vložené v prezentaci |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](./getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::FontStyleType](../fontstyletype/)) override | Načte pole bajtů představující data fontu pro zadaný styl fontu a data fontu. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](../ifontsmanager/getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [FontStyleType](../fontstyletype/)) | Načte pole bajtů představující data fontu pro zadaný styl fontu a data fontu. |
| [Aspose::Slides::EmbeddingLevel](../embeddinglevel/) [GetFontEmbeddingLevel](./getfontembeddinglevel/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/)) override | Určuje úroveň vkládání fontu z daného pole bajtů a názvu fontu. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetFonts](./getfonts/)() override | Vrací fonty použité v prezentaci |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování uživatelských objektů. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)() override | Získá informace o fontech, které budou nahrazeny při vykreslování prezentace. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)([System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Získá informace o fontech, které budou nahrazeny během vykreslování zadaných snímků. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného cílovým typem. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Přiřazovací operátor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [RemoveEmbeddedFont](./removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Odstraní vložený font |
| virtual void [RemoveEmbeddedFont](../ifontsmanager/removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Odstraní vložený font |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Nahradí font v prezentaci |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\>) override | Nahradí font v prezentaci pomocí informací poskytnutých v [FontSubstRule](../fontsubstrule/) |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Nahradí font v prezentaci pomocí informací poskytnutých v kolekci [FontSubstRule](../fontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nahradí font v prezentaci |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRule](../ifontsubstrule/)\>) | Nahradí font v prezentaci pomocí informací poskytnutých v [IFontSubstRule](../ifontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Nahradí font v prezentaci pomocí informací poskytnutých v kolekci [IFontSubstRule](../ifontsubstrule/) |
| void [set_FontFallBackRulesCollection](./set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) override | Reprezentuje kolekci pravidel FontFallBack uživatele pro správu kolekcí fontů pro správné nahrazení pomocí funkce záložní náhrady. Zapisovat [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| virtual void [set_FontFallBackRulesCollection](../ifontsmanager/set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) | Reprezentuje kolekci pravidel FontFallBack uživatele pro správu kolekcí fontů pro správné nahrazení pomocí funkce záložní náhrady. Zapisovat [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| void [set_FontSubstRuleList](./set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Nahrazení fontů pro použití při vykreslování. Zapisovat [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [set_FontSubstRuleList](../ifontsmanager/set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Nahrazení fontů pro použití při vykreslování. Zapisovat [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí podle C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Poznámky

Následující příklad ukazuje, jak přidat vložené fonty do PowerPoint [Presentation](../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [IFontsManager](../ifontsmanager/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)