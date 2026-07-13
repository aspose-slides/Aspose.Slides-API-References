---
title: VbaProjectFactory
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Consente di creare un progetto VBA tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/vbaprojectfactory/
---
**Eredità:**
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
| [getInstance()](#getInstance--) | Istanza statica della factory di progetto VBA. |
| [createVbaProject()](#createVbaProject--) | Crea un nuovo progetto VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Legge il progetto VBA dal contenitore OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Istanza statica della factory di progetto VBA. Solo lettura [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

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