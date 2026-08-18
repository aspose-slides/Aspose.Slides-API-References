---
title: MasterThemeManager
second_title: Referência da API Aspose.Slides para Java
description: Fornece acesso ao tema mestre da apresentação.
type: docs
url: /pt/com.aspose.slides/masterthememanager/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Fornece acesso ao tema mestre da apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Retorna o objeto de tema de substituição. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Retorna o objeto de tema de substituição. |
| [createThemeEffective()](#createThemeEffective--) | Retorna o objeto de tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina se OverrideTheme substitui o tema efetivo herdado (Presentation.MasterTheme) ou não. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Determina se OverrideTheme substitui o tema efetivo herdado (Presentation.MasterTheme) ou não. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Aplica esquema de cores extra a um slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Retorna o objeto de tema de substituição. Leitura/gravação [IMasterTheme](../../com.aspose.slides/imastertheme).

**Retorno:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Retorna o objeto de tema de substituição. Leitura/gravação [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Retorna o objeto de tema.

**Retorno:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Determina se OverrideTheme substitui o tema efetivo herdado (Presentation.MasterTheme) ou não. Leitura/gravação booleano.

**Retorno:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Determina se OverrideTheme substitui o tema efetivo herdado (Presentation.MasterTheme) ou não. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Aplica esquema de cores extra a um slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objeto. |