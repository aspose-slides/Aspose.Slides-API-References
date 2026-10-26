---
title: IAdjustValue
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa un valor de ajuste de una forma geométrica.
type: docs
url: /es/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Representa un valor de ajuste de una forma geométrica. Estos valores afectan la forma de la figura.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRawValue()](#getRawValue--) | Devuelve o establece el valor de ajuste "tal cual". |
| [setRawValue(long value)](#setRawValue-long-) | Devuelve o establece el valor de ajuste "tal cual". |
| [getAngleValue()](#getAngleValue--) | Devuelve o establece el valor, interpretándolo como ángulo en grados. |
| [setAngleValue(float value)](#setAngleValue-float-) | Devuelve o establece el valor, interpretándolo como ángulo en grados. |
| [getName()](#getName--) | Devuelve el nombre de este valor de ajuste. |
| [getType()](#getType--) | Devuelve el tipo del ajuste de la forma. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Devuelve o establece el valor de ajuste "tal cual". Lectura/escritura long.

**Returns:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Devuelve o establece el valor de ajuste "tal cual". Lectura/escritura long.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Devuelve o establece el valor, interpretándolo como ángulo en grados. Lectura/escritura float.

**Returns:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Devuelve o establece el valor, interpretándolo como ángulo en grados. Lectura/escritura float.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Devuelve el nombre de este valor de ajuste. Solo lectura String.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Devuelve el tipo del ajuste de la forma. Solo lectura [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Returns:**
int