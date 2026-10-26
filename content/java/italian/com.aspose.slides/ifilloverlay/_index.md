---
title: IFillOverlay
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un effetto Fill Overlay.
type: docs
url: /it/com.aspose.slides/ifilloverlay/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Rappresenta un effetto Fill Overlay. Un Fill Overlay può essere utilizzato per specificare un riempimento aggiuntivo per un oggetto e fondere i due riempimenti insieme.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. Lettura/Scrittura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Restituisce:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. Lettura/Scrittura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Formato di riempimento. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)