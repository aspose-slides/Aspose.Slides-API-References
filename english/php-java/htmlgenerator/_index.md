---
title: HtmlGenerator
type: docs
weight: 0
url: /php-java/htmlgenerator/
---

# HtmlGenerator class

 Html generator.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addAttributeValue](/slides/php-java/htmlgenerator/addattributevalue/)(String) | void | Quotes attribute value and adds it to the html file. |
| [addAttributeValue](/slides/php-java/htmlgenerator/addattributevalue/)(char[]) | void | Quotes attribute value and adds it to the html file. |
| [addAttributeValue](/slides/php-java/htmlgenerator/addattributevalue/)(char[], int, int) | void | Quotes attribute value and adds it to the html file. |
| [addHtml](/slides/php-java/htmlgenerator/addhtml/)(String) | void | Adds formatted HTML text. |
| [addHtml](/slides/php-java/htmlgenerator/addhtml/)(char[]) | void | Adds formatted HTML text. |
| [addHtml](/slides/php-java/htmlgenerator/addhtml/)(char[], int, int) | void | Adds formatted HTML text. |
| [addText](/slides/php-java/htmlgenerator/addtext/)(String) | void | Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced. |
| [addText](/slides/php-java/htmlgenerator/addtext/)(char[]) | void | Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced. |
| [addText](/slides/php-java/htmlgenerator/addtext/)(char[], int, int) | void | Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced. |
| [getNextSlideIndex](/slides/php-java/htmlgenerator/getnextslideindex/)() | int | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. Read-only int. |
| [getPreviousSlideIndex](/slides/php-java/htmlgenerator/getpreviousslideindex/)() | int | Returns index of previously rendered slide or -1 if first slide is rendering. Read-only int. |
| [getSlideImageSize](/slides/php-java/htmlgenerator/getslideimagesize/)() | Dimension2D | Returns slide image size. Read-only java.awt.geom.Dimension2D. |
| [getSlideImageSizeUnit](/slides/php-java/htmlgenerator/getslideimagesizeunit/)() | int | Returns a unit in which slide image size is specified. Read-only SvgCoordinateUnit. |
| [getSlideImageSizeUnitCode](/slides/php-java/htmlgenerator/getslideimagesizeunitcode/)() | String | Returns a css code of unit in which slide image size is specified. Read-only String. |
| [getSlideIndex](/slides/php-java/htmlgenerator/getslideindex/)() | int | Returns index of currently rendering slide. Read-only int. |
