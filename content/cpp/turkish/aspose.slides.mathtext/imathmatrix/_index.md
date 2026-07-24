---
title: IMathMatrix
second_title: Aspose.Slides for C++ API Referansı
description: Matris nesnesini belirtir; alt öğeler bir veya daha fazla satır ve sütunda düzenlenir. Matrislerin yerleşik sınırlayıcıları olmadığını not etmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için sınırlayıcı nesnesini (IMathDelimiter) kullanmalısınız. Null argümanlar, matrislerde boşluk oluşturmak için kullanılabilir.
type: docs
weight: 391
url: /tr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix sınıf

Matris nesnesini belirtir; alt öğeler bir veya daha fazla satır ve sütunda düzenlenir. Matrislerin yerleşik sınırlayıcıları olmadığını not etmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için sınırlayıcı nesnesini ([IMathDelimiter](../imathdelimiter/)) kullanmalısınız. Null argümanlar, matrislerde boşluk oluşturmak için kullanılabilir.

```cpp
class IMathMatrix : public virtual Aspose::Slides::MathText::IMathElement
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | Bu öğenin üstüne bir aksan işareti (öğenin üstündeki bir karakter) ayarlar |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Bu örnek argüman olarak kullanılarak belirtilen işlevi alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | Bu örnek argüman olarak kullanılarak belirtilen işlevi alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | Bu örnek argüman olarak kullanılarak belirtilen işlevi alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Bu örnek argüman olarak kullanarak belirtilen işlevi ve belirtilen ek argümanı alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | Bu örnek argüman olarak kullanarak belirtilen işlevi ve belirtilen ek argümanı alır |
| virtual void [DeleteColumn](./deletecolumn/)(**int32_t**) | Belirtilen sütunu siler |
| virtual void [DeleteRow](./deleterow/)(**int32_t**) | Belirtilen satırı siler |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | Bu payı ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | Bu payı ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | Matematik öğesini parantez içine alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | Bu öğeyi parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeveleyerek kapsar |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri IEC 60559:1989'a göre hiçbir değere eşit olmamasına rağmen eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri IEC 60559:1989'a göre hiçbir değere eşit olmamasına rağmen eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| virtual [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() | Çevre metne göre dikey hizalamayı belirler. Olası değerler üst, alt ve orta. Varsayılan: Orta |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Matrisin sütun sayısı |
| virtual **uint32_t** [get_ColumnGap](./get_columngap/)() | Matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") olarak ayarlanmışsa birim twip (noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlanmışsa birim 0,5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yoksayılır. Varsayılan: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() | Matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em ya da puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0) |
| virtual **bool** [get_HidePlaceholders](./get_hideplaceholders/)() | Boş matris öğeleri için yer tutucuları gizler. Varsayılan: false |
| virtual **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() | Twip cinsinden minimum sütun genişliği (noktanın 1/20'i). Boşluk (\"Column Gap\" ya da \"Gap Width\" olarak da adlandırılır) Minimum Sütun Genişliğine eklenerek toplam Matris [Column](../../aspose.slides/column/) Boşluğu (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0. |
| virtual **int32_t** [get_RowCount](./get_rowcount/)() | Matrisin satır sayısı |
| virtual **uint32_t** [get_RowGap](./get_rowgap/)() | Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") ise birim twip (noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") ise birim yarım satır olarak yorumlanır. Diğer durumlarda yoksayılır. Varsayılan: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() | Matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır ya da puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | Alt öğeleri alır |
| virtual [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) | Belirtilen sütunun yatay hizalamasını alır |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | Bu öğeyi alt köşeli parantez kullanarak bir gruba yerleştirir |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | Bu öğeyi alt köşeli parantez gibi bir grup karakteri kullanarak bir gruba yerleştirir |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Matris öğeleri |
| virtual void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Matris öğeleri |
| virtual void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) | Belirtilen sütunun ardından yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null'dur. |
| virtual void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) | Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null'dur. |
| virtual void [InsertRowAfter](./insertrowafter/)(**int32_t**) | Belirtilen satırın ardından yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null'dur. |
| virtual void [InsertRowBefore](./insertrowbefore/)(**int32_t**) | Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null'dur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | İntegrali alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | İntegrali alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | Sınırsız integral alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | İntegrali alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | İntegrali alır |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Matematiksel bir öğeyi birleştirir ve bir blok oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | Matematiksel bir öğeyi birleştirir ve bir blok oluşturur |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme özelliğini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin kopyalanmasını sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | N-arlı bir operatör oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | N-arlı bir operatör oluşturur |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | Bu öğenin üstüne bir çubuk (bar) ekler |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans açısından karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirilmiş hâli. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmiş hâli. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) | Çevre metne göre dikey hizalamayı belirler. Olası değerler üst, alt ve orta. Varsayılan: Orta |
| virtual void [set_ColumnGap](./set_columngap/)(**uint32_t**) | Matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") olarak ayarlanmışsa birim twip (noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlanmışsa birim 0,5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yoksayılır. Varsayılan: 0 |
| virtual void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) | Matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em ya da puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0) |
| virtual void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) | Boş matris öğeleri için yer tutucuları gizler. Varsayılan: false |
| virtual void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) | Twip cinsinden minimum sütun genişliği (noktanın 1/20'i). Boşluk (\"Column Gap\" ya da \"Gap Width\" olarak da adlandırılır) Minimum Sütun Genişliğine eklenerek toplam Matris [Column](../../aspose.slides/column/) Boşluğu (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0. |
| virtual void [set_RowGap](./set_rowgap/)(**uint32_t**) | Matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") ise birim twip (noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") ise birim yarım satır olarak yorumlanır. Diğer durumlarda yoksayılır. Varsayılan: 0 |
| virtual void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) | Matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır ya da puan (twip olarak saklanır) olabilir. Varsayılan: SingleSpacingGap (0) |
| virtual void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | Belirtilen sütunun yatay hizalamasını ayarlar |
| virtual void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | Belirtilen sütunların yatay hizalamasını ayarlar |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Alt sınırı alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | Alt sınırı alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Alt simge (subscript) oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | Alt simge (subscript) oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Sol tarafta alt ve üst simge oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | Sol tarafta alt ve üst simge oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Sağ tarafta alt ve üst simge oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | Sağ tarafta alt ve üst simge oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Üst simge (superscript) oluşturur |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | Üst simge (superscript) oluşturur |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Üst sınırı alır |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | Üst sınırı alır |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | Bu öğeyi, bir denklemin veya diğer matematiksel metin örneklerinin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal grup) yerleştirir. Kutulu bir nesne, örneğin, hizalama noktasıyla ya da olmadan bir operatör öykünücüsü, satır sonu noktası olarak hizmet edebilir veya satır sonu izin verilmeyecek şekilde gruplanabilir. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | Dikey bir diziye yerleştirir |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | Bu öğenin altına bir çubuk ekler |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar


Örnek: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Diğer Bağlantılar

* Sınıf [IMathElement](../imathelement/)
* Ad alanı [Aspose::Slides::MathText](../)
* Kütüphane [Aspose.Slides](../../)