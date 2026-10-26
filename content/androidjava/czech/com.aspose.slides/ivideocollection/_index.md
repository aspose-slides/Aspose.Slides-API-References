---
title: IVideoCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje kolekci objektů Video.
type: docs
url: /cs/com.aspose.slides/ivideocollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Představuje kolekci objektů Video.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Přidá kopii video souboru z jiné prezentace. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Vytvoří a přidá video do prezentace ze streamu. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Vytvoří a přidá video do prezentace z bytového pole. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

Získá prvek na určeném indexu. Pouze pro čtení [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

Přidá kopii video souboru z jiné prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Zdrojové video. |

**Návratová hodnota:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Vytvoří a přidá video do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se přidá video soubor. |
| loadingStreamBehavior | int | Chování, které bude použito na stream. |

**Návratová hodnota:**
[IVideo](../../com.aspose.slides/ivideo) - Přidáno [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

Vytvoří a přidá video do prezentace z bytového pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| videoData | byte[] | Bajty videa. |

**Návratová hodnota:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané video.