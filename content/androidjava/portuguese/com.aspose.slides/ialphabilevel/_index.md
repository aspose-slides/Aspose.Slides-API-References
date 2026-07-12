---
title: IAlphaBiLevel
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um efeito Alpha Bi-Level.
type: docs
url: /pt/com.aspose.slides/ialphabilevel/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Representa um efeito Alpha Bi-Level. Valores Alpha (Opacidade) menores que o limiar são alterados para 0 (totalmente transparente) e valores alpha maiores ou iguais ao limiar são alterados para 100% (totalmente opaco).

--------------------

Use ImageTransformOperationFactory para criar instâncias em COM.
## Métodos

| Método | Descrição |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retorna o limiar do efeito. |
| [setThreshold(float value)](#setThreshold-float-) | Retorna o limiar do efeito. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Retorna o limiar do efeito. Leitura/gravação float.

**Retorna:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Retorna o limiar do efeito. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |