---
title: IImage
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma imagem raster ou vetorial.
type: docs
url: /pt/com.aspose.slides/iimage/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Representa uma imagem raster ou vetorial.

--------------------

Esta interface fornece uma abstração comum para manipular imagens raster e vetoriais. As implementações podem variar dependendo do tipo subjacente da imagem.
## Métodos

| Método | Descrição |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Salva a imagem em um arquivo. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Salva a imagem em um arquivo no formato especificado. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva a imagem em um fluxo no formato especificado. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Salva a imagem em um arquivo no formato e qualidade especificados. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Salva a imagem em um fluxo no formato e qualidade especificados. |
| [getSize()](#getSize--) | Obtém o tamanho da imagem. |
| [getWidth()](#getWidth--) | Obtém a largura da imagem em pixels. |
| [getHeight()](#getHeight--) | Obtém a altura da imagem em pixels. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Salva a imagem em um arquivo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | java.lang.String | O caminho para o arquivo onde a imagem será salva. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Salva a imagem em um arquivo no formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | java.lang.String | O caminho para o arquivo onde a imagem será salva. |
| format | int | O formato da imagem. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Salva a imagem em um fluxo no formato especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | O fluxo onde a imagem será salva. |
| format | int | O formato da imagem. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Salva a imagem em um arquivo no formato e qualidade especificados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | java.lang.String | O caminho para o arquivo onde a imagem será salva. |
| format | int | O formato da imagem. |
| quality | int | A qualidade da imagem salva (0 a 100). Este parâmetro só afeta a gravação em [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); para todos os outros formatos, ele é ignorado. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Salva a imagem em um fluxo no formato e qualidade especificados.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | O fluxo onde a imagem será salva. |
| format | int | O formato da imagem. |
| quality | int | A qualidade da imagem salva (0 a 100). Este parâmetro só afeta a gravação em [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); para todos os outros formatos, ele é ignorado. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Obtém o tamanho da imagem.

**Retorna:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Obtém a largura da imagem em pixels.

**Retorna:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Obtém a altura da imagem em pixels.

**Retorna:**
int