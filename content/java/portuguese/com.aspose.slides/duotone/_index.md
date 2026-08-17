---
title: Duotone
second_title: Referência da API Aspose.Slides para Java
description: Representa um efeito Duotone.
type: docs
url: /pt/com.aspose.slides/duotone/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Representa um efeito Duotone. Para cada pixel, combina Color1 e Color2 através de uma interpolação linear para determinar a nova cor desse pixel.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColor1()](#getColor1--) | Retorna o formato de cor de destino para pixels escuros. |
| [getColor2()](#getColor2--) | Retorna o formato de cor de destino para pixels claros. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito Duotone com a herança aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [Duotone](../../com.aspose.slides/duotone) especificado é igual ao [Duotone](../../com.aspose.slides/duotone) atual. |
| [hashCode()](#hashCode--) | Serve como função hash para um tipo específico. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Retorna o formato de cor de destino para pixels escuros. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorno:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Retorna o formato de cor de destino para pixels claros. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorno:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Obtém os dados efetivos do efeito Duotone com a herança aplicada.

**Retorno:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorno:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se o [Duotone](../../com.aspose.slides/duotone) especificado é igual ao [Duotone](../../com.aspose.slides/duotone) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [Duotone](../../com.aspose.slides/duotone) a ser comparado. |

**Retorno:**
boolean - true se os objetos forem iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serve como função hash para um tipo específico.

**Retorno:**
int - Um código hash para o objeto atual.