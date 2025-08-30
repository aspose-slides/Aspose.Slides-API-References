---
title: IPortionFormat class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iportionformat/
---


## IPortionFormat class

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

The IPortionFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`bookmark_id`](/slides/python-net/aspose.slides/iportionformat/bookmark_id/) | Returns or sets bookmark identifier.<br/>            Read/write **str**. |
| [`smart_tag_clean`](/slides/python-net/aspose.slides/iportionformat/smart_tag_clean/) | Determines whether the smart tag should be cleaned. No inheritance applied.<br/>            Read/write **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_effective`](/slides/python-net/aspose.slides/iportionformat/get_effective/#) | Gets effective portion formatting data with the inheritance applied. |


### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".


In order to get the effective formatting parameter values including inherited you need to use [`IPortionFormat.get_effective`](/slides/python-net/aspose.slides/iportionformat/get_effective) method 
            which returns a [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata) instance.


### See Also
* class [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

