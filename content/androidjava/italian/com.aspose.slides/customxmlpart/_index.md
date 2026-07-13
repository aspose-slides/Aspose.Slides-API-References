---
title: CustomXmlPart
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una parte XML personalizzata.
type: docs
url: /it/com.aspose.slides/customxmlpart/
---
**Eredita da:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Rappresenta una parte XML personalizzata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXmlData()](#getXmlData--) | Restituisce o imposta i dati XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Restituisce o imposta i dati XML. |
| [getXmlAsString()](#getXmlAsString--) | Restituisce o imposta i dati XML come stringa UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Restituisce o imposta i dati XML come stringa UTF-8. |
| [getItemId()](#getItemId--) | Specifica un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifica un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Restituisce la raccolta di schemi XML associati alla parte XML personalizzata. |
| [remove()](#remove--) | Rimuove la parte XML personalizzata dalla presentazione. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Restituisce o imposta i dati XML. Lettura/scrittura byte[].

**Restituisce:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Restituisce o imposta i dati XML. Lettura/scrittura byte[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Restituisce o imposta i dati XML come stringa UTF-8. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Restituisce o imposta i dati XML come stringa UTF-8. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


SpecificA un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. Sola lettura java.util.UUID.

**Restituisce:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


SpecificA un identificatore univoco globale (GUID) che identifica in modo univoco una singola parte XML personalizzata all'interno di un documento Office Open XML. Sola lettura java.util.UUID.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Restituisce la raccolta di schemi XML associati alla parte XML personalizzata. Sola lettura String[].

**Restituisce:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Rimuove la parte XML personalizzata dalla presentazione.