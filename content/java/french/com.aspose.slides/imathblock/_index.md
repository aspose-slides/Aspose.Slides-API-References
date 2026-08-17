---
title: IMathBlock
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie une instance de texte mathématique contenue dans un MathParagraph et qui commence sur une ligne séparée.
type: docs
url: /fr/com.aspose.slides/imathblock/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur une ligne séparée. Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d'équations ou d'expressions et les formules, sont représentées par un bloc mathématique.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Délimite tous les éléments enfants avec le caractère séparateur (sans les crochets) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres comme cadre et les délimite avec un caractère séparateur |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Joint un autre bloc mathématique à celui-ci |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Enregistre le contenu de ce [IMathBlock](../../com.aspose.slides/imathblock) au format MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Délimite tous les éléments enfants avec le caractère séparateur (sans les crochets)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | Caractère utilisé comme séparateur |

**Retour :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instance de l'élément IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres comme cadre et les délimite avec un caractère séparateur

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (généralement le crochet ouvrant) |
| endingCharacter | char | Caractère de fin (généralement le crochet fermant) |
| separatorCharacter | char | Caractère séparateur |

**Retour :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les caractères spécifiés comme cadre et délimiteur
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Joint un autre bloc mathématique à celui-ci

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Le bloc de jointure |

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - ce bloc mathématique après la jointure
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Enregistre le contenu de ce [IMathBlock](../../com.aspose.slides/imathblock) au format MathML

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |