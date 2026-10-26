---
title: IAudioCollection
second_title: Aspose.Slides Androidra a Java API hivatkozáson keresztül
description: Beágyazott audiofájlok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/iaudiocollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Beágyazott audiofájlok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Hozzáad egy audio fájl másolatát egy másik prezentációból. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Létrehoz és hozzáad egy audio-t egy prezentációhoz adatfolyamból. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Létrehoz és hozzáad egy audio-t egy prezentációhoz adatfolyamból. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Létrehoz és hozzáad egy audio-t egy prezentációhoz bájt tömbből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Lekéri a megadott indexű elemet. Csak olvasható [IAudio](../../com.aspose.slides/iaudio).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

Hozzáad egy audio fájl másolatát egy másik prezentációból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Forrás audio. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Létrehoz és hozzáad egy audio-t egy prezentációhoz adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Az adatfolyam, amelyből az audiot hozzáadja. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Létrehoz és hozzáad egy audio-t egy prezentációhoz adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Az adatfolyam, amelyből a video audiot hozzáadja. |
| loadingStreamBehavior | int | A [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) amely az adatfolyamra lesz alkalmazva. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Létrehoz és hozzáad egy audio-t egy prezentációhoz bájt tömbből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audioData | byte[] | Audio bájtok. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott audio.