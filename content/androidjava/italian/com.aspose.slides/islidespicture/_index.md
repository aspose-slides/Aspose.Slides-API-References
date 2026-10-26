---
title: ISlidesPicture
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un'immagine in una presentazione.
type: docs
url: /it/com.aspose.slides/islidespicture/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Rappresenta un'immagine in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImage()](#getImage--) | Restituisce o imposta l'immagine incorporata. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Restituisce o imposta l'immagine incorporata. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce o imposta l'URL dell'immagine collegata. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce o imposta l'URL dell'immagine collegata. |
| [getImageTransform()](#getImageTransform--) | Restituisce la collezione di effetti di trasformazione dell'immagine. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Restituisce o imposta l'immagine incorporata. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


Restituisce o imposta l'immagine incorporata. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Restituisce o imposta l'URL dell'immagine collegata. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Restituisce o imposta l'URL dell'immagine collegata. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


Restituisce la collezione di effetti di trasformazione dell'immagine. Solo lettura [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Restituisce:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)