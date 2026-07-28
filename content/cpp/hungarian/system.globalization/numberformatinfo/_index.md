---
title: NumberFormatInfo
second_title: Aspose.Slides C++ API referencia
description: "Tartalmaz információkat arról, hogyan kell formázni a számokat. A beállító műveletek csak nem csak-olvasható objektumokon engedélyezettek. Az osztály objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum argumentumként történő átadásához a függvényeknek."
type: docs
weight: 248
url: /hu/system.globalization/numberformatinfo/
---
## NumberFormatInfo osztály

Tartalmaz információkat a számok formázásáról. A beállító műveletek csak nem csak-olvasható objektumokon engedélyezettek. Az osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel runtime hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum argumentumként való átadásához a függvényeknek.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Módszerek

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klónozza a formátuminformációt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Lekérdezi a pénznem tizedesjegyeinek számát. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Lekérdezi a pénznem tizedes elválasztóját. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Lekérdezi a pénznem csoportelválasztóját. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Lekérdezi a csoportonkénti pénznem tizedesjegyek számát. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Lekérdezi a pénznem negatív mintáját. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Lekérdezi a pénznem pozitív mintáját. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Lekérdezi a pénznem szimbólumát. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Lekérdezi az aktuális szál kultúrája által meghatározott számformátum-információt. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Lekérdezi azt az értéket, amely meghatározza, hogyan jelenjen meg egy számjegy alakja. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Lekérdezi az invariáns kultúra által meghatározott számformátum-információt. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Ellenőrzi, hogy a formátum csak olvasható-e. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Lekérdezi a Not-a-Number szimbólumot. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Lekérdezi a számjegy szimbólumokat (0-tól 9-ig). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Lekérdezi a negatív végtelen szimbólumot. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Lekérdezi a negatív előjelet. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Lekérdezi a tizedesjegyek számát. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Lekérdezi a tizedes elválasztót. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Lekérdezi a számcsoport elválasztót. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Lekérdezi csoportonkénti számjegyek számát. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Lekérdezi a szám negatív mintáját. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Lekérdezi a százalékértékek tizedesjegyeinek számát. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Lekérdezi a százalékértékek tizedes elválasztóját. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Lekérdezi a százalékértékek csoportelválasztóját. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Lekérdezi a százalékértékcsoportok csoportonkénti számjegyek számát. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Lekérdezi a százalék negatív mintáját. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Lekérdezi a százalék pozitív mintáját. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Lekérdezi a százalék szimbólumot. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Lekérdezi a promille szimbólumot. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Lekérdezi a pozitív végtelen szimbólumot. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Lekérdezi a pozitív előjelet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektumhoz társított referencia számláló adatstruktúrát. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Lekérdezi a specifikus típusú formázót. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Lekérdezi a formátum szolgáltatóhoz társított formázót. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [NumberFormatInfo](./numberformatinfo/)() | Alapértelmezett konstruktor (invariáns [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Lekérdezi a formázó csak olvasható változatát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint összehasonlítja az értéktípusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Beállítja a pénznem tizedesjegyeinek számát. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Beállítja a pénznem tizedes elválasztót. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Beállítja a pénznem csoportelválasztót. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Beállítja a csoportonkénti pénznem tizedesjegyek számát. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Beállítja a pénznem negatív mintáját. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Beállítja a pénznem pozitív mintáját. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Beállítja a pénznem szimbólumát. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Beállít egy értéket, amely meghatározza, hogyan jelenjen meg egy számjegy alakja. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Beállítja a Not-a-Number szimbólumot. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Beállítja a számjegy szimbólumokat (0-tól 9-ig). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Beállítja a negatív végtelen szimbólumot. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Beállítja a negatív előjelet. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Beállítja a tizedesjegyek számát. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Beállítja a tizedes elválasztót. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Beállítja a számcsoport elválasztót. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Beállítja csoportonkénti számjegyek számát. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Beállítja a szám negatív mintáját. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Beállítja a százalékértékek tizedes helyek számát. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Beállítja a százalékértékek tizedes elválasztóját. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Beállítja a százalékértékek csoportelválasztóját. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Beállítja a százalékértékcsoportok csoportonkénti számjegyek számát. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Beállítja a százalék negatív mintáját. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Beállítja a százalék pozitív mintáját. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Beállítja a százalék szimbólumot. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Beállítja a promille szimbólumot. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Beállítja a pozitív végtelen szimbólumot. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Beállítja a pozitív előjelet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben való weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Osztály [IFormatProvider](../../system/iformatprovider/)
* Osztály [ICloneable](../../system/icloneable/)
* Névtér [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)