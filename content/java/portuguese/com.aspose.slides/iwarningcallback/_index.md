---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface para classes que recebem avisos
type: docs
url: /pt/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interface para classes que recebem avisos
## Métodos

| Método | Descrição |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Método de callback que recebe aviso e decide se a operação deve ser abortada. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Método de callback que recebe aviso e decide se a operação deve ser abortada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Aviso a ser processado. |

**Retorna:**
int - Decisão de abortamento [ReturnAction](../../com.aspose.slides/returnaction).