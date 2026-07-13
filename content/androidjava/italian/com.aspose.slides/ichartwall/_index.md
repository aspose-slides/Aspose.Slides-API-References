---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta i muri nei grafici 3D.
type: docs
url: /it/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Rappresenta i muri nei grafici 3D.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getThickness()](#getThickness--) | Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del grafico. |
| [setThickness(int value)](#setThickness-int-) | Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del grafico. |
| [getFormat()](#getFormat--) | Restituisce il riempimento, la linea, l'effetto, gli stili 3D della parete. |
| [getPictureType()](#getPictureType--) | Restituisce o imposta il tipo di immagine. |
| [setPictureType(int value)](#setPictureType-int-) | Restituisce o imposta il tipo di immagine. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del grafico. Lettura/Scrittura int.

**Restituisce:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del grafico. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Restituisce il riempimento, la linea, l'effetto, gli stili 3D della parete. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


Restituisce o imposta il tipo di immagine. Lettura/Scrittura [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Restituisce:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


Restituisce o imposta il tipo di immagine. Lettura/Scrittura [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |