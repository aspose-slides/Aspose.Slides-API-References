---
title: IBlurEffectiveData
second_title: Aspose.Slides para Referência da API Java
description: Objeto imutável que representa um efeito de Blur aplicado a toda a forma, incluindo seu preenchimento.
type: docs
url: /pt/com.aspose.slides/iblureffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Objeto imutável que representa um efeito de Blur que é aplicado a toda a forma, incluindo seu preenchimento. Todos os canais de cor, incluindo alfa, são afetados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRadius()](#getRadius--) | Retorna ou define o raio do blur. |
| [getGrow()](#getGrow--) | Determina se os limites do objeto devem ser ampliados como resultado do blur. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Retorna ou define o raio do blur. Somente leitura double.

**Retorna:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Determina se os limites do objeto devem ser ampliados como resultado do blur. True indica que os limites são ampliados enquanto false indica que não são. Somente leitura boolean.

**Retorna:**
boolean