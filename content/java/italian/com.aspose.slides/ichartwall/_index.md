---
title: IChartWall
second_title: Aspose.Slides for Java API Reference
description: Rappresenta le pareti sui grafici 3d.
type: docs
url: /it/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Rappresenta le pareti sui grafici 3d.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getThickness()](#getThickness--) | Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del tracciato. |
| [setThickness(int value)](#setThickness-int-) | Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del tracciato. |
| [getFormat()](#getFormat--) | Restituisce il riempimento della parete, la linea, l'effetto, gli stili 3d. |
| [getPictureType()](#getPictureType--) | Restituisce o imposta il tipo di immagine. |
| [setPictureType(int value)](#setPictureType-int-) | Restituisce o imposta il tipo di immagine. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del tracciato. Lettura/Scrittura int.

**Restituisce:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


Restituisce o imposta lo spessore delle pareti come percentuale della dimensione più grande del volume del tracciato. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Restituisce il riempimento della parete, la linea, l'effetto, gli stili 3d. Solo lettura [IFormat](../../com.aspose.slides/iformat).

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