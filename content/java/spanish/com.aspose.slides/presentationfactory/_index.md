---
title: PresentationFactory
second_title: Referencia de API de Aspose.Slides para Java
description: Permite crear presentaciones mediante la interfaz COM
type: docs
url: /es/com.aspose.slides/presentationfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Permite crear presentaciones mediante la interfaz COM

--------------------

> ```
> El siguiente ejemplo muestra cómo verificar el formato de una presentación.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  El siguiente ejemplo muestra cómo obtener las propiedades de una presentación.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  El siguiente ejemplo muestra cómo actualizar las propiedades de una presentación.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInstance()](#getInstance--) | Instancia estática de la fábrica de presentaciones. |
| [createPresentation()](#createPresentation--) | Crea una nueva presentación. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Crea una nueva presentación con opciones de carga adicionales |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Crea un objeto PresentationInfo a partir de un archivo y lo enlaza a la presentación. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Crea un objeto PresentationInfo a partir de un flujo y lo enlaza a la presentación. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Lee una presentación existente desde un arreglo |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Lee una presentación existente desde un arreglo con opciones de carga adicionales |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Lee una presentación existente desde un flujo |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Lee una presentación existente desde un flujo con opciones de carga adicionales |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Lee una presentación existente desde un archivo |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Lee una presentación existente desde un flujo con opciones de carga adicionales |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Recupera el texto sin formato de las diapositivas |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Recupera el texto sin formato de las diapositivas |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Recupera el texto sin formato de las diapositivas |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Instancia estática de la fábrica de presentaciones. Solo lectura [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Devuelve:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Crea una nueva presentación.

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nueva presentación
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
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
public final IPresentationInfo getPresentationInfo(String file)
```

Crea un objeto PresentationInfo a partir de un archivo y lo enlaza a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de presentación. |

**Devuelve:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Información de presentación enlazada a la presentación.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Crea un objeto PresentationInfo a partir de un flujo y lo enlaza a la presentación. Obtiene información sobre la presentación en el flujo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de presentación. |

**Devuelve:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Información de presentación enlazada a la presentación.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Lee una presentación existente desde un arreglo

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Arreglo a leer |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Lee una presentación existente desde un arreglo con opciones de carga adicionales

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Arreglo a leer |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opciones de carga |

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentación leída
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
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
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
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
public final IPresentation readPresentation(String file)
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
public final IPresentation readPresentation(String file, ILoadOptions options)
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
public final IPresentationText getPresentationText(String file, int mode)
```

Recupera el texto sin formato de las diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de entrada |
| mode | int | Modo de extracción |

**Devuelve:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - La instancia de PresentationText que contiene la matriz SlideText representando el texto sin formato de las diapositivas
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

Recupera el texto sin formato de las diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada |
| mode | int | Modo de extracción |

**Devuelve:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - La instancia de PresentationText que contiene la matriz SlideText representando el texto sin formato de las diapositivas
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Recupera el texto sin formato de las diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada |
| mode | int | Modo de extracción |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opciones de carga |

**Devuelve:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - La instancia de PresentationText que contiene la matriz SlideText representando el texto sin formato de las diapositivas