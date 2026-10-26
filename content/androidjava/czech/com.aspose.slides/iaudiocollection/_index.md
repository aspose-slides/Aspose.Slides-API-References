---
title: IAudioCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje kolekci vložených audio souborů.
type: docs
url: /cs/com.aspose.slides/iaudiocollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Představuje kolekci vložených audio souborů.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadaném indexu. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Přidá kopii audio souboru z jiné prezentace. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Vytvoří a přidá audio do prezentace ze streamu. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Vytvoří a přidá audio do prezentace ze streamu. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Vytvoří a přidá audio do prezentace z pole bajtů. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Vrací prvek na zadaném indexu. Pouze pro čtení [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Přidá kopii audio souboru z jiné prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Zdrojové audio. |

**Návratová hodnota:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Vytvoří a přidá audio do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se má audio přidat. |

**Návratová hodnota:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Vytvoří a přidá audio do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se má video audio přidat. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) která bude použita na stream. |

**Návratová hodnota:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Vytvoří a přidá audio do prezentace z pole bajtů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| audioData | byte[] | Audio bajty. |

**Návratová hodnota:**
[IAudio](../../com.aspose.slides/iaudio) - Přidané audio.