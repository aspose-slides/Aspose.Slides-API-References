---
title: VbaProjectFactory
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Umożliwia tworzenie projektu VBA za pośrednictwem interfejsu COM
type: docs
url: /pl/com.aspose.slides/vbaprojectfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Umożliwia tworzenie projektu VBA przez interfejs COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInstance()](#getInstance--) | Statyczna instancja fabryki projektu VBA. |
| [createVbaProject()](#createVbaProject--) | Tworzy nowy projekt VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Odczytuje projekt VBA z kontenera OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Statyczna instancja fabryki projektu VBA. Tylko do odczytu [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Zwraca:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Tworzy nowy projekt VBA.

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nowy projekt VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Odczytuje projekt VBA z kontenera OLE.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] |  |

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Projekt VBA odczytany