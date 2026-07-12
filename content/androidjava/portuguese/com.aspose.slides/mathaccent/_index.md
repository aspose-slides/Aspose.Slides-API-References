---
title: MathAccent
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica a função de acento consistindo em uma base e um marca diacrítica combinada Exemplo ud835udc4eu0301
type: docs
url: /pt/com.aspose.slides/mathaccent/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Especifica a função de acento, consistindo em uma base e um marca diacrítica combinada Exemplo: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Cria um acento matemático aplicando a um elemento matemático especificado com o valor padrão do caractere de acento |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Cria um acento matemático aplicando a um elemento matemático especificado |
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | O argumento ao qual o acento foi aplicado |
| [getCharacter()](#getCharacter--) | Caractere de Acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Circunflexo Combinado (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Caractere de Acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Circunflexo Combinado (U+0302) |
| [getChildren()](#getChildren--) | Obter elementos filhos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades do Caractere de Controle |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Cria um acento matemático aplicando a um elemento matemático especificado com o valor padrão do caractere de acento

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | um elemento matemático para aplicar o acento |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Cria um acento matemático aplicando a um elemento matemático especificado

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático para aplicar o acento |
| accentCharacter | char | caractere de acento |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

O argumento ao qual o acento foi aplicado

--------------------

> ```
> Exemplo:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Caractere de Acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Circunflexo Combinado (U+0302)

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
public final void setCharacter(char value)
```

Caractere de Acento O valor deve estar dentro do intervalo de (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) Valor padrão: Circunflexo Combinado (U+0302)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obter elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriedades do Caractere de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps