---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umożliwia utworzenie projektu VBA za pośrednictwem interfejsu COM
type: docs
url: /pl/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Umożliwia utworzenie projektu VBA za pośrednictwem interfejsu COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Tworzy nowy projekt VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Odczytuje projekt VBA z kontenera OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Tworzy nowy projekt VBA.

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nowy projekt VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Odczytuje projekt VBA z kontenera OLE.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Odczytany projekt VBA