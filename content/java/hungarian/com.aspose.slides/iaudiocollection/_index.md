---
title: IAudioCollection
second_title: Aspose.Slides for Java API Referencia
description: Beágyazott hangfájlok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/iaudiocollection/
---
**Minden implementált interfész:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Beágyazott hangfájlok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Megkapja az elemet a megadott indexen. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Egy másik prezentációból másol egy hangfájl másolatát. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Létrehoz és hozzáad egy hangot a prezentációhoz egy adatfolyamból. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Létrehoz és hozzáad egy hangot a prezentációhoz egy adatfolyamból. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Létrehoz és hozzáad egy hangot a prezentációhoz egy bájt tömbből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Megkapja az elemet a megadott indexen. Csak olvasható [IAudio](../../com.aspose.slides/iaudio).

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

Egy másik prezentációból másol egy hangfájlt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Forrás hang. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott hang.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Létrehoz és hozzáad egy hangot a prezentációhoz egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Adatfolyam, amelyből a hangot hozzáadja. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott hang.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Létrehoz és hozzáad egy hangot a prezentációhoz egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Adatfolyam, amelyből a hangot hozzáadja. |
| loadingStreamBehavior | int | A [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) amely a folyamra lesz alkalmazva. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott hang.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Létrehoz és hozzáad egy hangot a prezentációhoz egy bájt tömbből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audioData | byte[] | Hang bitek. |

**Visszatérési érték:**
[IAudio](../../com.aspose.slides/iaudio) - Hozzáadott hang.