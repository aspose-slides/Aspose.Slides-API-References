---
title: BasePortionFormat
second_title: Aspose.Slides C++ API referencia
description: Közös szövegrész formázási tulajdonságok.
type: docs
weight: 144
url: /hu/aspose.slides/baseportionformat/
---
## BasePortionFormat osztály


Közös szövegrész formázási tulajdonságok.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlítja a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Visszaadja egy alternatív nyelv azonosítóját. Olvasd [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Visszaadja a komplex írásrendszer betűtípus információt. A null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Olvasd [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Visszaadja a kelet-ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Olvasd [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Visszaadja a szöveg [EffectFormat](../effectformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Visszaadja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és öröklődni kell a mesterből. Olvasd **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Visszaadja a szöveg [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Visszaadja egy rész betűmagasságát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs definiálva, és öröklődni kell a mesterből. Olvasd **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Visszaadja a szöveg aláhúzás típusát. Nincs öröklődés. Olvasd [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Visszaadja a szöveg kiemelésére használt színt. Nincs öröklődés. Csak olvasható [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Megállapítja, hogy az aláhúzás stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e, vagy örökli a [FillFormat](../fillformat/) tulajdonságát a szövegtől. Olvasd [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Megállapítja, hogy az aláhúzás stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e, vagy örökli a [LineFormat](../lineformat/) tulajdonságát a szövegtől. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Visszaadja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és öröklődni kell a mesterből. Olvasd **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Visszaadja egy ellenőrző nyelv azonosítóját. A helyesírás és nyelvtan ellenőrzéséhez használják. Olvasd [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Visszaadja a latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Olvasd [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Visszaadja a [LineFormat](../lineformat/) tulajdonságait a szöveg körvonalazásához. Nincs öröklődés. Csak olvasható [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Megállapítja, hogy a szöveg magassága normalizálni kell-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasható [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/) objektumot. Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Megállapítja, hogy a szöveg ne legyen ellenőrizve. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Visszaadja a karakterek közti távolság növekedését. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és öröklődni kell a mesterből. Olvasd **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Lekérdezi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság hamis, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha igaz, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték a **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Visszaadja a szöveg áthúzás típusát. Nincs öröklődés. Olvasd [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Visszaadja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Olvasd [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Visszaadja a szöveg nagybetűs formázásának típusát. Nincs öröklődés. Olvasd [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Visszaadja az aláhúzott vonal [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Visszaadja a [LineFormat](../lineformat/) tulajdonságait, amelyek az aláhúzott vonal körvonalazásához használatosak. Nincs öröklődés. Csak olvasható [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) védőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referencia alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referencia alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján összehasonlítja az érték típusú objektumot a nullptr-nel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Beállítja egy alternatív nyelv azonosítóját. Írj [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a komplex írásrendszer betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Írj [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a kelet-ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Írj [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Beállítja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és öröklődni kell a mesterből. Írj **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Beállítja egy rész betűmagasságát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs definiálva, és öröklődni kell a mesterből. Írj **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Beállítja a szöveg aláhúzás típusát. Nincs öröklődés. Írj [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy az aláhúzás stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e, vagy örökli a [FillFormat](../fillformat/) tulajdonságát a szövegtől. Írj [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy az aláhúzás stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e, vagy örökli a [LineFormat](../lineformat/) tulajdonságát a szövegtől. Írj [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és öröklődni kell a mesterből. Írj **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. Nincs öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Beállítja egy ellenőrző nyelv azonosítóját. A helyesírás és nyelvtan ellenőrzéséhez használják. Írj [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Írj [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a szöveg magassága normalizálni kell-e. Nincs öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a szöveg ne legyen ellenőrizve. Nincs öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Beállítja a karakterek közti távolság növekedését. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs definiálva, és öröklődni kell a mesterből. Írj **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Beállít egy értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság hamis, a helyesírás-ellenőrzés el van nyomva. Ha igaz, engedélyezett. Alapértelmezett érték a **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Beállítja a szöveg áthúzás típusát. Nincs öröklődés. Írj [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és öröklődni kell a mesterből. Írj [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Beállítja a szöveg nagybetűs formázásának típusát. Nincs öröklődés. Írj [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) védőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [IBasePortionFormat](../ibaseportionformat/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)