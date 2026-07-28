---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides for C++ API hivatkozás
description: Megváltoztathatatlan objektum, amely a hatékony szövegrész formázási tulajdonságait tartalmazza.
type: docs
weight: 3342
url: /hu/aspose.slides/iportionformateffectivedata/
---
## IPortionFormatEffectiveData osztály


Megváltoztathatatlan objektum, amely a hatékony szövegrész formázási tulajdonságait tartalmazza.

```cpp
class IPortionFormatEffectiveData : public virtual Aspose::Slides::IBasePortionFormatEffectiveData
```

## Methods

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nincs egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nincs egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformateffectivedata/get_alternativelanguageid/)() | Visszaadja egy alternatív nyelv azonosítóját. Csak olvasható [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Visszaadja a könyvjelző azonosítóját. Csak olvasható [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformateffectivedata/get_complexscriptfont/)() | Visszaadja a komplex írásrendszer betűtípus információját. Csak olvasható [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformateffectivedata/get_eastasianfont/)() | Visszaadja a kelet-ázsiai betűtípus információt. Csak olvasható [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](../ibaseportionformateffectivedata/get_effectformat/)() | Visszaadja a szöveg [EffectFormat](../effectformat/) tulajdonságait. Csak olvasható [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](../ibaseportionformateffectivedata/get_escapement/)() | Visszaadja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. Csak olvasható **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](../ibaseportionformateffectivedata/get_fillformat/)() | Visszaadja a szöveg [FillFormat](../fillformat/) tulajdonságait. Csak olvasható [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](../ibaseportionformateffectivedata/get_fontbold/)() | Megállapítja, hogy a betűtípus félkövér-e. Csak olvasható **bool**. |
| virtual **float** [get_FontHeight](../ibaseportionformateffectivedata/get_fontheight/)() | Visszaadja a szövegrész betűmagasságát pontban. Csak olvasható **float**. |
| virtual **bool** [get_FontItalic](../ibaseportionformateffectivedata/get_fontitalic/)() | Megállapítja, hogy a betűtípus dőlt-e. Csak olvasható **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformateffectivedata/get_fontunderline/)() | Visszaadja a szöveg aláhúzás típusát. Csak olvasható [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](../ibaseportionformateffectivedata/get_highlightcolor/)() | Visszaadja a szöveg kiemeléséhez használt színt. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() | Visszaadja az egérkattintásra definiált hiperlinket. Csak olvasható [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() | Visszaadja az egér fölé mozgatására definiált hiperlinket. Csak olvasható [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsHardUnderlineFill](../ibaseportionformateffectivedata/get_ishardunderlinefill/)() | Megállapítja, hogy az aláhúzási stílusnak vannak-e saját [FillFormat](../fillformat/) tulajdonságai, vagy örökli a [FillFormat](../fillformat/) tulajdonságokat a szövegtől. Csak olvasható **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](../ibaseportionformateffectivedata/get_ishardunderlineline/)() | Megállapítja, hogy az aláhúzási stílusnak vannak-e saját [LineFormat](../lineformat/) tulajdonságai, vagy örökli a [LineFormat](../lineformat/) tulajdonságokat a szövegtől. Csak olvasható **bool**. |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformateffectivedata/get_kerningminimalsize/)() | Visszaadja a minimális betűméretet, melynél bekapcsolandó a betűköző eltolás. Csak olvasható **float**. |
| virtual **bool** [get_Kumimoji](../ibaseportionformateffectivedata/get_kumimoji/)() | Megállapítja, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelv-specifikus függőleges szövegelrendezést. Csak olvasható **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformateffectivedata/get_languageid/)() | Visszaadja egy nyelv azonosítóját. Csak olvasható [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformateffectivedata/get_latinfont/)() | Visszaadja a latin betűtípus információt. Csak olvasható [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](../ibaseportionformateffectivedata/get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) tulajdonságait a szöveg körvonalazásához. Csak olvasható [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](../ibaseportionformateffectivedata/get_normaliseheight/)() | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Csak olvasható **bool**. |
| virtual **bool** [get_ProofDisabled](../ibaseportionformateffectivedata/get_proofdisabled/)() | Megállapítja, hogy a szöveget ne kell-e lektorálni. Csak olvasható **bool**. |
| virtual **bool** [get_SmartTagClean](../ibaseportionformateffectivedata/get_smarttagclean/)() | Megállapítja, hogy a smart tag-et tisztítani kell-e. Csak olvasható **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformateffectivedata/get_spacing/)() | Visszaadja a karakterek közti távolság növekedését pontban. Csak olvasható **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformateffectivedata/get_strikethroughtype/)() | Visszaadja a szöveg áthúzott típusát. Csak olvasható [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformateffectivedata/get_symbolfont/)() | Visszaadja a szimbolikus betűtípus információt. Csak olvasható [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformateffectivedata/get_textcaptype/)() | Visszaadja a szöveg nagybetűs formájának típusát. Csak olvasható [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](../ibaseportionformateffectivedata/get_underlinefillformat/)() | Visszaadja az aláhúzási vonal [FillFormat](../fillformat/) tulajdonságait. Csak olvasható [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](../ibaseportionformateffectivedata/get_underlinelineformat/)() | Visszaadja a [LineFormat](../lineformat/) tulajdonságait, amely az aláhúzási vonal körvonalazásához használatos. Csak olvasható [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja a értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók konténerekben gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Megjegyzések


Ez az interfész a [IPortionFormat](../iportionformat/) interfésszel együtt használatos a hatékony formázási értékek visszaadásához öröklődés alkalmazásával. 
## Lásd még

* Osztály [IBasePortionFormatEffectiveData](../ibaseportionformateffectivedata/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)