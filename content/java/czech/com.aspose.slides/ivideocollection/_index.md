---
title: IVideoCollection
second_title: Aspose.Slides pro Java API Reference
description: Representuje kolekci objektů Video.
type: docs
url: /cs/com.aspose.slides/ivideocollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Representuje kolekci objektů Video.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Přidá kopii video souboru z jiné prezentace. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Vytvoří a přidá video do prezentace ze streamu. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Vytvoří a přidá video do prezentace z pole bajtů. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Získá prvek na zadaném indexu. Pouze ke čtení [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
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

**Vrací:**
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

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo) - Přidaný [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Vytvoří a přaddá video do prezentace z pole bajtů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| videoData | byte[] | Bity videa. |

**Vrací:**
[IVideo](../../com.aspose.slides/ivideo) - Přidané video.