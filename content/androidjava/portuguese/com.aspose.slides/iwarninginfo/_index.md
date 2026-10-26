---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
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
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Se receiver não for nulo, termina o aviso para um receiver especificado e lança a AbortRequestedException se o receiver decidir abortar a operação. |
| [getWarningType()](#getWarningType--) | Retorna um tipo de aviso. |
| [getDescription()](#getDescription--) | Retorna uma descrição legível por humanos deste aviso. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Se receiver não for nulo, termina o aviso para um receiver especificado e lança a AbortRequestedException se o receiver decidir abortar a operação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objeto receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

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