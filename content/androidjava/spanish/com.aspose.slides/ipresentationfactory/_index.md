---
title: IPresentationFactory
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Permite crear presentaciones mediante la interfaz COM
type: docs
url: /es/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Permite crear presentaciones mediante la interfaz COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createPresentation()](#createPresentation--) | Crea una nueva presentación. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Crea una nueva presentación con opciones de carga adicionales |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Obtiene información sobre la presentación en el archivo especificado. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Obtiene información sobre la presentación en el flujo especificado. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Lee una presentación existente desde un array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Lee una presentación existente desde un array con opciones de carga adicionales |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Lee una presentación existente desde un flujo |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Lee una presentación existente desde un flujo con opciones de carga adicionales |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Lee una presentación existente desde un archivo |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Lee una presentación existente desde un flujo con opciones de carga adicionales |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Recupera el texto sin formato de las diapositivas |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Recupera el texto sin formato de las diapositivas |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Recupera el texto sin formato de las diapositivas |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Crea una nueva presentación.

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nueva presentación
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

Crea una nueva presentación con opciones de carga adicionales

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opciones de carga |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nueva presentación
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

Obtiene información sobre la presentación en el archivo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de la presentación. |

**Devuelve:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Información de la presentación
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Obtiene información sobre la presentación en el flujo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de la presentación. |

**Devuelve:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Información de la presentación.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Lee una presentación existente desde un array

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Array a leer |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Lee una presentación existente desde un array con opciones de carga adicionales

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Array a leer |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opciones de carga |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Lee una presentación existente desde un flujo

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada a leer |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Lee una presentación existente desde un flujo con opciones de carga adicionales

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada a leer |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opciones de carga |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Lee una presentación existente desde un archivo

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Nombre del archivo |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Lee una presentación existente desde un flujo con opciones de carga adicionales

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Nombre del archivo |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opciones de carga |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Recupera el texto sin formato de las diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de entrada |
| mode | int | Modo de extracción |

**Devuelve:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - La instancia de PresentationText que contiene la matriz SlideText que representa el texto sin formato de las diapositivas
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Recupera el texto sin formato de las diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada |
| mode | int | Modo de extracción |

**Devuelve:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - La instancia de PresentationText que contiene la matriz SlideText que representa el texto sin formato de las diapositivas
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Recupera el texto sin formato de las diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada |
| mode | int | Modo de extracción |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opciones de carga |

**Devuelve:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - La instancia de PresentationText que contiene la matriz SlideText que representa el texto sin formato de las diapositivas