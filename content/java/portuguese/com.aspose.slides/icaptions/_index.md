---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /pt/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Representa as legendas fechadas WebVTT.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Retorna o identificador globalmente único (GUID) das legendas fechadas. |
| [getLabel()](#getLabel--) | Retorna ou define o rótulo das legendas fechadas. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Retorna ou define o rótulo das legendas fechadas. |
| [getBinaryData()](#getBinaryData--) | Retorna os dados binários das legendas fechadas. |
| [getDataAsString()](#getDataAsString--) | Retorna os dados das legendas fechadas como string codificada em UTF-8 Somente leitura String. |
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


Retorna ou define o rótulo das legendas fechadas. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Retorna ou define o rótulo das legendas fechadas. Leitura/Gravação String.

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


Retorna os dados das legendas fechadas como string codificada em UTF-8 Somente leitura String.

**Retorna:**
java.lang.String