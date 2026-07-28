---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for C++ API Referencia
description: Megváltoztathatatlan objektum, amely az effektív bekezdésformázási tulajdonságokat tartalmaz.
type: docs
weight: 3160
url: /hu/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData osztály

Megváltoztathatatlan objektum, amely az effektív bekezdésformázási tulajdonságokat tartalmazza.

```cpp
class IParagraphFormatEffectiveData : public virtual System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Visszaadja egy bekezdés szövegigazítását. Csak olvasható [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [get_Bullet](./get_bullet/)() | Visszaadja egy bekezdés felsorolásformátumát. Csak olvasható [IBulletFormatEffectiveData](../ibulletformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Visszaadja egy bekezdés alapértelmezett részformátumát. Csak olvasható [IPortionFormatEffectiveData](../iportionformateffectivedata/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Visszaadja az alapértelmezett tabulálási méretet. Csak olvasható **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Visszaadja egy bekezdés mélységét. Csak olvasható **int16_t**. |
| virtual **bool** [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Megállapítja, hogy a kelet ázsiai sortörést használják-e egy bekezdésben. Csak olvasható **bool**. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Visszaadja egy bekezdés betűtípusigazítását. Csak olvasható [Slides::FontAlignment](../fontalignment/). |
| virtual **bool** [get_HangingPunctuation](./get_hangingpunctuation/)() | Megállapítja, hogy függő írásjelet használnak-e egy bekezdésben. Csak olvasható **bool**. |
| virtual **float** [get_Indent](./get_indent/)() | Visszaadja a bekezdés első sor behúzását/függő behúzást. A függő behúzás negatív értékkel is definiálható. Csak olvasható **float**. |
| virtual **bool** [get_LatinLineBreak](./get_latinlinebreak/)() | Megállapítja, hogy a latin sortörést használják-e egy bekezdésben. Csak olvasható **bool**. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Visszaadja a bal margót egy bekezdésben. Csak olvasható **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Visszaadja a jobb margót egy bekezdésben. Csak olvasható **float**. |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Megállapítja, hogy a jobbról balra írás irányt használják-e egy bekezdésben. Csak olvasható **bool**. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Visszaadja az utolsó sor után maradó térközt egy bekezdésben. Csak olvasható **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Visszaadja az első sor előtt lévő térközt egy bekezdésben. Csak olvasható **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Visszaadja az alapvonalak közti térközt egy bekezdésben. Csak olvasható **float**. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITabEffectiveData](../itabeffectivedata/)\>\> [get_Tabs](./get_tabs/)() | Visszaadja egy bekezdés tabulációit. Csak olvasható [ITabEffectiveData](../itabeffectivedata/)[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyelő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján összehasonlítja az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge pointerre (a megosztott helyett). Lehetővé teszi a pointerek átváltását gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

Ez az interfész a [IParagraphFormat](../iparagraphformat/) interfésszel együtt használatos, hogy visszaadja az öröklődéssel alkalmazott effektív formázási értékeket.

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)