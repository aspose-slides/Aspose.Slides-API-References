---
title: StringFormat
second_title: Aspose.Slides C++ API hivatkozás
description: "Átöleli a szöveg elrendezési információkat, a megjelenítés manipulációit és az OpenType funkciókat. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként való átadásához."
type: docs
weight: 313
url: /hu/system.drawing/stringformat/
---
## StringFormat osztály

Tömöríti a szöveg elrendezési információkat, a megjelenítés manipulációit és az OpenType funkciókat. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként való átadásához.

```cpp
class StringFormat : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [Clone](./clone/)() | Visszaadja az aktuális objektum pontos másolatát. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [StringAlignment](../stringalignment/) [get_Alignment](./get_alignment/)() const | Visszaad egy értéket, amely jelzi a karakterlánc vízszintes igazítását. |
| **int32_t** [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Visszaad egy értéket, amely jelzi a nyelvet, amelyet a helyi számjegyek nyugati számjegyekkel való helyettesítésekor használnak. |
| [StringDigitSubstitute](../stringdigitsubstitute/) [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Visszaadja a számjegyhelyettesítés módszerét. |
| [StringFormatFlags](../stringformatflags/) [get_FormatFlags](./get_formatflags/)() const | Visszaad egy bitenkénti kombinációt a StringFormatFlags-ból, amely meghatározza az aktuális objektum által képviselt karakterlánc formátumot. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericDefault](./get_genericdefault/)() | Visszaad egy [StringFormat](./) objektumot, amely egy általános alapértelmezett formátumot képvisel. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericTypographic](./get_generictypographic/)() | Visszaad egy [StringFormat](./) objektumot, amely egy általános tipográfiai formátumot képvisel. |
| [Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/) [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Visszaadja az értéket, amely jelzi, hogyan jelenik meg a gyorsbillentyű előtag. |
| [StringAlignment](../stringalignment/) [get_LineAlignment](./get_linealignment/)() const | Visszaad egy értéket, amely jelzi a karakterlánc függőleges igazítását. |
| [StringTrimming](../stringtrimming/) [get_Trimming](./get_trimming/)() const | Visszaad egy értéket, amely jelzi, hogyan van a karakterlánc levágva. |
| int [GetCharacterRangesCount](./getcharacterrangescount/)() const | Lekéri a [CharacterRange](../characterrange/) tömb méretét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hash-elését. |
| [ArrayPtr](../../system/arrayptr/)\<**float**\> [GetTabStops](./gettabstops/)(**float**\&) const | Visszaadja a tabulátorpozíciókat az aktuális [StringFormat](./) objektumhoz. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum az adott targetType által leírt típus egy példányát képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) megfigyelő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Alignment](./set_alignment/)([StringAlignment](../stringalignment/)) | Beállítja a karakterlánc vízszintes igazítását. |
| void [set_FormatFlags](./set_formatflags/)([StringFormatFlags](../stringformatflags/)) | Beállítja a karakterlánc formátum zászlókat. |
| void [set_HotkeyPrefix](./set_hotkeyprefix/)([Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/)) | Beállítja az értéket, amely meghatározza, hogyan jelenjen meg a gyorsbillentyű előtag. |
| void [set_LineAlignment](./set_linealignment/)([StringAlignment](../stringalignment/)) | Beállítja a karakterlánc függőleges igazítását. |
| void [set_Trimming](./set_trimming/)([StringTrimming](../stringtrimming/)) | Beállít egy értéket, amely meghatározza, hogyan legyen a karakterlánc levágva. |
| void [SetDigitSubstitution](./setdigitsubstitution/)(**int32_t**, [StringDigitSubstitute](../stringdigitsubstitute/)) | Beállítja a számjegyhelyettesítés nyelvét és módszerét. |
| void [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const [ArrayPtr](../../system/arrayptr/)\<[CharacterRange](../characterrange/)\>\&) | Beállít egy [CharacterRange](../characterrange/) objektumokból álló tömböt, amelyek a MeasureCharacterRanges() metódus hívásával mért karaktertartományokat reprezentálják. |
| void [SetTabStops](./settabstops/)(**float**, const [ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Beállítja a tabulátorpozíciókat az aktuális [StringFormat](./) objektumhoz. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett) állítja be. Lehetővé teszi a mutatók konténerekben történő átkapcsolását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [StringFormat](./stringformat/)() | Létrehoz egy új [StringFormat](./) osztálypéldányt. |
|  [StringFormat](./stringformat/)([StringFormatFlags](../stringformatflags/), **int32_t**) | Létrehoz egy új [StringFormat](./) osztálypéldányt a megadott formázási zászlókkal és nyelvvel. |
|  [StringFormat](./stringformat/)(const [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\>\&) | Másoló konstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) megfigyelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)