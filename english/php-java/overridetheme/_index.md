---
title: OverrideTheme
type: docs
weight: 0
url: /php-java/overridetheme/
---

# OverrideTheme class

 Represents a overriding theme.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [clear](/slides/php-java/overridetheme/clear/)() | void | Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object. |
| [getColorScheme](/slides/php-java/overridetheme/getcolorscheme/)() | IColorScheme | Returns the color scheme. Read-only IColorScheme. |
| [getFontScheme](/slides/php-java/overridetheme/getfontscheme/)() | IFontScheme | Returns the font scheme. Read-only IFontScheme. |
| [getFormatScheme](/slides/php-java/overridetheme/getformatscheme/)() | IFormatScheme | Returns the shape format scheme. Read-only IFormatScheme. |
| [getVersion](/slides/php-java/overridetheme/getversion/)() | long |  |
| [initColorScheme](/slides/php-java/overridetheme/initcolorscheme/)() | void | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initColorSchemeFrom](/slides/php-java/overridetheme/initcolorschemefrom/)(IColorScheme) | void | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [initColorSchemeFromInherited](/slides/php-java/overridetheme/initcolorschemefrominherited/)() | void | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. And initialize data of this new object with data of the ColorScheme of InheritedTheme. |
| [initFontScheme](/slides/php-java/overridetheme/initfontscheme/)() | void | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFontSchemeFrom](/slides/php-java/overridetheme/initfontschemefrom/)(IFontScheme) | void | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [initFontSchemeFromInherited](/slides/php-java/overridetheme/initfontschemefrominherited/)() | void | Init FontScheme with new object for overriding FontScheme of InheritedTheme. And initialize data of this new object with data of the FontScheme of InheritedTheme. |
| [initFormatScheme](/slides/php-java/overridetheme/initformatscheme/)() | void | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [initFormatSchemeFrom](/slides/php-java/overridetheme/initformatschemefrom/)(IFormatScheme) | void | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [initFormatSchemeFromInherited](/slides/php-java/overridetheme/initformatschemefrominherited/)() | void | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. And initialize data of this new object with data of the FormatScheme of InheritedTheme. |
| [isEmpty](/slides/php-java/overridetheme/isempty/)() | boolean | True value means that ColorScheme, FontScheme, FormatScheme is null and any overriding with this theme object are disabled. Read-only boolean. |
