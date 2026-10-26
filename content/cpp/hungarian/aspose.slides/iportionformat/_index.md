---
title: IPortionFormat
second_title: Aspose.Slides C++ API hivatkozása
description: Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. Az IPortionFormatEffectiveData-tól eltérően, az osztály összes tulajdonsága írható.
type: docs
weight: 3329
url: /hu/aspose.slides/iportionformat/
---
## IPortionFormat osztály


Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. A [IPortionFormatEffectiveData](../iportionformateffectivedata/)-től eltérően, az osztály összes tulajdonsága írható.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Visszaadja egy alternatív nyelv azonosítóját. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Visszaadja a könyvjelző azonosítóját. Olvasd [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Visszaadja a komplex írásrendszer betűtípus információját. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Visszaadja az kelet-ázsiai betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Visszaadja a szöveg [EffectFormat](../effectformat/) tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Visszaadja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. Olvasd **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Visszaadja a szöveg [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Visszaadja egy rész betűmagasságát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs definiálva, és a mesterből kell öröklődni. Olvasd **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Olvasd [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Visszaadja a szöveg aláhúzás típusát. Nincs öröklődés alkalmazva. Olvasd [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés alkalmazva. Csak olvasható [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hiperhivatkozás-kezelő Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Visszaadja az egér fölé viteléhez definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Megállapítja, hogy az aláhúzás stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e, vagy örökli őket a szöveg [FillFormat](../fillformat/) tulajdonságaiból. Olvasd [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Megállapítja, hogy az aláhúzás stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e, vagy örökli őket a szöveg [LineFormat](../lineformat/) tulajdonságaiból. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Visszaadja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. Olvasd **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvspecifikus függőleges elrendezését. Nincs öröklődés alkalmazva. Olvasd [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Visszaadja egy helyesírási nyelv azonosítóját. Helyesírás és nyelvtan ellenőrzésére használható. Olvasd [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Visszaadja a latin betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) tulajdonságait a szöveg körvonalazásához. Nincs öröklődés alkalmazva. Csak olvasható [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés alkalmazva. Olvasd [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Megállapítja, hogy a szöveget ne végezzék ellenőrzésnek. Nincs öröklődés alkalmazva. Olvasd [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Megállapítja, hogy az okos címkét meg kell tisztítani. Nincs öröklődés alkalmazva. Olvasd **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Visszaadja a karakterköz incrementumát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. Olvasd **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Megkap egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság false-ra van beállítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true-ra van állítva, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Visszaadja a szöveg áthúzási típusát. Nincs öröklődés alkalmazva. Olvasd [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Visszaadja a szimbolikus betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Visszaadja a szöveg nagybetűs forma típusát. Nincs öröklődés alkalmazva. Olvasd [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Visszaadja az aláhúzás vonal [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Visszaadja a [LineFormat](../lineformat/) tulajdonságait, amelyek az aláhúzás vonal körvonalazásához használatosak. Nincs öröklődés alkalmazva. Csak olvasható [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektummal társított referencia számláló adatstruktúrát. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Megkapja a hatékony rész formázási adatokat az öröklődés alkalmazásával. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és engedélyezi az alosztályok másolás konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és engedélyezi az alosztályok másolás konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az érték típusú objektumot a nullptr-al. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Beállítja egy alternatív nyelv azonosítóját. Írja [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Beállítja a könyvjelző azonosítóját. Írja [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a komplex írásrendszer betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a kelet-ázsiai betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Beállítja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. Írja **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Írja [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Beállítja egy rész betűmagasságát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs definiálva, és a mesterből kell öröklődni. Írja **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Írja [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Beállítja a szöveg aláhúzás típusát. Nincs öröklődés alkalmazva. Írja [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egérkattintásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egér fölé viteléhez definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Megállapítja, hogy az aláhúzás stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e, vagy örökli őket a szöveg [FillFormat](../fillformat/) tulajdonságaiból. Írja [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Megállapítja, hogy az aláhúzás stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e, vagy örökli őket a szöveg [LineFormat](../lineformat/) tulajdonságaiból. Írja [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. Írja **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvspecifikus függőleges elrendezését. Nincs öröklődés alkalmazva. Írja [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Beállítja egy helyesírási nyelv azonosítóját. Helyesírás és nyelvtan ellenőrzésére használható. Írja [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a latin betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés alkalmazva. Írja [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a szöveget ne végezzék ellenőrzésnek. Nincs öröklődés alkalmazva. Írja [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Megállapítja, hogy az okos címkét meg kell tisztítani. Nincs öröklődés alkalmazva. Írja **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Beállítja a karakterköz incrementumát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és a mesterből kell öröklődni. Írja **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság false-ra van beállítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true-ra van állítva, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Beállítja a szöveg áthúzási típusát. Nincs öröklődés alkalmazva. Írja [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a szimbolikus betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a mesterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Beállítja a szöveg nagybetűs forma típusát. Nincs öröklődés alkalmazva. Írja [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók váltását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

Ez az osztály a meghatározott részhez definiált szövegrész formázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy az értékek lekérdezésekor nincs öröklődés alkalmazva, így a legtöbb esetben a \"nem definiált\" értékeket kapja.

Az öröklődéssel együtt a hatékony formázási paraméterértékek lekéréséhez a [IPortionFormat::GetEffective](./geteffective/) metódust kell használni, amely egy [IPortionFormatEffectiveData](../iportionformateffectivedata/) példányt ad vissza.

## Lásd még

* Osztály [IBasePortionFormat](../ibaseportionformat/)
* Osztály [IHyperlinkContainer](../ihyperlinkcontainer/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)