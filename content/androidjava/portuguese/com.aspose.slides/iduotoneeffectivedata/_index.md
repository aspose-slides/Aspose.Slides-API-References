---
title: IDuotoneEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que representa um efeito Duotone.
type: docs
url: /pt/com.aspose.slides/iduotoneeffectivedata/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Objeto imutável que representa um efeito Duotone. Para cada pixel, combina clr1 e clr2 por meio de uma interpolação linear para determinar a nova cor desse pixel.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColor1()](#getColor1--) | Retorna o formato de cor de destino para pixels escuros. |
| [getColor2()](#getColor2--) | Retorna o formato de cor de destino para pixels claros. |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```


Retorna o formato de cor de destino para pixels escuros. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```


Retorna o formato de cor de destino para pixels claros. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer