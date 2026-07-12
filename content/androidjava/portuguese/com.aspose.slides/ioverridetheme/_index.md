---
title: IOverrideTheme
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa um tema de substituição.
type: docs
url: /pt/com.aspose.slides/ioverridetheme/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Representa um tema de substituição.
## Métodos

| Método | Descrição |
| --- | --- |
| [isEmpty()](#isEmpty--) | Valor verdadeiro significa que ColorScheme, FontScheme, FormatScheme é nulo e qualquer sobrescrita com este objeto de tema está desativada. |
| [initColorScheme()](#initColorScheme--) | Inicializa ColorScheme com um novo objeto para sobrescrever ColorScheme de InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inicializa ColorScheme com um novo objeto para sobrescrever ColorScheme de InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inicializa ColorScheme com um novo objeto para sobrescrever ColorScheme de InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Inicializa FontScheme com um novo objeto para sobrescrever FontScheme de InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inicializa FontScheme com um novo objeto para sobrescrever FontScheme de InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inicializa FontScheme com um novo objeto para sobrescrever FontScheme de InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Inicializa FormatScheme com um novo objeto para sobrescrever FormatScheme de InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inicializa FormatScheme com um novo objeto para sobrescrever FormatScheme de InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inicializa FormatScheme com um novo objeto para sobrescrever FormatScheme de InheritedTheme. |
| [clear()](#clear--) | Define ColorScheme, FontScheme, FormatScheme como nulo para desativar qualquer sobrescrita com este objeto de tema. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Valor verdadeiro significa que ColorScheme, FontScheme, FormatScheme é nulo e qualquer sobrescrita com este objeto de tema está desativada. Booleano somente leitura.

**Retorna:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Inicializa ColorScheme com um novo objeto para sobrescrever ColorScheme de InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Inicializa ColorScheme com um novo objeto para sobrescrever ColorScheme de InheritedTheme.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Dados para inicializar a partir de. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Inicializa ColorScheme com um novo objeto para sobrescrever ColorScheme de InheritedTheme. E inicializa os dados deste novo objeto com os dados do ColorScheme de InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Inicializa FontScheme com um novo objeto para sobrescrever FontScheme de InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Inicializa FontScheme com um novo objeto para sobrescrever FontScheme de InheritedTheme.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Dados para inicializar a partir de. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Inicializa FontScheme com um novo objeto para sobrescrever FontScheme de InheritedTheme. E inicializa os dados deste novo objeto com os dados do FontScheme de InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Inicializa FormatScheme com um novo objeto para sobrescrever FormatScheme de InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Inicializa FormatScheme com um novo objeto para sobrescrever FormatScheme de InheritedTheme.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Dados para inicializar a partir de. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Inicializa FormatScheme com um novo objeto para sobrescrever FormatScheme de InheritedTheme. E inicializa os dados deste novo objeto com os dados do FormatScheme de InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Define ColorScheme, FontScheme, FormatScheme como nulo para desativar qualquer sobrescrita com este objeto de tema.