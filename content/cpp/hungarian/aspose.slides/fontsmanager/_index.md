---
title: FontsManager
second_title: Aspose.Slides C++ API referencia
description: A prezentációban a betűtípusokat kezeli.
type: docs
weight: 989
url: /hu/aspose.slides/fontsmanager/
---
## FontsManager osztály

A betűtípusok kezelését végzi az egész bemutatóban.

```cpp
class FontsManager : public Aspose::Slides::IFontsManager
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [AddEmbeddedFont](./addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Hozzáadja a beágyazott betűtípust |
| void [AddEmbeddedFont](./addembeddedfont/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Hozzáadja a beágyazott betűtípust |
| virtual void [AddEmbeddedFont](../ifontsmanager/addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) | Hozzáadja a beágyazott betűtípust. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az érték típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/)\> [get_FontFallBackRule](./get_fontfallbackrule/)(**int32_t**) override | Visszaadja a szabályt a megadott indexnél a helyes helyettesítéshez visszaeső funkcióval. Csak olvasható [Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\> [get_FontFallBackRulesCollection](./get_fontfallbackrulescollection/)() override | A felhasználó FontFallBack szabálykészletét képviseli a betűtípusok gyűjtésének kezelése érdekében a megfelelő helyettesítéshez visszaeső funkcióval. Olvas [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\> [get_FontSubstRule](./get_fontsubstrule/)(**int32_t**) override | Visszaadja a betűtípus helyettesítési szabályt a megadott indexnél a rendereléshez. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\> [get_FontSubstRuleList](./get_fontsubstrulelist/)() override | Betűtípus helyettesítések a rendereléshez. Olvas [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetEmbeddedFonts](./getembeddedfonts/)() override | Visszaadja a bemutatóban beágyazott betűtípusokat |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](./getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::FontStyleType](../fontstyletype/)) override | Lekéri a bájt tömböt, amely a megadott betűstílus és betűtípus adatot reprezentálja. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](../ifontsmanager/getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [FontStyleType](../fontstyletype/)) | Lekéri a bájt tömböt, amely a megadott betűstílus és betűtípus adatot reprezentálja. |
| [Aspose::Slides::EmbeddingLevel](../embeddinglevel/) [GetFontEmbeddingLevel](./getfontembeddinglevel/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/)) override | Meghatározza a betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus név alapján. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetFonts](./getfonts/)() override | Visszaadja a bemutatóban használt betűtípusokat |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hasítóértékének számítását. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)() override | Lekéri a betűtípusokra vonatkozó információkat, amelyek a bemutató renderelésekor lesznek helyettesítve. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)([System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Lekéri a betűtípusokra vonatkozó információkat, amelyek a megadott diák renderelése során lesznek helyettesítve. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zárolásra. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló példányosítását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló példányosítását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [RemoveEmbeddedFont](./removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Eltávolítja a beágyazott betűtípust |
| virtual void [RemoveEmbeddedFont](../ifontsmanager/removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Eltávolítja a beágyazott betűtípust |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Betűtípust cserél a bemutatóban |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\>) override | Betűtípust cserél a bemutatóban a [FontSubstRule](../fontsubstrule/) által biztosított információk alapján |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Betűtípust cserél a bemutatóban a [FontSubstRule](../fontsubstrule/) gyűjtemény által biztosított információk alapján |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Betűtípust cserél a bemutatóban |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRule](../ifontsubstrule/)\>) | Betűtípust cserél a bemutatóban a [IFontSubstRule](../ifontsubstrule/) által biztosított információk alapján |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Betűtípust cserél a bemutatóban a [IFontSubstRule](../ifontsubstrule/) gyűjtemény által biztosított információk alapján |
| void [set_FontFallBackRulesCollection](./set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) override | A felhasználó FontFallBack szabálykészletét képviseli a betűtípusok gyűjtésének kezeléséhez a megfelelő helyettesítéshez visszaeső funkcióval. Ír [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| virtual void [set_FontFallBackRulesCollection](../ifontsmanager/set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) | A felhasználó FontFallBack szabálykészletét képviseli a betűtípusok gyűjtésének kezeléséhez a megfelelő helyettesítéshez visszaeső funkcióval. Ír [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| void [set_FontSubstRuleList](./set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Betűtípus helyettesítések a rendereléshez. Ír [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [set_FontSubstRuleList](../ifontsmanager/set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Betűtípus helyettesítések a rendereléshez. Ír [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n.-ik sablonargumentumot gyenge mutatóval állítja be (nem megosztott). Lehetővé teszi a mutatók konténerekben való átváltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

A következő példa bemutatja, hogyan lehet beágyazott betűtípusokat hozzáadni a PowerPoint [Presentation](../presentation/)-hoz.
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

// Mentse a prezentációt
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [IFontsManager](../ifontsmanager/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)