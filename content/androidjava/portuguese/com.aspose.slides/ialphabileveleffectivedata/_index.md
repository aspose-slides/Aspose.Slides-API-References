---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que representa um efeito Alpha Bi-Level.
type: docs
url: /pt/com.aspose.slides/ialphabileveleffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Objeto imutável que representa um efeito Alpha Bi-Level. Valores de Alpha (Opacidade) menores que o limite são alterados para 0 (totalmente transparente) e valores de alpha maiores ou iguais ao limite são alterados para 100 % (totalmente opaco).
## Métodos

| Método | Descrição |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retorna o limite do efeito. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Retorna o limite do efeito. Somente leitura float.

**Retorna:**
float