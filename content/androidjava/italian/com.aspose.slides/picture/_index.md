---
title: Picture
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un'immagine in una presentazione.
type: docs
url: /it/com.aspose.slides/picture/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Rappresenta un'immagine in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Restituisce o imposta l'immagine incorporata. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Restituisce o imposta l'immagine incorporata. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce o imposta l'URL dell'immagine collegata. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce o imposta l'URL dell'immagine collegata. |
| [getImageTransform()](#getImageTransform--) | Restituisce la collezione degli effetti di trasformazione dell'immagine. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione. |
| [equals(Object obj)](#equals-java.lang.Object-) | Confronta con l'oggetto specificato. |
| [hashCode()](#hashCode--) | Restituisce l'hash. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore dell'immagine. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Restituisce il genitore IPresentationComponent. Solo lettura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Restituisce o imposta l'immagine incorporata. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Restituisce o imposta l'immagine incorporata. Lettura/scrittura [IPPImage](../../com.aspose.slides/ippimage).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkLong()
```

Restituisce o imposta l'URL dell'immagine collegata. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Restituisce o imposta l'URL dell'immagine collegata. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Restituisce la collezione degli effetti di trasformazione dell'immagine. Solo lettura [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Restituisce:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Confronta con l'oggetto specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Oggetto da confrontare. |

**Restituisce:**
boolean - True se gli oggetti sono uguali, altrimenti false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Restituisce l'hash.

**Restituisce:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva genitore dell'immagine. Solo lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)