---
title: IBiLevelEffectiveData
second_title: Referência da API Java do Aspose.Slides para Android
description: Objeto imutável que representa um efeito Bi-Level preto/branco.
type: docs
url: /pt/com.aspose.slides/ibileveleffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Objeto imutável que representa um efeito Bi-Level (preto/branco). Cores de entrada cuja luminância é menor que o valor de limiar especificado são alteradas para preto. Cores de entrada cuja luminância é maior ou igual ao valor especificado são definidas como branco. Os valores de efeito alfa não são afetados por este efeito.
## Métodos

| Método | Descrição |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retorna o valor do limiar. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Retorna o valor do limiar. Float somente leitura.

**Retorna:**
float