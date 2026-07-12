---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Representa as legendas fechadas WebVTT.
type: docs
url: /pt/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Representa as legendas fechadas WebVTT.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Returns the globally unique identifier (GUID) of the closed captions. |
| [getLabel()](#getLabel--) | Returns or sets the label of the closed captions. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Returns or sets the label of the closed captions. |
| [getBinaryData()](#getBinaryData--) | Returns the binary data of the closed captions. |
| [getDataAsString()](#getDataAsString--) | Returns the closed captions data as UTF-8 encoded string Read-only String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Retorna o identificador globalmente único (GUID) das legendas fechadas. Somente leitura java.util.UUID.

**Retorna:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Retorna ou define o rótulo das legendas fechadas. Leitura/gravação String.

**Retorna:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Retorna ou define o rótulo das legendas fechadas. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retorna os dados binários das legendas fechadas. Somente leitura byte[].

**Retorna:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Retorna os dados das legendas fechadas como string codificada em UTF-8. Somente leitura String.

**Retorna:**
java.lang.String