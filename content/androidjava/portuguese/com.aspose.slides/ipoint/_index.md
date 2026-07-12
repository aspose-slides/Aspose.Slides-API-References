---
title: IPoint
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa ponto de animação.
type: docs
url: /pt/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Representa ponto de animação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTime()](#getTime--) | Representa valor de tempo. |
| [setTime(float value)](#setTime-float-) | Representa valor de tempo. |
| [getValue()](#getValue--) | Representa valor de ponto. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Representa valor de ponto. |
| [getFormula()](#getFormula--) | Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências a propriedades (propriedades suportadas pelo host), por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/gravação String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências a propriedades (propriedades suportadas pelo host), por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/gravação String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Representa valor de tempo. Leitura/gravação float.

**Retorna:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Representa valor de tempo. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Representa valor de ponto. Somente: bool, ColorFormat, float, int, string. Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Representa valor de ponto. Somente: bool, ColorFormat, float, int, string. Leitura/gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências a propriedades (propriedades suportadas pelo host), por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/gravação String.

**Retorna:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências a propriedades (propriedades suportadas pelo host), por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |