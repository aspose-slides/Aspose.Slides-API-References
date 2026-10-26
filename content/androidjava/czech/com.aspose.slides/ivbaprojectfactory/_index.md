---
title: IVbaProjectFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvořit VBA projekt přes COM rozhraní
type: docs
url: /cs/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Umožňuje vytvořit VBA projekt přes COM rozhraní
## Metody

| Metoda | Popis |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Vytvoří nový VBA projekt. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Čte VBA projekt z OLE kontejneru. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Vytvoří nový VBA projekt.

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nový VBA projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Čte VBA projekt z OLE kontejneru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Načtený VBA projekt