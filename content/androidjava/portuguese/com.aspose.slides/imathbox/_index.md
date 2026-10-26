---
title: IMathBox
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o empacotamento lógico de caixa de elemento matemático.
type: docs
url: /pt/com.aspose.slides/imathbox/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Especifica a caixa lógica (empacotamento) de elemento matemático. Por exemplo, um objeto em caixa pode servir como um emulador de operador com ou sem um ponto de alinhamento, servir como um ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha dentro dele. Por exemplo, o operador "==" deve ser colocado em caixa para impedir quebras de linha.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulador de Operador. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulador de Operador. |
| [getNoBreak()](#getNoBreak--) | Sem quebra. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Sem quebra. |
| [getDifferential()](#getDifferential--) | Diferencial. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferencial. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, os pontos de alinhamento designados em outras equações podem ser alinhados com ele. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, os pontos de alinhamento designados em outras equações podem ser alinhados com ele. |
| [getExplicitBreak()](#getExplicitBreak--) | Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```


**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Emulador de Operador. Quando verdadeiro, a caixa e seu conteúdo comportam-se como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```


**Retorna:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Emulador de Operador. Quando verdadeiro, a caixa e seu conteúdo comportam-se como um único operador e herdam as propriedades de um operador. Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores. Emuladores de Operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='. Valor padrão: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Sem quebra. Esta propriedade especifica a propriedade “inquebrável” na caixa do objeto. Quando verdadeiro, nenhuma quebra de linha pode ocorrer dentro da caixa. Isto pode ser importante para emuladores de operador que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Retorna:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Sem quebra. Esta propriedade especifica a propriedade “inquebrável” na caixa do objeto. Quando verdadeiro, nenhuma quebra de linha pode ocorrer dentro da caixa. Isto pode ser importante para emuladores de operador que consistem em mais de um operador binário. Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa. Padrão: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Diferencial. Quando verdadeiro, a caixa funciona como um diferencial (por exemplo, \\ud835\\udc51\\ud835\\udc65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

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
public abstract void setDifferential(boolean value)
```

Diferencial. Quando verdadeiro, a caixa funciona como um diferencial (por exemplo, \\ud835\\udc51\\ud835\\udc65 em um integrando), e recebe o espaçamento horizontal apropriado para o diferencial matemático. Padrão: false

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
public abstract boolean getAlignmentPoint()
```

Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, os pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false

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
public abstract void setAlignmentPoint(boolean value)
```

Quando verdadeiro, este emulador de operador serve como um ponto de alinhamento; isto é, os pontos de alinhamento designados em outras equações podem ser alinhados com ele. Padrão: false

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
public abstract byte getExplicitBreak()
```

Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. Especifica o número do operador na linha anterior de texto matemático que deverá ser usado como ponto de alinhamento para a linha atual de texto matemático. Valores possíveis: 1..255 Padrão: 0 (nenhuma quebra explícita)

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
public abstract void setExplicitBreak(byte value)
```

Quebra explícita especifica se há uma quebra de linha no início do objeto Box, de modo que a linha seja quebrada no início do objeto Box. Especifica o número do operador na linha anterior de texto matemático que deverá ser usado como ponto de alinhamento para a linha atual de texto matemático. Valores possíveis: 1..255 Padrão: 0 (nenhuma quebra explícita)

--------------------

> ```
> Exemplo:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |