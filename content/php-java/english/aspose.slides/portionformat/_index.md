---
title: PortionFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/portionformat/
---

## PortionFormat class

 This class contains the text portion formatting properties. Unlike  IPortionFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  PortionFormat#getEffective method 
 which returns a  IPortionFormatEffectiveData instance.

## Constructors

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Initializes a new instance of PortionFormat class. |

## Methods

| Name | Description |
| --- | --- |
| [getBookmarkId](getbookmarkid)() | Returns or sets bookmark identifier. Read/write String. |
| [getEffective](geteffective)() | Gets effective portion formatting data with the inheritance applied. |
| [getHyperlinkClick](gethyperlinkclick)() | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [getHyperlinkManager](gethyperlinkmanager)() | Hyperlinks manager. Read-only IHyperlinkManager. |
| [getHyperlinkMouseOver](gethyperlinkmouseover)() | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [getSmartTagClean](getsmarttagclean)() | Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean. |
| [setBookmarkId](setbookmarkid)(String) | Returns or sets bookmark identifier. Read/write String. |
| [setHyperlinkClick](sethyperlinkclick)([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse click. Read/write IHyperlink. |
| [setHyperlinkMouseOver](sethyperlinkmouseover)([Hyperlink](../hyperlink)) | Returns or sets the hyperlink defined for mouse over. Read/write IHyperlink. |
| [setSmartTagClean](setsmarttagclean)(boolean) | Determines whether the smart tag should be cleaned. No inheritance applied. Read/write boolean. |
