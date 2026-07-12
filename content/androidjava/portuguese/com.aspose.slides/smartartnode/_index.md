---
title: SmartArtNode
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um nó de um objeto SmartArt
type: docs
url: /pt/com.aspose.slides/smartartnode/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Representa um nó de um objeto SmartArt
## Métodos

| Método | Descrição |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Retorna coleções de todos os nós filhos do nó atual. |
| [getShapes()](#getShapes--) | Retorna coleções de todas as formas associadas ao nó. |
| [getTextFrame()](#getTextFrame--) | Retorna a caixa de texto do nó. |
| [isAssistant()](#isAssistant--) | Retorna ou define o nó como assistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Retorna ou define o nó como assistente. |
| [getLevel()](#getLevel--) | Retorna o nível de aninhamento do nó. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Retorna o objeto FillFormat que contém as propriedades de formatação de preenchimento para a bala de um nó. |
| [getPosition()](#getPosition--) | Retorna ou define a posição baseada em zero do nó entre os nós irmãos. |
| [setPosition(int value)](#setPosition-int-) | Retorna ou define a posição baseada em zero do nó entre os nós irmãos. |
| [isHidden()](#isHidden--) | Retorna true se este nó for um nó oculto no modelo de dados. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Retorna ou define o tipo de layout do organograma associado ao nó atual. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Retorna ou define o tipo de layout do organograma associado ao nó atual. |
| [remove()](#remove--) | Remove o nó atual. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Retorna coleções de todos os nós filhos do nó atual. Somente leitura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retorna:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Retorna coleções de todas as formas associadas ao nó. Somente leitura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Retorna:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retorna a caixa de texto do nó. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Retorna ou define o nó como assistente. Leitura/Gravação boolean.

**Retorna:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Retorna ou define o nó como assistente. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Retorna o nível de aninhamento do nó. Somente leitura int.

**Retorna:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Retorna o objeto FillFormat que contém as propriedades de formatação de preenchimento para a bala de um nó. Observação: pode retornar null para certos tipos de layout SmartArt que não fornecem balas para nós. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Retorna ou define a posição baseada em zero do nó entre os nós irmãos. Leitura/Gravação int.

**Retorna:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Retorna ou define a posição baseada em zero do nó entre os nós irmãos. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Retorna true se este nó for um nó oculto no modelo de dados. Somente leitura boolean.

**Retorna:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Retorna ou define o tipo de layout do organograma associado ao nó atual. Leitura/Gravação [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Retorna:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Retorna ou define o tipo de layout do organograma associado ao nó atual. Leitura/Gravação [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Remove o nó atual.

**Retorna:**
boolean - true se removido com sucesso, caso contrário false