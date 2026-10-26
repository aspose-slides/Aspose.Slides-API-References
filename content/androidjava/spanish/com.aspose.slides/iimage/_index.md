---
title: IImage
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa una imagen raster o vectorial.
type: docs
url: /es/com.aspose.slides/iimage/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Representa una imagen raster o vectorial.

--------------------

Esta interfaz proporciona una abstracción común para manejar tanto imágenes raster como vectoriales. Las implementaciones pueden variar según el tipo subyacente de la imagen.
## Métodos

| Método | Descripción |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Guarda la imagen en un archivo. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Guarda la imagen en un archivo en el formato especificado. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Guarda la imagen en un flujo en el formato especificado. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Guarda la imagen en un archivo en el formato y calidad especificados. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Guarda la imagen en un flujo en el formato y calidad especificados. |
| [getSize()](#getSize--) | Obtiene el tamaño de la imagen. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen en píxeles. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen en píxeles. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Guarda la imagen en un archivo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | java.lang.String | La ruta al archivo donde se guardará la imagen. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Guarda la imagen en un archivo en el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | java.lang.String | La ruta al archivo donde se guardará la imagen. |
| format | int | El formato de la imagen. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Guarda la imagen en un flujo en el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El flujo donde se guardará la imagen. |
| format | int | El formato de la imagen. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Guarda la imagen en un archivo en el formato y calidad especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | java.lang.String | La ruta al archivo donde se guardará la imagen. |
| format | int | El formato de la imagen. |
| quality | int | La calidad de la imagen guardada (0 a 100). Este parámetro solo afecta al guardado en [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); para todos los demás formatos, se ignora. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Guarda la imagen en un flujo en el formato y calidad especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | El flujo donde se guardará la imagen. |
| format | int | El formato de la imagen. |
| quality | int | La calidad de la imagen guardada (0 a 100). Este parámetro solo afecta al guardado en [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); para todos los demás formatos, se ignora. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Obtiene el tamaño de la imagen.

**Devuelve:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Obtiene el ancho de la imagen en píxeles.

**Devuelve:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Obtiene la altura de la imagen en píxeles.

**Devuelve:**
int