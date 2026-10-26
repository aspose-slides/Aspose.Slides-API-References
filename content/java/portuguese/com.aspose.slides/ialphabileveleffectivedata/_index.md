---
title: IAlphaBiLevelEffectiveData
second_title: Referência da API Aspose.Slides para Java
description: Objeto imutável que representa um efeito Alpha Bi-Level.
type: docs
url: /pt/com.aspose.slides/ialphabileveleffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Objeto imutável que representa um efeito Alpha Bi-Level. Valores Alpha (Opacidade) menores que o limiar são alterados para 0 (totalmente transparente) e valores alpha maiores ou iguais ao limiar são alterados para 100% (totalmente opaco).
## Métodos

| Método | Descrição |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retorna o limiar do efeito. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Retorna o limiar do efeito. Float somente leitura.

**Retorno:**
float