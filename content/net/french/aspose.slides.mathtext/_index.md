---
title: Aspose.Slides.MathText
second_title: Référence de l'API Aspose.Slides pour .NET
description: Contient des classes pour travailler avec le texte mathématique dans les présentations Microsoft PowerPoint.
type: docs
weight: 120
url: /fr/aspose.slides.mathtext/
---

Contient des classes pour travailler avec le texte mathématique dans les présentations Microsoft PowerPoint.

## Classes

| Classe | Description |
| --- | --- |
| [BaseScript](./basescript) | Script mathématique |
| [MathAccent](./mathaccent) | Spécifie la fonction d'accent, composée d'une base et d'un signe diacritique combinant Exemple : 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Permet de créer un accent mathématique |
| [MathArray](./matharray) | Spécifie un tableau vertical d'équations ou d'objets mathématiques |
| [MathArrayFactory](./matharrayfactory) | Permet de créer un tableau mathématique |
| [MathBar](./mathbar) | Spécifie la fonction de barre, composée d'un argument de base et d'une barre supérieure ou inférieure |
| [MathBarFactory](./mathbarfactory) | Permet de créer une barre mathématique |
| [MathBlock](./mathblock) | Spécifie une instance de texte mathématique contenue dans un MathParagraph et commence sur sa propre ligne. Toutes les zones mathématiques, y compris les équations, expressions, tableaux d'équations ou expressions, et formules sont représentées par un bloc mathématique. |
| [MathBlockFactory](./mathblockfactory) | Permet de créer un bloc mathématique |
| [MathBorderBox](./mathborderbox) | Dessine une bordure rectangulaire ou d'une autre forme autour de l'IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Permet de créer une boîte de bordure mathématique |
| [MathBox](./mathbox) | Spécifie l'encadrement logique (packaging) des éléments mathématiques. Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans un point d'alignement, servir de point de rupture de ligne, ou être regroupé de manière à ne pas permettre de ruptures de ligne à l'intérieur. Par exemple, l'opérateur "==" doit être encadré pour éviter les ruptures de ligne. |
| [MathBoxFactory](./mathboxfactory) | Permet de créer une boîte mathématique |
| [MathDelimiter](./mathdelimiter) | Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que parenthèses, accolades, crochets et barres verticales), et un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Permet de créer un délimiteur mathématique |
| [MathElementBase](./mathelementbase) | Classe de base pour IMathElement avec l'implémentation de certaines méthodes qui sont communes à toutes les classes héritées. Pour usage interne seulement. La classe héritée doit être IMathElement. |
| [MathematicalText](./mathematicaltext) | Texte mathématique |
| [MathematicalTextFactory](./mathematicaltextfactory) | Permet de créer un élément MathematicalText |
| [MathFraction](./mathfraction) | Spécifie l'objet fraction, composé d'un numérateur et d'un dénominateur séparés par une barre de fraction. La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction. L'objet fraction est également utilisé pour représenter la fonction de pile, qui place un élément au-dessus d'un autre, sans barre de fraction. |
| [MathFractionFactory](./mathfractionfactory) | Permet de créer une fraction mathématique |
| [MathFunction](./mathfunction) | Spécifie une fonction d'un argument. |
| [MathFunctionFactory](./mathfunctionfactory) | Permet de créer une fonction mathématique |
| [MathGroupingCharacter](./mathgroupingcharacter) | Spécifie un symbole de regroupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Permet de créer un caractère de regroupement mathématique |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Spécifie l'objet Sub-Superscript, qui se compose d'une base et d'un indice et d'un exposant placés à gauche de la base. |
| [MathLimit](./mathlimit) | Spécifie l'objet Limit, composé de texte sur la ligne de base et de texte de taille réduite immédiatement au-dessus ou au-dessous. |
| [MathLimitFactory](./mathlimitfactory) | Permet de créer IMathLimit |
| [MathMatrix](./mathmatrix) | Spécifie l'objet Matrix, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice dans des parenthèses, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices. |
| [MathMatrixFactory](./mathmatrixfactory) | Permet de créer une matrice mathématique |
| [MathNaryOperator](./mathnaryoperator) | Spécifie un objet mathématique N-aire, tel que la Somme et l'Intégrale. Il se compose d'un opérateur, d'une base (ou d'un opérande), et de limites supérieures et inférieures facultatives. Exemples d'opérateurs N-aires : Somme, Union, Intersection, Intégrale |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Permet de créer IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Paragraphe mathématique qui est un conteneur pour des blocs mathématiques (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Permet de créer un paragraphe mathématique |
| [MathPortion](./mathportion) | Représente une portion avec un contexte mathématique à l'intérieur. |
| [MathRadical](./mathradical) | Spécifie la fonction radicielle, composée d'une base et d'un degré facultatif. Exemple d'objet radical est √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Permet de créer un radical mathématique |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Spécifie l'objet Sub-Superscript, qui se compose d'une base et d'un indice et d'un exposant placés à droite de la base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Permet de créer IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Spécifie l'objet indice, qui se compose d'une base et d'un indice de taille réduite placée en dessous et à droite. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Permet de créer IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Spécifie l'objet exposant, qui se compose d'une base et d'un exposant de taille réduite placé au-dessus et à droite |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Permet de créer IMathSuperscriptElement |
## Interfaces

