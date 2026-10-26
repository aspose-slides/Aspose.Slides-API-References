---
title: IWarningInfo
second_title: Referência da API Aspose.Slides para Java
description: Representa uma interface base para todos os avisos.
type: docs
url: /pt/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Representa uma interface base para todos os avisos.
## Métodos

| Método | Descrição |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Se o receptor não for nulo, finaliza o aviso para um receptor especificado e lança a AbortRequestedException se o receptor decidir abortar uma operação. |
| [getWarningType()](#getWarningType--) | Retorna um tipo de aviso. |
| [getDescription()](#getDescription--) | Retorna uma descrição legível por humanos deste aviso. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Se o receptor não for nulo, finaliza o aviso para um receptor especificado e lança a AbortRequestedException se o receptor decidir abortar uma operação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | objeto Receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Retorna um tipo de aviso. Somente leitura [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Retorna:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Retorna uma descrição legível por humanos deste aviso. Somente leitura String.

**Retorna:**
java.lang.String