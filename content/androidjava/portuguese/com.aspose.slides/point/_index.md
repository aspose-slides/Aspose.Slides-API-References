---
title: Point
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa ponto de animação.
type: docs
url: /pt/com.aspose.slides/point/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Representa ponto de animação.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Point()](#Point--) | Construtor padrão. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Cria ponto de animação com tempo, valor e fórmula. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getTime()](#getTime--) | Representa o valor de tempo. |
| [setTime(float value)](#setTime-float-) | Representa o valor de tempo. |
| [getValue()](#getValue--) | Representa o valor do ponto. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Representa o valor do ponto. |
| [getFormula()](#getFormula--) | Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências de propriedade (propriedades suportadas pelo host) por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/escrita String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências de propriedade (propriedades suportadas pelo host) por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/escrita String. |
### Point() {#Point--}
```
public Point()
```

Construtor padrão.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Cria ponto de animação com tempo, valor e fórmula.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| time | float | Valor de tempo. |
| value | java.lang.Object | Valor do ponto. |
| formula | java.lang.String | Fórmula. |

### getTime() {#getTime--}
```
public final float getTime()
```

Representa o valor de tempo. Leitura/escrita float.

**Retorna:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Representa o valor de tempo. Leitura/escrita float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Representa o valor do ponto. Apenas: bool, ColorFormat, float, int, string. Leitura/escrita Object.

**Retorna:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Representa o valor do ponto. Apenas: bool, ColorFormat, float, int, string. Leitura/escrita Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências de propriedade (propriedades suportadas pelo host) por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/escrita String.

**Retorna:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Fórmulas dentro de valores, atributos from, to, by podem ser compostas por: Operadores aritméticos padrão: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionais: 'abs', 'min', 'max', '?' (if) Operadores de comparação: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referências de propriedade (propriedades suportadas pelo host) por exemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Leitura/escrita String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |