---
title: IOverrideTheme
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje nadpisujący motyw.
type: docs
url: /pl/com.aspose.slides/ioverridetheme/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Reprezentuje nadpisujący motyw.
## Metody

| Metoda | Opis |
| --- | --- |
| [isEmpty()](#isEmpty--) | Wartość true oznacza, że ColorScheme, FontScheme, FormatScheme są null i wszelkie nadpisywanie przy użyciu tego obiektu motywu jest wyłączone. |
| [initColorScheme()](#initColorScheme--) | Inicjalizuje ColorScheme nowym obiektem w celu nadpisania ColorScheme obiektu InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inicjalizuje ColorScheme nowym obiektem w celu nadpisania ColorScheme obiektu InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inicjalizuje ColorScheme nowym obiektem w celu nadpisania ColorScheme obiektu InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Inicjalizuje FontScheme nowym obiektem w celu nadpisania FontScheme obiektu InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inicjalizuje FontScheme nowym obiektem w celu nadpisania FontScheme obiektu InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inicjalizuje FontScheme nowym obiektem w celu nadpisania FontScheme obiektu InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Inicjalizuje FormatScheme nowym obiektem w celu nadpisania FormatScheme obiektu InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inicjalizuje FormatScheme nowym obiektem w celu nadpisania FormatScheme obiektu InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inicjalizuje FormatScheme nowym obiektem w celu nadpisania FormatScheme obiektu InheritedTheme. |
| [clear()](#clear--) | Ustawia ColorScheme, FontScheme, FormatScheme na null, aby wyłączyć wszelkie nadpisywanie przy użyciu tego obiektu motywu. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```


Wartość true oznacza, że ColorScheme, FontScheme, FormatScheme są null i wszelkie nadpisywanie przy użyciu tego obiektu motywu jest wyłączone. Wartość tylko do odczytu typu boolean.

**Zwraca:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```


Inicjalizuje ColorScheme nowym obiektem w celu nadpisania ColorScheme obiektu InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```


Inicjalizuje ColorScheme nowym obiektem w celu nadpisania ColorScheme obiektu InheritedTheme.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Dane do inicjalizacji. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```


Inicjalizuje ColorScheme nowym obiektem w celu nadpisania ColorScheme obiektu InheritedTheme. I inicjalizuje dane tego nowego obiektu danymi ColorScheme obiektu InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```


Inicjalizuje FontScheme nowym obiektem w celu nadpisania FontScheme obiektu InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```


Inicjalizuje FontScheme nowym obiektem w celu nadpisania FontScheme obiektu InheritedTheme.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Dane do inicjalizacji. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```


Inicjalizuje FontScheme nowym obiektem w celu nadpisania FontScheme obiektu InheritedTheme. I inicjalizuje dane tego nowego obiektu danymi FontScheme obiektu InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```


Inicjalizuje FormatScheme nowym obiektem w celu nadpisania FormatScheme obiektu InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```


Inicjalizuje FormatScheme nowym obiektem w celu nadpisania FormatScheme obiektu InheritedTheme.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Dane do inicjalizacji. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```


Inicjalizuje FormatScheme nowym obiektem w celu nadpisania FormatScheme obiektu InheritedTheme. I inicjalizuje dane tego nowego obiektu danymi FormatScheme obiektu InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```


Ustawia ColorScheme, FontScheme, FormatScheme na null, aby wyłączyć wszelkie nadpisywanie przy użyciu tego obiektu motywu.