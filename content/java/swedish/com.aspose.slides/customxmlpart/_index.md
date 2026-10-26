---
title: CustomXmlPart
second_title: Aspose.Slides för Java API-referens
description: Representerar anpassad xml-del.
type: docs
url: /sv/com.aspose.slides/customxmlpart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Representerar anpassad xml-del.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXmlData()](#getXmlData--) | Returnerar eller sätter xml-data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returnerar eller sätter xml-data. |
| [getXmlAsString()](#getXmlAsString--) | Returnerar eller sätter xml-data som UTF-8-sträng. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Returnerar eller sätter xml-data som UTF-8-sträng. |
| [getItemId()](#getItemId--) | Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del i ett Office Open XML-dokument. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del i ett Office Open XML-dokument. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Returnerar samlingen av XML-scheman som är associerade med den anpassade XML-delen. |
| [remove()](#remove--) | Tar bort den anpassade xml-delen från presentationen. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Returnerar eller sätter xml-data. Läs/skriv byte[].

**Returnerar:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Returnerar eller sätter xml-data. Läs/skriv byte[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Returnerar eller sätter xml-data som UTF-8-sträng. Läs/skriv String.

**Returnerar:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Returnerar eller sätter xml-data som UTF-8-sträng. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del i ett Office Open XML-dokument. Skrivskyddad java.util.UUID.

**Returnerar:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del i ett Office Open XML-dokument. Skrivskyddad java.util.UUID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Returnerar samlingen av XML-scheman som är associerade med den anpassade XML-delen. Skrivskyddad String[].

**Returnerar:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Tar bort den anpassade xml-delen från presentationen.