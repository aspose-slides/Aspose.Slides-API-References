---
title: IOverrideTheme
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje motyw nadpisujący.
type: docs
url: /pl/com.aspose.slides/ioverridetheme/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Reprezentuje motyw nadpisujący.
## Metody

| Metoda | Opis |
| --- | --- |
| [isEmpty()](#isEmpty--) | Wartość true oznacza, że ColorScheme, FontScheme, FormatScheme jest null i wszelkie nadpisywanie przy użyciu tego obiektu motywu jest wyłączone. |
| [initColorScheme()](#initColorScheme--) | Inicjalizuj ColorScheme nowym obiektem w celu nadpisywania ColorScheme z InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inicjalizuj ColorScheme nowym obiektem w celu nadpisywania ColorScheme z InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inicjalizuj ColorScheme nowym obiektem w celu nadpisywania ColorScheme z InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Inicjalizuj FontScheme nowym obiektem w celu nadpisywania FontScheme z InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inicjalizuj FontScheme nowym obiektem w celu nadpisywania FontScheme z InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inicjalizuj FontScheme nowym obiektem w celu nadpisywania FontScheme z InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Inicjalizuj FormatScheme nowym obiektem w celu nadpisywania FormatScheme z InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inicjalizuj FormatScheme nowym obiektem w celu nadpisywania FormatScheme z InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inicjalizuj FormatScheme nowym obiektem w celu nadpisywania FormatScheme z InheritedTheme. |
| [clear()](#clear--) | Ustaw ColorScheme, FontScheme, FormatScheme na null, aby wyłączyć wszelkie nadpisywanie przy użyciu tego obiektu motywu. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Wartość true oznacza, że ColorScheme, FontScheme, FormatScheme jest null i wszelkie nadpisywanie przy użyciu tego obiektu motywu jest wyłączone. Boolean tylko do odczytu.

**Zwraca:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Inicjalizuj ColorScheme nowym obiektem w celu nadpisywania ColorScheme z InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Inicjalizuj ColorScheme nowym obiektem w celu nadpisywania ColorScheme z InheritedTheme.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Dane do inicjalizacji. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Inicjalizuj ColorScheme nowym obiektem w celu nadpisywania ColorScheme z InheritedTheme. Następnie zainicjalizuj dane tego nowego obiektu danymi ColorScheme z InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Inicjalizuj FontScheme nowym obiektem w celu nadpisywania FontScheme z InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Inicjalizuj FontScheme nowym obiektem w celu nadpisywania FontScheme z InheritedTheme.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Dane do inicjalizacji. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Inicjalizuj FontScheme nowym obiektem w celu nadpisywania FontScheme z InheritedTheme. Następnie zainicjalizuj dane tego nowego obiektu danymi FontScheme z InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Inicjalizuj FormatScheme nowym obiektem w celu nadpisywania FormatScheme z InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Inicjalizuj FormatScheme nowym obiektem w celu nadpisywania FormatScheme z InheritedTheme.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Dane do inicjalizacji. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Inicjalizuj FormatScheme nowym obiektem w celu nadpisywania FormatScheme z InheritedTheme. Następnie zainicjalizuj dane tego nowego obiektu danymi FormatScheme z InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Ustaw ColorScheme, FontScheme, FormatScheme na null, aby wyłączyć wszelkie nadpisywanie przy użyciu tego obiektu motywu.