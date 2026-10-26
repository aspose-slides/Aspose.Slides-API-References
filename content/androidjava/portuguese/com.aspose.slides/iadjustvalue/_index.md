---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /pt/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Representa o valor de ajuste de uma forma geométrica. Esses valores afetam a forma da forma.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRawValue()](#getRawValue--) | Obtém ou define o valor de ajuste "como está". |
| [setRawValue(long value)](#setRawValue-long-) | Obtém ou define o valor de ajuste "como está". |
| [getAngleValue()](#getAngleValue--) | Obtém ou define o valor, interpretando-o como ângulo em graus. |
| [setAngleValue(float value)](#setAngleValue-float-) | Obtém ou define o valor, interpretando-o como ângulo em graus. |
| [getName()](#getName--) | Retorna o nome deste valor de ajuste. |
| [getType()](#getType--) | Retorna o tipo do ajuste da forma. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Obtém ou define o valor de ajuste "como está". Leitura/gravação long.

**Retorna:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Obtém ou define o valor de ajuste "como está". Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Obtém ou define o valor, interpretando-o como ângulo em graus. Leitura/gravação float.

**Retorna:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Obtém ou define o valor, interpretando-o como ângulo em graus. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Retorna um nome deste valor de ajuste. Somente leitura String.

**Retorna:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Retorna o tipo do ajuste da forma. Somente leitura [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Retorna:**
int