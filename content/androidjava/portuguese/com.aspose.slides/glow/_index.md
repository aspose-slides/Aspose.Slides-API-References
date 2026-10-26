---
title: Glow
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um efeito Glow no qual um contorno borrado de cor é adicionado fora das bordas do objeto.
type: docs
url: /pt/com.aspose.slides/glow/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representa um efeito Glow, no qual um contorno borrado de cor é adicionado fora das bordas do objeto.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRadius()](#getRadius--) | Raio. |
| [setRadius(double value)](#setRadius-double-) | Raio. |
| [getColor()](#getColor--) | Formato de cor. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito Glow com a herança aplicada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [Glow](../../com.aspose.slides/glow) especificado é igual ao [Glow](../../com.aspose.slides/glow) atual. |
| [hashCode()](#hashCode--) | Serve como uma função hash para um tipo específico. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Raio. Leitura/Gravação double.

**Retorna:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Raio. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Formato de cor. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Obtém os dados efetivos do efeito Glow com a herança aplicada.

**Retorna:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Retorna o pai IPresentationComponent. Somente leitura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retorna:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se o [Glow](../../com.aspose.slides/glow) especificado é igual ao [Glow](../../com.aspose.slides/glow) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [Glow](../../com.aspose.slides/glow) a comparar. |

**Retorna:**
boolean - true se os objetos são iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serve como uma função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.