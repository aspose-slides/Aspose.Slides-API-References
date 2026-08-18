---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: A WebVTT zárt feliratokat reprezentálja.
type: docs
url: /hu/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

A WebVTT zárt feliratokat reprezentálja.
## Módszerek

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Visszaadja a zárt feliratok globálisan egyedi azonosítóját (GUID). |
| [getLabel()](#getLabel--) | Visszaadja vagy beállítja a zárt feliratok címkéjét. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Visszaadja vagy beállítja a zárt feliratok címkéjét. |
| [getBinaryData()](#getBinaryData--) | Visszaadja a zárt feliratok bináris adatait. |
| [getDataAsString()](#getDataAsString--) | Visszaadja a zárt feliratok adatait UTF-8 kódolású karakterláncként. Csak olvasható String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Visszaadja a zárt feliratok globálisan egyedi azonosítóját (GUID). Csak olvasható java.util.UUID.

**Visszatér:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Visszaadja vagy beállítja a zárt feliratok címkéjét. Olvasás-írás String.

**Visszatér:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Visszaadja vagy beállítja a zárt feliratok címkéjét. Olvasás-írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Visszaadja a zárt feliratok bináris adatait. Csak olvasható byte[].

**Visszatér:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Visszaadja a zárt feliratok adatait UTF-8 kódolású karakterláncként. Csak olvasható String.

**Visszatér:**
java.lang.String