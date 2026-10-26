---
title: ISmartArt
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta un diagramma SmartArt.
type: docs
url: /it/com.aspose.slides/ismartart/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Rappresenta un diagramma SmartArt.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Restituisce le collezioni di tutti i nodi nell'oggetto SmartArt. |
| [getNodes()](#getNodes--) | Restituisce le collezioni dei nodi radice nell'oggetto SmartArt. |
| [getLayout()](#getLayout--) | Restituisce o imposta il layout dell'oggetto SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Restituisce o imposta il layout dell'oggetto SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Restituisce o imposta lo stile rapido dell'oggetto SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Restituisce o imposta lo stile rapido dell'oggetto SmartArt. |
| [getColorStyle()](#getColorStyle--) | Restituisce o imposta lo stile colore dell'oggetto SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Restituisce o imposta lo stile colore dell'oggetto SmartArt. |
| [isReversed()](#isReversed--) | Restituisce o imposta lo stato del diagramma SmartArt rispetto a (da sinistra a destra) LTR o (da destra a sinistra) RTL, se il diagramma supporta l'inversione. |
| [setReversed(boolean value)](#setReversed-boolean-) | Restituisce o imposta lo stato del diagramma SmartArt rispetto a (da sinistra a destra) LTR o (da destra a sinistra) RTL, se il diagramma supporta l'inversione. |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Restituisce le collezioni di tutti i nodi nell'oggetto SmartArt. Solo lettura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Restituisce:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Restituisce le collezioni dei nodi radice nell'oggetto SmartArt. Solo lettura [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Restituisce:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Restituisce o imposta il layout dell'oggetto SmartArt. Lettura/scrittura [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Restituisce:**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Restituisce o imposta il layout dell'oggetto SmartArt. Lettura/scrittura [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Restituisce o imposta lo stile rapido dell'oggetto SmartArt. Lettura/scrittura [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Restituisce:**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Restituisce o imposta lo stile rapido dell'oggetto SmartArt. Lettura/scrittura [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Restituisce o imposta lo stile colore dell'oggetto SmartArt. Lettura/scrittura [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Restituisce:**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Restituisce o imposta lo stile colore dell'oggetto SmartArt. Lettura/scrittura [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Restituisce o imposta lo stato del diagramma SmartArt rispetto a (da sinistra a destra) LTR o (da destra a sinistra) RTL, se il diagramma supporta l'inversione. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Restituisce o imposta lo stato del diagramma SmartArt rispetto a (da sinistra a destra) LTR o (da destra a sinistra) RTL, se il diagramma supporta l'inversione. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |