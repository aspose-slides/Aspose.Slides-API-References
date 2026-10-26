---
title: CustomXmlPart
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en anpassad xml-del.
type: docs
url: /sv/com.aspose.slides/customxmlpart/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Representerar en anpassad XML-del.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXmlData()](#getXmlData--) | Returnerar eller anger xml-data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returnerar eller anger xml-data. |
| [getXmlAsString()](#getXmlAsString--) | Returnerar eller anger xml-data som UTF-8-sträng. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Returnerar eller anger xml-data som UTF-8-sträng. |
| [getItemId()](#getItemId--) | Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Returnerar samlingen av XML-scheman som är associerade med den anpassade XML-delen. |
| [remove()](#remove--) | Tar bort den anpassade xml-delen från presentationen. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Returnerar eller anger xml-data. Läs/skriv byte[].

**Returnerar:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Returnerar eller anger xml-data. Läs/skriv byte[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Returnerar eller anger xml-data som UTF-8-sträng. Läs/skriv String.

**Returnerar:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Returnerar eller anger xml-data som UTF-8-sträng. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. Endast läsning java.util.UUID.

**Returnerar:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Anger en globalt unik identifierare (GUID) som unikt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. Endast läsning java.util.UUID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Returnerar samlingen av XML-scheman som är associerade med den anpassade XML-delen. Endast läsning String[].

**Returnerar:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Tar bort den anpassade xml-delen från presentationen.