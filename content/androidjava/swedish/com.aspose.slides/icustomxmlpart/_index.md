---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar anpassad xml-del.
type: docs
url: /sv/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Representerar anpassad xml-del.
## Metoder

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Returnerar eller anger xml-data som UTF-8-sträng. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Returnerar eller anger xml-data som UTF-8-sträng. |
| [getXmlData()](#getXmlData--) | Returnerar eller anger xml-data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returnerar eller anger xml-data. |
| [getItemId()](#getItemId--) | Anger en globalt unik identifierare (GUID) som entydigt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Anger en globalt unik identifierare (GUID) som entydigt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Returnerar samlingen av XML-scheman som är associerade med den anpassade XML-delen. |
| [remove()](#remove--) | Tar bort den anpassade xml-delen från presentationen. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Returnerar eller anger xml-data som UTF-8-sträng. Läs/skriv String.

**Returnerar:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Returnerar eller anger xml-data som UTF-8-sträng. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Returnerar eller anger xml-data. Läs/skriv byte[].

**Returnerar:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Returnerar eller anger xml-data. Läs/skriv byte[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Anger en globalt unik identifierare (GUID) som entydigt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. Skrivskyddad java.util.UUID.

**Returnerar:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Anger en globalt unik identifierare (GUID) som entydigt identifierar en enskild anpassad XML-del inom ett Office Open XML-dokument. Skrivskyddad java.util.UUID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Returnerar samlingen av XML-scheman som är associerade med den anpassade XML-delen. Skrivskyddad String[].

**Returnerar:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Tar bort den anpassade xml-delen från presentationen.