---
title: Duotone
type: docs
weight: 0
url: /php-java/duotone/
---

# Duotone class

 Represents a Duotone effect.
 For each pixel, combines Color1 and Color2 through a linear interpolation
 to determine the new color for that pixel.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [equals](/slides/php-java/duotone/equals/)(Object) | boolean | Determines whether the specified Duotone is equal to the current Duotone. |
| [getColor1](/slides/php-java/duotone/getcolor1/)() | IColorFormat | Returns target color format for dark pixels. Read-only IColorFormat. |
| [getColor2](/slides/php-java/duotone/getcolor2/)() | IColorFormat | Returns target color format for light pixels. Read-only IColorFormat. |
| [getEffective](/slides/php-java/duotone/geteffective/)() | IDuotoneEffectiveData | Gets effective Duotone effect data with the inheritance applied. |
| [getVersion](/slides/php-java/duotone/getversion/)() | long |  |
| [hashCode](/slides/php-java/duotone/hashcode/)() | int | Serves as a hash function for a particular type. |
