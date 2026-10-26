---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for classes which receive warning
type: docs
url: /pt/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interface para classes que recebem aviso
## Métodos

| Método | Descrição |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Método de retorno de chamada que recebe aviso e decide se a operação deve ser abortada. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Método de retorno de chamada que recebe aviso e decide se a operação deve ser abortada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Aviso a processar. |

**Retorna:**
int - Decisão de abortamento [ReturnAction](../../com.aspose.slides/returnaction).