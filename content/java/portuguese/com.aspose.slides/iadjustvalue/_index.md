---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
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
| [getRawValue()](#getRawValue--) | Retorna ou define o valor de ajuste “as is”. |
| [setRawValue(long value)](#setRawValue-long-) | Retorna ou define o valor de ajuste “as is”. |
| [getAngleValue()](#getAngleValue--) | Retorna ou define o valor, interpretando-o como ângulo em graus. |
| [setAngleValue(float value)](#setAngleValue-float-) | Retorna ou define o valor, interpretando-o como ângulo em graus. |
| [getName()](#getName--) | Retorna um nome deste valor de ajuste. |
| [getType()](#getType--) | Retorna o tipo do ajuste da forma. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Retorna ou define o valor de ajuste “as is”. Leitura/gravação long.

**Retorna:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Retorna ou define o valor de ajuste “as is”. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Retorna ou define o valor, interpretando-o como ângulo em graus. Leitura/gravação float.

**Retorna:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Retorna ou define o valor, interpretando-o como ângulo em graus. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Retorna o nome deste valor de ajuste. Somente leitura String.

**Retorna:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Retorna o tipo do ajuste da forma. Somente leitura [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Retorna:**
int