---
title: Captions
second_title: Aspose.Slides Androidra Java API hivatkozás útján
description: A WebVTT zárt feliratokat képviseli.
type: docs
url: /hu/com.aspose.slides/captions/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

A WebVTT zárt feliratokat képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Visszaadja a zárt feliratok globálisan egyedi azonosítóját (GUID). |
| [getLabel()](#getLabel--) | Visszaadja vagy beállítja a zárt feliratok címkéjét. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Visszaadja vagy beállítja a zárt feliratok címkéjét. |
| [getBinaryData()](#getBinaryData--) | Visszaadja a zárt feliratok bináris adatát. |
| [getDataAsString()](#getDataAsString--) | Visszaadja a zárt feliratok adatait UTF-8 kódolású karakterláncként csak olvasható String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Visszaadja a zárt feliratok globálisan egyedi azonosítóját (GUID). Csak olvasható java.util.UUID.

**Visszatér:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Visszaadja vagy beállítja a zárt feliratok címkéjét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Visszaadja vagy beállítja a zárt feliratok címkéjét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Visszaadja a zárt feliratok bináris adatát. Csak olvasható byte[] .

**Visszatér:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Visszaadja a zárt feliratok adatait UTF-8 kódolású karakterláncként csak olvasható String.

**Visszatér:**
java.lang.String