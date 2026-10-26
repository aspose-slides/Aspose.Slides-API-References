---
title: IColorChangeEffectiveData
second_title: Riferimento API Aspose.Slides per Java
description: Oggetto immutabile che rappresenta un effetto di cambio colore.
type: docs
url: /it/com.aspose.slides/icolorchangeeffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto di cambio colore. Le istanze di FromColor sono sostituite con istanze di ToColor.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFromColor()](#getFromColor--) | Colore che sarà sostituito. |
| [getToColor()](#getToColor--) | Colore che sostituirà. |
| [getUseAlpha()](#getUseAlpha--) | Restituisce un valore booleano che determina se il componente alfa deve essere usato. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Colore che sarà sostituito. Solo lettura java.awt.Color.

**Restituisce:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Colore che sostituirà. Solo lettura java.awt.Color.

**Restituisce:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Restituisce un valore booleano che determina se il componente alfa deve essere usato. Solo lettura boolean.

**Restituisce:**
boolean