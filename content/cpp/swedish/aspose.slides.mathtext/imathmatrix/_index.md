---
title: IMathMatrix
second_title: Aspose.Slides för C++ API-referens
description: Specificerar Matrix-objektet, bestående av underordnade element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsningsobjektet (IMathDelimiter). Nollargument kan användas för att skapa luckor i matriser.
type: docs
weight: 391
url: /sv/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix klass

Specificerar Matrix-objektet, bestående av underordnade element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsningsobjektet ([IMathDelimiter](../imathdelimiter/)). Nollargument kan användas för att skapa luckor i matriser.

```cpp
class IMathMatrix : public virtual Aspose::Slides::MathText::IMathElement
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../imathelement/accent/)(char16_t) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Tar angiven funktion med denna instans som argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([System::String](../../system/string/)) | Tar angiven funktion med denna instans som argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | Tar angiven funktion med denna instans som argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Tar angiven funktion med denna instans som argument och angivet ytterligare argument |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../imathelement/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | Tar angiven funktion med denna instans som argument och angivet ytterligare argument |
| virtual void [DeleteColumn](./deletecolumn/)(**int32_t**) | Tar bort den angivna kolumnen |
| virtual void [DeleteRow](./deleterow/)(**int32_t**) | Tar bort den angivna raden |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Skapar ett bråk med detta täljare och angivet nämnare |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/)) | Skapar ett bråk med detta täljare och angivet nämnare |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) | Skapar ett bråk av den angivna typen med detta täljare och angivet nämnare |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../imathelement/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | Skapar ett bråk av den angivna typen med detta täljare och angivet nämnare |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)() | Innesluter ett matematiskt element i parentes |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../imathelement/enclose/)(char16_t, char16_t) | Innesluter detta element i angivna tecken såsom parentes eller andra tecken som ram |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN anses lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../imathelement/function/)([System::String](../../system/string/)) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| virtual [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() | Specificerar den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Antal kolumner i matrisen |
| virtual **uint32_t** [get_ColumnGap](./get_columngap/)() | Värdet för horisontellt avstånd mellan matrisens kolumner; om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antalet 0,5 em-ökningar. I andra fall ignoreras. Standard: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() | Typen av horisontellt avstånd mellan matrisens kolumner; enheter för horisontellt avstånd kan vara ems eller points (lagrade som twips). Standard: SingleSpacingGap (0) |
| virtual **bool** [get_HidePlaceholders](./get_hideplaceholders/)() | Dölj platshållarna för tomma matris-element Standard: false |
| virtual **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() | Minsta kolumnbredd i twips (1/20 av en punkt) Avståndet mellan kolumner (även kallat \\u201CColumn Gap\\u201D eller \\u201CGap Width\\u201D) läggs till MinColumnWidth för att bestämma den totala matrismellanrummet [Column](../../aspose.slides/column/) (avståndet mellan samma kanter på olika kolumner). Standard: 0. |
| virtual **int32_t** [get_RowCount](./get_rowcount/)() | Antal rader i matrisen |
| virtual **uint32_t** [get_RowGap](./get_rowgap/)() | Värdet för vertikalt avstånd mellan matrisens rader; om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halvlänkar. Standard: 0 |
| virtual [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() | Typen av vertikalt avstånd mellan matrisens rader; vertikala avståndsenheter kan vara lines eller points (lagrade som twips). Standard: SingleSpacingGap (0) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](../imathelement/getchildren/)() | Hämta barn-element |
| virtual [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) | Hämta horisontell justering för den angivna kolumnen |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av egna objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)() | Placera detta element i en grupp med en nedre klammerparentes |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../imathelement/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | Placera detta element i en grupp med ett grupperingstecken såsom nedre klammerparentes eller annat |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Element i matris |
| virtual void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Element i matris |
| virtual void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) | Infoga en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null. |
| virtual void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) | Infoga en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null. |
| virtual void [InsertRowAfter](./insertrowafter/)(**int32_t**) | Infoga en ny rad efter den angivna. Initialt är alla element i den nya raden null. |
| virtual void [InsertRowBefore](./insertrowbefore/)(**int32_t**) | Infoga en ny rad före den angivna. Initialt är alla element i den nya raden null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) | Tar integral |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Tar integral |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/)) | Tar integral utan gränser |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | Tar integral |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../imathelement/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Tar integral |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../imathelement/join/)([System::String](../../system/string/)) | Sammanfogar en matematisk text och bildar ett matematiskt block |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats för låsning. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av egna typer. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Skapar en N-är operator |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../imathelement/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Skapar en N-är operator |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../imathelement/overbar/)() | Sätter ett streck över detta element |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Specificerar den matematiska roten av given grad från det angivna argumentet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../imathelement/radical/)([System::String](../../system/string/)) | Specificerar den matematiska roten av given grad från det angivna argumentet. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med det angivna värdet. |
| virtual void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) | Specificerar den vertikala justeringen i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center |
| virtual void [set_ColumnGap](./set_columngap/)(**uint32_t**) | Värdet för horisontellt avstånd mellan matrisens kolumner; om ColumnGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 (\"Multiple\"), tolkas enheten som antalet 0,5 em-ökningar. I andra fall ignoreras. Standard: 0 |
| virtual void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) | Typen av horisontellt avstånd mellan matrisens kolumner; enheter för horisontellt avstånd kan vara ems eller points (lagrade som twips). Standard: SingleSpacingGap (0) |
| virtual void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) | Dölj platshållarna för tomma matris-element Standard: false |
| virtual void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) | Minsta kolumnbredd i twips (1/20 av en punkt) Avståndet mellan kolumner (även kallat \\u201CColumn Gap\\u201D eller \\u201CGap Width\\u201D) läggs till MinColumnWidth för att bestämma den totala matrismellanrummet [Column](../../aspose.slides/column/) (avståndet mellan samma kanter på olika kolumner). Standard: 0. |
| virtual void [set_RowGap](./set_rowgap/)(**uint32_t**) | Värdet för vertikalt avstånd mellan matrisens rader; om RowGapRule är satt till 3 (\"Exactly\"), tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 (\"Multiple\"), tolkas enheten som halvlänkar. Standard: 0 |
| virtual void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) | Typen av vertikalt avstånd mellan matrisens rader; vertikala avståndsenheter kan vara lines eller points (lagrade som twips). Standard: SingleSpacingGap (0) |
| virtual void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | Ställ in horisontell justering för den angivna kolumnen |
| virtual void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) | Ställ in horisontell justering för de angivna kolumnerna |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Tar lägre gräns |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../imathelement/setlowerlimit/)([System::String](../../system/string/)) | Tar lägre gräns |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Skapar ett nedsänkt index |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../imathelement/setsubscript/)([System::String](../../system/string/)) | Skapar ett nedsänkt index |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Skapar nedsänkt och upphöjt index till vänster |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../imathelement/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | Skapar nedsänkt och upphöjt index till vänster |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Skapar nedsänkt och upphöjt index till höger |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../imathelement/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | Skapar nedsänkt och upphöjt index till höger |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Skapar upphöjt index |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../imathelement/setsuperscript/)([System::String](../../system/string/)) | Skapar upphöjt index |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Tar övre gräns |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../imathelement/setupperlimit/)([System::String](../../system/string/)) | Tar övre gräns |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)() | Placera detta element i en kantbox |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../imathelement/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | Placera detta element i en kantbox |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../imathelement/tobox/)() | Placera detta element i en icke-visuell box (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. En inramad objekt kan (till exempel) fungera som en operator-emulator med eller utan justeringspunkt, fungera som en radbrytning, eller grupperas så att radbrytningar inom den inte tillåts. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../imathelement/tomatharray/)() | Sätter i en vertikal matris |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av egna objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../imathelement/underbar/)() | Sätter ett streck under detta element |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats för upplåsning. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar

Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Se också

* Klass [IMathElement](../imathelement/)
* Namnrymd [Aspose::Slides::MathText](../)
* Bibliotek [Aspose.Slides](../../)