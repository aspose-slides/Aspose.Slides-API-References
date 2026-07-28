---
title: IMathMatrix
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a Matrix objektumot, amely gyermekelemeket tartalmaz, egy vagy több sorban és oszlopban elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrixot a zárójelekbe kell helyezni a határoló objektummal (IMathDelimiter). Null argumentumok használhatók a mátrixokban hézagok létrehozására.
type: docs
weight: 391
url: /hu/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix osztály


Meghatározza a Matrix objektumot, amely gyermekelemeket tartalmaz, egy vagy több sorban és oszlopban elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrixot a zárójelekbe helyezni a határoló objektummal ([IMathDelimiter](../imathdelimiter/)) kell. Null argumentumok használhatók a mátrixokban hézagok létrehozására.

```cpp
class IMathMatrix : public virtual Aspose::Slides::MathText::IMathElement
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | Beállít egy ékezetjel (a karakter az elem tetején) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Megkapja a megadott függvényt, amely ezt a példányt argumentumként használja |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | Megkapja a megadott függvényt, amely ezt a példányt argumentumként használja |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | Megkapja a megadott függvényt, amely ezt a példányt argumentumként használja |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Megkapja a megadott függvényt, amely ezt a példányt argumentumként használja, valamint a megadott további argumentumot |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | Megkapja a megadott függvényt, amely ezt a példányt argumentumként használja, valamint a megadott további argumentumot |
| virtual void [DeleteColumn](./deletecolumn/)(**int32_t**) | Törli a megadott oszlopot |
| virtual void [DeleteRow](./deleterow/)(**int32_t**) | Törli a megadott sort |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | Zárja a matematikai elemet zárójelek közé |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | Az elemet a megadott karakterekkel (pl. zárójelek vagy más keretező karakterek) körülveszi |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az érték típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Megkap egy argumentumfüggvényt, amely ezt a példányt használja függvénynévként |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | Megkap egy argumentumfüggvényt, amely ezt a példányt használja függvénynévként |
| virtual [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() | Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, és center. Alapértelmezett: Center |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | A mátrix oszlopainak száma |
| virtual **uint32_t** [get_ColumnGap](./get_columngap/)() | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik. Ha a ColumnGapRule 4-re (\"Multiple\") van állítva, akkor az egység 0,5 em lépés számaként értelmeződik. Más esetben figyelmen kívül hagyott. Alapértelmezett: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egysége lehet em vagy pont (twipként tárolva). Alapértelmezett: SingleSpacingGap (0) |
| virtual **bool** [get_HidePlaceholders](./get_hideplaceholders/)() | Elrejti az üres mátrixelemek helyőrzőit. Alapértelmezett: false |
| virtual **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() | A minimum oszlopszélesség twipben (1/20 pont). A hézag (amelyet \\u201CColumn Gap\\u201D vagy \\u201CGap Width\\u201D néven is ismernek) hozzáadódik a MinColumnWidth-hez a teljes [Column](../../aspose.slides/column/) távolság meghatározásához (a különböző oszlopok azonos élei közötti távolság). Alapértelmezett: 0. |
| virtual **int32_t** [get_RowCount](./get_rowcount/)() | A mátrix sorainak száma |
| virtual **uint32_t** [get_RowGap](./get_rowgap/)() | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik. Ha a RowGapRule 4-re (\"Multiple\") van állítva, akkor az egység fél sorként értelmeződik. Alapértelmezett: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egysége lehet sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | Gyermekelemek lekérése |
| virtual [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) | A megadott oszlop vízszintes igazításának lekérése |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | Az elemet egy keretdobozba helyezi |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | Az elemet egy csoportba helyezi egy csoportosító karakter használatával, például egy alsó kapcsos zárójel vagy más |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Mátrix elemei |
| virtual void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Mátrix elemei |
| virtual void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) | Új oszlop beszúrása a megadott után. Kezdetben az új oszlop összes eleme null. |
| virtual void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) | Új oszlop beszúrása a megadott előtt. Kezdetben az új oszlop összes eleme null. |
| virtual void [InsertRowAfter](./insertrowafter/)(**int32_t**) | Új sor beszúrása a megadott után. Kezdetben az új sor összes eleme null. |
| virtual void [InsertRowBefore](./insertrowbefore/)(**int32_t**) | Új sor beszúrása a megadott előtt. Kezdetben az új sor összes eleme null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | Integrált vesz |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Integrált vesz |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | Integrált vesz határok nélkül |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | Integrált vesz |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Integrált vesz |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Létrehoz egy N-áris operátort |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Létrehoz egy N-áris operátort |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolását. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | A elem tetejére vonalat helyez |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Megadja a megadott argumentum adott fokú matematikai gyökerét. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | Megadja a megadott argumentum adott fokú matematikai gyökerét. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) | Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, és center. Alapértelmezett: Center |
| virtual void [set_ColumnGap](./set_columngap/)(**uint32_t**) | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik. Ha a ColumnGapRule 4-re (\"Multiple\") van állítva, akkor az egység 0,5 em lépés számaként értelmeződik. Más esetben figyelmen kívül hagyott. Alapértelmezett: 0 |
| virtual void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egysége lehet em vagy pont (twipként tárolva). Alapértelmezett: SingleSpacingGap (0) |
| virtual void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) | Elrejti az üres mátrixelemek helyőrzőit. Alapértelmezett: false |
| virtual void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) | A minimum oszlopszélesség twipben (1/20 pont). A hézag (amelyet \\u201CColumn Gap\\u201D vagy \\u201CGap Width\\u201D néven is ismernek) hozzáadódik a MinColumnWidth-hez a teljes [Column](../../aspose.slides/column/) távolság meghatározásához (a különböző oszlopok azonos élei közötti távolság). Alapértelmezett: 0. |
| virtual void [set_RowGap](./set_rowgap/)(**uint32_t**) | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik. Ha a RowGapRule 4-re (\"Multiple\") van állítva, akkor az egység fél sorként értelmeződik. Alapértelmezett: 0 |
| virtual void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egysége lehet sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0) |
| virtual void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | A megadott oszlop vízszintes igazításának beállítása |
| virtual void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | A megadott oszlopok vízszintes igazításának beállítása |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Alsó határt vesz |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | Alsó határt vesz |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Alsó indexet hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | Alsó indexet hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Bal oldali alsó és felső indexet hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | Bal oldali alsó és felső indexet hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Jobb oldali alsó és felső indexet hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | Jobb oldali alsó és felső indexet hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Felső indexet hoz létre |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | Felső indexet hoz létre |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Felső határt vesz |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | Felső határt vesz |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | Az elemet egy keretdobozba helyezi |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | Az elemet egy keretdobozba helyezi |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. Egy dobozba helyezett objektum például operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, sortörés helyeként funkcionálhat, vagy úgy csoportosítható, hogy ne engedje meg a sorok törését. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | Függőleges tömbbe helyezi |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | A elem aljára vonalat helyez |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítást feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések


Példa:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Lásd még

* Osztály [IMathElement](../imathelement/)
* Névtér [Aspose::Slides::MathText](../)
* Könyvtár [Aspose.Slides](../../)