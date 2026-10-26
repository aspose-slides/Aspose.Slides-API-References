---
title: VbaProjectFactory
second_title: Aspose.Slides för Java API-referens
description: Tillåter att skapa VBA-projekt via COM-gränssnitt
type: docs
url: /sv/com.aspose.slides/vbaprojectfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Tillåter att skapa VBA-projekt via COM-gränssnitt
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInstance()](#getInstance--) | Statisk instans av VBA-projektfabrik. |
| [createVbaProject()](#createVbaProject--) | Skapar ett nytt VBA-projekt. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Läser VBA-projekt från OLE-behållare. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Statisk instans av VBA-projektfabrik. Skrivskyddad [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Returnerar:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Skapar ett nytt VBA-projekt.

**Returnerar:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nytt VBA-projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Läser VBA-projekt från OLE-behållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] |  |

**Returnerar:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Läs VBA-projekt