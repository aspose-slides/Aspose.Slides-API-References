---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Neměnný objekt, který obsahuje vlastnosti výplně obrázku.
type: docs
url: /cs/com.aspose.slides/ipicturefillformateffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Neměnný objekt, který obsahuje vlastnosti výplně obrázku.

--------------------

Toto rozhraní se používá jako součást [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getDpi()](#getDpi--) | Vrací dpi, který se používá k vyplnění obrázku. |
| [getPictureFillMode()](#getPictureFillMode--) | Vrací režim výplně obrázku. |
| [getPicture()](#getPicture--) | Vrací obrázek. |
| [getCropLeft()](#getCropLeft--) | Vrací počet procent skutečné šířky obrázku, která je oříznuta z levé strany obrázku. |
| [getCropTop()](#getCropTop--) | Vrací počet procent skutečné výšky obrázku, která je oříznuta z horní strany obrázku. |
| [getCropRight()](#getCropRight--) | Vrací počet procent skutečné šířky obrázku, která je oříznuta z pravé strany obrázku. |
| [getCropBottom()](#getCropBottom--) | Vrací počet procent skutečné výšky obrázku, která je oříznuta ze spodní strany obrázku. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Vrací dpi, který se používá k vyplnění obrázku. Pouze pro čtení int.

**Vrací:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Vrací režim výplně obrázku. Pouze pro čtení [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Vrací:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Vrací obrázek. Pouze pro čtení [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Vrací:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Vrací počet procent skutečné šířky obrázku, která je oříznuta z levé strany obrázku. Pouze pro čtení float.

**Vrací:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Vrací počet procent skutečné výšky obrázku, která je oříznuta z horní strany obrázku. Pouze pro čtení float.

**Vrací:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Vrací počet procent skutečné šířky obrázku, která je oříznuta z pravé strany obrázku. Pouze pro čtení float.

**Vrací:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Vrací počet procent skutečné výšky obrázku, která je oříznuta ze spodní strany obrázku. Pouze pro čtení float.

**Vrací:**
float