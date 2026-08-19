---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /it/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interfaccia per le classi che ricevono avvisi
## Metodi

| Method | Description |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Metodo callback che riceve un avviso e decide se l'operazione debba essere interrotta. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Metodo callback che riceve un avviso e decide se l'operazione debba essere interrotta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Avviso da elaborare. |

**Restituisce:**
int - Decisione di interruzione [ReturnAction](../../com.aspose.slides/returnaction).