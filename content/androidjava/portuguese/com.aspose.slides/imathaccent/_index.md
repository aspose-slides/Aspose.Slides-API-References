---
title: IMathAccent
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica a função de acento que consiste em uma base e um sinal diacrítico combinante Exemplo ud835udc4eu0301
type: docs
url: /pt/com.aspose.slides/imathaccent/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Especifica a função de acentuação, consistindo de uma base e um sinal diacrítico combinante Exemplo: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | O argumento ao qual o acento foi aplicado |
| [getCharacter()](#getCharacter--) | Caractere de Acento O valor deve estar no intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo Combinado (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Caractere de Acento O valor deve estar no intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo Combinado (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


O argumento ao qual o acento foi aplicado

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Caractere de Acento O valor deve estar no intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo Combinado (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Retorna:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Caractere de Acento O valor deve estar no intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Acento Circunflexo Combinado (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |