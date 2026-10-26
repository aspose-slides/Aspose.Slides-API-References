---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Umożliwia tworzenie projektu VBA przez interfejs COM
type: docs
url: /pl/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Allows to create VBA project via COM interface
## Metody

| Metoda | Opis |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Odczytuje projekt VBA z kontenera OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Creates new VBA project.

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nowy projekt VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Reads VBA project from OLE container.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**Zwraca:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Odczytany projekt VBA