---
title: Audio
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Beágyazott hangfájlt képvisel.
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

Beágyazott hangfájlt képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getContentType()](#getContentType--) | Visszaad egy hang MIME-típusát, amely a (\#getBinaryData.getBinaryData) által kódolt. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Visszaad egy hang MIME-típusát, amely a (\#getBinaryData.getBinaryData) által kódolt. |
| [getBinaryData()](#getBinaryData--) | Visszaadja a hang adatmásolatát. |
| [getStream()](#getStream--) | Visszaad egy Stream stream-et olvasáshoz. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Visszaad egy hang MIME-típusát, amely a (\#getBinaryData.getBinaryData) által kódolt. Csak olvasható String.

**Visszatérési érték:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Visszaad egy hang MIME-típusát, amely a (\#getBinaryData.getBinaryData) által kódolt. Csak olvasható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Visszaadja a hang adatmásolatát. Nagy adatmennyiség esetén fontolja meg a \#getStream.getStream metódus használatát, hogy elkerülje a hang adatainak felesleges betöltését a memóriába, vagy akár OutOfMemoryException kivételt. Csak olvasható byte[].

**Visszatérési érték:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Visszaad egy Stream stream-et olvasáshoz. Használja a 'using'-et, vagy zárja le a stream-et a használat után.

**Visszatérési érték:**
java.io.InputStream - Olvasásra szolgáló stream.