---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides dla C++ – referencja API
description: 
type: docs
weight: 157
url: /pl/aspose.slides.mathtext/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [BaseScript](./basescript/) | Skrypt matematyczny |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) z [Control](../aspose.slides/control/) właściwościami znaków |
| [IMathAccent](./imathaccent/) | Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego. Przykład: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Umożliwia tworzenie akcentu matematycznego |
| [IMathArray](./imatharray/) | Określa pionową tablicę równań lub dowolnych obiektów matematycznych |
| [IMathArrayFactory](./imatharrayfactory/) | Umożliwia tworzenie tablicy matematycznej |
| [IMathBar](./imathbar/) | Określa funkcję kreski, składającą się z argumentu bazowego oraz kreski górnej lub dolnej |
| [IMathBarFactory](./imathbarfactory/) | Umożliwia tworzenie kreski matematycznej |
| [IMathBlock](./imathblock/) | Określa instancję tekstu matematycznego, znajdującą się wewnątrz [MathParagraph](./mathparagraph/) i rozpoczynającą się w osobnym wierszu. Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły są reprezentowane przez blok matematyczny. |
| [IMathBlockCollection](./imathblockcollection/) | Zbiór bloków matematycznych ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Umożliwia tworzenie bloku matematycznego |
| [IMathBorderBox](./imathborderbox/) | Rysuje prostokątną lub inną ramkę wokół [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Umożliwia tworzenie ramki granicznej matematycznej |
| [IMathBox](./imathbox/) | Określa logiczne opakowanie (pakowanie) elementu matematycznego. Na przykład, obiekt w ramce może służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt przełamania linii lub być grupowany w taki sposób, aby nie zezwalał na przełamania linii wewnątrz. Na przykład operator \"==\" powinien być opakowany, aby zapobiec przełamaniu linii. |
| [IMathBoxFactory](./imathboxfactory/) | Umożliwia tworzenie pudełka matematycznego |
| [IMathDelimiter](./imathdelimiter/) | Określa obiekt ogranicznika, składający się z znaków otwierających i zamykających (takich jak nawiasy okrągłe, klamrowe, kwadratowe oraz pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Umożliwia tworzenie ogranicznika matematycznego |
| [IMathElement](./imathelement/) | Podstawowy interfejs dowolnego elementu matematycznego: ułamka, tekstu matematycznego, funkcji, wyrażenia z wieloma elementami itp. |
| [IMathElementCollection](./imathelementcollection/) | Reprezentuje kolekcję elementów matematycznych (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Tekst matematyczny |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Umożliwia tworzenie elementu [MathematicalText](./mathematicaltext/) |
| [IMathFraction](./imathfraction/) | Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową. Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka. Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej. |
| [IMathFractionFactory](./imathfractionfactory/) | Umożliwia tworzenie ułamka matematycznego |
| [IMathFunction](./imathfunction/) | Określa funkcję argumentu. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Umożliwia tworzenie funkcji matematycznej |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Określa symbol grupujący nad lub pod wyrażeniem, zwykle aby podkreślić zależność między elementami |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Umożliwia tworzenie znaku grupowania matematycznego |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Określa obiekt indeks dolny-górny, który składa się z podstawy oraz indeksu dolnego i górnego umieszczonych po lewej stronie podstawy. |
| [IMathLimit](./imathlimit/) | Określa obiekt limitu, składający się z tekstu na linii bazowej oraz zmniejszonego tekstu bezpośrednio powyżej lub poniżej. |
| [IMathLimitFactory](./imathlimitfactory/) | Umożliwia tworzenie [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Określa obiekt macierzy, składający się z elementów potomnych ułożonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika ([IMathDelimiter](./imathdelimiter/)). Argumenty zerowe mogą być użyte do tworzenia przerw w macierzach. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Umożliwia tworzenie macierzy matematycznej |
| [IMathNaryOperator](./imathnaryoperator/) | Określa n-argumentowy obiekt matematyczny, taki jak sumowanie i całka. Składa się z operatora, podstawy (lub argumentu) oraz opcjonalnych limitów górnych i dolnych. Przykłady operatorów n-argumentowych: Sumowanie, Unia, Przecięcie, Całka |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Umożliwia tworzenie [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Określa właściwości [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Akapit matematyczny będący kontenerem dla bloków matematycznych ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Umożliwia tworzenie akapitu matematycznego |
| [IMathPhantom](./imathphantom/) | Reprezentuje fantomowy obiekt matematyczny (<m:phant>), który wpływa na układ swojego elementu potomnego, niekoniecznie go wyświetlając. Fantom może ukrywać wyrażenie bazowe, zachowując jednocześnie jego szerokość, wysokość lub głębokość w celu wyrównania formuł lub zarezerwowania miejsca. Widoczność i zachowanie geometryczne są kontrolowane przez właściwości takie jak Show, ZeroWid, ZeroAsc, ZeroDesc i Transp. |
| [IMathPortion](./imathportion/) | Reprezentuje fragment z kontekstem matematycznym wewnątrz. |
| [IMathRadical](./imathradical/) | Określa funkcję pierwiastkową, składającą się z podstawy i opcjonalnego stopnia. Przykład obiektu pierwiastkowego: \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Umożliwia tworzenie pierwiastka matematycznego |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Określa obiekt indeks dolny-górny, który składa się z podstawy oraz indeksu dolnego i górnego umieszczonych po prawej stronie podstawy. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Umożliwia tworzenie [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Określa obiekt indeksu dolnego, który składa się z podstawy oraz zmniejszonego indeksu dolnego umieszczonego poniżej i po prawej stronie. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Umożliwia tworzenie [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Określa obiekt indeksu górnego, który składa się z podstawy oraz zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Umożliwia tworzenie [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego. Przykład: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Umożliwia tworzenie akcentu matematycznego |
| [MathArray](./matharray/) | Określa pionową tablicę równań lub dowolnych obiektów matematycznych |
| [MathArrayFactory](./matharrayfactory/) | Umożliwia tworzenie tablicy matematycznej |
| [MathBar](./mathbar/) | Określa funkcję kreski, składającą się z argumentu bazowego oraz kreski górnej lub dolnej |
| [MathBarFactory](./mathbarfactory/) | Umożliwia tworzenie kreski matematycznej |
| [MathBlock](./mathblock/) | Określa instancję tekstu matematycznego, znajdującą się w [MathParagraph](./mathparagraph/) i rozpoczynającą się w osobnym wierszu. Wszystkie obszary matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły, są reprezentowane przez blok matematyczny. |
| [MathBlockFactory](./mathblockfactory/) | Umożliwia tworzenie bloku matematycznego |
| [MathBorderBox](./mathborderbox/) | Rysuje prostokątną lub inną ramkę wokół [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Umożliwia tworzenie ramki granicznej matematycznej |
| [MathBox](./mathbox/) | Określa logiczne opakowanie (pakowanie) elementu matematycznego. Na przykład, obiekt w ramce może służyć jako emulator operatora z punktem wyrównania lub bez niego, jako punkt przełamania linii lub być grupowany w taki sposób, aby nie zezwalał na przełamania linii wewnątrz. Na przykład operator \"==\" powinien być opakowany, aby zapobiec przełamaniu linii. |
| [MathBoxFactory](./mathboxfactory/) | Umożliwia tworzenie pudełka matematycznego |
| [MathDelimiter](./mathdelimiter/) | Określa obiekt ogranicznika, składający się z znaków otwierających i zamykających (takich jak nawiasy okrągłe, klamrowe, kwadratowe oraz pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem. Przykłady: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Umożliwia tworzenie ogranicznika matematycznego |
| [MathElementBase](./mathelementbase/) | Klasa bazowa dla [IMathElement](./imathelement/) z implementacją niektórych metod wspólnych dla wszystkich klas dziedziczących. Do użytku wewnętrznego. Klasa dziedzicząca musi być [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Tekst matematyczny |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Umożliwia tworzenie elementu [MathematicalText](./mathematicaltext/) |
| [MathFraction](./mathfraction/) | Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową. Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka. Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej. |
| [MathFractionFactory](./mathfractionfactory/) | Umożliwia tworzenie ułamka matematycznego |
| [MathFunction](./mathfunction/) | Określa funkcję argumentu. |
| [MathFunctionFactory](./mathfunctionfactory/) | Umożliwia tworzenie funkcji matematycznej |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Określa symbol grupujący nad lub pod wyrażeniem, zwykle aby podkreślić zależność między elementami |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Umożliwia tworzenie znaku grupowania matematycznego |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Określa obiekt indeks dolny-górny, który składa się z podstawy oraz indeksu dolnego i górnego umieszczonych po lewej stronie podstawy. |
| [MathLimit](./mathlimit/) | Określa obiekt limitu, składający się z tekstu na linii bazowej oraz zmniejszonego tekstu bezpośrednio powyżej lub poniżej. |
| [MathLimitFactory](./mathlimitfactory/) | Umożliwia tworzenie [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Określa obiekt macierzy, składający się z elementów potomnych ułożonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych ograniczników. Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika ([IMathDelimiter](./imathdelimiter/)). Argumenty zerowe mogą być użyte do tworzenia przerw w macierzach. |
| [MathMatrixFactory](./mathmatrixfactory/) | Umożliwia tworzenie macierzy matematycznej |
| [MathNaryOperator](./mathnaryoperator/) | Określa n-argumentowy obiekt matematyczny, taki jak sumowanie i całka. Składa się z operatora, podstawy (lub argumentu) oraz opcjonalnych limitów górnych i dolnych. Przykłady operatorów n-argumentowych: Sumowanie, Unia, Przecięcie, Całka |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Umożliwia tworzenie [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Akapit matematyczny będący kontenerem dla bloków matematycznych ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Umożliwia tworzenie akapitu matematycznego |
| [MathPhantom](./mathphantom/) | Reprezentuje fantomowy obiekt matematyczny (<m:phant>), który wpływa na układ swojego elementu potomnego, niekoniecznie go wyświetlając. Fantom może ukrywać wyrażenie bazowe, zachowując jednocześnie jego szerokość, wysokość lub głębokość w celu wyrównania formuł lub zarezerwowania miejsca. Widoczność i zachowanie geometryczne są kontrolowane przez właściwości takie jak Show, ZeroWid, ZeroAsc, ZeroDesc i Transp. |
| [MathPortion](./mathportion/) | Reprezentuje fragment z kontekstem matematycznym wewnątrz. |
| [MathRadical](./mathradical/) | Określa funkcję pierwiastkową, składającą się z podstawy i opcjonalnego stopnia. Przykład obiektu pierwiastkowego: \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Umożliwia tworzenie pierwiastka matematycznego |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Określa obiekt indeks dolny-górny, który składa się z podstawy oraz indeksu dolnego i górnego umieszczonych po prawej stronie podstawy. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Umożliwia tworzenie [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Określa obiekt indeksu dolnego, który składa się z podstawy oraz zmniejszonego indeksu dolnego umieszczonego poniżej i po prawej stronie. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Umożliwia tworzenie [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Określa obiekt indeksu górnego, który składa się z podstawy oraz zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Umożliwia tworzenie [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | Położenie i rozmiar ograniczników względem zawartości operandów |
| [MathFractionTypes](./mathfractiontypes/) | Typy ułamków |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Typowe funkcje matematyczne jednego argumentu |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Typowe funkcje matematyczne dwóch argumentów |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Wyrównanie poziome |
| [MathIntegralTypes](./mathintegraltypes/) | Typy całek matematycznych |
| [MathJustification](./mathjustification/) | Określa justowanie akapitu matematycznego (serii sąsiednich instancji tekstu matematycznego w tym samym akapicie) |
| [MathLimitLocations](./mathlimitlocations/) | Położenie limitów (indeks dolny/górny) w operatorach n-argumentowych. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Typy operatorów n-argumentowych [IMathNaryOperator](./imathnaryoperator/) (z wyłączeniem całek). Dla całek [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Typ pionowego odstępu między kolumnami w macierzy lub tablicy |
| [MathSpacingRules](./mathspacingrules/) | Typy przerw (odstępów poziomych) między kolumnami macierzy |
| [MathTopBotPositions](./mathtopbotpositions/) | Wyliczenie pozycji górna/dolna |
| [MathVerticalAlignment](./mathverticalalignment/) | Wyrównanie pionowe |