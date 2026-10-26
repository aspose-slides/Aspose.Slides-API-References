---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /it/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Rappresenta la rotazione 3D di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRotationX()](#getRotationX--) | Restituisce o imposta il grado di rotazione attorno all'asse X, cioè |
| [setRotationX(byte value)](#setRotationX-byte-) | Restituisce o imposta il grado di rotazione attorno all'asse X, cioè |
| [getRotationY()](#getRotationY--) | Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè |
| [setRotationY(int value)](#setRotationY-int-) | Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè |
| [getPerspective()](#getPerspective--) | Restituisce o imposta il valore di prospettiva (angolo del campo visivo) per i grafici 3D (tra 0 e 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Restituisce o imposta il valore di prospettiva (angolo del campo visivo) per i grafici 3D (tra 0 e 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determina se gli assi del grafico sono ad angolo retto, anziché disegnati in prospettiva. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determina se gli assi del grafico sono ad angolo retto, anziché disegnati in prospettiva. |
| [getDepthPercents()](#getDepthPercents--) | Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). |
| [getHeightPercents()](#getHeightPercents--) | Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Restituisce o imposta il grado di rotazione attorno all'asse X, cioè nella direzione Y per i grafici 3D (tra -90 e 90 gradi). La proprietà corrisponde all’elemento 21.2.2.157 rotX (X Rotation) in ECMA-376 e all’opzione "Y Rotation" in PowerPoint 2007+. Lettura/scrittura byte.

**Restituisce:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Restituisce o imposta il grado di rotazione attorno all'asse X, cioè nella direzione Y per i grafici 3D (tra -90 e 90 gradi). La proprietà corrisponde all’elemento 21.2.2.157 rotX (X Rotation) in ECMA-376 e all’opzione "Y Rotation" in PowerPoint 2007+. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè nella direzione X per i grafici 3D (tra 0 e 360 gradi). La proprietà corrisponde all’elemento 21.2.2.158 rotY (Y Rotation) in ECMA-376 e all’opzione "X Rotation" in PowerPoint 2007+. Lettura/scrittura int.

**Restituisce:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè nella direzione X per i grafici 3D (tra 0 e 360 gradi). La proprietà corrisponde all’elemento 21.2.2.158 rotY (Y Rotation) in ECMA-376 e all’opzione "X Rotation" in PowerPoint 2007+. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Restituisce o imposta il valore di prospettiva (angolo del campo visivo) per i grafici 3D (tra 0 e 100). Ignorato se il valore della proprietà RightAngleAxes è true. Lettura/scrittura byte.

**Restituisce:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Restituisce o imposta il valore di prospettiva (angolo del campo visivo) per i grafici 3D (tra 0 e 100). Ignorato se il valore della proprietà RightAngleAxes è true. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Determina se gli assi del grafico sono ad angolo retto, anziché disegnati in prospettiva. In altre parole determina se gli angoli degli assi sono indipendenti dalla rotazione o dall'elevazione del grafico. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Determina se gli assi del grafico sono ad angolo retto, anziché disegnati in prospettiva. In altre parole determina se gli angoli degli assi sono indipendenti dalla rotazione o dall'elevazione del grafico. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). Lettura/scrittura int.

**Restituisce:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). Lettura/scrittura int.

**Restituisce:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |