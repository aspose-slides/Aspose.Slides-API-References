---
title: PVIObject
second_title: Aspose.Slides para Android via Referência da API Java
description: Encapsula a infraestrutura básica de serviço para objetos que podem ser objeto de herança de valor de propriedade.
type: docs
url: /pt/com.aspose.slides/pviobject/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Encapsula a infraestrutura básica de serviço para objetos que podem ser objeto de herança de valor de propriedade.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Compara com o objeto especificado. |
| [hashCode()](#hashCode--) | Retorna o código hash. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Retorna o IPresentationComponent pai. Somente leitura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retorna:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Retorna:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Retorna o slide base. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Retorna a apresentação. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compara com o objeto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | Objeto a ser comparado. |

**Retorna:**
boolean - True se os objetos são iguais, caso contrário false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Retorna o código hash.

**Retorna:**
int - Código hash.