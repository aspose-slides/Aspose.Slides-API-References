---
title: IOverrideTheme
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Representa un tema que sobrescribe.
type: docs
url: /es/com.aspose.slides/ioverridetheme/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Representa un tema que sobrescribe.
## Métodos

| Método | Descripción |
| --- | --- |
| [isEmpty()](#isEmpty--) | Un valor verdadero indica que ColorScheme, FontScheme, FormatScheme son nulos y cualquier sobrescritura con este objeto de tema está deshabilitada. |
| [initColorScheme()](#initColorScheme--) | Inicializa ColorScheme con un nuevo objeto para sobrescribir ColorScheme de InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inicializa ColorScheme con un nuevo objeto para sobrescribir ColorScheme de InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inicializa ColorScheme con un nuevo objeto para sobrescribir ColorScheme de InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Inicializa FontScheme con un nuevo objeto para sobrescribir FontScheme de InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inicializa FontScheme con un nuevo objeto para sobrescribir FontScheme de InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inicializa FontScheme con un nuevo objeto para sobrescribir FontScheme de InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Inicializa FormatScheme con un nuevo objeto para sobrescribir FormatScheme de InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inicializa FormatScheme con un nuevo objeto para sobrescribir FormatScheme de InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inicializa FormatScheme con un nuevo objeto para sobrescribir FormatScheme de InheritedTheme. |
| [clear()](#clear--) | Establece ColorScheme, FontScheme, FormatScheme a nulo para deshabilitar cualquier sobrescritura con este objeto de tema. |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Un valor verdadero indica que ColorScheme, FontScheme, FormatScheme son nulos y cualquier sobrescritura con este objeto de tema está deshabilitada. Boolean de solo lectura.

**Devuelve:**
boolean

### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Inicializa ColorScheme con un nuevo objeto para sobrescribir ColorScheme de InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Inicializa ColorScheme con un nuevo objeto para sobrescribir ColorScheme de InheritedTheme.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Datos para inicializar desde. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Inicializa ColorScheme con un nuevo objeto para sobrescribir ColorScheme de InheritedTheme. Y inicializa los datos de este nuevo objeto con los datos del ColorScheme de InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Inicializa FontScheme con un nuevo objeto para sobrescribir FontScheme de InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Inicializa FontScheme con un nuevo objeto para sobrescribir FontScheme de InheritedTheme.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Datos para inicializar desde. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Inicializa FontScheme con un nuevo objeto para sobrescribir FontScheme de InheritedTheme. Y inicializa los datos de este nuevo objeto con los datos del FontScheme de InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Inicializa FormatScheme con un nuevo objeto para sobrescribir FormatScheme de InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Inicializa FormatScheme con un nuevo objeto para sobrescribir FormatScheme de InheritedTheme.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Datos para inicializar desde. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Inicializa FormatScheme con un nuevo objeto para sobrescribir FormatScheme de InheritedTheme. Y inicializa los datos de este nuevo objeto con los datos del FormatScheme de InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Establece ColorScheme, FontScheme, FormatScheme a nulo para deshabilitar cualquier sobrescritura con este objeto de tema.