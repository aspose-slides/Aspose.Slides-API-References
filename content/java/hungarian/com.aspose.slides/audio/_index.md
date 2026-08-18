---
title: Audio
second_title: Aspose.Slides Java API referencia
description: Beágyazott audiofájlt képvisel.
type: docs
url: /hu/com.aspose.slides/audio/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Beágyazott audiofájlt képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getContentType()](#getContentType--) | Visszaad egy audio MIME-típust, amely a (\#getBinaryData.getBinaryData) által kódolt. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Visszaad egy audio MIME-típust, amely a (\#getBinaryData.getBinaryData) által kódolt. |
| [getBinaryData()](#getBinaryData--) | Visszaad egy audio adatmásolatot. |
| [getStream()](#getStream--) | Visszaad Stream adatfolyamot olvasáshoz. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Visszaad egy audio MIME-típust, amely a (\#getBinaryData.getBinaryData) által kódolt. Csak olvasható String.

**Visszaad:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Visszaad egy audio MIME-típust, amely a (\#getBinaryData.getBinaryData) által kódolt. Csak olvasható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Visszaad egy audio adatmásolatot. Nagy mennyiségű adat esetén fontolja meg a \#getStream.getStream metódus használatát, hogy elkerülje az audio adatának szükségtelen betöltését a memóriába vagy akár OutOfMemoryException-t. Csak olvasható byte[].

**Visszaad:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Visszaad Stream adatfolyamot olvasáshoz. Használja a 'using' vagy zárja be az adatfolyamot a használat után.

**Visszaad:**
java.io.InputStream - Olvasáshoz szolgáló Stream.