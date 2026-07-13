---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta un nodo di un diagramma SmartArt.
type: docs
url: /it/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Rappresenta un nodo di un diagramma SmartArt.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Restituisce le raccolte di tutti i nodi figlio del nodo corrente. |
| [getShapes()](#getShapes--) | Restituisce le raccolte di tutte le forme associate al nodo. |
| [getTextFrame()](#getTextFrame--) | Restituisce o imposta il testo del nodo. |
| [isAssistant()](#isAssistant--) | Restituisce o imposta il nodo come assistente. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Restituisce o imposta il nodo come assistente. |
| [getLevel()](#getLevel--) | Restituisce il livello di nidificazione del nodo. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per il pallino del nodo. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione a indice zero del nodo tra i nodi fratelli. |
| [setPosition(int value)](#setPosition-int-) | Restituisce o imposta la posizione a indice zero del nodo tra i nodi fratelli. |
| [isHidden()](#isHidden--) | Restituisce true se questo nodo è un nodo nascosto nel modello dati. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. |
| [remove()](#remove--) | Rimuove il nodo corrente. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Restituisce le raccolte di tutti i nodi figlio del nodo corrente. Solo lettura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Restituisce:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Restituisce le raccolte di tutte le forme associate al nodo. Solo lettura [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Restituisce:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Restituisce o imposta il testo del nodo. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Restituisce o imposta il nodo come assistente. Lettura/Scrittura booleano.

**Restituisce:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Restituisce o imposta il nodo come assistente. Lettura/Scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Restituisce il livello di nidificazione del nodo. Solo lettura int.

**Restituisce:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per il pallino del nodo. Nota: può restituire null per alcuni tipi di layout SmartArt che non forniscono pallini per i nodi. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Restituisce o imposta la posizione a indice zero del nodo tra i nodi fratelli. Lettura/Scrittura int.

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Restituisce o imposta la posizione a indice zero del nodo tra i nodi fratelli. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Restituisce true se questo nodo è un nodo nascosto nel modello dati. Solo lettura boolean.

**Restituisce:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. Lettura/Scrittura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Restituisce:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente. Lettura/Scrittura [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


Rimuove il nodo corrente.

**Restituisce:**
boolean - true se rimosso con successo, altrimenti false.