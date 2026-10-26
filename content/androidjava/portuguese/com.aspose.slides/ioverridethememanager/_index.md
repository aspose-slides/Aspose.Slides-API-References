---
title: IOverrideThemeManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece acesso a diferentes tipos de temas substituídos.
type: docs
url: /pt/com.aspose.slides/ioverridethememanager/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Fornece acesso a diferentes tipos de temas substituídos.
## Métodos

| Método | Descrição |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina se OverrideTheme substitui o tema efetivo herdado ou não. |
| [getOverrideTheme()](#getOverrideTheme--) | Retorna o objeto de tema substituto. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Retorna o objeto de tema substituto. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Determina se OverrideTheme substitui o tema efetivo herdado ou não. Para habilitar OverrideTheme para substituição, use os métodos OverrideTheme.Init\*(). Para desabilitar OverrideTheme de substituição, use o método OverrideTheme.Clear(). Boolean de somente leitura.

**Retorna:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Retorna o objeto de tema substituto. Leitura/gravação [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Retorna:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Retorna o objeto de tema substituto. Leitura/gravação [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |