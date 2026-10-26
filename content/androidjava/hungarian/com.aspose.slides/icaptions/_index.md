---
title: ICaptions
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A WebVTT zárt feliratokat képviseli.
type: docs
url: /hu/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

A WebVTT zárt feliratokat képviseli.
## Metódusok

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Visszaadja a zárt feliratok globálisan egyedi azonosítóját (GUID). |
| [getLabel()](#getLabel--) | Visszaadja vagy beállítja a zárt feliratok címkéjét. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Visszaadja vagy beállítja a zárt feliratok címkéjét. |
| [getBinaryData()](#getBinaryData--) | Visszaadja a zárt feliratok bináris adatát. |
| [getDataAsString()](#getDataAsString--) | Visszaadja a zárt feliratok adatait UTF-8 kódolású karakterláncként, csak olvasható String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Visszaadja a zárt feliratok globálisan egyedi azonosítóját (GUID). Csak olvasható java.util.UUID.

**Returns:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Visszaadja vagy beállítja a zárt feliratok címkéjét. Olvasás/írás String.

**Returns:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Visszaadja vagy beállítja a zárt feliratok címkéjét. Olvasás/írás String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Visszaadja a zárt feliratok bináris adatát. Csak olvasható byte[].

**Returns:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Visszaadja a zárt feliratok adatait UTF-8 kódolású karakterláncként, csak olvasható String.

**Returns:**
java.lang.String