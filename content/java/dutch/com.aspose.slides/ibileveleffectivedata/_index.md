---
title: IBiLevelEffectiveData
second_title: Aspose.Slides voor Java API Referentie
description: Onveranderlijk object dat een Bi-Level zwart/wit effect vertegenwoordigt.
type: docs
url: /nl/com.aspose.slides/ibileveleffectivedata/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Onveranderlijk object dat een Bi-Level (zwart/wit) effect vertegenwoordigt. Invoerkleuren waarvan de luminantie lager is dan de opgegeven drempelwaarde worden veranderd naar zwart. Invoerkleuren waarvan de luminantie groter dan of gelijk aan de opgegeven waarde is, worden wit. De alfawaarde-effecten blijven onaangetast door dit effect.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retourneert de drempelwaarde. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Retourneert de drempelwaarde. Alleen-lezen float.

**Retour:**
float