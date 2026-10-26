---
title: ISmartArt
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um diagrama SmartArt.
type: docs
url: /pt/com.aspose.slides/ismartart/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Representa um diagrama SmartArt.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Retorna coleções de todos os nós no objeto SmartArt. |
| [getNodes()](#getNodes--) | Retorna coleções de nós raiz no objeto SmartArt. |
| [getLayout()](#getLayout--) | Retorna ou define o layout do objeto SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Retorna ou define o layout do objeto SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Retorna ou define o estilo rápido do objeto SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Retorna ou define o estilo rápido do objeto SmartArt. |
| [getColorStyle()](#getColorStyle--) | Retorna ou define o estilo de cor do objeto SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Retorna ou define o estilo de cor do objeto SmartArt. |
| [isReversed()](#isReversed--) | Retorna ou define o estado do diagrama SmartArt em relação a (da esquerda para a direita) LTR ou (da direita para a esquerda) RTL, se o diagrama suportar inversão. |
| [setReversed(boolean value)](#setReversed-boolean-) | Retorna ou define o estado do diagrama SmartArt em relação a (da esquerda para a direita) LTR ou (da direita para a esquerda) RTL, se o diagrama suportar inversão. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Retorna coleções de todos os nós no objeto SmartArt. Somente leitura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retorna:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Retorna coleções de nós raiz no objeto SmartArt. Somente leitura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retorna:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Retorna ou define o layout do objeto SmartArt. Leitura/gravação [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Retorna:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Retorna ou define o layout do objeto SmartArt. Leitura/gravação [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Retorna ou define o estilo rápido do objeto SmartArt. Leitura/gravação [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Retorna:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Retorna ou define o estilo rápido do objeto SmartArt. Leitura/gravação [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Retorna ou define o estilo de cor do objeto SmartArt. Leitura/gravação [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Retorna:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Retorna ou define o estilo de cor do objeto SmartArt. Leitura/gravação [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Retorna ou define o estado do diagrama SmartArt em relação a (da esquerda para a direita) LTR ou (da direita para a esquerda) RTL, se o diagrama suportar inversão. Leitura/gravação boolean.

**Retorna:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Retorna ou define o estado do diagrama SmartArt em relação a (da esquerda para a direita) LTR ou (da direita para a esquerda) RTL, se o diagrama suportar inversão. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |