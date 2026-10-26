---
title: IWarningCallback
second_title: Aspose.Slides per Android tramite Java API Reference
description: Interfaccia per le classi che ricevono un avviso
type: docs
url: /it/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interfaccia per le classi che ricevono un avviso
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Metodo di callback che riceve un avviso e decide se l'operazione deve essere interrotta. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Metodo di callback che riceve un avviso e decide se l'operazione deve essere interrotta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Avviso da elaborare. |

**Restituisce:**
int - Decisione di interruzione [ReturnAction](../../com.aspose.slides/returnaction).