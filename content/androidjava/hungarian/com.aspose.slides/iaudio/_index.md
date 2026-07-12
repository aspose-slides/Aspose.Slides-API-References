---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Beágyazott audiofájlt reprezentál.
type: docs
url: /hu/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Beágyazott audiofájlt reprezentál.
## Methods

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Visszaadja egy audio MIME-típusát, amely a (\#getBinaryData.getBinaryData) által kódolt. |
| [getBinaryData()](#getBinaryData--) | Visszaadja egy audio adatmásolatát. |
| [getStream()](#getStream--) | Visszaadja a Stream-et olvasáshoz. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Visszaad egy audio MIME típusát, amely a (\#getBinaryData.getBinaryData) által kódolt. Csak olvasható String.

**Visszatér:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Visszaadja egy audio adatmásolatát. Nagy mennyiségű adat esetén javasolt a \#getStream.getStream metódus használata, hogy elkerüljük az audio adatának szükségtelen betöltését a memóriába vagy akár OutOfMemoryException kivételt. Csak olvasható byte[].

**Visszatér:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Visszaad egy Stream-et olvasáshoz. Használja a 'using' kulcsszót vagy zárja le az áramlást a használat után.

**Visszatér:**
java.io.InputStream - Olvasáshoz használt Stream.