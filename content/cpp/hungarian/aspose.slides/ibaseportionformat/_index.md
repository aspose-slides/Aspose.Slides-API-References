---
title: IBasePortionFormat
second_title: Aspose.Slides C++ API Referenciája
description: Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. Az IPortionFormatEffectiveData-től eltérően ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 1457
url: /hu/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat osztály


Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. A [IPortionFormatEffectiveData](../iportionformateffectivedata/)-tól eltérően ennek az osztálynak az összes tulajdonsága írható.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Visszaadja egy alternatív nyelv azonosítóját. Olvasd [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Visszaadja a komplex szkript betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Visszaadja az kelet-ázsiai betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Visszaadja a szöveg [EffectFormat](../effectformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Visszaadja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Olvasd **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Visszaadja a szöveg [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Visszaadja egy részlet betűmagasságát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs meghatározva, és a Masterből kell öröklődni. Olvasd **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Visszaadja a szöveg aláhúzás típusát. Nincs öröklődés. Olvasd [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasható [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Megállapítja, hogy az aláhúzási stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e vagy a szöveg [FillFormat](../fillformat/) tulajdonságaiból örököl. Olvasd [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Megállapítja, hogy az aláhúzási stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e vagy a szöveg [LineFormat](../lineformat/) tulajdonságaiból örököl. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Visszaadja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Olvasd **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvspecifikus függőleges elrendezését. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Visszaadja egy helyesírási nyelv azonosítóját. Helyesírás és nyelvtan ellenőrzésére használatos. Olvasd [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Visszaadja a latin betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) tulajdonságokat a szöveg körvonalazásához. Nincs öröklődés. Csak olvasható [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Megállapítja, hogy a szöveg ne legyen helyesírás ellenőrzés alatt. Nincs öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Visszaadja a karakterek közötti távolság növekményét. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Olvasd **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Lekér egy értéket, amely jelzi, hogy a szövegrész helyesírási ellenőrzése engedélyezett-e. Ha ez a tulajdonság false, a helyesírás-ellenőrzés elnyomásra kerül. Ha true, engedélyezett. Alapértelmezett érték **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Visszaadja a szöveg áthúzott típusát. Nincs öröklődés. Olvasd [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Visszaadja a szimbolikus betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasd [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Visszaadja a szöveg nagybetűs formázásának típusát. Nincs öröklődés. Olvasd [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Visszaadja az aláhúzási vonal [FillFormat](../fillformat/) tulajdonságait. Nincs öröklődés. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Visszaadja a [LineFormat](../lineformat/) tulajdonságokat, amelyek az aláhúzási vonal körvonalazásához használatosak. Nincs öröklődés. Csak olvasható [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-ét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Tulajdonképpen semmit nem másol, csak újat inicializál, és lehetővé teszi az alosztályok másolós konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadás-operátor. Tulajdonképpen semmit nem másol, csak újat inicializál, és lehetővé teszi az alosztályok másolós konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Beállítja egy alternatív nyelv azonosítóját. Írja [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a komplex szkript betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a kelet-ázsiai betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Beállítja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Írja **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Beállítja, hogy a betűtípus félkövér legyen-e. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Beállítja a részlet betűmagasságát. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy a magasság nincs meghatározva, és a Masterből kell öröklődni. Írja **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Beállítja, hogy a betűtípus dőlt legyen-e. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Beállítja a szöveg aláhúzás típusát. Nincs öröklődés. Írja [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Megállapítja, hogy az aláhúzási stílus saját [FillFormat](../fillformat/) tulajdonságokkal rendelkezik-e vagy a szöveg [FillFormat](../fillformat/) tulajdonságaiból örököl. Írja [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Megállapítja, hogy az aláhúzási stílus saját [LineFormat](../lineformat/) tulajdonságokkal rendelkezik-e vagy a szöveg [LineFormat](../lineformat/) tulajdonságaiból örököl. Írja [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Írja **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvspecifikus függőleges elrendezését. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Beállítja egy helyesírási nyelv azonosítóját. Helyesírás és nyelvtan ellenőrzésére használatos. Írja [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a latin betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a szöveg ne legyen helyesírási ellenőrzés alatt. Nincs öröklődés. Írja [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Beállítja a karakterek közötti távolság növekményét. **std::numeric_limits<float>::quiet_NaN()** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Írja **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Beállít egy értéket, amely jelzi, hogy a szövegrész helyesírási ellenőrzése engedélyezett-e. Ha ez a tulajdonság false, a helyesírás-ellenőrzés elnyomásra kerül. Ha true, engedélyezett. Alapértelmezett érték **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Beállítja a szöveg áthúzott típusát. Nincs öröklődés. Írja [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a szimbolikus betűtípus információkat. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Írja [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Beállítja a szöveg nagybetűs formázásának típusát. Nincs öröklődés. Írja [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként állítja be (nem megosztott). Lehetővé teszi a mutatók konténerben való gyenge módra történő átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok karakterlánccá alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések


Ez az osztály a konkrét részlethez definiált szövegrész formázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy értéklekéréskor nincs öröklődés, ezért a legtöbb esetben „nem definiált” értékeket kapunk.

A hatékony formázási paraméterértékek, beleértve az örökölteket, lekéréséhez a [IPortionFormat::GetEffective](../iportionformat/geteffective/) metódust kell használni, amely egy [IPortionFormatEffectiveData](../iportionformateffectivedata/) példányt ad vissza.

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)