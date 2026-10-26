---
title: MathBox
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica a embalagem lógica de caixa de elemento matemático.
type: docs
url: /pt/com.aspose.slides/mathbox/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Especifica a caixa lógica (empacotamento) de um elemento matemático. Por exemplo, um objeto em caixa pode servir como um emulador de operador com ou sem um ponto de alinhamento, servir como um ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha dentro dele. Por exemplo, o operador \"==\" deve ser colocado em caixa para impedir quebras de linha.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Inicializa MathBox com o elemento especificado como argumento |
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulador de Operador. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulador de Operador. |
| [getNoBreak()](#getNoBreak--) | Sem quebra Esta propriedade especifica a propriedade "unbreakable" na caixa do objeto. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Sem quebra Esta propriedade especifica a propriedade "unbreakable" na caixa do objeto. |
| [getDifferential()](#getDifferential--) | Diferencial Quando verdadeiro, a caixa atua como um diferencial (por exemplo, \\ud835\\udc51\\ud835\\udc65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferencial Quando verdadeiro, a caixa atua como um diferencial (por exemplo, \\ud835\\udc51\\ud835\\udc65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, pontos de alinhamento designados em outras equações podem ser alinhados com ele. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, pontos de alinhamento designados em outras equações podem ser alinhados com ele. |
| [getExplicitBreak()](#getExplicitBreak--) | Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha se quebre no início do objeto box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha se quebre no início do objeto box. |
| [getChildren()](#getChildren--) | Obter elementos filhos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades de Caracteres de Controle |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Inicializa MathBox com o elemento especificado como argumento

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | O elemento base ao qual a caixa é aplicada. Pode ser nulo. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Emulador de Operador. Quando verdadeiro, a caixa e seu conteúdo se comportam como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Retorna:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Emulador de Operador. Quando verdadeiro, a caixa e seu conteúdo se comportam como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


Sem quebra Esta propriedade especifica a propriedade "unbreakable" na caixa do objeto. Quando verdadeiro, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operador que consistem em mais de um operador binário. Quando este elemento não for especificado, quebras podem ocorrer dentro da caixa. Padrão: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Retorna:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


Sem quebra Esta propriedade especifica a propriedade "unbreakable" na caixa do objeto. Quando verdadeiro, nenhuma quebra de linha pode ocorrer dentro da caixa. Isso pode ser importante para emuladores de operador que consistem em mais de um operador binário. Quando este elemento não for especificado, quebras podem ocorrer dentro da caixa. Padrão: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Diferencial Quando verdadeiro, a caixa atua como um diferencial (por exemplo, \\ud835\\udc51\\ud835\\udc65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Retorna:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```


Diferencial Quando verdadeiro, a caixa atua como um diferencial (por exemplo, \\ud835\\udc51\\ud835\\udc65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```


Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Retorna:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```


Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha se quebre no início do objeto box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático. Valores possíveis: 1..255. Padrão: 0 (sem quebra explícita)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Retorna:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```


Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha se quebre no início do objeto box. Especifica o número do operador na linha anterior do texto matemático que deve ser usado como ponto de alinhamento para a linha atual do texto matemático. Valores possíveis: 1..255. Padrão: 0 (sem quebra explícita)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

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


Propriedades de Caracteres de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps