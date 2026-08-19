---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un nodo di un diagramma SmartArt.
type: docs
url: /it/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Rappresenta un nodo di un diagramma SmartArt.
## Metodi

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Restituisce le collezioni di tutti i nodi figli del nodo corrente. |
| [getShapes()](#getShapes--) | Restituisce le collezioni di tutte le forme associate al nodo. |
| [getTextFrame()](#getTextFrame--) | Restituisce o imposta il testo del nodo. |
| [isAssistant()](#isAssistant--) | Restituisce o imposta il nodo come assistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Restituisce o imposta il nodo come assistente. |
| [getLevel()](#getLevel--) | Restituisce il livello di nidificazione del nodo. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per un punto elenco del nodo. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione a base zero del nodo tra i nodi fratelli. |
| [setPosition(int value)](#setPosition-int-) | Restituisce o imposta la posizione a base zero del nodo tra i nodi fratelli. |
| [isHidden()](#isHidden--) | Restituisce true se questo nodo è un nodo nascosto nel modello dei dati. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. |
| [remove()](#remove--) | Rimuove il nodo corrente. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Restituisce le collezioni di tutti i nodi figli del nodo corrente. Solo lettura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Restituisce le collezioni di tutte le forme associate al nodo. Solo lettura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returns:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Restituisce o imposta il testo del nodo. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Restituisce o imposta il nodo come assistente. Lettura/scrittura boolean.

**Returns:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Restituisce o imposta il nodo come assistente. Lettura/scrittura boolean.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Restituisce il livello di nidificazione del nodo. Solo lettura int.

**Returns:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per un punto elenco del nodo. Nota: può restituire null per alcuni tipi di layout SmartArt che non forniscono punti elenco per i nodi. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Restituisce o imposta la posizione a base zero del nodo tra i nodi fratelli. Lettura/scrittura int.

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Restituisce o imposta la posizione a base zero del nodo tra i nodi fratelli. Lettura/scrittura int.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Restituisce true se questo nodo è un nodo nascosto nel modello dei dati. Solo lettura boolean.

**Returns:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. Lettura/scrittura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returns:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. Lettura/scrittura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Rimuove il nodo corrente.

**Returns:**
boolean - true se rimosso con successo, altrimenti false.