---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta una parte xml personalizzata.
type: docs
url: /it/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Rappresenta una parte xml personalizzata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Restituisce o imposta i dati xml come String in UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Restituisce o imposta i dati xml come String in UTF-8. |
| [getXmlData()](#getXmlData--) | Restituisce o imposta i dati xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Restituisce o imposta i dati xml. |
| [getItemId()](#getItemId--) | Specifica un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifica un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Restituisce la raccolta di schemi XML associati alla parte XML personalizzata. |
| [remove()](#remove--) | Rimuove la parte xml personalizzata dalla presentazione. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Restituisce o imposta i dati xml come String in UTF-8. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Restituisce o imposta i dati xml come String in UTF-8. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Restituisce o imposta i dati xml. Lettura/scrittura byte[].

**Restituisce:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Restituisce o imposta i dati xml. Lettura/scrittura byte[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Specifică un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. Sola lettura java.util.UUID.

**Restituisce:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Specifică un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. Sola lettura java.util.UUID.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Restituisce la raccolta di schemi XML associati alla parte XML personalizzata. Sola lettura String[].

**Restituisce:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Rimuove la parte xml personalizzata dalla presentazione.