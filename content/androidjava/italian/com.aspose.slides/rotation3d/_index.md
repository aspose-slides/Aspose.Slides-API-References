---
title: Rotation3D
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta la rotazione 3D di un grafico.
type: docs
url: /it/com.aspose.slides/rotation3d/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Rappresenta la rotazione 3D di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRotationX()](#getRotationX--) | Restituisce o imposta il grado di rotazione attorno all'asse X, cioè |
| [setRotationX(byte value)](#setRotationX-byte-) | Restituisce o imposta il grado di rotazione attorno all'asse X, cioè |
| [getRotationY()](#getRotationY--) | Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè |
| [setRotationY(int value)](#setRotationY-int-) | Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè |
| [getPerspective()](#getPerspective--) | Restituisce o imposta il valore di prospettiva (angolo di campo visivo) per grafici 3D (tra 0 e 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Restituisce o imposta il valore di prospettiva (angolo di campo visivo) per grafici 3D (tra 0 e 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determina se gli assi del grafico sono ad angolo retto, invece di essere disegnati in prospettiva. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determina se gli assi del grafico sono ad angolo retto, invece di essere disegnati in prospettiva. |
| [getDepthPercents()](#getDepthPercents--) | Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). |
| [getHeightPercents()](#getHeightPercents--) | Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Restituisce o imposta il grado di rotazione attorno all'asse X, cioè nella direzione Y per i grafici 3D (tra -90 e 90 gradi). La proprietà corrisponde all'elemento 21.2.2.157 rotX (X Rotation) in ECMA-376 e all'opzione "Y Rotation" in PowerPoint 2007+. Lettura/Scrittura byte.

**Restituisce:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Restituisce o imposta il grado di rotazione attorno all'asse X, cioè nella direzione Y per i grafici 3D (tra -90 e 90 gradi). La proprietà corrisponde all'elemento 21.2.2.157 rotX (X Rotation) in ECMA-376 e all'opzione "Y Rotation" in PowerPoint 2007+. Lettura/Scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè nella direzione X per i grafici 3D (tra 0 e 360 gradi). La proprietà corrisponde all'elemento 21.2.2.158 rotY (Y Rotation) in ECMA-376 e all'opzione "X Rotation" in PowerPoint 2007+. Lettura/Scrittura int.

**Restituisce:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Restituisce o imposta il grado di rotazione attorno all'asse Y, cioè nella direzione X per i grafici 3D (tra 0 e 360 gradi). La proprietà corrisponde all'elemento 21.2.2.158 rotY (Y Rotation) in ECMA-376 e all'opzione "X Rotation" in PowerPoint 2007+. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Restituisce o imposta il valore di prospettiva (angolo di campo visivo) per i grafici 3D (tra 0 e 240). Ignorato se il valore della proprietà RightAngleAxes è true. Lettura/Scrittura byte.

**Restituisce:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Restituisce o imposta il valore di prospettiva (angolo di campo visivo) per i grafici 3D (tra 0 e 240). Ignorato se il valore della proprietà RightAngleAxes è true. Lettura/Scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Determina se gli assi del grafico sono ad angolo retto, invece di essere disegnati in prospettiva. In altre parole determina se gli angoli degli assi del grafico sono indipendenti dalla rotazione o elevazione del grafico. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Determina se gli assi del grafico sono ad angolo retto, invece di essere disegnati in prospettiva. In altre parole determina se gli angoli degli assi del grafico sono indipendenti dalla rotazione o elevazione del grafico. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). Lettura/Scrittura int.

**Restituisce:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Restituisce o imposta la profondità di un grafico 3D come percentuale della larghezza del grafico (tra 20 e 2000 percento). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). Lettura/Scrittura int.

**Restituisce:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Specifica l'altezza di un grafico 3-D come percentuale della larghezza del grafico (tra 5 e 500 percento). Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Sola lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject