---
title: CustomXmlPart
second_title: Aspose.Slides Androidhoz a Java API hivatkozáson keresztül
description: Az egyéni XML részt képviseli.
type: docs
url: /hu/com.aspose.slides/customxmlpart/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Az egyéni XML részt képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getXmlData()](#getXmlData--) | Visszaadja vagy beállítja az XML adatot. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Visszaadja vagy beállítja az XML adatot. |
| [getXmlAsString()](#getXmlAsString--) | Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. |
| [getItemId()](#getItemId--) | Megadja a globálisan egyedi azonosítót (GUID), amely egyetlen egyéni XML részt azonosít egy Office Open XML dokumentumban. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Megadja a globálisan egyedi azonosítót (GUID), amely egyetlen egyéni XML részt azonosít egy Office Open XML dokumentumban. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Visszaadja az egyéni XML részhez kapcsolódó XML séma gyűjteményt. |
| [remove()](#remove--) | Eltávolítja az egyéni XML részt a bemutatóból. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Visszaadja vagy beállítja az XML adatot. Olvasás/írás byte[].

**Visszatér:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Visszaadja vagy beállítja az XML adatot. Olvasás/írás byte[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Megadja a globálisan egyedi azonosítót (GUID), amely egyetlen egyéni XML részt azonosít egy Office Open XML dokumentumban. Csak olvasható java.util.UUID.

**Visszatér:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Megadja a globálisan egyedi azonosítót (GUID), amely egyetlen egyéni XML részt azonosít egy Office Open XML dokumentumban. Csak olvasható java.util.UUID.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Visszaadja az egyéni XML részhez kapcsolódó XML séma gyűjteményt. Csak olvasható String[].

**Visszatér:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Eltávolítja az egyéni XML részt a bemutatóból.