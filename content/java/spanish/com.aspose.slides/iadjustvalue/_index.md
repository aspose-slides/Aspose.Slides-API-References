---
title: IAdjustValue
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa el valor de ajuste de una forma geométrica.
type: docs
url: /es/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Representa el valor de ajuste de una forma geométrica. Estos valores afectan la forma de la figura.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRawValue()](#getRawValue--) | Devuelve o establece el valor de ajuste "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Devuelve o establece el valor de ajuste "as is". |
| [getAngleValue()](#getAngleValue--) | Devuelve o establece el valor, interpretándolo como ángulo en grados. |
| [setAngleValue(float value)](#setAngleValue-float-) | Devuelve o establece el valor, interpretándolo como ángulo en grados. |
| [getName()](#getName--) | Devuelve el nombre de este valor de ajuste. |
| [getType()](#getType--) | Devuelve el tipo de ajuste de la forma. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Devuelve o establece el valor de ajuste "as is". Lectura/escritura long.

**Devuelve:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Devuelve o establece el valor de ajuste "as is". Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Devuelve o establece el valor, interpretándolo como ángulo en grados. Lectura/escritura float.

**Devuelve:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Devuelve o establece el valor, interpretándolo como ángulo en grados. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Devuelve el nombre de este valor de ajuste. Solo lectura String.

**Devuelve:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Devuelve el tipo de ajuste de la forma. Solo lectura [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Devuelve:**
int