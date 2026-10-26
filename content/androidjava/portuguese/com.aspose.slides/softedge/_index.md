---
title: SoftEdge
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um efeito de borda suave.
type: docs
url: /pt/com.aspose.slides/softedge/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representa um efeito de borda suave. As bordas da forma são desfocadas, enquanto o preenchimento não é afetado.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRadius()](#getRadius--) | Especifica o raio de desfoque a ser aplicado nas bordas. |
| [setRadius(double value)](#setRadius-double-) | Especifica o raio de desfoque a ser aplicado nas bordas. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito Soft Edge com a herança aplicada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [SoftEdge](../../com.aspose.slides/softedge) especificado é igual ao [SoftEdge](../../com.aspose.slides/softedge) atual. |
| [hashCode()](#hashCode--) | Serve como uma função hash para um tipo específico. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Especifica o raio de desfoque a ser aplicado nas bordas. Leitura/gravação double.

**Retorna:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Especifica o raio de desfoque a ser aplicado nas bordas. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Obtém os dados efetivos do efeito Soft Edge com a herança aplicada.

**Retorna:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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

Retorna o IPresentationComponent pai. Somente leitura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retorna:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se o [SoftEdge](../../com.aspose.slides/softedge) especificado é igual ao [SoftEdge](../../com.aspose.slides/softedge) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [SoftEdge](../../com.aspose.slides/softedge) a ser comparado. |

**Retorna:**
boolean - true se os objetos são iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como uma função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.