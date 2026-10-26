---
title: aspose.slides.mathtext
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/
---
Contient des classes pour travailler avec du texte mathématique dans les présentations Microsoft PowerPoint.
## Classes

| Class | Description |
| :- | :- |
| [`BaseScript`](/slides/python-net/fr/aspose.slides.mathtext/basescript/) | Script mathématique |
| [`IMathAccent`](/slides/python-net/fr/aspose.slides.mathtext/imathaccent/) | Spécifie la fonction d'accent, composée d'une base et d'un signe diacritique combiné<br/>            Example: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathaccentfactory/) | Permet de créer un accent mathématique |
| [`IMathArray`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/) | Spécifie un tableau vertical d'équations ou de tout objet mathématique |
| [`IMathArrayFactory`](/slides/python-net/fr/aspose.slides.mathtext/imatharrayfactory/) | Permet de créer un tableau mathématique |
| [`IMathBar`](/slides/python-net/fr/aspose.slides.mathtext/imathbar/) | Spécifie la fonction de barre, composée d'un argument de base et d'une barre supérieure ou inférieure |
| [`IMathBarFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathbarfactory/) | Permet de créer une barre mathématique |
| [`IMathBlock`](/slides/python-net/fr/aspose.slides.mathtext/imathblock/) | Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur une ligne séparée.<br/>            Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d'équations ou d'expressions, et les formules sont représentées par un bloc mathématique. |
| [`IMathBlockCollection`](/slides/python-net/fr/aspose.slides.mathtext/imathblockcollection/) | Collection de blocs mathématiques (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathblockfactory/) | Permet de créer un bloc mathématique |
| [`IMathBorderBox`](/slides/python-net/fr/aspose.slides.mathtext/imathborderbox/) | Dessine une bordure rectangulaire ou une autre autour de l'IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathborderboxfactory/) | Permet de créer une boîte de bordure mathématique |
| [`IMathBox`](/slides/python-net/fr/aspose.slides.mathtext/imathbox/) | Spécifie l'encapsulation logique (emballage) d'un élément mathématique.<br/>            Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de retour à la ligne, ou être groupé de façon à ne pas permettre de retours à la ligne à l'intérieur.<br/>            Par exemple, l'opérateur "==" doit être encadré pour empêcher les retours à la ligne. |
| [`IMathBoxFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathboxfactory/) | Permet de créer une boîte mathématique |
| [`IMathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/) | Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que les parenthèses,<br/>            accolades, crochets et barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié.<br/>            Exemples : (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiterfactory/) | Permet de créer un délimiteur mathématique |
| [`IMathElement`](/slides/python-net/fr/aspose.slides.mathtext/imathelement/) | Interface de base de tout élément mathématique : <br/>            fraction, texte mathématique, fonction, expression avec plusieurs éléments, etc |
| [`IMathElementCollection`](/slides/python-net/fr/aspose.slides.mathtext/imathelementcollection/) | Représente une collection d'éléments mathématiques (MathElement). |
| [`IMathFraction`](/slides/python-net/fr/aspose.slides.mathtext/imathfraction/) | Spécifie l'objet fraction, composé d'un numérateur et d'un dénominateur séparés par une barre de fraction.<br/>            La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction.<br/>            L'objet fraction est également utilisé pour représenter la fonction pile, qui place un élément au-dessus d'un autre, sans barre de fraction. |
| [`IMathFractionFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathfractionfactory/) | Permet de créer une fraction mathématique |
| [`IMathFunction`](/slides/python-net/fr/aspose.slides.mathtext/imathfunction/) | Spécifie une fonction d'un argument. |
| [`IMathFunctionFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathfunctionfactory/) | Permet de créer une fonction mathématique |
| [`IMathGroupingCharacter`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/) | Spécifie un symbole de groupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments |
| [`IMathGroupingCharacterFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Permet de créer un caractère de groupement mathématique |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Spécifie l'objet indice-suscript, qui consiste en une base <br/>            et un indice et un suscript placés à gauche de la base. |
| [`IMathLimit`](/slides/python-net/fr/aspose.slides.mathtext/imathlimit/) | Spécifie l'objet Limite, composé de texte sur la ligne de base et de texte de taille réduite immédiatement au-dessus ou en dessous. |
| [`IMathLimitFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathlimitfactory/) | Permet de créer IMathLimit |
| [`IMathMatrix`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/) | Spécifie l'objet Matrice, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. <br/>            Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. <br/>            Pour placer la matrice entre des crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter).<br/>            Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices. |
| [`IMathMatrixFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrixfactory/) | Permet de créer une matrice mathématique |
| [`IMathNaryOperator`](/slides/python-net/fr/aspose.slides.mathtext/imathnaryoperator/) | Spécifie un objet mathématique N-aire, tel que la Somme et l'Intégrale.<br/>            Il se compose d'un opérateur, d'une base (ou opérande), et de limites supérieures et inférieures optionnelles. <br/>            Exemples d'opérateurs N-aires : Somme, Union, Intersection, Intégrale |
| [`IMathNaryOperatorFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathnaryoperatorfactory/) | Permet de créer IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/fr/aspose.slides.mathtext/imathnaryoperatorproperties/) | Spécifie les propriétés de IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/fr/aspose.slides.mathtext/imathparagraph/) | Paragraphe mathématique qui est un conteneur pour des blocs mathématiques (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathparagraphfactory/) | Permet de créer un paragraphe mathématique |
| [`IMathPhantom`](/slides/python-net/fr/aspose.slides.mathtext/imathphantom/) | Représente un objet mathématique fantôme (<m:phant>) qui influence la mise en page de son élément enfant<br/>            sans nécessairement l'afficher. Un fantôme peut masquer son expression de base tout en préservant<br/>            sa largeur, sa hauteur ou sa profondeur afin d'aligner les formules ou de réserver de l'espace. <br/>            La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc et Transp. |
| [`IMathPortion`](/slides/python-net/fr/aspose.slides.mathtext/imathportion/) | Représente une portion avec un contexte mathématique à l'intérieur. |
| [`IMathRadical`](/slides/python-net/fr/aspose.slides.mathtext/imathradical/) | Spécifie la fonction radicielle, composée d'une base et d'un degré optionnel.<br/>            Exemple d'objet radical : √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathradicalfactory/) | Permet de créer un radical mathématique |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Spécifie l'objet indice-suscript, qui consiste en une base <br/>            et un indice et un suscript placés à droite de la base. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Permet de créer IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/imathsubscriptelement/) | Spécifie l'objet indice, qui consiste en une base <br/>            et un indice de taille réduite placé en dessous et à droite. |
| [`IMathSubscriptElementFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathsubscriptelementfactory/) | Permet de créer IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/imathsuperscriptelement/) | Spécifie l'objet exposant, qui consiste en une base <br/>            et un exposant de taille réduite placé au-dessus et à droite |
| [`IMathSuperscriptElementFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Permet de créer IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/fr/aspose.slides.mathtext/imathematicaltext/) | Texte mathématique |
| [`IMathematicalTextFactory`](/slides/python-net/fr/aspose.slides.mathtext/imathematicaltextfactory/) | Permet de créer un élément MathematicalText |
| [`MathAccent`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/) | Spécifie la fonction d'accent, composée d'une base et d'un signe diacritique combiné<br/>            Example: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathaccentfactory/) | Permet de créer un accent mathématique |
| [`MathArray`](/slides/python-net/fr/aspose.slides.mathtext/matharray/) | Spécifie un tableau vertical d'équations ou de tout objet mathématique |
| [`MathArrayFactory`](/slides/python-net/fr/aspose.slides.mathtext/matharrayfactory/) | Permet de créer un tableau mathématique |
| [`MathBar`](/slides/python-net/fr/aspose.slides.mathtext/mathbar/) | Spécifie la fonction de barre, composée d'un argument de base et d'une barre supérieure ou inférieure |
| [`MathBarFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathbarfactory/) | Permet de créer une barre mathématique |
| [`MathBlock`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/) | Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur une ligne séparée.<br/>            Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d'équations ou d'expressions, et les formules sont représentées par un bloc mathématique. |
| [`MathBlockFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathblockfactory/) | Permet de créer un bloc mathématique |
| [`MathBorderBox`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/) | Dessine une bordure rectangulaire ou une autre autour de l'IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathborderboxfactory/) | Permet de créer une boîte de bordure mathématique |
| [`MathBox`](/slides/python-net/fr/aspose.slides.mathtext/mathbox/) | Spécifie l'encapsulation logique (emballage) d'un élément mathématique.<br/>            Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de retour à la ligne, ou être groupé de façon à ne pas permettre de retours à la ligne à l'intérieur.<br/>            Par exemple, l'opérateur "==" doit être encadré pour empêcher les retours à la ligne. |
| [`MathBoxFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathboxfactory/) | Permet de créer une boîte mathématique |
| [`MathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/) | Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que les parenthèses,<br/>            accolades, crochets et barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié.<br/>            Exemples : (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiterfactory/) | Permet de créer un délimiteur mathématique |
| [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase/) | Classe de base pour IMathElement avec l'implémentation de certaines méthodes communes à toutes les classes héritées<br/>            Usage interne uniquement. La classe héritée doit être IMathElement. |
| [`MathFraction`](/slides/python-net/fr/aspose.slides.mathtext/mathfraction/) | Spécifie l'objet fraction, composé d'un numérateur et d'un dénominateur séparés par une barre de fraction.<br/>            La barre de fraction peut être horizontale ou diagonale, selon les propriétés de la fraction.<br/>            L'objet fraction est également utilisé pour représenter la fonction pile, qui place un élément au-dessus d'un autre, sans barre de fraction. |
| [`MathFractionFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathfractionfactory/) | Permet de créer une fraction mathématique |
| [`MathFunction`](/slides/python-net/fr/aspose.slides.mathtext/mathfunction/) | Spécifie une fonction d'un argument. |
| [`MathFunctionFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathfunctionfactory/) | Permet de créer une fonction mathématique |
| [`MathGroupingCharacter`](/slides/python-net/fr/aspose.slides.mathtext/mathgroupingcharacter/) | Spécifie un symbole de groupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments |
| [`MathGroupingCharacterFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Permet de créer un caractère de groupement mathématique |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Spécifie l'objet indice-suscript, qui consiste en une base <br/>            et un indice et un suscript placés à gauche de la base. |
| [`MathLimit`](/slides/python-net/fr/aspose.slides.mathtext/mathlimit/) | Spécifie l'objet Limite, composé de texte sur la ligne de base et de texte de taille réduite immédiatement au-dessus ou en dessous. |
| [`MathLimitFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathlimitfactory/) | Permet de créer IMathLimit |
| [`MathMatrix`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/) | Spécifie l'objet Matrice, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. <br/>            Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. <br/>            Pour placer la matrice entre des crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter).<br/>            Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices. |
| [`MathMatrixFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrixfactory/) | Permet de créer une matrice mathématique |
| [`MathNaryOperator`](/slides/python-net/fr/aspose.slides.mathtext/mathnaryoperator/) | Spécifie un objet mathématique N-aire, tel que la Somme et l'Intégrale.<br/>            Il se compose d'un opérateur, d'une base (ou opérande), et de limites supérieures et inférieures optionnelles. <br/>            Exemples d'opérateurs N-aires : Somme, Union, Intersection, Intégrale |
| [`MathNaryOperatorFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathnaryoperatorfactory/) | Permet de créer IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/fr/aspose.slides.mathtext/mathparagraph/) | Paragraphe mathématique qui est un conteneur pour des blocs mathématiques (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathparagraphfactory/) | Permet de créer un paragraphe mathématique |
| [`MathPhantom`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/) | Représente un objet mathématique fantôme (<m:phant>) qui influence la mise en page de son élément enfant<br/>            sans nécessairement l'afficher. Un fantôme peut masquer son expression de base tout en préservant<br/>            sa largeur, sa hauteur ou sa profondeur afin d'aligner les formules ou de réserver de l'espace. <br/>            La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc et Transp. |
| [`MathPortion`](/slides/python-net/fr/aspose.slides.mathtext/mathportion/) | Représente une portion avec un contexte mathématique à l'intérieur. |
| [`MathRadical`](/slides/python-net/fr/aspose.slides.mathtext/mathradical/) | Spécifie la fonction radicielle, composée d'une base et d'un degré optionnel.<br/>            Exemple d'objet radical : √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathradicalfactory/) | Permet de créer un radical mathématique |
| [`MathRightSubSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Spécifie l'objet indice-suscript, qui consiste en une base <br/>            et un indice et un suscript placés à droite de la base. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Permet de créer IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/) | Spécifie l'objet indice, qui consiste en une base <br/>            et un indice de taille réduite placé en dessous et à droite. |
| [`MathSubscriptElementFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelementfactory/) | Permet de créer IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/) | Spécifie l'objet exposant, qui consiste en une base <br/>            et un exposant de taille réduite placé au-dessus et à droite |
| [`MathSuperscriptElementFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Permet de créer IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/fr/aspose.slides.mathtext/mathematicaltext/) | Texte mathématique |
| [`MathematicalTextFactory`](/slides/python-net/fr/aspose.slides.mathtext/mathematicaltextfactory/) | Permet de créer un élément MathematicalText |

## Énumérations

| Énumération | Description |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimitershape/) | L'emplacement et la taille des délimiteurs par rapport au contenu des opérandes |
| [`MathFractionTypes`](/slides/python-net/fr/aspose.slides.mathtext/mathfractiontypes/) | Types de fractions |
| [`MathFunctionsOfOneArgument`](/slides/python-net/fr/aspose.slides.mathtext/mathfunctionsofoneargument/) | Fonctions mathématiques communes d'un argument |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/fr/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Fonctions mathématiques communes de deux arguments |
| [`MathHorizontalAlignment`](/slides/python-net/fr/aspose.slides.mathtext/mathhorizontalalignment/) | Alignement horizontal |
| [`MathIntegralTypes`](/slides/python-net/fr/aspose.slides.mathtext/mathintegraltypes/) | Types d'intégrales mathématiques |
| [`MathJustification`](/slides/python-net/fr/aspose.slides.mathtext/mathjustification/) | Spécifie la justification du paragraphe mathématique (une série d'instances adjacentes de texte mathématique au sein du même paragraphe) |
| [`MathLimitLocations`](/slides/python-net/fr/aspose.slides.mathtext/mathlimitlocations/) | Emplacement des limites (indice/suscript) dans les opérateurs n-aires. |
| [`MathNaryOperatorTypes`](/slides/python-net/fr/aspose.slides.mathtext/mathnaryoperatortypes/) | Types d'opérateurs n-aires IMathNaryOperator (excluant les intégrales)<br/>            Pour les intégrales [`MathIntegralTypes`](/slides/python-net/fr/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/fr/aspose.slides.mathtext/mathrowspacingrule/) | Type d'espacement vertical entre les colonnes d'une matrice ou d'un tableau |
| [`MathSpacingRules`](/slides/python-net/fr/aspose.slides.mathtext/mathspacingrules/) | Types d'écart (espacement horizontal) entre les colonnes d'une matrice |
| [`MathTopBotPositions`](/slides/python-net/fr/aspose.slides.mathtext/mathtopbotpositions/) | Énumération des positions haut/bas |
| [`MathVerticalAlignment`](/slides/python-net/fr/aspose.slides.mathtext/mathverticalalignment/) | Alignement vertical |