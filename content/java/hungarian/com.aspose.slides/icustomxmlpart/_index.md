---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Egyedi XML részt képvisel.
type: docs
url: /hu/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Egyedi XML részt képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. |
| [getXmlData()](#getXmlData--) | Visszaadja vagy beállítja az XML adatot. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Visszaadja vagy beállítja az XML adatot. |
| [getItemId()](#getItemId--) | Megad egy globálisan egyedi azonosítót (GUID), amely egyetlen egyedi XML részt azonosít az Office Open XML dokumentumban. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Megad egy globálisan egyedi azonosítót (GUID), amely egyetlen egyedi XML részt azonosít az Office Open XML dokumentumban. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Visszaadja a custom XML részhez tartozó XML séma gyűjteményt. |
| [remove()](#remove--) | Eltávolítja az egyedi XML részt a prezentációból. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Visszaadja vagy beállítja az XML adatot UTF-8 karakterláncként. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Visszaadja vagy beállítja az XML adatot. Olvasás/írás byte[].

**Visszatérési érték:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Visszaadja vagy beállítja az XML adatot. Olvasás/írás byte[].

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Megad egy globálisan egyedi azonosítót (GUID), amely egyetlen egyedi XML részt azonosít az Office Open XML dokumentumban. Csak olvasható java.util.UUID.

**Visszatérési érték:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Megad egy globálisan egyedi azonosítót (GUID), amely egyetlen egyedi XML részt azonosít az Office Open XML dokumentumban. Csak olvasható java.util.UUID.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Visszaadja a custom XML részhez tartozó XML séma gyűjteményt. Csak olvasható String[].

**Visszatérési érték:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja az egyedi XML részt a prezentációból.