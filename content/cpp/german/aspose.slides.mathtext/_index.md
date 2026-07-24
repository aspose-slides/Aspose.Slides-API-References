---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides für C++ API Referenz
description: 
type: docs
weight: 157
url: /de/aspose.slides.mathtext/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BaseScript](./basescript/) | Mathematikskript |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) mit [Control](../aspose.slides/control/) Zeicheneigenschaften |
| [IMathAccent](./imathaccent/) | Gibt die Akzentfunktion an, bestehend aus einer Basis und einem kombinierenden diakritischen Zeichen Beispiel: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Ermöglicht das Erstellen eines mathematischen Akzents |
| [IMathArray](./imatharray/) | Gibt ein vertikales Array von Gleichungen oder beliebigen mathematischen Objekten an |
| [IMathArrayFactory](./imatharrayfactory/) | Ermöglicht das Erstellen eines mathematischen Arrays |
| [IMathBar](./imathbar/) | Gibt die Balkenfunktion an, bestehend aus einem Basisargument und einem Ober- oder Unterstrich |
| [IMathBarFactory](./imathbarfactory/) | Ermöglicht das Erstellen eines mathematischen Balkens |
| [IMathBlock](./imathblock/) | Gibt eine Instanz von mathematischem Text an, die innerhalb eines [MathParagraph](./mathparagraph/) enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch einen Math-Block dargestellt. |
| [IMathBlockCollection](./imathblockcollection/) | Sammlung von Math-Blöcken ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Ermöglicht das Erstellen eines Math-Blocks |
| [IMathBorderBox](./imathborderbox/) | Zeichnet einen rechteckigen oder anderen Rahmen um das [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Ermöglicht das Erstellen einer Math-Rahmenbox |
| [IMathBox](./imathbox/) | Gibt die logische Verpackung (Boxing) eines mathematischen Elements an. Zum Beispiel kann ein verpacktes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt dienen oder gruppiert werden, sodass innerhalb keine Zeilenumbrüche erlaubt sind. Zum Beispiel sollte der \"==\"-Operator verpackt werden, um Zeilenumbrüche zu verhindern. |
| [IMathBoxFactory](./imathboxfactory/) | Ermöglicht das Erstellen einer Math-Box |
| [IMathDelimiter](./imathdelimiter/) | Gibt das Trennzeichenobjekt an, bestehend aus öffnenden und schließenden Zeichen (wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen) und einem oder mehreren mathematischen Elementen darin, getrennt durch ein angegebenes Zeichen. Beispiele: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Ermöglicht das Erstellen eines mathematischen Trennzeichens |
| [IMathElement](./imathelement/) | Basisschnittstelle für jedes mathematische Element: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw. |
| [IMathElementCollection](./imathelementcollection/) | Stellt eine Sammlung von mathematischen Elementen (MathElement) dar. |
| [IMathematicalText](./imathematicaltext/) | Mathematischer Text |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Ermöglicht das Erstellen eines [MathematicalText](./mathematicaltext/) Elements |
| [IMathFraction](./imathfraction/) | Gibt das Bruchobjekt an, bestehend aus Zähler und Nenner, getrennt durch einen Bruchstrich. Der Bruchstrich kann horizontal oder diagonal sein, abhängig von den Bruch-Eigenschaften. Das Bruchobjekt wird auch verwendet, um die Stapelfunktion darzustellen, die ein Element über ein anderes legt, ohne Bruchstrich. |
| [IMathFractionFactory](./imathfractionfactory/) | Ermöglicht das Erstellen eines mathematischen Bruchs |
| [IMathFunction](./imathfunction/) | Gibt eine Funktion eines Arguments an. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Ermöglicht das Erstellen einer mathematischen Funktion |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Gibt ein Gruppierungssymbol über oder unter einem Ausdruck an, üblicherweise zur Hervorhebung der Beziehung zwischen Elementen. |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Ermöglicht das Erstellen eines mathematischen Gruppierungszeichens |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Gibt das Tief-Hochstellung-Objekt an, das aus einer Basis sowie einer tiefer- und höhergestellten Komponente links von der Basis besteht. |
| [IMathLimit](./imathlimit/) | Gibt das Grenzwertobjekt an, bestehend aus Text auf der Grundlinie und verkleinertem Text direkt darüber oder darunter. |
| [IMathLimitFactory](./imathlimitfactory/) | Ermöglicht das Erstellen von [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Gibt das Matrixobjekt an, bestehend aus Kind-Elementen, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen besitzen. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichenobjekt ([IMathDelimiter](./imathdelimiter/)) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Ermöglicht das Erstellen einer mathematischen Matrix |
| [IMathNaryOperator](./imathnaryoperator/) | Gibt ein n-stelliges mathematisches Objekt an, wie Summation und Integral. Es besteht aus einem Operator, einer Basis (oder Operanden) und optionalen oberen und unteren Grenzen. Beispiele für n-stellige Operatoren sind: Summation, Vereinigung, Schnittmenge, Integral. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Ermöglicht das Erstellen von [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Gibt Eigenschaften von [IMathNaryOperator](./imathnaryoperator/) an. |
| [IMathParagraph](./imathparagraph/) | Mathematischer Absatz, der ein Container für mathematische Blöcke ([IMathBlock](./imathblock/)) ist. |
| [IMathParagraphFactory](./imathparagraphfactory/) | Ermöglicht das Erstellen eines mathematischen Absatzes |
| [IMathPhantom](./imathphantom/) | Stellt ein Phantom-Matheobjekt (<m:phant>) dar, das das Layout seines Kindelements beeinflusst, ohne es zwingend anzuzeigen. Ein Phantom kann den Basisausdruck verbergen, während es Breite, Höhe oder Tiefe beibehält, um Formeln auszurichten oder Platz zu reservieren. Sichtbarkeit und Geometrieverhalten werden durch Eigenschaften wie Show, ZeroWid, ZeroAsc, ZeroDesc und Transp gesteuert. |
| [IMathPortion](./imathportion/) | Stellt einen Abschnitt mit mathematischem Kontext dar. |
| [IMathRadical](./imathradical/) | Gibt die Wurzelfunktion an, bestehend aus einer Basis und einem optionalen Grad. Beispiel für ein Wurzelobjekt ist \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Ermöglicht das Erstellen einer mathematischen Wurzel |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Gibt das Tief-Hochstellung-Objekt an, das aus einer Basis sowie einer tiefer- und höhergestellten Komponente rechts von der Basis besteht. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Ermöglicht das Erstellen von [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Gibt das Tiefgestellt-Objekt an, das aus einer Basis und einem verkleinerten Tiefstellungstext rechts unten besteht. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Ermöglicht das Erstellen von [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Gibt das Hochgestellt-Objekt an, das aus einer Basis und einem verkleinerten Hochstellungstext rechts oben besteht. |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Ermöglicht das Erstellen von [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Gibt die Akzentfunktion an, bestehend aus einer Basis und einem kombinierenden diakritischen Zeichen Beispiel: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Ermöglicht das Erstellen eines mathematischen Akzents |
| [MathArray](./matharray/) | Gibt ein vertikales Array von Gleichungen oder beliebigen mathematischen Objekten an. |
| [MathArrayFactory](./matharrayfactory/) | Ermöglicht das Erstellen eines mathematischen Arrays |
| [MathBar](./mathbar/) | Gibt die Balkenfunktion an, bestehend aus einem Basisargument und einem Ober- oder Unterstrich. |
| [MathBarFactory](./mathbarfactory/) | Ermöglicht das Erstellen eines mathematischen Balkens |
| [MathBlock](./mathblock/) | Gibt eine Instanz von mathematischem Text an, die innerhalb eines [MathParagraph](./mathparagraph/) enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch einen Math-Block dargestellt. |
| [MathBlockFactory](./mathblockfactory/) | Ermöglicht das Erstellen eines Math-Blocks |
| [MathBorderBox](./mathborderbox/) | Zeichnet einen rechteckigen oder anderen Rahmen um das [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Ermöglicht das Erstellen einer Math-Rahmenbox |
| [MathBox](./mathbox/) | Gibt die logische Verpackung (Boxing) eines mathematischen Elements an. Zum Beispiel kann ein verpacktes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt dienen oder gruppiert werden, sodass innerhalb keine Zeilenumbrüche erlaubt sind. Zum Beispiel sollte der \"==\"-Operator verpackt werden, um Zeilenumbrüche zu verhindern. |
| [MathBoxFactory](./mathboxfactory/) | Ermöglicht das Erstellen einer Math-Box |
| [MathDelimiter](./mathdelimiter/) | Gibt das Trennzeichenobjekt an, bestehend aus öffnenden und schließenden Zeichen (wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen) und einem oder mehreren mathematischen Elementen darin, getrennt durch ein angegebenes Zeichen. Beispiele: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Ermöglicht das Erstellen eines mathematischen Trennzeichens |
| [MathElementBase](./mathelementbase/) | Basisklasse für [IMathElement](./imathelement/) mit der Implementierung einiger Methoden, die allen abgeleiteten Klassen gemeinsam sind. Nur für den internen Gebrauch. Abgeleitete Klasse muss [IMathElement](./imathelement/) sein. |
| [MathematicalText](./mathematicaltext/) | Mathematischer Text |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Ermöglicht das Erstellen eines [MathematicalText](./mathematicaltext/) Elements |
| [MathFraction](./mathfraction/) | Gibt das Bruchobjekt an, bestehend aus Zähler und Nenner, getrennt durch einen Bruchstrich. Der Bruchstrich kann horizontal oder diagonal sein, abhängig von den Bruch-Eigenschaften. Das Bruchobjekt wird auch zur Darstellung der Stapelfunktion verwendet, die ein Element über ein anderes legt, ohne Bruchstrich. |
| [MathFractionFactory](./mathfractionfactory/) | Ermöglicht das Erstellen eines mathematischen Bruchs |
| [MathFunction](./mathfunction/) | Gibt eine Funktion eines Arguments an. |
| [MathFunctionFactory](./mathfunctionfactory/) | Ermöglicht das Erstellen einer mathematischen Funktion |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Gibt ein Gruppierungssymbol über oder unter einem Ausdruck an, üblicherweise zur Hervorhebung der Beziehung zwischen Elementen. |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Ermöglicht das Erstellen eines mathematischen Gruppierungszeichens |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Gibt das Tief-Hochstellungs-Objekt an, das aus einer Basis sowie einer tiefer- und höhergestellten Komponente links von der Basis besteht. |
| [MathLimit](./mathlimit/) | Gibt das Grenzwertobjekt an, bestehend aus Text auf der Grundlinie und verkleinertem Text direkt darüber oder darunter. |
| [MathLimitFactory](./mathlimitfactory/) | Ermöglicht das Erstellen von [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Gibt das Matrixobjekt an, bestehend aus Kindelementen, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen besitzen. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichenobjekt ([IMathDelimiter](./imathdelimiter/)) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen. |
| [MathMatrixFactory](./mathmatrixfactory/) | Ermöglicht das Erstellen einer mathematischen Matrix |
| [MathNaryOperator](./mathnaryoperator/) | Gibt ein n-stelliges mathematisches Objekt an, wie Summation und Integral. Es besteht aus einem Operator, einer Basis (oder Operanden) und optionalen oberen und unteren Grenzen. Beispiele für n-stellige Operatoren sind: Summation, Vereinigung, Schnittmenge, Integral. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Ermöglicht das Erstellen von [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Mathematischer Absatz, der ein Container für mathematische Blöcke ([IMathBlock](./imathblock/)) ist. |
| [MathParagraphFactory](./mathparagraphfactory/) | Ermöglicht das Erstellen eines mathematischen Absatzes |
| [MathPhantom](./mathphantom/) | Stellt ein Phantom-Matheobjekt (<m:phant>) dar, das das Layout seines Kindelements beeinflusst, ohne es zwingend anzuzeigen. Ein Phantom kann den Basisausdruck verbergen, während es Breite, Höhe oder Tiefe beibehält, um Formeln auszurichten oder Platz zu reservieren. Sichtbarkeit und Geometrieverhalten werden durch Eigenschaften wie Show, ZeroWid, ZeroAsc, ZeroDesc und Transp gesteuert. |
| [MathPortion](./mathportion/) | Stellt einen Abschnitt mit mathematischem Kontext dar. |
| [MathRadical](./mathradical/) | Gibt die Wurzelfunktion an, bestehend aus einer Basis und einem optionalen Grad. Beispiel für ein Wurzelobjekt ist \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Ermöglicht das Erstellen einer mathematischen Wurzel |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Gibt das Tief-Hochstellung-Objekt an, das aus einer Basis sowie einer tiefer- und höhergestellten Komponente rechts von der Basis besteht. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Ermöglicht das Erstellen von [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Gibt das Tiefgestellt-Objekt an, das aus einer Basis und einem verkleinerten Tiefstellungstext rechts unten besteht. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Ermöglicht das Erstellen von [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Gibt das Hochgestellt-Objekt an, das aus einer Basis und einem verkleinerten Hochstellungstext rechts oben besteht. |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Ermöglicht das Erstellen von [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | Der Ort und die Größe der Trennzeichen relativ zum Inhalt der Operanden. |
| [MathFractionTypes](./mathfractiontypes/) | Brucharten |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Gemeinsame mathematische Funktionen eines Arguments |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Gemeinsame mathematische Funktionen von zwei Argumenten |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Horizontale Ausrichtung |
| [MathIntegralTypes](./mathintegraltypes/) | Mathematische Integraltypen |
| [MathJustification](./mathjustification/) | Gibt die Ausrichtung des mathematischen Absatzes an (eine Reihe benachbarter Instanzen von mathematischem Text innerhalb desselben Absatzes). |
| [MathLimitLocations](./mathlimitlocations/) | Position der Grenzen (Tief-/Hochstellung) bei n-stelligen Operatoren. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | N-stellige Operator [IMathNaryOperator](./imathnaryoperator/) Typen (ausgenommen Integrale) Für Integrale [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Der Typ des vertikalen Abstands zwischen Spalten in einer Matrix oder einem Array. |
| [MathSpacingRules](./mathspacingrules/) | Arten von Lücken (horizontaler Abstand) zwischen Spalten einer Matrix. |
| [MathTopBotPositions](./mathtopbotpositions/) | Aufzählung der oberen/unteren Positionen. |
| [MathVerticalAlignment](./mathverticalalignment/) | Vertikale Ausrichtung |