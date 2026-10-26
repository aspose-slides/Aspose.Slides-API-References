---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes dla .NET – Dokumentacja API
description: Zawiera klasy do pracy z tekstem matematycznym w prezentacjach Microsoft PowerPoint.
type: docs
weight: 140
url: /pl/aspose.slides.mathtext/
---
Zawiera klasy do pracy z tekstem matematycznym w prezentacjach Microsoft PowerPoint.

## Klasy

| Klasa | Opis |
| --- | --- |
| [BaseScript](./basescript) | Skrypt matematyczny |
| [MathAccent](./mathaccent) | Określa funkcję akcentu, składającą się z bazy i łączącego znaku diakrytycznego Przykład: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Umożliwia tworzenie akcentu matematycznego |
| [MathArray](./matharray) | Określa pionowy układ równań lub dowolnych obiektów matematycznych |
| [MathArrayFactory](./matharrayfactory) | Umożliwia tworzenie macierzy matematycznej |
| [MathBar](./mathbar) | Określa funkcję kreski, składającą się z argumentu bazowego i kreski górnej lub dolnej |
| [MathBarFactory](./mathbarfactory) | Umożliwia tworzenie kreski matematycznej |
| [MathBlock](./mathblock) | Określa wystąpienie tekstu matematycznego, które znajduje się w MathParagraph i zaczyna się w nowej linii. Wszystkie obszary matematyczne, w tym równania, wyrażenia, macierze równań lub wyrażeń oraz formuły, są reprezentowane przez blok matematyczny. |
| [MathBlockFactory](./mathblockfactory) | Umożliwia tworzenie bloku matematycznego |
| [MathBorderBox](./mathborderbox) | Rysuje prostokątną lub inną ramkę wokół IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Umożliwia tworzenie ramki matematycznej |
| [MathBox](./mathbox) | Określa logiczne opakowanie (pakowanie) elementu matematycznego. Na przykład obiekt w ramce może służyć jako emulator operatora z lub bez punktu wyrównania, jako punkt podziału wiersza lub być grupowany tak, aby nie zezwalać na podziały wierszy wewnątrz. Przykładowo operator "==" powinien być opakowany, aby zapobiec podziałom wierszy. |
| [MathBoxFactory](./mathboxfactory) | Umożliwia tworzenie ramki matematycznej |
| [MathDelimiter](./mathdelimiter) | Określa obiekt delimitera, składający się z znaków otwierających i zamykających (np. nawiasy, klamry, nawiasy kwadratowe i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Umożliwia tworzenie delimitera matematycznego |
| [MathElementBase](./mathelementbase) | Klasa bazowa dla IMathElement z implementacją niektórych metod wspólnych dla wszystkich klas pochodnych. Do użytku wewnętrznego. Klasa pochodna musi być IMathElement. |
| [MathematicalText](./mathematicaltext) | Tekst matematyczny |
| [MathematicalTextFactory](./mathematicaltextfactory) | Umożliwia tworzenie elementu MathematicalText |
| [MathFraction](./mathfraction) | Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową. Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka. Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej. |
| [MathFractionFactory](./mathfractionfactory) | Umożliwia tworzenie ułamka matematycznego |
| [MathFunction](./mathfunction) | Określa funkcję argumentu. |
| [MathFunctionFactory](./mathfunctionfactory) | Umożliwia tworzenie funkcji matematycznej |
| [MathGroupingCharacter](./mathgroupingcharacter) | Określa symbol grupujący powyżej lub poniżej wyrażenia, zwykle aby podkreślić zależność między elementami |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Umożliwia tworzenie znaku grupującego w matematyce |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Określa obiekt Sub-Superscript, który składa się z bazy oraz indeksu dolnego i górnego umieszczonych po lewej stronie bazy. |
| [MathLimit](./mathlimit) | Określa obiekt Limit, składający się z tekstu na linii bazowej i zmniejszonego tekstu natychmiast powyżej lub poniżej niego. |
| [MathLimitFactory](./mathlimitfactory) | Umożliwia tworzenie IMathLimit |
| [MathMatrix](./mathmatrix) | Określa obiekt Matrix, składający się z elementów podrzędnych ułożonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimiterów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimitera (IMathDelimiter). Argumenty null mogą być użyte do tworzenia przerw w macierzach. |
| [MathMatrixFactory](./mathmatrixfactory) | Umożliwia tworzenie macierzy matematycznej |
| [MathNaryOperator](./mathnaryoperator) | Określa obiekt N-arny, taki jak sumacja i całka. Składa się z operatora, bazy (lub operandu) oraz opcjonalnych górnych i dolnych limitów. Przykłady operatorów N-arnych: Sumacja, Zbiór, Przecięcie, Całka |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Umożliwia tworzenie IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Akapit matematyczny będący kontenerem dla bloków matematycznych (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Umożliwia tworzenie akapitu matematycznego |
| [MathPhantom](./mathphantom) | Reprezentuje obiekt fantomowy matematyczny (&lt;m:phant&gt;) który wpływa na układ swojego elementu podrzędnego bez konieczności wyświetlania go. Fantom może ukrywać swoją bazową ekspresję, zachowując jej szerokość, wysokość lub głębokość w celu wyrównania formuł lub rezerwacji miejsca. Widoczność i zachowanie geometrii kontrolowane są przez właściwości takie jak Show, ZeroWid, ZeroAsc, ZeroDesc oraz Transp. |
| [MathPortion](./mathportion) | Reprezentuje fragment z kontekstem matematycznym wewnątrz. |
| [MathRadical](./mathradical) | Określa funkcję pierwiastkową, składającą się z bazy i opcjonalnego stopnia. Przykład obiektu pierwiastka to √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Umożliwia tworzenie pierwiastka matematycznego |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Określa obiekt Sub-Superscript, który składa się z bazy oraz indeksu dolnego i górnego umieszczonych po prawej stronie bazy. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Umożliwia tworzenie IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Określa obiekt subskryptu, składający się z bazy i zmniejszonego subskryptu umieszczonego poniżej i po prawej stronie. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Umożliwia tworzenie IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Określa obiekt superscriptu, który składa się z bazy i zmniejszonego superscriptu umieszczonego powyżej i po prawej stronie |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Umożliwia tworzenie IMathSuperscriptElement |

## Interfejsy

| Interfejs | Opis |
| --- | --- |
| [IMathAccent](./imathaccent) | Określa funkcję akcentu, składającą się z bazy i łączącego znaku diakrytycznego Przykład: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Umożliwia tworzenie akcentu matematycznego |
| [IMathArray](./imatharray) | Określa pionowy układ równań lub dowolnych obiektów matematycznych |
| [IMathArrayFactory](./imatharrayfactory) | Umożliwia tworzenie macierzy matematycznej |
| [IMathBar](./imathbar) | Określa funkcję kreski, składającą się z argumentu bazowego i kreski górnej lub dolnej |
| [IMathBarFactory](./imathbarfactory) | Umożliwia tworzenie kreski matematycznej |
| [IMathBlock](./imathblock) | Określa wystąpienie tekstu matematycznego, które znajduje się w MathParagraph i zaczyna się w nowej linii. Wszystkie obszary matematyczne, w tym równania, wyrażenia, macierze równań lub wyrażeń oraz formuły, są reprezentowane przez blok matematyczny. |
| [IMathBlockCollection](./imathblockcollection) | Zbiór bloków matematycznych (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Umożliwia tworzenie bloku matematycznego |
| [IMathBorderBox](./imathborderbox) | Rysuje prostokątną lub inną ramkę wokół IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Umożliwia tworzenie ramki matematycznej |
| [IMathBox](./imathbox) | Określa logiczne opakowanie (pakowanie) elementu matematycznego. Na przykład obiekt w ramce może służyć jako emulator operatora z lub bez punktu wyrównania, jako punkt podziału wiersza lub być grupowany tak, aby nie zezwalać na podziały wierszy wewnątrz. Przykładowo operator "==" powinien być opakowany, aby zapobiec podziałom wierszy. |
| [IMathBoxFactory](./imathboxfactory) | Umożliwia tworzenie ramki matematycznej |
| [IMathDelimiter](./imathdelimiter) | Określa obiekt delimitera, składający się z znaków otwierających i zamykających (np. nawiasy, klamry, nawiasy kwadratowe i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Umożliwia tworzenie delimitera matematycznego |
| [IMathElement](./imathelement) | Podstawowy interfejs dowolnego elementu matematycznego: ułamek, tekst matematyczny, funkcja, wyrażenie z wieloma elementami itp. |
| [IMathElementCollection](./imathelementcollection) | Reprezentuje kolekcję elementów matematycznych (MathElement). |
| [IMathematicalText](./imathematicaltext) | Tekst matematyczny |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Umożliwia tworzenie elementu MathematicalText |
| [IMathFraction](./imathfraction) | Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową. Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka. Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej. |
| [IMathFractionFactory](./imathfractionfactory) | Umożliwia tworzenie ułamka matematycznego |
| [IMathFunction](./imathfunction) | Określa funkcję argumentu. |
| [IMathFunctionFactory](./imathfunctionfactory) | Umożliwia tworzenie funkcji matematycznej |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Określa symbol grupujący powyżej lub poniżej wyrażenia, zwykle aby podkreślić zależność między elementami |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Umożliwia tworzenie znaku grupującego w matematyce |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Określa obiekt Sub-Superscript, który składa się z bazy oraz indeksu dolnego i górnego umieszczonych po lewej stronie bazy. |
| [IMathLimit](./imathlimit) | Określa obiekt Limit, składający się z tekstu na linii bazowej i zmniejszonego tekstu natychmiast powyżej lub poniżej niego. |
| [IMathLimitFactory](./imathlimitfactory) | Umożliwia tworzenie IMathLimit |
| [IMathMatrix](./imathmatrix) | Określa obiekt Matrix, składający się z elementów podrzędnych ułożonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimiterów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimitera (IMathDelimiter). Argumenty null mogą być użyte do tworzenia przerw w macierzach. |
| [IMathMatrixFactory](./imathmatrixfactory) | Umożliwia tworzenie macierzy matematycznej |
| [IMathNaryOperator](./imathnaryoperator) | Określa obiekt N-arny, taki jak sumacja i całka. Składa się z operatora, bazy (lub operandu) oraz opcjonalnych górnych i dolnych limitów. Przykłady operatorów N-arnych: Sumacja, Zbiór, Przecięcie, Całka |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Umożliwia tworzenie IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Określa właściwości IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Akapit matematyczny będący kontenerem dla bloków matematycznych (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Umożliwia tworzenie akapitu matematycznego |
| [IMathPhantom](./imathphantom) | Reprezentuje obiekt fantomowy matematyczny (&lt;m:phant&gt;) który wpływa na układ swojego elementu podrzędnego bez konieczności wyświetlania go. Fantom może ukrywać swoją bazową ekspresję, zachowując jej szerokość, wysokość lub głębokość w celu wyrównania formuł lub rezerwacji miejsca. Widoczność i zachowanie geometrii kontrolowane są przez właściwości takie jak Show, ZeroWid, ZeroAsc, ZeroDesc i Transp. |
| [IMathPortion](./imathportion) | Reprezentuje fragment z kontekstem matematycznym wewnątrz. |
| [IMathRadical](./imathradical) | Określa funkcję pierwiastkową, składającą się z bazy i opcjonalnego stopnia. Przykład obiektu pierwiastka to √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Umożliwia tworzenie pierwiastka matematycznego |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Określa obiekt Sub-Superscript, który składa się z bazy oraz indeksu dolnego i górnego umieszczonych po prawej stronie bazy. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Umożliwia tworzenie IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Określa obiekt subskryptu, składający się z bazy i zmniejszonego subskryptu umieszczonego poniżej i po prawej stronie. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Umożliwia tworzenie IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Określa obiekt superscriptu, który składa się z bazy i zmniejszonego superscriptu umieszczonego powyżej i po prawej stronie |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Umożliwia tworzenie IMathSuperscriptElement |

## Enumeracje

| Enumeracja | Opis |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | Położenie i rozmiar delimiterów względem zawartości operandów |
| [MathFractionTypes](./mathfractiontypes) | Typy ułamków |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Typowe funkcje matematyczne jednego argumentu |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Typowe funkcje matematyczne dwóch argumentów |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Wyrównanie poziome |
| [MathIntegralTypes](./mathintegraltypes) | Typy całek matematycznych |
| [MathJustification](./mathjustification) | Określa justowanie akapitu matematycznego (serii sąsiadujących wystąpień tekstu matematycznego w tym samym akapicie) |
| [MathLimitLocations](./mathlimitlocations) | Położenie limitów (subskrypt/superscript) w operatorach n-arnych. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Typy IMathNaryOperator (z wyłączeniem całek) Dla całek [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Typ odstępu pionowego między kolumnami w macierzy lub tablicy |
| [MathSpacingRules](./mathspacingrules) | Typy przerw (odstępów poziomych) między kolumnami macierzy |
| [MathTopBotPositions](./mathtopbotpositions) | Enumeracja pozycji góra/dół |
| [MathVerticalAlignment](./mathverticalalignment) | Wyrównanie pionowe |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->