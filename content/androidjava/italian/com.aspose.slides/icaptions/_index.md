---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta i sottotitoli chiusi WebVTT.
type: docs
url: /it/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Rappresenta i sottotitoli chiusi WebVTT.
## Metodi

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Restituisce l'identificatore univoco globale (GUID) dei sottotitoli chiusi. |
| [getLabel()](#getLabel--) | Restituisce o imposta l'etichetta dei sottotitoli chiusi. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Restituisce o imposta l'etichetta dei sottotitoli chiusi. |
| [getBinaryData()](#getBinaryData--) | Restituisce i dati binari dei sottotitoli chiusi. |
| [getDataAsString()](#getDataAsString--) | Restituisce i dati dei sottotitoli chiusi come stringa codificata UTF-8 Solo lettura String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Restituisce l'identificatore univoco globale (GUID) dei sottotitoli chiusi. Solo lettura java.util.UUID.

**Restituisce:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Restituisce o imposta l'etichetta dei sottotitoli chiusi. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Restituisce o imposta l'etichetta dei sottotitoli chiusi. Lettura/scrittura String.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Restituisce i dati binari dei sottotitoli chiusi. Solo lettura byte[].

**Restituisce:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Restituisce i dati dei sottotitoli chiusi come stringa codificata UTF-8 Solo lettura String.

**Restituisce:**
java.lang.String