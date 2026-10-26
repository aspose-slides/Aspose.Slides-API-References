---
title: VbaProjectFactory
second_title: Riferimento API di Aspose.Slides per Java
description: Consente di creare un progetto VBA tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/vbaprojectfactory/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Consente di creare un progetto VBA tramite interfaccia COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Metodi

| Metodo | Descrizione |
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


Istanza statica della fabbrica di progetti VBA. Sola lettura [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Restituisce:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Crea un nuovo progetto VBA.

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nuovo progetto VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Legge il progetto VBA dal contenitore OLE.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] |  |

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Leggi progetto VBA