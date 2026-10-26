---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Representa un hipervínculo.
type: docs
url: /es/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Representa un hipervínculo.
## Métodos

| Method | Description |
| --- | --- |
| [getActionType()](#getActionType--) | Devuelve el tipo de la acción de HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Especifica la URL externa. Si esta propiedad no es nula, la propiedad TargetSlide será nula. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representa un hipervínculo establecido para esta porción sin considerar el contenido real de la porción. |
| [getTargetSlide()](#getTargetSlide--) | Si HyperlinkEx apunta a una diapositiva específica, devuelve esa diapositiva. |
| [getTargetFrame()](#getTargetFrame--) | Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. |
| [getTooltip()](#getTooltip--) | Devuelve la cadena que puede mostrarse en la interfaz de usuario asociada al hipervínculo padre. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Devuelve la cadena que puede mostrarse en la interfaz de usuario asociada al hipervínculo padre. |
| [getHistory()](#getHistory--) | Determina si el objetivo del hipervínculo padre debe añadirse a una lista de hipervínculos vistos cuando se invoca. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determina si el objetivo del hipervínculo padre debe añadirse a una lista de hipervínculos vistos cuando se invoca. |
| [getHighlightClick()](#getHighlightClick--) | Determina si el hipervínculo debe resaltarse al hacer clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determina si el hipervínculo debe resaltarse al hacer clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determina si el sonido debe detenerse al hacer clic en el hipervínculo. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determina si el sonido debe detenerse al hacer clic en el hipervínculo. |
| [getSound()](#getSound--) | Representa el sonido en reproducción del hipervínculo. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representa el sonido en reproducción del hipervínculo. |
| [getColorSource()](#getColorSource--) | Representa el origen del color del hipervínculo: estilos o formato de porción. |
| [setColorSource(int value)](#setColorSource-int-) | Representa el origen del color del hipervínculo: estilos o formato de porción. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determina si las dos instancias de Hyperlink son iguales. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Devuelve el tipo de la acción de HyperLinkEx. Solo lectura [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Devuelve:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Especifica la URL externa. Si esta propiedad no es nula, la propiedad TargetSlide será nula. Solo lectura String.

**Devuelve:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Representa un hipervínculo establecido para esta porción sin considerar el contenido real de la porción.

--------------------

PowerPoint se comporta de forma específica con los enlaces y su texto correspondiente en una porción. Permite crear texto para el hipervínculo en forma de una URL válida, diferente de la dirección real del enlace. En este caso, cuando se visualiza el enlace en la ventana de edición, se cambiará para que coincida con la porción de texto. Esta propiedad representa el valor original del hipervínculo.

**Devuelve:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Si HyperlinkEx apunta a una diapositiva específica, devuelve esa diapositiva. Si la propiedad no es nula, la propiedad ExternalUrl será nula. Solo lectura [ISlide](../../com.aspose.slides/islide).

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Devuelve el marco dentro del conjunto de marcos HTML padre para el objetivo del hipervínculo padre cuando existe. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Devuelve la cadena que puede mostrarse en la interfaz de usuario asociada al hipervínculo padre. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Devuelve la cadena que puede mostrarse en la interfaz de usuario asociada al hipervínculo padre. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Determina si el objetivo del hipervínculo padre debe añadirse a una lista de hipervínculos vistos cuando se invoca. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Determina si el objetivo del hipervínculo padre debe añadirse a una lista de hipervínculos vistos cuando se invoca. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Determina si el hipervínculo debe resaltarse al hacer clic. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Determina si el hipervínculo debe resaltarse al hacer clic. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Determina si el sonido debe detenerse al hacer clic en el hipervínculo. Lectura/escritura boolean.

**Devuelve:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Determina si el sonido debe detenerse al hacer clic en el hipervínculo. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Representa el sonido en reproducción del hipervínculo. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtiene el primer hipervínculo de la forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrae el sonido del hipervínculo en un arreglo de bytes
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
public abstract void setSound(IAudio value)
```

Representa el sonido en reproducción del hipervínculo. Lectura/escritura [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtiene el primer hipervínculo de la forma
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrae el sonido del hipervínculo en un arreglo de bytes
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
public abstract int getColorSource()
```

Representa el origen del color del hipervínculo: estilos o formato de porción. Lectura/escritura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Devuelve:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Representa el origen del color del hipervínculo: estilos o formato de porción. Lectura/escritura [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Determina si las dos instancias de Hyperlink son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | El Hyperlink con el que comparar el Hyperlink actual. |

**Devuelve:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.