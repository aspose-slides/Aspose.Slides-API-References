---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto imutável que contém as propriedades de preenchimento de imagem.
type: docs
url: /pt/com.aspose.slides/ipicturefillformateffectivedata/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Objeto imutável que contém as propriedades de preenchimento de imagem.

--------------------

Esta interface é usada como parte de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getDpi()](#getDpi--) | Retorna o dpi que é usado para preencher uma imagem. |
| [getPictureFillMode()](#getPictureFillMode--) | Retorna o modo de preenchimento da imagem. |
| [getPicture()](#getPicture--) | Retorna a imagem. |
| [getCropLeft()](#getCropLeft--) | Retorna o número de porcentagens da largura real da imagem que são recortadas à esquerda da imagem. |
| [getCropTop()](#getCropTop--) | Retorna o número de porcentagens da altura real da imagem que são recortadas no topo da imagem. |
| [getCropRight()](#getCropRight--) | Retorna o número de porcentagens da largura real da imagem que são recortadas à direita da imagem. |
| [getCropBottom()](#getCropBottom--) | Retorna o número de porcentagens da altura real da imagem que são recortadas na parte inferior da imagem. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Retorna o dpi que é usado para preencher uma imagem. Somente leitura int.

**Retorna:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Retorna o modo de preenchimento da imagem. Somente leitura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Retorna:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Retorna a imagem. Somente leitura [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Retorna:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Retorna o número de porcentagens da largura real da imagem que são recortadas à esquerda da imagem. Somente leitura float.

**Retorna:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Retorna o número de porcentagens da altura real da imagem que são recortadas no topo da imagem. Somente leitura float.

**Retorna:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Retorna o número de porcentagens da largura real da imagem que são recortadas à direita da imagem. Somente leitura float.

**Retorna:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Retorna o número de porcentagens da altura real da imagem que são recortadas na parte inferior da imagem. Somente leitura float.

**Retorna:**
float