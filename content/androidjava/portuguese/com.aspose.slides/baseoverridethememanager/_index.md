---
title: BaseOverrideThemeManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Classe base para classes que fornecem acesso a diferentes tipos de temas sobrescritos.
type: docs
url: /pt/com.aspose.slides/baseoverridethememanager/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Classe base para classes que fornecem acesso a diferentes tipos de temas sobrescritos.
## Métodos

| Método | Descrição |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Retorna o objeto de tema sobrescrito. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Retorna o objeto de tema sobrescrito. |
| [createThemeEffective()](#createThemeEffective--) | Retorna o objeto de tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina se OverrideTheme sobrescreve o tema efetivo herdado ou não. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Aplica esquema de cores extra a um slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Retorna o objeto de tema sobrescrito. Leitura/Gravação [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Retorna:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Retorna o objeto de tema sobrescrito. Leitura/Gravação [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Retorna o objeto de tema.

**Retorna:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Determina se OverrideTheme sobrescreve o tema efetivo herdado ou não. Para habilitar OverrideTheme para sobrescrita, use os métodos OverrideTheme.Init\*(). Para desabilitar OverrideTheme da sobrescrita, use o método OverrideTheme.Clear(). Somente leitura boolean.

**Retorna:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Aplica esquema de cores extra a um slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | O objeto [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |