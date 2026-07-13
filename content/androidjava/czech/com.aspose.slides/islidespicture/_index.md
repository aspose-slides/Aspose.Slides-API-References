---
title: ISlidesPicture
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Reprezentuje obrázek v prezentaci.
type: docs
url: /cs/com.aspose.slides/islidespicture/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Reprezentuje obrázek v prezentaci.
## Metody

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | Vrací nebo nastavuje vložený obrázek. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Vrací nebo nastavuje vložený obrázek. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje URL propojeného obrázku. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje URL propojeného obrázku. |
| [getImageTransform()](#getImageTransform--) | Vrací kolekci efektů transformace obrázku. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Vrací nebo nastavuje vložený obrázek. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Vrací nebo nastavuje vložený obrázek. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Vrací nebo nastavuje URL propojeného obrázku. Čtení/zápis String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Vrací nebo nastavuje URL propojeného obrázku. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Vrací kolekci efektů transformace obrázku. Pouze pro čtení [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Vrací:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)