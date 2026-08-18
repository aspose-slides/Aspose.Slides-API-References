---
title: IVideoCollection
second_title: Aspose.Slides Java API hivatkozás
description: Video objektumok gyűjteménye.
type: docs
url: /hu/com.aspose.slides/ivideocollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Video objektumok gyűjteménye.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexen. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Hozzáad egy videófájl másolatát egy másik prezentációból. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Létrehoz és hozzáad egy videót egy prezentációhoz egy folyamatról. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Létrehoz és hozzáad egy videót egy prezentációhoz egy bájt tömbből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Lekéri az elemet a megadott indexen. Csak olvasható [IVideo](../../com.aspose.slides/ivideo).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


Hozzáad egy videófájl másolatát egy másik prezentációból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Forrás video. |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott videó.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Létrehoz és hozzáad egy videót egy prezentációhoz egy folyamatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, amelyből a videófájl hozzáadandó. |
| loadingStreamBehavior | int | A viselkedés, amely a folyamra lesz alkalmazva. |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Létrehoz és hozzáad egy videót egy prezentációhoz egy bájt tömbből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| videoData | byte[] | Videó bájtok. |

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo) - Hozzáadott videó.