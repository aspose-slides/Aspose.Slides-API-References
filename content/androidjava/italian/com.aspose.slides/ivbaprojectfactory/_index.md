---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Consente di creare progetti VBA tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Consente di creare progetti VBA tramite interfaccia COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Crea un nuovo progetto VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Legge il progetto VBA dal contenitore OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Crea un nuovo progetto VBA.

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nuovo progetto VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Legge il progetto VBA dal contenitore OLE.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Dati Ole byte[] |

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Progetto VBA letto