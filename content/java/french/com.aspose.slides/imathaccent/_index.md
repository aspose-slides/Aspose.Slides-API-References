---
title: IMathAccent
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie la fonction d'accent composée d'une base et d'un diacritique combinant Exemple ud835udc4eu0301
type: docs
url: /fr/com.aspose.slides/imathaccent/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Spécifie la fonction d’accent, composée d’une base et d’un diacritique combinant Exemple : \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | L’argument auquel l’accent a été appliqué |
| [getCharacter()](#getCharacter--) | Caractère d’accent La valeur doit être dans la plage (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valeur par défaut : Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Caractère d’accent La valeur doit être dans la plage (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valeur par défaut : Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

L’argument auquel l’accent a été appliqué

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Renvoie:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Caractère d’accent La valeur doit être dans la plage (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valeur par défaut : Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Renvoie:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Caractère d’accent La valeur doit être dans la plage (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valeur par défaut : Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |