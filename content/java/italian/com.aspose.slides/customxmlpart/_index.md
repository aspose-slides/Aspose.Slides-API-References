---
title: CustomXmlPart
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta una parte xml personalizzata.
type: docs
url: /it/com.aspose.slides/customxmlpart/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Rappresenta una parte xml personalizzata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXmlData()](#getXmlData--) | Restituisce o imposta i dati xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Restituisce o imposta i dati xml. |
| [getXmlAsString()](#getXmlAsString--) | Restituisce o imposta i dati xml come stringa UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Restituisce o imposta i dati xml come stringa UTF-8. |
| [getItemId()](#getItemId--) | Specifica un identificatore unico globale (GUID) che identifica univocamente una singola parte XML personalizzata all'interno di un documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifica un identificatore unico globale (GUID) che identifica univocamente una singola parte XML personalizzata all'interno di un documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Restituisce la collezione di schemi XML associati alla parte XML personalizzata. |
| [remove()](#remove--) | Rimuove la parte xml personalizzata dalla presentazione. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Restituisce o imposta i dati xml. Lettura/scrittura byte[].

**Restituisce:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Restituisce o imposta i dati xml. Lettura/scrittura byte[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Restituisce o imposta i dati xml come stringa UTF-8. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Restituisce o imposta i dati xml come stringa UTF-8. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Specifica un identificatore unico globale (GUID) che identifica univocamente una singola parte XML personalizzata all'interno di un documento Office Open XML. Solo lettura java.util.UUID.

**Restituisce:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Specifica un identificatore unico globale (GUID) che identifica univocamente una singola parte XML personalizzata all'interno di un documento Office Open XML. Solo lettura java.util.UUID.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Restituisce la collezione di schemi XML associati alla parte XML personalizzata. Solo lettura String[].

**Restituisce:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Rimuove la parte xml personalizzata dalla presentazione.