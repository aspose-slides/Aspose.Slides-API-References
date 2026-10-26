---
title: IBackgroundEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che contiene le proprietà di sfondo effettive.
type: docs
url: /it/com.aspose.slides/ibackgroundeffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

Oggetto immutabile che contiene le proprietà di sfondo effettive.

--------------------

Questa interfaccia è usata insieme all'interfaccia [IBackground](../../com.aspose.slides/ibackground) per restituire i valori di formattazione effettivi con eredità applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Restituisce il formato di riempimento effettivo. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce il formato di effetto effettivo. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Restituisce il formato di riempimento effettivo. Solo lettura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Restituisce:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Restituisce il formato di effetto effettivo. Solo lettura [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Restituisce:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)