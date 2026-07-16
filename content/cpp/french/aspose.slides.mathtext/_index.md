---
title: "Aspose::Slides::MathText"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 157
url: /fr/aspose.slides.mathtext/
---
## Classes

| Class | Description |
| --- | --- |
| [BaseScript](./basescript/) | Script math |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) avec les propriétés de caractères [Control](../aspose.slides/control/) |
| [IMathAccent](./imathaccent/) | Spécifie la fonction d'accent, composée d'une base et d'une marque diacritique combinée Exemple : \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Permet de créer un accent mathématique |
| [IMathArray](./imatharray/) | Spécifie un tableau vertical d'équations ou de tout objet mathématique |
| [IMathArrayFactory](./imatharrayfactory/) | Permet de créer un tableau mathématique |
| [IMathBar](./imathbar/) | Spécifie la fonction barre, composée d'un argument de base et d'une barre supérieure ou inférieure |
| [IMathBarFactory](./imathbarfactory/) | Permet de créer une barre mathématique |
| [IMathBlock](./imathblock/) | Spécifie une instance de texte mathématique contenue dans un [MathParagraph](./mathparagraph/) et commençant sur sa propre ligne. Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d'équations ou d'expressions et les formules sont représentées par un bloc mathématique. |
| [IMathBlockCollection](./imathblockcollection/) | Collection de blocs mathématiques ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Permet de créer un bloc mathématique |
| [IMathBorderBox](./imathborderbox/) | Dessine un bord rectangulaire ou autre autour du [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Permet de créer une boîte de bordure mathématique |
| [IMathBox](./imathbox/) | Spécifie l'encapsulation logique (emballage) d'un élément mathématique. Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de rupture de ligne, ou être groupé afin d'interdire les ruptures de ligne à l'intérieur. Par exemple, l'opérateur \"==\" doit être encadré pour éviter les ruptures de ligne. |
| [IMathBoxFactory](./imathboxfactory/) | Permet de créer une boîte mathématique |
| [IMathDelimiter](./imathdelimiter/) | Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que parenthèses, accolades, crochets et barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Permet de créer un délimiteur mathématique |
| [IMathElement](./imathelement/) | Interface de base de tout élément mathématique : fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc. |
| [IMathElementCollection](./imathelementcollection/) | Représente une collection d'éléments mathématiques (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Texte mathématique |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Permet de créer un élément [MathematicalText](./mathematicaltext/) |
| [IMathFraction](./imathfraction/) | Spécifie l'objet fraction, composé d'un numérateur et d'un dénominateur séparés par une barre de fraction. La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction. L'objet fraction est également utilisé pour représenter la fonction pile, qui place un élément au-dessus d'un autre, sans barre de fraction. |
| [IMathFractionFactory](./imathfractionfactory/) | Permet de créer une fraction mathématique |
| [IMathFunction](./imathfunction/) | Spécifie une fonction d'un argument. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Permet de créer une fonction mathématique |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Spécifie un symbole de groupe au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Permet de créer un caractère de regroupement mathématique |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Spécifie l'objet indice-sursindice, qui se compose d'une base et d'un indice et d'un surindice placés à gauche de la base. |
| [IMathLimit](./imathlimit/) | Spécifie l'objet limite, composé d'un texte sur la ligne de base et d'un texte de taille réduite immédiatement au-dessus ou en dessous. |
| [IMathLimitFactory](./imathlimitfactory/) | Permet de créer [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Spécifie l'objet Matrice, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur ([IMathDelimiter](./imathdelimiter/)). Des arguments null peuvent être utilisés pour créer des espaces dans les matrices. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Permet de créer une matrice mathématique |
| [IMathNaryOperator](./imathnaryoperator/) | Spécifie un objet mathématique n-aire, tel que Summation, Union, Intersection, Integral. Il se compose d'un opérateur, d'une base (ou opérande), et de limites supérieures et inférieures optionnelles. Des exemples d'opérateurs n-aires sont : Summation, Union, Intersection, Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Permet de créer [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Spécifie les propriétés de [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Paragraphe mathématique qui est un conteneur pour les blocs mathématiques ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Permet de créer un paragraphe mathématique |
| [IMathPhantom](./imathphantom/) | Représente un objet mathématique fantôme (<m:phant>) qui affecte la mise en page de son élément enfant sans nécessairement l'afficher. Un fantôme peut masquer son expression de base tout en conservant sa largeur, sa hauteur ou sa profondeur afin d'aligner les formules ou de réserver de l'espace. La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, ZeroDesc et Transp. |
| [IMathPortion](./imathportion/) | Représente une portion avec un contexte mathématique à l'intérieur. |
| [IMathRadical](./imathradical/) | Spécifie la fonction radicale, composée d'une base et d'un degré optionnel. Exemple d'objet radical : \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Permet de créer un radical mathématique |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Spécifie l'objet indice-sursindice, qui se compose d'une base et d'un indice et d'un surindice placés à droite de la base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Permet de créer [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Spécifie l'objet indice, qui se compose d'une base et d'un indice de taille réduite placé en dessous et à droite. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Permet de créer [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Spécifie l'objet surindice, qui se compose d'une base et d'un surindice de taille réduite placé au-dessus et à droite |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Permet de créer [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Spécifie la fonction d'accent, composée d'une base et d'une marque diacritique combinée Exemple : \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Permet de créer un accent mathématique |
| [MathArray](./matharray/) | Spécifie un tableau vertical d'équations ou de tout objet mathématique |
| [MathArrayFactory](./matharrayfactory/) | Permet de créer un tableau mathématique |
| [MathBar](./mathbar/) | Spécifie la fonction barre, composée d'un argument de base et d'une barre supérieure ou inférieure |
| [MathBarFactory](./mathbarfactory/) | Permet de créer une barre mathématique |
| [MathBlock](./mathblock/) | Spécifie une instance de texte mathématique contenue dans un [MathParagraph](./mathparagraph/) et commençant sur sa propre ligne. Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d'équations ou d'expressions et les formules sont représentées par un bloc mathématique. |
| [MathBlockFactory](./mathblockfactory/) | Permet de créer un bloc mathématique |
| [MathBorderBox](./mathborderbox/) | Dessine un bord rectangulaire ou autre autour du [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Permet de créer une boîte de bordure mathématique |
| [MathBox](./mathbox/) | Spécifie l'encapsulation logique (emballage) d'un élément mathématique. Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de rupture de ligne, ou être groupé afin d'interdire les ruptures de ligne à l'intérieur. Par exemple, l'opérateur \"==\" doit être encadré pour éviter les ruptures de ligne. |
| [MathBoxFactory](./mathboxfactory/) | Permet de créer une boîte mathématique |
| [MathDelimiter](./mathdelimiter/) | Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que parenthèses, accolades, crochets et barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Permet de créer un délimiteur mathématique |
| [MathElementBase](./mathelementbase/) | Classe de base pour [IMathElement](./imathelement/) avec l'implémentation de certaines méthodes communes à toutes les classes héritées. À usage interne uniquement. La classe héritée doit être [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Texte mathématique |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Permet de créer un élément [MathematicalText](./mathematicaltext/) |
| [MathFraction](./mathfraction/) | Spécifie l'objet fraction, composé d'un numérateur et d'un dénominateur séparés par une barre de fraction. La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction. L'objet fraction est également utilisé pour représenter la fonction pile, qui place un élément au-dessus d'un autre, sans barre de fraction. |
| [MathFractionFactory](./mathfractionfactory/) | Permet de créer une fraction mathématique |
| [MathFunction](./mathfunction/) | Spécifie une fonction d'un argument. |
| [MathFunctionFactory](./mathfunctionfactory/) | Permet de créer une fonction mathématique |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Spécifie un symbole de groupe au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Permet de créer un caractère de regroupement mathématique |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Spécifie l'objet indice-sursindice, qui se compose d'une base et d'un indice et d'un surindice placés à gauche de la base. |
| [MathLimit](./mathlimit/) | Spécifie l'objet limite, composé d'un texte sur la ligne de base et d'un texte de taille réduite immédiatement au-dessus ou en dessous. |
| [MathLimitFactory](./mathlimitfactory/) | Permet de créer [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Spécifie l'objet Matrice, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur ([IMathDelimiter](./imathdelimiter/)). Des arguments null peuvent être utilisés pour créer des espaces dans les matrices. |
| [MathMatrixFactory](./mathmatrixfactory/) | Permet de créer une matrice mathématique |
| [MathNaryOperator](./mathnaryoperator/) | Spécifie un objet mathématique n-aire, tel que Summation et Integral. Il se compose d'un opérateur, d'une base (ou opérande), et de limites supérieures et inférieures optionnelles. Des exemples d'opérateurs n-aires sont : Summation, Union, Intersection, Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Permet de créer [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Paragraphe mathématique qui est un conteneur pour les blocs mathématiques ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Permet de créer un paragraphe mathématique |
| [MathPhantom](./mathphantom/) | Représente un objet mathématique fantôme (<m:phant>) qui affecte la mise en page de son élément enfant sans nécessairement l'afficher. Un fantôme peut masquer son expression de base tout en conservant sa largeur, sa hauteur ou sa profondeur afin d'aligner les formules ou de réserver de l'espace. La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, ZeroDesc et Transp. |
| [MathPortion](./mathportion/) | Représente une portion avec un contexte mathématique à l'intérieur. |
| [MathRadical](./mathradical/) | Spécifie la fonction radicale, composée d'une base et d'un degré optionnel. Exemple d'objet radical : \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Permet de créer un radical mathématique |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Spécifie l'objet indice-sursindice, qui se compose d'une base et d'un indice et d'un surindice placés à droite de la base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Permet de créer [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Spécifie l'objet indice, qui se compose d'une base et d'un indice de taille réduite placé en dessous et à droite. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Permet de créer [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Spécifie l'objet surindice, qui se compose d'une base et d'un surindice de taille réduite placé au-dessus et à droite |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Permet de créer [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Enums

| Enum | Description |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | L'emplacement et la taille des délimiteurs par rapport au contenu des opérandes |
| [MathFractionTypes](./mathfractiontypes/) | Types de fraction |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Fonctions mathématiques courantes d'un argument |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Fonctions mathématiques courantes de deux arguments |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Alignement horizontal |
| [MathIntegralTypes](./mathintegraltypes/) | Types d'intégrales mathématiques |
| [MathJustification](./mathjustification/) | Spécifie la justification du paragraphe mathématique (une série d'instances adjacentes de texte mathématique dans le même paragraphe) |
| [MathLimitLocations](./mathlimitlocations/) | Emplacement des limites (indice/sursindice) dans les opérateurs n-aires. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Types d'opérateur n-aire [IMathNaryOperator](./imathnaryoperator/) (excluant les intégrales) Pour les intégrales [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Le type d'espacement vertical entre les colonnes dans une matrice ou un tableau |
| [MathSpacingRules](./mathspacingrules/) | Types d'écart (espacement horizontal) entre les colonnes d'une matrice |
| [MathTopBotPositions](./mathtopbotpositions/) | Énumération des positions haut/bas |
| [MathVerticalAlignment](./mathverticalalignment/) | Alignement vertical |