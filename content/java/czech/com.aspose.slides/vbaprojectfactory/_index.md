---
title: VbaProjectFactory
second_title: Aspose.Slides pro Java API Reference
description: Umožňuje vytvořit VBA projekt přes COM rozhraní
type: docs
url: /cs/com.aspose.slides/vbaprojectfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Umožňuje vytvořit VBA projekt přes COM rozhraní
## Konstruktor

| Konstruktor | Popis |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getInstance()](#getInstance--) | VBA projekt tovární statická instance. |
| [createVbaProject()](#createVbaProject--) | Vytvoří nový VBA projekt. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Načte VBA projekt z OLE kontejneru. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA projekt tovární statická instance. Pouze pro čtení [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Vrací:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Vytvoří nový VBA projekt.

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nový VBA projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Načte VBA projekt z OLE kontejneru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] |  |

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Načtený VBA projekt