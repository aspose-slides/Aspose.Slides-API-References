---
title: HyperlinkQueries
type: docs
weight: 0
url: /php-java/hyperlinkqueries/
---

# HyperlinkQueries class

 Provide easy access to contained hyperlinks.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAnyHyperlinks](/slides/php-java/hyperlinkqueries/getanyhyperlinks/)() | IGenericList | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. With given IHyperlinkContainer object you can manage its hyperlink (read, update or remove). See IHyperlinkContainer interface. |
| [getHyperlinkClicks](/slides/php-java/hyperlinkqueries/gethyperlinkclicks/)() | IGenericList | Get all IHyperlinkContainer subobjects that contain not null HyperlinkClick. With given IHyperlinkContainer object you can manage its hyperlink (read, update or remove). See IHyperlinkContainer interface. |
| [getHyperlinkMouseOvers](/slides/php-java/hyperlinkqueries/gethyperlinkmouseovers/)() | IGenericList | Get all IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver. With given IHyperlinkContainer object you can manage its hyperlink (read, update or remove). See IHyperlinkContainer interface. |
| [removeAllHyperlinks](/slides/php-java/hyperlinkqueries/removeallhyperlinks/)() | void | Removes all contained HyperlinkClick and HyperlinkMouseOver hyperlinks (in all IHyperlinkContainer subobjects). |
