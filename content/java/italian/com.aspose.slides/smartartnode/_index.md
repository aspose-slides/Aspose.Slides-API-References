---
title: SmartArtNode
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un nodo di un oggetto SmartArt
type: docs
url: /it/com.aspose.slides/smartartnode/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Rappresenta un nodo di un oggetto SmartArt
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Restituisce le collezioni di tutti i nodi figli del nodo corrente. |
| [getShapes()](#getShapes--) | Restituisce le collezioni di tutte le forme associate al nodo. |
| [getTextFrame()](#getTextFrame--) | Restituisce il frame di testo del nodo. |
| [isAssistant()](#isAssistant--) | Restituisce o imposta il nodo come assistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Restituisce o imposta il nodo come assistente. |
| [getLevel()](#getLevel--) | Restituisce il livello di annidamento del nodo. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per il punto elenco di un nodo. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione basata su zero del nodo tra i nodi fratelli. |
| [setPosition(int value)](#setPosition-int-) | Restituisce o imposta la posizione basata su zero del nodo tra i nodi fratelli. |
| [isHidden()](#isHidden--) | Restituisce true se questo nodo è un nodo nascosto nel modello dei dati. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. |
| [remove()](#remove--) | Rimuove il nodo corrente. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Restituisce le collezioni di tutti i nodi figli del nodo corrente. Solo lettura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Restituisce:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Restituisce le collezioni di tutte le forme associate al nodo. Solo lettura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Restituisce:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Restituisce il frame di testo del nodo. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Restituisce o imposta il nodo come assistente. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Restituisce o imposta il nodo come assistente. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Restituisce il livello di annidamento del nodo. Solo lettura int.

**Restituisce:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per il punto elenco di un nodo. Nota: può restituire null per alcuni tipi di layout SmartArt che non forniscono punti elenco per i nodi. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Restituisce o imposta la posizione basata su zero del nodo tra i nodi fratelli. Lettura/scrittura int.

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Restituisce o imposta la posizione basata su zero del nodo tra i nodi fratelli. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Restituisce true se questo nodo è un nodo nascosto nel modello dei dati. Solo lettura boolean.

**Restituisce:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. Lettura/scrittura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Restituisce:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. Lettura/scrittura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Rimuove il nodo corrente.

**Restituisce:**
boolean - true se rimosso con successo, altrimenti false