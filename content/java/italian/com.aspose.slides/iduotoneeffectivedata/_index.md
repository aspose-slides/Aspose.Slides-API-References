---
title: IDuotoneEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che rappresenta un effetto Duotono.
type: docs
url: /it/com.aspose.slides/iduotoneeffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto Duotono. Per ogni pixel, combina clr1 e clr2 mediante un'interpolazione lineare per determinare il nuovo colore di quel pixel.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor1()](#getColor1--) | Restituisce il formato colore di destinazione per i pixel scuri. |
| [getColor2()](#getColor2--) | Restituisce il formato colore di destinazione per i pixel chiari. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```

Restituisce il formato colore di destinazione per i pixel scuri. Solo lettura java.awt.Color.

**Restituisce:**  
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```

Restituisce il formato colore di destinazione per i pixel chiari. Solo lettura java.awt.Color.

**Restituisce:**  
java.awt.Color