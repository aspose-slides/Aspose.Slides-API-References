---
title: IBlur
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um efeito de Desfoque que é aplicado a toda a forma, incluindo seu preenchimento.
type: docs
url: /pt/com.aspose.slides/iblur/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Representa um efeito de Desfoque que é aplicado a toda a forma, incluindo seu preenchimento. Todos os canais de cor, incluindo alfa, são afetados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRadius()](#getRadius--) | Retorna ou define o raio de desfoque. |
| [setRadius(double value)](#setRadius-double-) | Retorna ou define o raio de desfoque. |
| [getGrow()](#getGrow--) | Determina se os limites do objeto devem ser ampliados como resultado do desfoque. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determina se os limites do objeto devem ser ampliados como resultado do desfoque. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Retorna ou define o raio de desfoque. Leitura/gravação double.

**Retorna:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Retorna ou define o raio de desfoque. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Determina se os limites do objeto devem ser ampliados como resultado do desfoque. True indica que os limites são ampliados enquanto false indica que não são. Leitura/gravação boolean.

**Retorna:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Determina se os limites do objeto devem ser ampliados como resultado do desfoque. True indica que os limites são ampliados enquanto false indica que não são. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |