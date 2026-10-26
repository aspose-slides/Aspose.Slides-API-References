---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /es/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Representa los subtítulos cerrados WebVTT.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Devuelve el identificador globalmente único (GUID) de los subtítulos cerrados. |
| [getLabel()](#getLabel--) | Devuelve o establece la etiqueta de los subtítulos cerrados. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Devuelve o establece la etiqueta de los subtítulos cerrados. |
| [getBinaryData()](#getBinaryData--) | Devuelve los datos binarios de los subtítulos cerrados. |
| [getDataAsString()](#getDataAsString--) | Devuelve los datos de los subtítulos cerrados como cadena codificada en UTF-8 Solo lectura String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Devuelve el identificador globalmente único (GUID) de los subtítulos cerrados. Solo lectura java.util.UUID.

**Devuelve:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Devuelve o establece la etiqueta de los subtítulos cerrados. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Devuelve o establece la etiqueta de los subtítulos cerrados. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Devuelve los datos binarios de los subtítulos cerrados. Solo lectura byte[].

**Devuelve:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Devuelve los datos de los subtítulos cerrados como cadena codificada en UTF-8 Solo lectura String.

**Devuelve:**
java.lang.String