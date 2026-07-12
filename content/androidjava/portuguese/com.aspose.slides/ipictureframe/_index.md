---
title: IPictureFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um quadro com uma imagem dentro.
type: docs
url: /pt/com.aspose.slides/ipictureframe/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Representa um quadro com uma imagem dentro.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Retorna os bloqueios de PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Retorna o objeto PictureFillFormat para um quadro de imagem. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Retorna os bloqueios de PictureFrame. Somente leitura [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Retorna:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Retorna o objeto PictureFillFormat para um quadro de imagem. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação float.

**Retorna:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação float.

**Retorna:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |