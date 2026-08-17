---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
url: /pt/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Representa um nó de um diagrama SmartArt.
## Métodos

| Método | Descrição |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Retorna coleções de todos os nós filhos do nó atual. |
| [getShapes()](#getShapes--) | Retorna coleções de todas as formas associadas ao nó. |
| [getTextFrame()](#getTextFrame--) | Retorna ou define o texto do nó. |
| [isAssistant()](#isAssistant--) | Retorna ou define o nó como assistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Retorna ou define o nó como assistente. |
| [getLevel()](#getLevel--) | Retorna o nível de aninhamento do nó. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Retorna o objeto FillFormat que contém as propriedades de formatação de preenchimento para a marca de um nó. |
| [getPosition()](#getPosition--) | Retorna ou define a posição baseada em zero do nó entre os nós irmãos. |
| [setPosition(int value)](#setPosition-int-) | Retorna ou define a posição baseada em zero do nó entre os nós irmãos. |
| [isHidden()](#isHidden--) | Retorna true se este nó for um nó oculto no modelo de dados. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Retorna ou define o tipo de layout do organograma associado ao nó atual. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Retorna ou define o tipo de layout do organograma associado ao nó atual. |
| [remove()](#remove--) | Remove o nó atual. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Retorna coleções de todos os nós filhos do nó atual. Somente leitura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retorna:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Retorna coleções de todas as formas associadas ao nó. Somente leitura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Retorna:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Retorna ou define o texto do nó. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Retorna ou define o nó como assistente. Leitura/gravação boolean.

**Retorna:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Retorna ou define o nó como assistente. Leitura/gravação boolean.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Retorna o nível de aninhamento do nó. Somente leitura int.

**Retorna:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Retorna o objeto FillFormat que contém as propriedades de formatação de preenchimento para a marca de um nó. Nota: pode retornar null para certos tipos de layout SmartArt que não fornecem marcadores para nós. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Retorna ou define a posição baseada em zero do nó entre os nós irmãos. Leitura/gravação int.

**Retorna:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Retorna ou define a posição baseada em zero do nó entre os nós irmãos. Leitura/gravação int.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Retorna true se este nó for um nó oculto no modelo de dados. Somente leitura boolean.

**Retorna:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Retorna ou define o tipo de layout do organograma associado ao nó atual. Leitura/gravação [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Retorna:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Retorna ou define o tipo de layout do organograma associado ao nó atual. Leitura/gravação [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public abstract boolean remove()
```


Remove o nó atual.

**Retorna:**
boolean - true if removed succesfully, otherwise false.