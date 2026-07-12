---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
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
| [getChildNodes()](#getChildNodes--) | Returns collections of all child nodes of current node. |
| [getShapes()](#getShapes--) | Returns collections of all shapes associated with the node. |
| [getTextFrame()](#getTextFrame--) | Returns or sets text of the node. |
| [isAssistant()](#isAssistant--) | Returns or sets the node as assistant. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Returns or sets the node as assistant. |
| [getLevel()](#getLevel--) | Returns nesting level of the node. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a node bullet. |
| [getPosition()](#getPosition--) | Returns or sets zero-based position of the node among sibling nodes. |
| [setPosition(int value)](#setPosition-int-) | Returns or sets zero-based position of the node among sibling nodes. |
| [isHidden()](#isHidden--) | Returns true if this node is a hidden node in the data model. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Returns or sets organization chart layout type associated with current node. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Returns or sets organization chart layout type associated with current node. |
| [remove()](#remove--) | Remove current node. |
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
| Parâmetro | Tipo | Descrição |
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


Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para o marcador de um nó. Observação: pode retornar null para certos tipos de layout SmartArt que não fornecem marcadores para nós. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

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
| Parâmetro | Tipo | Descrição |
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


Retorna ou define o tipo de layout de organograma associado ao nó atual. Leitura/gravação [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Retorna:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Retorna ou define o tipo de layout de organograma associado ao nó atual. Leitura/gravação [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


Remove o nó atual.

**Retorna:**
boolean - true se removido com sucesso, caso contrário false.