---
title: MathMatrix
second_title: Referencja API Aspose.Slides dla C++
description: Określa obiekt Matrix, składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimitatorów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimitatora (IMathDelimiter). Argumenty null można użyć do tworzenia przerw w macierzach.
type: docs
weight: 950
url: /pl/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix klasa

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object ([IMathDelimiter](../imathdelimiter/)). Null arguments can be used to create gaps in matrices.

```cpp
class MathMatrix : public Aspose::Slides::MathText::MathElementBase,
                   public Aspose::Slides::MathText::IMathMatrix,
                   public Aspose::Slides::MathText::IHasControlCharacterProperties
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | Ustawia znak akcentu (znak na górze tego elementu) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | Przyjmuje określoną funkcję, używając tej instancji jako argumentu |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | Przyjmuje określoną funkcję, używając tej instancji jako argumentu oraz określony dodatkowy argument |
| void [DeleteColumn](./deletecolumn/)(**int32_t**) override | Usuwa określoną kolumnę |
| void [DeleteRow](./deleterow/)(**int32_t**) override | Usuwa określony wiersz |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | Otacza element matematyczny w nawiasach |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | Przyjmuje funkcję argumentu, używając tej instancji jako nazwy funkcji |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | Określa pionowe wyrównanie względem otaczającego tekstu. Możliwe wartości to top, bottom i center. Domyślnie: Center |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Liczba kolumn w macierzy |
| **uint32_t** [get_ColumnGap](./get_columngap/)() override | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako liczba kroków po 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_ColumnGapRule](./get_columngaprule/)() override | Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu mogą być em lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |
| **bool** [get_HidePlaceholders](./get_hideplaceholders/)() override | Ukrywa miejsce na puste elementy macierzy. Domyślnie: false |
| **uint32_t** [get_MinColumnWidth](./get_mincolumnwidth/)() override | Minimalna szerokość kolumny w twipach (1/20 punktu). Odstęp (również nazywany \\u201CColumn Gap\\u201D lub \\u201CGap Width\\u201D) jest dodawany do MinColumnWidth, aby określić całkowity odstęp [Column](../../aspose.slides/column/) macierzy (odległość między takimi samymi krawędziami różnych kolumn). Domyślnie: 0. |
| **int32_t** [get_RowCount](./get_rowcount/)() override | Liczba wierszy w macierzy |
| **uint32_t** [get_RowGap](./get_rowgap/)() override | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako pół linii. Domyślnie: 0 |
| [MathSpacingRules](../mathspacingrules/) [get_RowGapRule](./get_rowgaprule/)() override | Typ pionowego odstępu między wierszami macierzy; jednostki odstępu mogą być linie lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | Pobiera elementy potomne |
| [MathHorizontalAlignment](../mathhorizontalalignment/) [GetColumnAlignment](./getcolumnalignment/)(**int32_t**) override | Pobiera poziome wyrównanie określonej kolumny |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | Element macierzy |
| void [idx_set](./idx_set/)(**int32_t**, **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Element macierzy |
| void [InsertColumnAfter](./insertcolumnafter/)(**int32_t**) override | Wstawia nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null. |
| void [InsertColumnBefore](./insertcolumnbefore/)(**int32_t**) override | Wstawia nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null. |
| void [InsertRowAfter](./insertrowafter/)(**int32_t**) override | Wstawia nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| void [InsertRowBefore](./insertrowbefore/)(**int32_t**) override | Wstawia nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | Przyjmuje całkę |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Przyjmuje całkę |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | Przyjmuje całkę bez granic |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | Przyjmuje całkę |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Przyjmuje całkę |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Łączy element matematyczny i tworzy blok matematyczny |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | Łączy tekst matematyczny i tworzy blok matematyczny |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock(). Wywołuj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
|  [MathMatrix](./mathmatrix/)(**int32_t**, **int32_t**) | Inicjalizuje nową instancję klasy [MathMatrix](./). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Tworzy operator N-arny |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Tworzy operator N-arny |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | Ustawia kreskę na górze tego elementu |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Określa pierwiastek matematyczny stopnia podanego z określonego argumentu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | Określa pierwiastek matematyczny stopnia podanego z określonego argumentu. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | Określa pionowe wyrównanie względem otaczającego tekstu. Możliwe wartości to top, bottom i center. Domyślnie: Center |
| void [set_ColumnGap](./set_columngap/)(**uint32_t**) override | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako liczba kroków po 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0 |
| void [set_ColumnGapRule](./set_columngaprule/)([MathSpacingRules](../mathspacingrules/)) override | Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu mogą być em lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |
| void [set_HidePlaceholders](./set_hideplaceholders/)(**bool**) override | Ukrywa miejsce na puste elementy macierzy. Domyślnie: false |
| void [set_MinColumnWidth](./set_mincolumnwidth/)(**uint32_t**) override | Minimalna szerokość kolumny w twipach (1/20 punktu). Odstęp (również nazywany \\u201CColumn Gap\\u201D lub \\u201CGap Width\\u201D) jest dodawany do MinColumnWidth, aby określić całkowity odstęp [Column](../../aspose.slides/column/) macierzy (odległość między takimi samymi krawędziami różnych kolumn). Domyślnie: 0. |
| void [set_RowGap](./set_rowgap/)(**uint32_t**) override | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako pół linii. Domyślnie: 0 |
| void [set_RowGapRule](./set_rowgaprule/)([MathSpacingRules](../mathspacingrules/)) override | Typ pionowego odstępu między wierszami macierzy; jednostki odstępu mogą być linie lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0) |
| void [SetColumnAlignment](./setcolumnalignment/)(**int32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | Ustawia poziome wyrównanie określonej kolumny |
| void [SetColumnsAlignment](./setcolumnsalignment/)(**int32_t**, **uint32_t**, [MathHorizontalAlignment](../mathhorizontalalignment/)) override | Ustawia poziome wyrównanie określonych kolumn |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Przyjmuje dolny limit |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | Przyjmuje dolny limit |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Tworzy indeks dolny |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | Tworzy indeks dolny |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Tworzy indeks dolny i górny po lewej |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Tworzy indeks dolny i górny po lewej |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Tworzy indeks dolny i górny po prawej |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Tworzy indeks dolny i górny po prawej |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Tworzy indeks górny |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | Tworzy indeks górny |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Przyjmuje górny limit |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | Przyjmuje górny limit |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | Umieszcza ten element w ramce |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | Umieszcza ten element w ramce |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | Umieszcza ten element w nie-wizualnym polu (grupowaniu logicznym), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Obiekt w polu może (na przykład) służyć jako emulator operatora z lub bez punktu wyrównania, służyć jako punkt podziału wiersza lub być grupowany tak, aby nie dopuszczać do podziału wierszy wewnątrz. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | Umieszcza w pionowej tablicy |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | Ustawia kreskę na dole tego elementu |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie C# lock(). Wywołuj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwolnia wszystkie wewnętrzne struktury danych. |

## Uwagi

Przykład: 
```cpp
System::SharedPtr<IMathMatrix> matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Zobacz także

* Klasa [MathElementBase](../mathelementbase/)
* Klasa [IMathMatrix](../imathmatrix/)
* Klasa [IHasControlCharacterProperties](../ihascontrolcharacterproperties/)
* Przestrzeń nazw [Aspose::Slides::MathText](../)
* Biblioteka [Aspose.Slides](../../)