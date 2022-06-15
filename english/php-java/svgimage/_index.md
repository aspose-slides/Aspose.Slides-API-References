---
title: SvgImage
type: docs
weight: 0
url: /php-java/svgimage/
---

# SvgImage class

 Represents an SVG image.
 

## Constructors

| name | description |
| --- | --- |
| [SvgImage](/slides/php-java/svgimage/svgimage/)(byte[]) | Creates new SvgImage object. |
| [SvgImage](/slides/php-java/svgimage/svgimage/)(String) | Creates new SvgImage object. |
| [SvgImage](/slides/php-java/svgimage/svgimage/)(InputStream) | Creates new SvgImage object. |
| [SvgImage](/slides/php-java/svgimage/svgimage/)(byte[], IExternalResourceResolver, String) | Creates new SvgImage object. |
| [SvgImage](/slides/php-java/svgimage/svgimage/)(String, IExternalResourceResolver, String) | Creates new SvgImage object. |
| [SvgImage](/slides/php-java/svgimage/svgimage/)(InputStream, IExternalResourceResolver, String) | Creates new SvgImage object. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBaseUri](/slides/php-java/svgimage/getbaseuri/)() | String | Returns base URI of the specified Svg. Used to resolve relative links. Read-only String. |
| [getExternalResourceResolver](/slides/php-java/svgimage/getexternalresourceresolver/)() | IExternalResourceResolver | Return callback interface used to resolve external resources during Svg documents import. Read-only IExternalResourceResolver. |
| [getSvgContent](/slides/php-java/svgimage/getsvgcontent/)() | String | Returns SVG content. Read-only String. |
| [getSvgData](/slides/php-java/svgimage/getsvgdata/)() | byte | Returns SVG data. Read-only byte[]. |
