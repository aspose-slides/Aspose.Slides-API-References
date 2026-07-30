---
title: IMathElement
second_title: Aspose.Slides pro C++ API Reference
description: "Základní rozhraní libovolného matematického prvku: zlomek, matematický text, funkce, výraz s více prvky atd."
type: docs
weight: 222
url: /cs/aspose.slides.mathtext/imathelement/
---
## IMathElement třída

Base interface of any mathematical element: fraction, mathmatical text, function, expression with multiple elements etc

```cpp
class IMathElement : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](./accent/)(char16_t) | Nastaví akcent (znak nad tímto prvkem) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Přijme zadanou funkci s touto instancí jako argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([System::String](../../system/string/)) | Přijme zadanou funkci s touto instancí jako argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | Přijme zadanou funkci s touto instancí jako argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::String](../../system/string/)) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [MathFractionTypes](../mathfractiontypes/)) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](./enclose/)() | Obalí matematický prvek závorkami |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](./enclose/)(char16_t, char16_t) | Obalí tento prvek zadanými znaky, jako jsou závorky nebo jiné znaky |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](./function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](./function/)([System::String](../../system/string/)) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>\> [GetChildren](./getchildren/)() | Získá podřízené prvky |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](./group/)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](./group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | Umístí tento prvek do skupiny pomocí znakové skupiny, jako je dolní složená závorka nebo jiný znak |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [MathLimitLocations](../mathlimitlocations/)) | Přijme integrál |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Přijme integrál |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/)) | Přijme integrál bez mezí |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | Přijme integrál |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Přijme integrál |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](./join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](./join/)([System::String](../../system/string/)) | Spojí matematický text a vytvoří matematický blok |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# lock() výrazu. Volat přímo nebo použít objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](./nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Vytvoří N-ární operátor |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](./nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Vytvoří N-ární operátor |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](./overbar/)() | Umístí čáru na horní část tohoto prvku |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](./radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Určuje matematický kořen daného stupně z určeného argumentu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](./radical/)([System::String](../../system/string/)) | Určuje matematický kořen daného stupně z určeného argumentu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených referencí o zadanou hodnotu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](./setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Přijme dolní limit. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](./setlowerlimit/)([System::String](../../system/string/)) | Přijme dolní limit. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](./setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Vytvoří dolní index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](./setsubscript/)([System::String](../../system/string/)) | Vytvoří dolní index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](./setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Vytvoří dolní i horní index vlevo. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](./setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | Vytvoří dolní i horní index vlevo. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](./setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Vytvoří dolní i horní index vpravo. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](./setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | Vytvoří dolní i horní index vpravo. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](./setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Vytvoří horní index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](./setsuperscript/)([System::String](../../system/string/)) | Vytvoří horní index. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](./setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Přijme horní limit. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](./setupperlimit/)([System::String](../../system/string/)) | Přijme horní limit. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počitadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](./toborderbox/)() | Umístí tento prvek do ohraničeného boxu |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](./toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | Umístí tento prvek do ohraničeného boxu |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](./tobox/)() | Umístí tento prvek do neviditelného boxu (logické seskupení), který se používá k seskupení součástí rovnice nebo jiné instance matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s či bez bodu zarovnání, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](./tomatharray/)() | Umístí do svislého pole |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](./underbar/)() | Umístí čáru na spodní část tohoto prvku |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání C# lock() výrazu. Volat přímo nebo použít objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Poznámky

Příklad:
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
```

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides::MathText](../)
* Knihovna [Aspose.Slides](../../)