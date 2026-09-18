---
title: aspose.slides.mathtext
second_title: Aspose.Slides dla Pythona poprzez .NET odwołanie API
description: 
type: docs
url: /pl/aspose.slides.mathtext/
---
Zawiera klasy do pracy z tekstem matematycznym w prezentacjach Microsoft PowerPoint.

## Klasy

| Klasa | Opis |
| :- | :- |
| [`BaseScript`](/slides/python-net/pl/aspose.slides.mathtext/basescript/) | Skrypt matematyczny |
| [`IMathAccent`](/slides/python-net/pl/aspose.slides.mathtext/imathaccent/) | Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego<br/>            Przykład: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathaccentfactory/) | Umożliwia tworzenie akcentu matematycznego |
| [`IMathArray`](/slides/python-net/pl/aspose.slides.mathtext/imatharray/) | Określa pionową tablicę równań lub dowolnych obiektów matematycznych |
| [`IMathArrayFactory`](/slides/python-net/pl/aspose.slides.mathtext/imatharrayfactory/) | Umożliwia tworzenie tablicy matematycznej |
| [`IMathBar`](/slides/python-net/pl/aspose.slides.mathtext/imathbar/) | Określa funkcję kreski, składającą się z argumentu bazowego i kreski górnej lub dolnej |
| [`IMathBarFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathbarfactory/) | Umożliwia tworzenie kreski matematycznej |
| [`IMathBlock`](/slides/python-net/pl/aspose.slides.mathtext/imathblock/) | Określa instancję tekstu matematycznego zawartego w MathParagraph i rozpoczynającego się w nowej linii.<br/>            Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły są reprezentowane przez blok matematyczny. |
| [`IMathBlockCollection`](/slides/python-net/pl/aspose.slides.mathtext/imathblockcollection/) | Zbiór bloków matematycznych (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathblockfactory/) | Umożliwia tworzenie bloku matematycznego |
| [`IMathBorderBox`](/slides/python-net/pl/aspose.slides.mathtext/imathborderbox/) | Rysuje prostokątną lub inną ramkę wokół IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathborderboxfactory/) | Umożliwia tworzenie ramki granicznej matematycznej |
| [`IMathBox`](/slides/python-net/pl/aspose.slides.mathtext/imathbox/) | Określa logiczne opakowanie (pakowanie) elementu matematycznego.<br/>            Na przykład, obiekt w ramce może służyć jako emulator operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt podziału linii lub być grupowany tak, aby nie zezwalał na podziały linii wewnątrz.<br/>            Na przykład operator "==" powinien być opakowany, aby zapobiec podziałom linii. |
| [`IMathBoxFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathboxfactory/) | Umożliwia tworzenie pudełka matematycznego |
| [`IMathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiter/) | Określa obiekt ogranicznika, składający się z znaków otwierających i zamykających (takich jak nawiasy, <br/>            klamry, kwadraty i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem.<br/>            Przykłady: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathdelimiterfactory/) | Umożliwia tworzenie ogranicznika matematycznego |
| [`IMathElement`](/slides/python-net/pl/aspose.slides.mathtext/imathelement/) | Podstawowy interfejs dowolnego elementu matematycznego: <br/>            ułamek, tekst matematyczny, funkcja, wyrażenie z wieloma elementami itp |
| [`IMathElementCollection`](/slides/python-net/pl/aspose.slides.mathtext/imathelementcollection/) | Reprezentuje zbiór elementów matematycznych (MathElement). |
| [`IMathFraction`](/slides/python-net/pl/aspose.slides.mathtext/imathfraction/) | Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową.<br/>            Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka.<br/>            Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej. |
| [`IMathFractionFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathfractionfactory/) | Umożliwia tworzenie ułamka matematycznego |
| [`IMathFunction`](/slides/python-net/pl/aspose.slides.mathtext/imathfunction/) | Określa funkcję argumentu. |
| [`IMathFunctionFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathfunctionfactory/) | Umożliwia tworzenie funkcji matematycznej |
| [`IMathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacter/) | Określa symbol grupujący powyżej lub poniżej wyrażenia, zazwyczaj w celu podkreślenia relacji między elementami |
| [`IMathGroupingCharacterFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Umożliwia tworzenie znaku grupowania matematycznego |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Określa obiekt indeksu dolnego i górnego, który składa się z podstawy <br/>            oraz indeksu dolnego i górnego umieszczonych po lewej stronie podstawy. |
| [`IMathLimit`](/slides/python-net/pl/aspose.slides.mathtext/imathlimit/) | Określa obiekt limitu, składający się z tekstu na linii bazowej oraz zmniejszonego tekstu natychmiast powyżej lub poniżej niego. |
| [`IMathLimitFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathlimitfactory/) | Umożliwia tworzenie IMathLimit |
| [`IMathMatrix`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/) | Określa obiekt macierzy, składający się z elementów podrzędnych ułożonych w jeden lub więcej wierszy i kolumn. <br/>            Ważne jest, aby zauważyć, że macierze nie mają wbudowanych ograniczników. <br/>            Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika (IMathDelimiter).<br/>            Argumenty null mogą być użyte do tworzenia luk w macierzach. |
| [`IMathMatrixFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrixfactory/) | Umożliwia tworzenie macierzy matematycznej |
| [`IMathNaryOperator`](/slides/python-net/pl/aspose.slides.mathtext/imathnaryoperator/) | Określa obiekt matematyczny N-arny, taki jak sumowanie i całka.<br/>            Składa się z operatora, podstawy (lub operand), oraz opcjonalnych górnych i dolnych limitów. <br/>            Przykłady operatorów N-arnych: Sumowanie, Złączenie, Przecięcie, Całka |
| [`IMathNaryOperatorFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathnaryoperatorfactory/) | Umożliwia tworzenie IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/pl/aspose.slides.mathtext/imathnaryoperatorproperties/) | Określa właściwości IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/pl/aspose.slides.mathtext/imathparagraph/) | Akapit matematyczny będący kontenerem dla bloków matematycznych (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathparagraphfactory/) | Umożliwia tworzenie akapitu matematycznego |
| [`IMathPhantom`](/slides/python-net/pl/aspose.slides.mathtext/imathphantom/) | Reprezentuje phantomowy obiekt matematyczny (<m:phant>), który wpływa na układ swojego elementu podrzędnego<br/>            niekoniecznie go wyświetlając. Phantom może ukrywać swoją podstawową ekspresję, zachowując jednocześnie<br/>            jej szerokość, wysokość lub głębokość w celu wyrównania formuł lub rezerwacji miejsca. <br/>            Widoczność i zachowanie geometryczne są kontrolowane przez właściwości takie jak Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc oraz Transp. |
| [`IMathPortion`](/slides/python-net/pl/aspose.slides.mathtext/imathportion/) | Reprezentuje fragment z kontekstem matematycznym wewnątrz. |
| [`IMathRadical`](/slides/python-net/pl/aspose.slides.mathtext/imathradical/) | Określa funkcję pierwiastka, składającą się z podstawy i opcjonalnego stopnia.<br/>            Przykład obiektu pierwiastka to √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathradicalfactory/) | Umożliwia tworzenie pierwiastka matematycznego |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Określa obiekt indeksu dolnego i górnego, który składa się z podstawy <br/>            oraz indeksu dolnego i górnego umieszczonych po prawej stronie podstawy. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Umożliwia tworzenie IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/imathsubscriptelement/) | Określa obiekt indeksu dolnego, który składa się z podstawy <br/>            oraz zmniejszonego indeksu dolnego umieszczonego poniżej i po prawej stronie. |
| [`IMathSubscriptElementFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathsubscriptelementfactory/) | Umożliwia tworzenie IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/imathsuperscriptelement/) | Określa obiekt indeksu górnego, który składa się z podstawy <br/>            oraz zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie |
| [`IMathSuperscriptElementFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Umożliwia tworzenie IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/pl/aspose.slides.mathtext/imathematicaltext/) | Tekst matematyczny |
| [`IMathematicalTextFactory`](/slides/python-net/pl/aspose.slides.mathtext/imathematicaltextfactory/) | Umożliwia tworzenie elementu MathematicalText |
| [`MathAccent`](/slides/python-net/pl/aspose.slides.mathtext/mathaccent/) | Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego<br/>            Przykład: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathaccentfactory/) | Umożliwia tworzenie akcentu matematycznego |
| [`MathArray`](/slides/python-net/pl/aspose.slides.mathtext/matharray/) | Określa pionową tablicę równań lub dowolnych obiektów matematycznych |
| [`MathArrayFactory`](/slides/python-net/pl/aspose.slides.mathtext/matharrayfactory/) | Umożliwia tworzenie tablicy matematycznej |
| [`MathBar`](/slides/python-net/pl/aspose.slides.mathtext/mathbar/) | Określa funkcję kreski, składającą się z argumentu bazowego i kreski górnej lub dolnej |
| [`MathBarFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathbarfactory/) | Umożliwia tworzenie kreski matematycznej |
| [`MathBlock`](/slides/python-net/pl/aspose.slides.mathtext/mathblock/) | Określa instancję tekstu matematycznego zawartego w MathParagraph i rozpoczynającego się w nowej linii.<br/>            Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły są reprezentowane przez blok matematyczny. |
| [`MathBlockFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathblockfactory/) | Umożliwia tworzenie bloku matematycznego |
| [`MathBorderBox`](/slides/python-net/pl/aspose.slides.mathtext/mathborderbox/) | Rysuje prostokątną lub inną ramkę wokół IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathborderboxfactory/) | Umożliwia tworzenie ramki granicznej matematycznej |
| [`MathBox`](/slides/python-net/pl/aspose.slides.mathtext/mathbox/) | Określa logiczne opakowanie (pakowanie) elementu matematycznego.<br/>            Na przykład, obiekt w ramce może służyć jako emulator operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt podziału linii lub być grupowany tak, aby nie zezwalał na podziały linii wewnątrz.<br/>            Na przykład operator "==" powinien być opakowany, aby zapobiec podziałom linii. |
| [`MathBoxFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathboxfactory/) | Umożliwia tworzenie pudełka matematycznego |
| [`MathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter/) | Określa obiekt ogranicznika, składający się z znaków otwierających i zamykających (takich jak nawiasy, <br/>            klamry, kwadraty i pionowe kreski) oraz jednego lub więcej elementów matematycznych wewnątrz, oddzielonych określonym znakiem.<br/>            Przykłady: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiterfactory/) | Umożliwia tworzenie ogranicznika matematycznego |
| [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase/) | Podstawowa klasa dla IMathElement z implementacją niektórych metod wspólnych dla wszystkich klas dziedziczących<br/>            Do użytku wewnętrznego. Klasa dziedzicząca musi być IMathElement. |
| [`MathFraction`](/slides/python-net/pl/aspose.slides.mathtext/mathfraction/) | Określa obiekt ułamka, składający się z licznika i mianownika oddzielonych kreską ułamkową.<br/>            Kreska ułamkowa może być pozioma lub skośna, w zależności od właściwości ułamka.<br/>            Obiekt ułamka jest również używany do reprezentacji funkcji stosu, która umieszcza jeden element nad drugim, bez kreski ułamkowej. |
| [`MathFractionFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathfractionfactory/) | Umożliwia tworzenie ułamka matematycznego |
| [`MathFunction`](/slides/python-net/pl/aspose.slides.mathtext/mathfunction/) | Określa funkcję argumentu. |
| [`MathFunctionFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathfunctionfactory/) | Umożliwia tworzenie funkcji matematycznej |
| [`MathGroupingCharacter`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacter/) | Określa symbol grupujący powyżej lub poniżej wyrażenia, zazwyczaj w celu podkreślenia relacji między elementami |
| [`MathGroupingCharacterFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Umożliwia tworzenie znaku grupowania matematycznego |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Określa obiekt indeksu dolnego i górnego, który składa się z podstawy <br/>            oraz indeksu dolnego i górnego umieszczonych po lewej stronie podstawy. |
| [`MathLimit`](/slides/python-net/pl/aspose.slides.mathtext/mathlimit/) | Określa obiekt limitu, składający się z tekstu na linii bazowej oraz zmniejszonego tekstu natychmiast powyżej lub poniżej niego. |
| [`MathLimitFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathlimitfactory/) | Umożliwia tworzenie IMathLimit |
| [`MathMatrix`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/) | Określa obiekt macierzy, składający się z elementów podrzędnych ułożonych w jeden lub więcej wierszy i kolumn. <br/>            Ważne jest, aby zauważyć, że macierze nie mają wbudowanych ograniczników. <br/>            Aby umieścić macierz w nawiasach, należy użyć obiektu ogranicznika (IMathDelimiter).<br/>            Argumenty null mogą być użyte do tworzenia luk w macierzach. |
| [`MathMatrixFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrixfactory/) | Umożliwia tworzenie macierzy matematycznej |
| [`MathNaryOperator`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperator/) | Określa obiekt matematyczny N-arny, taki jak sumowanie i całka.<br/>            Składa się z operatora, podstawy (lub operand), oraz opcjonalnych górnych i dolnych limitów. <br/>            Przykłady operatorów N-arnych: Sumowanie, Złączenie, Przecięcie, Całka |
| [`MathNaryOperatorFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperatorfactory/) | Umożliwia tworzenie IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/pl/aspose.slides.mathtext/mathparagraph/) | Akapit matematyczny będący kontenerem dla bloków matematycznych (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathparagraphfactory/) | Umożliwia tworzenie akapitu matematycznego |
| [`MathPhantom`](/slides/python-net/pl/aspose.slides.mathtext/mathphantom/) | Reprezentuje phantomowy obiekt matematyczny (<m:phant>), który wpływa na układ swojego elementu podrzędnego<br/>            niekoniecznie go wyświetlając. Phantom może ukrywać swoją podstawową ekspresję, zachowując jednocześnie<br/>            jej szerokość, wysokość lub głębokość w celu wyrównania formuł lub rezerwacji miejsca. <br/>            Widoczność i zachowanie geometryczne są kontrolowane przez właściwości takie jak Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc oraz Transp. |
| [`MathPortion`](/slides/python-net/pl/aspose.slides.mathtext/mathportion/) | Reprezentuje fragment z kontekstem matematycznym wewnątrz. |
| [`MathRadical`](/slides/python-net/pl/aspose.slides.mathtext/mathradical/) | Określa funkcję pierwiastka, składającą się z podstawy i opcjonalnego stopnia.<br/>            Przykład obiektu pierwiastka to √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathradicalfactory/) | Umożliwia tworzenie pierwiastka matematycznego |
| [`MathRightSubSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Określa obiekt indeksu dolnego i górnego, który składa się z podstawy <br/>            oraz indeksu dolnego i górnego umieszczonych po prawej stronie podstawy. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Umożliwia tworzenie IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/mathsubscriptelement/) | Określa obiekt indeksu dolnego, który składa się z podstawy <br/>            oraz zmniejszonego indeksu dolnego umieszczonego poniżej i po prawej stronie. |
| [`MathSubscriptElementFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathsubscriptelementfactory/) | Umożliwia tworzenie IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/pl/aspose.slides.mathtext/mathsuperscriptelement/) | Określa obiekt indeksu górnego, który składa się z podstawy <br/>            oraz zmniejszonego indeksu górnego umieszczonego powyżej i po prawej stronie |
| [`MathSuperscriptElementFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Umożliwia tworzenie IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltext/) | Tekst matematyczny |
| [`MathematicalTextFactory`](/slides/python-net/pl/aspose.slides.mathtext/mathematicaltextfactory/) | Umożliwia tworzenie elementu MathematicalText |

## Wyliczenia

| Wyliczenie | Opis |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimitershape/) | Położenie i rozmiar ograniczników względem zawartości operandów |
| [`MathFractionTypes`](/slides/python-net/pl/aspose.slides.mathtext/mathfractiontypes/) | Typy ułamków |
| [`MathFunctionsOfOneArgument`](/slides/python-net/pl/aspose.slides.mathtext/mathfunctionsofoneargument/) | Typowe funkcje matematyczne jednego argumentu |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/pl/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Typowe funkcje matematyczne dwóch argumentów |
| [`MathHorizontalAlignment`](/slides/python-net/pl/aspose.slides.mathtext/mathhorizontalalignment/) | Wyrównanie poziome |
| [`MathIntegralTypes`](/slides/python-net/pl/aspose.slides.mathtext/mathintegraltypes/) | Typy całek matematycznych |
| [`MathJustification`](/slides/python-net/pl/aspose.slides.mathtext/mathjustification/) | Określa justowanie akapitu matematycznego (ciąg sąsiadujących instancji tekstu matematycznego w tym samym akapicie) |
| [`MathLimitLocations`](/slides/python-net/pl/aspose.slides.mathtext/mathlimitlocations/) | Położenie limitów (indeks dolny/górny) w operatorach N-arnych. |
| [`MathNaryOperatorTypes`](/slides/python-net/pl/aspose.slides.mathtext/mathnaryoperatortypes/) | Typy operatorów N-ary IMathNaryOperator (z wyłączeniem całek)<br/>            Dla całek [`MathIntegralTypes`](/slides/python-net/pl/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/pl/aspose.slides.mathtext/mathrowspacingrule/) | Typ pionowego odstępu między kolumnami w macierzy lub tablicy |
| [`MathSpacingRules`](/slides/python-net/pl/aspose.slides.mathtext/mathspacingrules/) | Typy przerw (odstępów poziomych) między kolumnami macierzy |
| [`MathTopBotPositions`](/slides/python-net/pl/aspose.slides.mathtext/mathtopbotpositions/) | Wyliczenie pozycji górnych/dolnych |
| [`MathVerticalAlignment`](/slides/python-net/pl/aspose.slides.mathtext/mathverticalalignment/) | Wyrównanie pionowe |