| Interface | Description |
| --- | --- |
| [IMathAccent](./imathaccent) | Spécifie la fonction d'accent, composée d'une base et d'un signe diacritique combinant Exemple : 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Permet de créer un accent mathématique |
| [IMathArray](./imatharray) | Spécifie un tableau vertical d'équations ou d'objets mathématiques |
| [IMathArrayFactory](./imatharrayfactory) | Permet de créer un tableau mathématique |
| [IMathBar](./imathbar) | Spécifie la fonction de barre, composée d'un argument de base et d'une barre supérieure ou inférieure |
| [IMathBarFactory](./imathbarfactory) | Permet de créer une barre mathématique |
| [IMathBlock](./imathblock) | Spécifie une instance de texte mathématique contenue dans un MathParagraph et commence sur sa propre ligne. Toutes les zones mathématiques, y compris les équations, expressions, tableaux d'équations ou expressions, et formules sont représentées par un bloc mathématique. |
| [IMathBlockCollection](./imathblockcollection) | Collection de blocs mathématiques (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Permet de créer un bloc mathématique |
| [IMathBorderBox](./imathborderbox) | Dessine une bordure rectangulaire ou d'une autre forme autour de l'IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Permet de créer une boîte de bordure mathématique |
| [IMathBox](./imathbox) | Spécifie l'encadrement logique (packaging) des éléments mathématiques. Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans un point d'alignement, servir de point de rupture de ligne, ou être regroupé de manière à ne pas permettre de ruptures de ligne à l'intérieur. Par exemple, l'opérateur "==" doit être encadré pour éviter les ruptures de ligne. |
| [IMathBoxFactory](./imathboxfactory) | Permet de créer une boîte mathématique |
| [IMathDelimiter](./imathdelimiter) | Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que parenthèses, accolades, crochets et barres verticales), et un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Permet de créer un délimiteur mathématique |
| [IMathElement](./imathelement) | Interface de base de tout élément mathématique : fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc. |
| [IMathElementCollection](./imathelementcollection) | Représente une collection d'éléments mathématiques (MathElement). |
| [IMathematicalText](./imathematicaltext) | Texte mathématique |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Permet de créer un élément MathematicalText |
| [IMathFraction](./imathfraction) | Spécifie l'objet fraction, composé d'un numérateur et d'un dénominateur séparés par une barre de fraction. La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction. L'objet fraction est également utilisé pour représenter la fonction de pile, qui place un élément au-dessus d'un autre, sans barre de fraction. |
| [IMathFractionFactory](./imathfractionfactory) | Permet de créer une fraction mathématique |
| [IMathFunction](./imathfunction) | Spécifie une fonction d'un argument. |
| [IMathFunctionFactory](./imathfunctionfactory) | Permet de créer une fonction mathématique |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Spécifie un symbole de regroupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Permet de créer un caractère de regroupement mathématique |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Spécifie l'objet Sub-Superscript, qui se compose d'une base et d'un indice et d'un exposant placés à gauche de la base. |
| [IMathLimit](./imathlimit) | Spécifie l'objet Limit, composé de texte sur la ligne de base et de texte de taille réduite immédiatement au-dessus ou au-dessous. |
| [IMathLimitFactory](./imathlimitfactory) | Permet de créer IMathLimit |
| [IMathMatrix](./imathmatrix) | Spécifie l'objet Matrix, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice dans des parenthèses, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices. |
| [IMathMatrixFactory](./imathmatrixfactory) | Permet de créer une matrice mathématique |
| [IMathNaryOperator](./imathnaryoperator) | Spécifie un objet mathématique N-aire, tel que Somme et Intégrale. Il se compose d'un opérateur, d'une base (ou d'un opérande), et de limites supérieures et inférieures facultatives. Exemples d'opérateurs N-aires : Somme, Union, Intersection, Intégrale |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Permet de créer IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Spécifie les propriétés de IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Paragraphe mathématique qui est un conteneur pour des blocs mathématiques (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Permet de créer un paragraphe mathématique |
| [IMathPortion](./imathportion) | Représente une portion avec un contexte mathématique à l'intérieur. |
| [IMathRadical](./imathradical) | Spécifie la fonction radicielle, composée d'une base et d'un degré facultatif. Exemple d'objet radical est √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Permet de créer un radical mathématique |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Spécifie l'objet Sub-Superscript, qui se compose d'une base et d'un indice et d'un exposant placés à droite de la base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Permet de créer IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Spécifie l'objet indice, qui se compose d'une base et d'un indice de taille réduite placée en dessous et à droite. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Permet de créer IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Spécifie l'objet exposant, qui se compose d'une base et d'un exposant de taille réduite placé au-dessus et à droite |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Permet de créer IMathSuperscriptElement |
## Énumération

| Énumération | Description |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | L'emplacement et la taille des délimiteurs par rapport au contenu des opérandes |
| [MathFractionTypes](./mathfractiontypes) | Types de fractions |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Fonctions mathématiques courantes d'un argument |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Fonctions mathématiques courantes de deux arguments |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Alignement horizontal |
| [MathIntegralTypes](./mathintegraltypes) | Types d'intégrales mathématiques |
| [MathJustification](./mathjustification) | Spécifie la justification du paragraphe mathématique (une série d'instances adjacentes de texte mathématique au sein du même paragraphe) |
| [MathLimitLocations](./mathlimitlocations) | Emplacement des limites (indice/exposant) dans les opérateurs N-aires. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Types d'opérateurs N-aires IMathNaryOperator (excluant les intégrales) Pour les intégrales [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Le type d'espacement vertical entre les colonnes dans une matrice ou un tableau |
| [MathSpacingRules](./mathspacingrules) | Types d'espace (espacement horizontal) entre les colonnes d'une matrice |
| [MathTopBotPositions](./mathtopbotpositions) | Énumération des positions haut/bas |
| [MathVerticalAlignment](./mathverticalalignment) | Alignement vertical |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->