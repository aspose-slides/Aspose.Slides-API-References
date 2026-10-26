---
title: IVbaModuleCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av VBA Project-moduler.
type: docs
url: /sv/com.aspose.slides/ivbamodulecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Representerar en samling av VBA Project-moduler.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Lägger till en ny tom modul i VBA Project. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Lägger till en ny tom modul i VBA Project.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Modulens namn |

**Returnerar:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Tillagd modul.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Tar bort den första förekomsten av ett specifikt objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Modulen som ska tas bort från samlingen. |