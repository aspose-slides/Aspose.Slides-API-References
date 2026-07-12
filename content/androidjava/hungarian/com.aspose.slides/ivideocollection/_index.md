---
title: IVideoCollection
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Videóobjektumok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ivideocollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Represents a collection of Video objects.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Egy videofájl másik prezentációból származó másolatát adja hozzá. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Videót hoz létre és ad hozzá egy prezentációhoz egy adatfolyamból. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Videót hoz létre és ad hozzá egy prezentációhoz egy bájttömbből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak olvasható [IVideo](../../com.aspose.slides/ivideo).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

Egy videofájl másik prezentációból származó másolatát adja hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Forrás videó. |

**Visszatérési érték:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott videó.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Videót hoz létre és ad hozzá egy prezentációhoz egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | A videofájl hozzáadásához használt adatfolyam. |
| loadingStreamBehavior | int | A stream-re alkalmazandó viselkedés. |

**Visszatérési érték:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

Videót hoz létre és ad hozzá egy prezentációhoz egy bájttömbből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| videoData | byte[] | Videó bájtok. |

**Visszatérési érték:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott videó.