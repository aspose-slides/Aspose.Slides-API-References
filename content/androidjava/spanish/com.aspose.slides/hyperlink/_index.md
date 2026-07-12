---
title: Hyperlink
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un hipervínculo.
type: docs
url: /es/com.aspose.slides/hyperlink/
---
**Herencia:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**  
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject  
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Representa un hipervínculo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Crea una instancia de un hipervínculo. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Crea una instancia de un hipervínculo que apunta a una diapositiva específica. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Crea una instancia de un hipervínculo usando otro hipervínculo como origen, sobrescribiendo propiedades secundarias. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Devuelve un hipervínculo especial "no hacer nada". |
| [getMedia()](#getMedia--) | Devuelve un hipervínculo especial "reproducir archivo multimedia". |
| [getNextSlide()](#getNextSlide--) | Devuelve un hipervínculo a la diapositiva siguiente. |
| [getPreviousSlide()](#getPreviousSlide--) | Devuelve un hipervínculo a la diapositiva anterior. |
| [getFirstSlide()](#getFirstSlide--) | Devuelve un hipervínculo a la primera diapositiva de la presentación. |
| [getLastSlide()](#getLastSlide--) | Devuelve un hipervínculo a la última diapositiva de la presentación. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Devuelve un hipervínculo a la última diapositiva vista. |
| [getEndShow()](#getEndShow--) | Devuelve un hipervínculo que termina la presentación. |
| [getActionType()](#getActionType--) | Devuelve el tipo de acción del Hipervínculo. |
| [getExternalUrl()](#getExternalUrl--) | Especifica la URL externa. |
| [getTargetSlide()](#getTargetSlide--) | Si el Hipervínculo apunta a una diapositiva específica, devuelve esa diapositiva. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representa un hipervínculo que se establece para esta porción sin tener en cuenta el contenido real de la porción. |
| [getTargetFrame()](#getTargetFrame--) | Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. |
| [getTooltip()](#getTooltip--) | Devuelve la cadena que puede mostrarse en una interfaz de usuario asociada al hipervínculo padre. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Devuelve la cadena que puede mostrarse en una interfaz de usuario asociada al hipervínculo padre. |
| [getHistory()](#getHistory--) | Determina si el objetivo del hipervínculo padre debe agregarse a una lista de hipervínculos vistos cuando se invoca. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina si el objetivo del hipervínculo padre debe agregarse a una lista de hipervínculos vistos cuando se invoca. |
| [getHighlightClick()](#getHighlightClick--) | Determina si el hipervínculo debe resaltarse al hacer clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina si el hipervínculo debe resaltarse al hacer clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina si el sonido debe detenerse al hacer clic en el hipervínculo. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina si el sonido debe detenerse al hacer clic en el hipervínculo. |
| [getSound()](#getSound--) | Representa el sonido en reproducción del hipervínculo. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representa el sonido en reproducción del hipervínculo. |
| [getColorSource()](#getColorSource--) | Representa la fuente del color del hipervínculo: estilos o formato de porción. |
| [setColorSource(int value)](#setColorSource-int-) | Representa la fuente del color del hipervínculo: estilos o formato de porción. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si las dos instancias de Hipervínculo son iguales. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina si las dos instancias de Hipervínculo son iguales. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Prueba dos hipervínculos para igualdad. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Prueba dos hipervínculos para desigualdad. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular, adecuada para su uso en algoritmos de hash y estructuras de datos como una tabla hash. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Crea una instancia de un hipervínculo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del hipervínculo. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Crea una instancia de un hipervínculo que apunta a una diapositiva específica. Nota: el hipervínculo creado debe asignarse a algún objeto de la misma presentación, de lo contrario el enlace se guardará como NoAction.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva objetivo. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Crea una instancia de un hipervínculo usando otro hipervínculo como origen, sobrescribiendo propiedades secundarias.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hipervínculo fuente |
| targetFrame | java.lang.String | Marco destino |
| tooltip | java.lang.String | Texto de información sobre herramientas |
| history | boolean | Determina si el objetivo del hipervínculo padre debe agregarse a una lista de hipervínculos vistos cuando se invoca. |
| stopSoundsOnClick | boolean | Determina si el sonido debe detenerse al hacer clic en el hipervínculo. |
| highlightClick | boolean | Determina si el hipervínculo debe resaltarse al hacer clic. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Devuelve un hipervínculo especial "no hacer nada". Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Devuelve un hipervínculo especial "reproducir archivo multimedia". Usado en AudioFrame y VideoFrame. Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Devuelve un hipervínculo a la diapositiva siguiente. Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Devuelve un hipervínculo a la diapositiva anterior. Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Devuelve un hipervínculo a la primera diapositiva de la presentación. Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Devuelve un hipervínculo a la última diapositiva de la presentación. Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Devuelve un hipervínculo a la última diapositiva vista. Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Devuelve un hipervínculo que termina la presentación. Solo lectura [Hyperlink](../../com.aspose.slides/hyperlink).

**Devuelve:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Devuelve el tipo de acción del Hipervínculo. Solo lectura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Devuelve:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Especifica la URL externa. Solo lectura String.

**Devuelve:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Si el Hipervínculo apunta a una diapositiva específica, devuelve esa diapositiva. Solo lectura [ISlide](../../com.aspose.slides/islide).

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Representa un hipervínculo que se establece para esta porción sin tener en cuenta el contenido real de la porción.

--------------------

PowerPoint se comporta de forma específica con los enlaces y su texto correspondiente en una porción. Permite crear texto para el hipervínculo en forma de una URL válida, diferente de la dirección real del enlace. En este caso, cuando se visualiza el enlace en la ventana de edición, se cambiará para que coincida con la porción de texto. Esta propiedad representa el valor original del hipervínculo.

**Devuelve:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Establece el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Devuelve la cadena que puede mostrarse en una interfaz de usuario asociada al hipervínculo padre. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Establece la cadena que puede mostrarse en una interfaz de usuario asociada al hipervínculo padre. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Determina si el objetivo del hipervínculo padre debe agregarse a una lista de hipervínculos vistos cuando se invoca. Lectura/escritura boolean.

**Devuelve:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Determina si el objetivo del hipervínculo padre debe agregarse a una lista de hipervínculos vistos cuando se invoca. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Determina si el hipervínculo debe resaltarse al hacer clic. Lectura/escritura boolean.

**Devuelve:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Determina si el hipervínculo debe resaltarse al hacer clic. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Determina si el sonido debe detenerse al hacer clic en el hipervínculo. Lectura/escritura boolean.

**Devuelve:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Determina si el sonido debe detenerse al hacer clic en el hipervínculo. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Representa el sonido en reproducción del hipervínculo. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtenga el hipervínculo de la primera forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraiga el sonido del hipervínculo en un arreglo de bytes
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Representa el sonido en reproducción del hipervínculo. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtenga el hipervínculo de la primera forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraiga el sonido del hipervínculo en un arreglo de bytes
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Representa la fuente del color del hipervínculo: estilos o formato de porción. Lectura/escritura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Devuelve:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Representa la fuente del color del hipervínculo: estilos o formato de porción. Lectura/escritura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina si las dos instancias de Hipervínculo son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El Hipervínculo a comparar con el Hipervínculo actual. |

**Devuelve:**
boolean - **true** si el Hipervínculo especificado es igual al Hipervínculo actual; de lo contrario, **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Determina si las dos instancias de Hipervínculo son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | El Hipervínculo a comparar con el Hipervínculo actual. |

**Devuelve:**
boolean - **true** si el Hipervínculo especificado es igual al Hipervínculo actual; de lo contrario, **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Prueba dos hipervínculos para igualdad.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primer hipervínculo a probar. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Segundo hipervínculo a probar. |

**Devuelve:**
boolean - **true** si los hipervínculos son iguales.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Prueba dos hipervínculos para desigualdad.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Primer hipervínculo a probar. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Segundo hipervínculo a probar. |

**Devuelve:**
boolean - **false** si los hipervínculos son iguales.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular, adecuada para su uso en algoritmos de hash y estructuras de datos como una tabla hash.

**Devuelve:**
int - Código hash para una URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject