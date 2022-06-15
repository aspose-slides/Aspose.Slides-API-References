---
title: PortionFormat
type: docs
weight: 0
url: /php-java/portionformat/
---

# PortionFormat class

 This class contains the text portion formatting properties. Unlike  IPortionFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  PortionFormat#getEffective method 
 which returns a  IPortionFormatEffectiveData instance.

## Constructors

| name | description |
| --- | --- |
| [PortionFormat](/php-java/portionformat/portionformat/)() | Initializes a new instance of PortionFormat class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBookmarkId](/php-java/portionformat/getbookmarkid/)() | String | Returns or sets bookmark identifier. Read/write String. |
| [getEffective](/php-java/portionformat/geteffective/)() | IPortionFormatEffectiveData | Gets effective portion formatting data with the inheritance applied. |
| [getHyperlinkClick](/php-java/portionformat/gethyperlinkclick/)() | IHyperlink | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [getHyperlinkManager](/php-java/portionformat/gethyperlinkmanager/)() | IHyperlinkManager | Hyperlinks manager. Read-only IHyperlinkManager. |
| [getHyperlinkMouseOver](/php-java/portionformat/gethyperlinkmouseover/)() | IHyperlink | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [getSmartTagClean](/php-java/portionformat/getsmarttagclean/)() | boolean | Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean. |
| [setBookmarkId](/php-java/portionformat/setbookmarkid/)(String) | void | Returns or sets bookmark identifier. Read/write String. |
| [setHyperlinkClick](/php-java/portionformat/sethyperlinkclick/)(IHyperlink) | void | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [setHyperlinkMouseOver](/php-java/portionformat/sethyperlinkmouseover/)(IHyperlink) | void | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [setSmartTagClean](/php-java/portionformat/setsmarttagclean/)(boolean) | void | Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean. |
