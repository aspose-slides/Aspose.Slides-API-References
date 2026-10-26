---
title: IVbaProjectFactory
second_title: Aspose.Slides pro Java API Reference
description: Umožňuje vytvořit VBA projekt pomocí rozhraní COM
type: docs
url: /cs/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Umožňuje vytvořit VBA projekt pomocí rozhraní COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Vytvoří nový VBA projekt.

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - nový VBA projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Načte VBA projekt z kontejneru OLE.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Načtený VBA projekt