---
title: IColorReplaceEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che rappresenta un effetto di sostituzione colore.
type: docs
url: /it/com.aspose.slides/icolorreplaceeffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorReplaceEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto di sostituzione colore. Tutti i colori dell'effetto vengono cambiati in un colore fisso. I valori alfa non sono influenzati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Restituisce il formato colore che sostituirà il colore di ogni pixel. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Restituisce il formato colore che sostituirà il colore di ogni pixel. Sola lettura java.awt.Color.

**Restituisce:**
java.awt.Color