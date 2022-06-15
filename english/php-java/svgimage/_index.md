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
| [SvgImage](/php-java/svgimage/svgimage/)(byte[]) | Creates new SvgImage object. |
| [SvgImage](/php-java/svgimage/svgimage/)(String) | Creates new SvgImage object. |
| [SvgImage](/php-java/svgimage/svgimage/)(InputStream) | Creates new SvgImage object. |
| [SvgImage](/php-java/svgimage/svgimage/)(byte[], IExternalResourceResolver, String) | Creates new SvgImage object. |
| [SvgImage](/php-java/svgimage/svgimage/)(String, IExternalResourceResolver, String) | Creates new SvgImage object. |
| [SvgImage](/php-java/svgimage/svgimage/)(InputStream, IExternalResourceResolver, String) | Creates new SvgImage object. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBaseUri](/php-java/svgimage/getbaseuri/)() | String | Returns base URI of the specified Svg. Used to resolve relative links. Read-only String. |
| [getExternalResourceResolver](/php-java/svgimage/getexternalresourceresolver/)() | IExternalResourceResolver | Return callback interface used to resolve external resources during Svg documents import. Read-only IExternalResourceResolver. |
| [getSvgContent](/php-java/svgimage/getsvgcontent/)() | String | Returns SVG content. Read-only String. |
| [getSvgData](/php-java/svgimage/getsvgdata/)() | byte | Returns SVG data. Read-only byte[]. |
