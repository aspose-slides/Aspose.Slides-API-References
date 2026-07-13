---
title: VbaProjectFactory
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Umožňuje vytvořit VBA projekt pomocí rozhraní COM
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

Umožňuje vytvořit VBA projekt pomocí COM rozhraní
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project factory static instance. |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Statická instance továrny VBA projektů. Pouze pro čtení [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Návratová hodnota:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Vytváří nový VBA projekt.

**Návratová hodnota:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nový VBA projekt
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Čte VBA projekt z OLE kontejneru.

**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| data | byte[] |  |

**Návratová hodnota:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Přečtený VBA projekt