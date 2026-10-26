---
title: PortionFormat
second_title: Aspose.Slides C++ API referencia
description: Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. Az IPortionFormatEffectiveData-től eltérően, ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 4811
url: /hu/aspose.slides/portionformat/
---
## PortionFormat osztály


Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. A [IPortionFormatEffectiveData](../iportionformateffectivedata/)-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlítja a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) szemantika használatával hasonlítja össze az objektumokat. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stílusban hasonlítja össze a referencia típusú objektumokat. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Visszaadja egy alternatív nyelv azonosítóját. Olvasd [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Visszaadja a könyvjelző azonosítóját. Olvasd [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Visszaadja a komplex szkript betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Olvasd [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Visszaadja a kelet-ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Olvasd [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Visszaadja a szöveg [EffectFormat](../effectformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Visszaadja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell örökölni. Olvasd **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Visszaadja a szöveg [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Visszaadja egy rész betűméretét. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs definiálva, és a Masterből kell örökölni. Olvasd **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Visszaadja a szöveg aláhúzás típusát. Nincs öröklődés. Olvasd [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasható [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Hiperhivatkozások kezelője. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Visszaadja az egérmutatásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Megállapítja, hogy az aláhúzási stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e, vagy a szöveg [FillFormat](../fillformat/) tulajdonságaiból örököl. Olvasd [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Megállapítja, hogy az aláhúzási stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e, vagy a szöveg [LineFormat](../lineformat/) tulajdonságaiból örököl. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Visszaadja a minimális betűméretet, amelynél a kerninget be kell kapcsolni. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell örökölni. Olvasd **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvre jellemző függőleges elrendezést. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Visszaadja egy helyesírási nyelv azonosítóját. Helyesírás- és nyelvtan-ellenőrzéshez használják. Olvasd [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Visszaadja a latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Olvasd [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Visszaadja a szöveg kontúrjának [LineFormat](../lineformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasható [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/)-t. Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Megállapítja, hogy a szöveget ne ellenőrizze-e helyesírásra. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Megállapítja, hogy a smart tag-et tisztítani kell-e. Nincs öröklődés. Olvasd **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Visszaadja a karakterköz közti növekedést. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell örökölni. Olvasd **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Megkap egy értéket, amely azt jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha a tulajdonság false, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Visszaadja a szöveg áthúzás típusát. Nincs öröklődés. Olvasd [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Visszaadja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Olvasd [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Visszaadja a szöveg nagybetűs írás típusát. Nincs öröklődés. Olvasd [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Visszaadja az aláhúzási vonal [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Visszaadja a [LineFormat](../lineformat/) tulajdonságokat, amelyeket az aláhúzási vonal körvonalazásához használnak. Nincs öröklődés. Csak olvasható [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciacs counter adatstruktúrát. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Megkapja a hatékony rész formázási adatokat az öröklődés alkalmazásával. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Közvetlenül hívja, vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
|  [PortionFormat](./portionformat/)() | Inicializál egy új [PortionFormat](./) osztálypéldányt. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-al. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacs számlálót a megadott értékkel. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Beállítja egy alternatív nyelv azonosítóját. Írja [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Beállítja a könyvjelző azonosítóját. Írja [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a komplex szkript betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Írja [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a kelet-ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Írja [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Beállítja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell örökölni. Írja **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Beállítja egy rész betűmagasságát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs definiálva, és a Masterből kell örökölni. Írja **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Beállítja a szöveg aláhúzás típusát. Nincs öröklődés. Írja [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egérmutatásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy az aláhúzási stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e, vagy a szöveg [FillFormat](../fillformat/) tulajdonságaiból örököl. Írja [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy az aláhúzási stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e, vagy a szöveg [LineFormat](../lineformat/) tulajdonságaiból örököl. Írja [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Beállítja a minimális betűméretet, amelynél a kerninget be kell kapcsolni. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell örökölni. Írja **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvre jellemző függőleges elrendezést. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Beállítja egy helyesírási nyelv azonosítóját. Helyesírás- és nyelvtan-ellenőrzéshez használják. Írja [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Írja [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a szöveget ne ellenőrizze-e helyesírásra. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Megállapítja, hogy a smart tag-et tisztítani kell-e. Nincs öröklődés. Írja **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Beállítja a karakterköz növekedést. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell örökölni. Írja **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Beállít egy értéket, amely azt jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha a tulajdonság false, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Beállítja a szöveg áthúzás típusát. Nincs öröklődés. Írja [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell örökölni. Írja [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Beállítja a szöveg nagybetűs írás típusát. Nincs öröklődés. Írja [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a shared helyett). Lehetővé teszi, hogy a tárolókban lévő mutatókat gyenge módra állítsa. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciacs számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacs számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacs számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Közvetlenül hívja, vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacs számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacs számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Megjegyzések


Ez az osztály a konkrét szövegrészhez definiált formázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy az értékek lekérésekor nincs öröklődés, így a legtöbb esetben az "undefined" jelentésű értékeket kapja.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterek értékeinek lekéréséhez használni kell a [PortionFormat::GetEffective](./geteffective/) metódust, amely egy [IPortionFormatEffectiveData](../iportionformateffectivedata/) példányt ad vissza.

A következő példák megmutatják, hogyan lehet a Latin betűtípust egy [Paragraph](../paragraph/) részéhez a PowerPoint [Presentation](../presentation/)-ben hozzárendelni.
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Az Aspose.Slides ezeket a speciális azonosítókat használja (hasonlóan a PowerPoint-ban használtakhoz):
// +mn-lt - Test betűtípusa Latin (Kisebb Latin betűtípus)
// +mj-lt - Fejléc betűtípusa Latin (Nagy Latin betűtípusa)
// +mn-ea - Test betűtípusa Kelet-ázsiai (Kisebb Kelet-ázsiai betűtípus)
// +mj-ea - Test betűtípusa Kelet-ázsiai (Kisebb Kelet-ázsiai betűtípus)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Lásd még

* Osztály [BasePortionFormat](../baseportionformat/)
* Osztály [IPortionFormat](../iportionformat/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)