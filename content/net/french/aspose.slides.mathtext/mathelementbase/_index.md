---  
title: MathElementBase
second_title: Aspose.Sildes pour la référence API .NET  
description: Classe de base pour IMathElement avec l'implémentation de certaines méthodes qui sont communes à toutes les classes héritées Utilisation interne uniquement. La classe héritée doit être IMathElement.
type: docs
weight: 8420  
url: /fr/aspose.slides.mathtext/mathelementbase/
---  

## Classe MathElementBase  

Classe de base pour IMathElement avec l'implémentation de certaines méthodes qui sont communes à toutes les classes héritées Utilisation interne uniquement. La classe héritée doit être IMathElement.  

```csharp  
public abstract class MathElementBase : IMathElement  
```  

## Méthodes  

| Nom | Description |  
| --- | --- |  
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Définit un accent (un caractère au-dessus de cet élément) |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Prend la fonction spécifiée en utilisant cette instance comme argument |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Prend la fonction spécifiée en utilisant cette instance comme argument |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Prend la fonction spécifiée en utilisant cette instance comme argument et l'argument supplémentaire spécifié |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Crée une fraction avec ce numérateur et le dénominateur spécifié |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |  
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Enclose un élément mathématique entre parenthèses |  
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Enclose un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Place cet élément dans un groupe en utilisant une accolade ouvrante |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade ouvrante ou autre |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Prend l'intégrale sans limites |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Prend l'intégrale |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | Prend l'intégrale |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prend l'intégrale |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Prend l'intégrale |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Joint un élément mathématique et forme un bloc mathématique |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Joint un texte mathématique et forme un bloc mathématique |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crée un opérateur N-aire |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | Crée un opérateur N-aire |  
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Définit une barre au-dessus de cet élément |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Spécifie la racine mathématique de degré donné à partir de l'argument spécifié. |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Spécifie la racine mathématique de degré donné à partir de l'argument spécifié. |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Prend la limite inférieure |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Prend la limite inférieure |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Crée un indice inférieur |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Crée un indice inférieur |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crée un indice et un exposant à gauche |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Crée un indice et un exposant à gauche |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Crée un indice et un exposant à droite |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Crée un indice et un exposant à droite |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Crée un exposant |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Crée un exposant |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Prend la limite supérieure |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Prend la limite supérieure |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Place cet élément dans une boîte de bord |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Place cet élément dans une boîte de bord |  
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de rupture de ligne, ou être regroupé de manière à ne pas autoriser les sauts de ligne à l'intérieur. |  
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Met dans un tableau vertical |  
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Définit une barre en bas de cet élément |  

### Voir Aussi  

* interface [IMathElement](../imathelement)  
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)  
* assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  