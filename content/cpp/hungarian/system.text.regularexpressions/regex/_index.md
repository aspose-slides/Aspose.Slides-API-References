---
title: Regex
second_title: Aspose.Slides C++ API Referencia
description: "Reguláris kifejezés, amely C#-szerű szintaxist követ. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr pointerbe, és használja ezt a pointert a függvényeknek argumentumként történő átadásához."
type: docs
weight: 92
url: /hu/system.text.regularexpressions/regex/
---
## Regex osztály

C#-szerű szintaxist követő reguláris kifejezés. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusról a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert a függvényeknek argumentumként történő átadásához.

```cpp
class Regex : public System::Object
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantikájával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | Különleges karaktereket escape-eli, hogy a karakterláncot a minta részeként lehessen használni. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [TimeSpan](../../system/timespan/) [get_MatchTimeout](./get_matchtimeout/)() | A matching időkorlátot adja vissza. |
| [RegexOptions](../regexoptions/) [get_Options](./get_options/)() | A regex opciókat adja vissza. |
| **bool** [get_RightToLeft](./get_righttoleft/)() | Ellenőrzi, hogy a matching jobbról balra történik-e. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz tartozó referencia számláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja. |
| **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, int) | A regexet a karakterláncra illeszti. |
| static **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int) | Ellenőrzi, hogy a karakterlánc illeszkedik-e a mintára. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&) | A regexet a karakterláncra illeszti. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, int, int) | A regexet a karakterláncra illeszti. |
| static [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | Karakterláncot és mintát illeszt össze. |
| [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, int) | Az adott karakterláncban a regex összes egyezését adja vissza ismételt illesztéssel. |
| static [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | A karakterlánc és a minta közötti összes egyezést adja vissza. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípusú objektumot nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
|  [Regex](./regex/)() | Üres reguláris kifejezést hoz létre. |
|  [Regex](./regex/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | Konstruktor. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Konstruktor. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | A regex összes egyezését a karakterláncban a helyettesítő karakterlánccal cseréli. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *) | A regex összes egyezését a karakterláncban a helyettesítő karakterlánccal cseréli. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *, const char_t *) | A regex összes egyezését a karakterláncban a helyettesítő karakterlánccal cseréli. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const char_t *) | A regex összes egyezését a karakterláncban a helyettesítő karakterlánccal cseréli. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | A karakterláncban lévő összes egyezést a delegátum által generált helyettesítő karakterláncokkal cseréli. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int) | A karakterláncban lévő összes egyezést a delegátum által generált helyettesítő karakterláncokkal cseréli. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int, int) | A karakterláncban lévő összes egyezést a delegátum által generált helyettesítő karakterláncokkal cseréli. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, [RegexOptions](../regexoptions/)) | A karakterláncban lévő összes egyezést a delegátum által generált helyettesítő karakterláncokkal cseréli (statikus függvény). |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | A regex összes egyezését a karakterláncban a helyettesítő karakterlánccal cseréli. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) | A karakterláncban lévő részkarakterláncokat cseréli. Nincs megvalósítva. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | A karakterláncban lévő részkarakterláncokat cseréli. Nincs megvalósítva. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | A regex egyezéseit cseréli. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | A regex egyezéseit cseréli. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge pointerre (a shared helyett). Lehetővé teszi a pointerek konténerben való weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referencia számláló jelenlegi értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&) | A karakterláncot a regex egyezései alapján felosztja. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int) | A karakterláncot a regex egyezései alapján felosztja. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int, int) | Az bemeneti karakterláncot legfeljebb a megadott számú alkalommal felosztja egy részkarakterláncok tömbjévé, a [Regex](./) konstruktorban megadott reguláris kifejezéssel meghatározott pozícióknál. A reguláris kifejezés minta keresése a bemeneti karakterlánc egy meghatározott karakterpozíciójától kezdődik. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | A karakterláncot regexp alapján felosztja. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | A karakterláncot regexp alapján felosztja. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A regexet karakterlánccá konvertálja. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| static [String](../../system/string/) [Unescape](./unescape/)(const [String](../../system/string/)\&) | A mintaként használt karakterlánc speciális karaktereit vissza-escape-eli. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | Speciális időkorlát érték a match megszakításának letiltásához időkorlát alapján. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [System::Text::RegularExpressions](../)
* Könyvtár [Aspose.Slides](../../)