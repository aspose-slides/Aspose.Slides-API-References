---
title: IMasterTheme
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um tema mestre.
type: docs
url: /pt/com.aspose.slides/imastertheme/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Representa um tema mestre.
## Métodos

| Método | Descrição |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Retorna a coleção de esquemas de cores adicionais. |
| [getName()](#getName--) | Retorna o nome de um tema. |
| [setName(String value)](#setName-java.lang.String-) | Retorna o nome de um tema. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Retorna a coleção de esquemas de cores adicionais. Esses esquemas não afetam a aparência da apresentação, podendo ser selecionados como esquema de cores principal para um slide. Somente leitura [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Retorna:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Retorna o nome de um tema. Leitura/gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retorna o nome de um tema. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |